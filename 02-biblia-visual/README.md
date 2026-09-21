# 🎨 02 - Bíblia Visual (Concept Art)

Repositório de referências visuais fixas — personagens, figurinos e cenários — utilizadas como âncora de consistência para as ferramentas de IA generativa (Midjourney, Flux) antes da geração de vídeo.

## Estrutura

```
02-biblia-visual/
├── personagens/        # Fichas visuais de cada personagem
├── figurinos/          # Referências de vestuário e variações por cena/clima
├── cenarios/           # Referências de ambientação (Nárnia, Pântanos, Mundo Subterrâneo, etc.)
├── prompts-referencia/ # Prompts consolidados usados para gerar cada asset
└── templates/          # Modelos padrão de ficha visual
```

## Objetivo

Garantir que elementos como o rosto do **Príncipe Rilian**, o figurino de **Puddleglum (Brejeiro)** ou a atmosfera do **Castelo de Harfang** permaneçam consistentes em todas as cenas e planos gerados por IA.

## Fluxo de Trabalho

1. Antes de iniciar a geração de vídeo de qualquer capítulo, identifique os personagens/cenários envolvidos.
2. Verifique se já existe uma ficha em `personagens/`, `figurinos/` ou `cenarios/`.
3. Caso não exista, crie a ficha usando o template correspondente em `templates/`, gere as imagens de referência (Midjourney/Flux) e salve o prompt final em `prompts-referencia/`.
4. Toda vez que uma cena for decupada (`01-roteiro/decupagem/`), referencie o arquivo da Bíblia Visual correspondente.

## Nomenclatura de Arquivos

- Personagem: `personagem-nome.md` (ex: `personagem-principe-rilian.md`)
- Figurino: `figurino-personagem-contexto.md` (ex: `figurino-rilian-armadura-negra.md`)
- Cenário: `cenario-nome-do-lugar.md` (ex: `cenario-castelo-harfang.md`)
