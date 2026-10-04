# ECM252 — React

Exercícios de Git, aplicações React e exemplos de integração com backend da disciplina ECM252 do Instituto Mauá de Tecnologia, em 2026.

## Aulas

| Pasta | Conteúdo |
| --- | --- |
| [ap001_git_introducao](ap001_git_introducao/) | Introdução ao Git, com calculadora e testes em Python. |
| [ap003_react_jsx_componentes](ap003_react_jsx_componentes/) | JSX e componentes. |
| [ap004_react_props](ap004_react_props/) | Propriedades de componentes. |
| [ap005_estado_contador](ap005_estado_contador/) | Estado e contador. |
| [ap005_estado_estacao_climatica](ap005_estado_estacao_climatica/) | Estado em uma estação climática. |
| [ap006_react_useEffect/efeitos](ap006_react_useEffect/efeitos/) | Efeitos com `useEffect`. |
| [ap007_react_exibe_fotos](ap007_react_exibe_fotos/) | Aplicação de exibição de fotos. |
| [ap00x_back_front_integracao/backend](ap00x_back_front_integracao/backend/) | Backend Node.js de integração com Express e MySQL. |

Cada aplicação possui suas próprias dependências e scripts. Não existe um workspace npm nem uma aplicação única na raiz deste repositório.

## Executar

Instale o Node.js e o npm compatíveis com as dependências da aula. Exemplo de execução:

```powershell
cd ap003_react_jsx_componentes
npm ci
npm run dev
```

Nas aplicações React, `npm run build` gera o build e `npm run lint` executa a verificação configurada. Para a aula de efeitos, execute os comandos dentro de `ap006_react_useEffect/efeitos`.

Para o backend, a partir da raiz:

```powershell
cd ap00x_back_front_integracao/backend
npm ci
npm run dev
```

Configure o MySQL e as variáveis de ambiente exigidas pelo backend antes de executá-lo. A aula de fotos também pode precisar de configuração local de serviços externos. Os arquivos `.env` permanecem locais e não são publicados; consulte o código e o README de cada aula para a configuração correspondente.

## Origem e histórico

Este projeto foi separado da pasta `react` da `main` de [2026_maua_ecm252](https://github.com/JoaoVitorSesma/2026_maua_ecm252), incluindo os nomes e caminhos antigos das aulas. Autores, datas e mensagens foram preservados; os identificadores dos commits mudaram com a extração. As branches auxiliares e as tags continuam no repositório original.

O desenvolvimento dessas aulas passa a ocorrer neste repositório. As pastas do repositório original permanecem como referência e não são sincronizadas automaticamente.

Projetos relacionados: [Dart](https://github.com/JoaoVitorSesma/2026_maua_ecm252_dart) e [Flutter](https://github.com/JoaoVitorSesma/2026_maua_ecm252_flutter).
