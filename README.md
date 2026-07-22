# Manual de Marca — VML

**Site publicado:** https://tomcoliveira.github.io/manual-vml/
**Repositório:** https://github.com/tomcoliveira/manual-vml (público)

Duas coisas, a mesma fonte de verdade:

| Pasta | Para quem | O que é |
|---|---|---|
| [`docs/`](docs/index.html) | Humanos | Site HTML navegável — publicado no GitHub Pages, ou abra `docs/index.html` localmente no navegador. Logo, cores, tipografia e regras aplicadas visualmente, com os assets reais. |
| [`agente/`](agente/00_LEIA-ME_INSTRUCOES_PARA_AGENTES.md) | Agentes de IA | Pacote markdown autossuficiente (~28MB) para injetar no contexto de qualquer agente que precise gerar ou avaliar peças de marca VML. Já inclui os assets físicos mínimos (logo, cor, tipografia, exemplos) em `agente/assets/`. Para colar de uma vez em chats sem upload de arquivo, use [`agente/_pacote_completo.md`](agente/_pacote_completo.md) — os 14 arquivos concatenados em um só (~77KB, só texto, sem os assets binários). |

## Origem

Fonte oficial: `VML Brand Identity Guidelines | Version 1 | January 2026`. Extraído e organizado a partir do brand kit completo em:

`/Users/tom/Library/CloudStorage/OneDrive-WPPCloud/VML_onedrive/3_recursos/vml_brand_kit_2026-06-30/`

Datado de 2026-06-30. Em caso de dúvida sobre versão mais recente, **my.vml.com** é a fonte de verdade — não este recorte.

## Escopo

Este é um recorte **enxuto**, não uma cópia 1:1 do brand kit (que tem ~1,4GB). Cobre 100% de logo, cor e tipografia oficiais; para elementos de design, templates de apresentação e vídeo institucional, documenta a regra mas inclui só amostras representativas — o arquivo completo, quando necessário, deve ser buscado no brand kit completo (path acima) ou sinalizado como pendência.

Ver a tabela completa do que foi incluído/excluído em [`agente/00_LEIA-ME_INSTRUCOES_PARA_AGENTES.md`](agente/00_LEIA-ME_INSTRUCOES_PARA_AGENTES.md).

## Contatos

Dúvidas gerais sobre o guideline: alex.cree@vml.com · rachel.mozena@vml.com.

## Changelog

**2026-07-22** — Validado com um agente de IA real (sem contexto prévio, só a pasta `agente/`) resolvendo 5 tarefas de marca; 3 lacunas reais encontradas e corrigidas:
- Adicionada tabela determinística de contraste logo×fundo em `agente/03_cor.md` e `docs/cor.html` (antes só havia o princípio geral "prioriza contraste", ambíguo o bastante para gerar decisões divergentes).
- Adicionada ordem de prioridade para quando regras de seções diferentes colidem, em `agente/00_LEIA-ME_INSTRUCOES_PARA_AGENTES.md` e `docs/governanca.html` (gap de asset > proibição dura > regra de estilo > QA final).
- Confirmado, por busca direta no brand kit completo, que os ícones hand-drawn por categoria (People, Comms, Data Insights etc.) não existem como arquivo em lugar nenhum — nota reforçada em `agente/06_elementos_de_design.md` e `docs/elementos.html` para não gerar/inventar esse asset.

**2026-07-22 (2)** — Um segundo agente, lendo `_pacote_completo.md` de forma independente, concluiu (incorretamente) que a base "não se destina à criação de peças novas, só à checagem de material pronto". Verificação mostrou que essa leitura era um viés de generalização: o propósito declarado no LEIA-ME já dizia "gerar ou avaliar", e as 6 instruções de "não recriar/não gerar" no texto travam alvos específicos (logotipo/Spark, assets Human First, asset inexistente), nunca criação em geral. Adicionada declaração de propósito explícita no topo de `agente/00_LEIA-ME_INSTRUCOES_PARA_AGENTES.md` e `docs/index.html`, com tabela "proibido recriar × liberado para gerar", para eliminar essa ambiguidade de leitura.
