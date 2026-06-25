# {{PROJECT_NAME}}

Template Android nativo em Kotlin + XML, pensado para virar um repositório base no GitHub.

## O que ele entrega

- `MainActivity` e classes genéricas já prontas como ponto de partida
- `ViewBinding` habilitado
- tema Material3 básico
- `local.properties.example` para configurar o SDK sem versionar arquivo local
- script de inicialização para substituir os valores dinâmicos do template

## O que muda por projeto

- `{{PROJECT_NAME}}`
- `{{APP_LABEL}}`
- `{{PACKAGE_NAME}}`
- `{{PACKAGE_PATH}}`
- `{{APPLICATION_CLASS_NAME}}`

## Estrutura

- `app/` código e recursos Android
- `scripts/init-template.sh` inicialização do template
- `template.config.example.json` exemplo de configuração
- `local.properties.example` exemplo de configuração local do Android Studio

## Como usar

1. Copie `template.config.example.json` para `template.config.json`
2. Ajuste `projectName`, `appLabel`, `packageName` e `applicationClassName`
3. Copie `local.properties.example` para `local.properties` se for abrir o projeto no Android Studio
4. Rode `scripts/init-template.sh`

## Observações

- O script substitui os placeholders e gera uma cópia pronta do template em `out/`
- O nome das classes genéricas não é dinâmico de propósito
- Se quiser montar um novo projeto manualmente, os únicos pontos que dependem do nome do app estão nos placeholders acima
