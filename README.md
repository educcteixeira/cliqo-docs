# cliqo-docs — o que o `docs.cliqo.io` publica

⚠️ **Não edite os artigos aqui.** Esta pasta é um ESPELHO.

A fonte é `docs/help-center/` no repositório do produto (`brunoccteixeira/cliqo`).
Lá o conteúdo tem gate de CI que confere, a cada mudança:

- toda página declarada no `docs.json` tem arquivo, e todo arquivo está no menu
- todo redirecionamento aponta pra página que existe
- os dois idiomas seguem espelhados
- a referência de API não descreve endpoint que não existe

Editar direto aqui contorna esses gates — que é exatamente como a versão anterior
deste site passou a documentar ~20 operações e 2 SDKs inexistentes (#1813), até um
cliente perder horas procurando o que não há.

## Como atualizar

Mudança no conteúdo entra por PR no repositório do produto, em
`docs/help-center/`. Daqui sai só a cópia.

## O que tem

- `pt-BR/` e `en/` — os artigos, com slugs espelhados 1:1
- `en/developers/` — a referência de API, escrita em inglês por decisão
- `docs.json` — navegação, tema e os redirecionamentos do corte da doc antiga

## Histórico

Antes de 30/08/2026 este repositório servia a documentação de uma API que não
existia. Os endereços daquela versão continuam funcionando: viram
redirecionamento pra referência real, que também lista o que a API **não** tem.
