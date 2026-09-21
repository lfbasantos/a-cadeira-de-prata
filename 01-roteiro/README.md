# 📜 01 - Roteiro e Decupagem

Esta pasta contém o roteiro adaptado da obra e a decupagem técnica (shot list) de cada cena.

## Estrutura

```
01-roteiro/
├── roteiro-completo/       # Roteiro adaptado, capítulo a capítulo
├── decupagem/              # Quebra de cena em planos de câmera (shot lists)
└── templates/              # Modelos padrão para roteiro e decupagem
```

## Fluxo de Trabalho

1. O roteirista adapta o capítulo do livro em `roteiro-completo/`, usando o template `templates/template-roteiro.md`.
2. Após aprovação do roteiro, o diretor realiza a decupagem em `decupagem/`, usando o template `templates/template-decupagem.md`, quebrando cada cena em planos numerados (ex: Close-up, Plano Aberto, Plano Médio).
3. Cada cena/plano decupado vira uma *Issue* no GitHub para acompanhamento de geração de imagem/vídeo.

## Nomenclatura de Arquivos

- Roteiro: `cap-XX-nome-do-capitulo.md`
- Decupagem: `cena-XXX-nome-da-cena.md`
