# Base de Conhecimento de Marca — VML (Pacote Portátil)
Fonte: `VML Brand Identity Guidelines | Version 1 | January 2026` + seleção enxuta de assets do brand kit oficial.
Gerado em: 2026-06-30. Válido enquanto não houver nova versão do guideline publicada em my.vml.com.

## Antes de qualquer outra coisa: esta base serve para CRIAR peças novas

**O caso de uso principal desta base é geração — não checagem de material pronto.** Um agente deve usar isto para montar decks, posts, documentos e peças novas do zero, aplicando as regras de marca corretamente desde a primeira versão. Avaliar uma peça já pronta é um caso de uso secundário, não o principal.

As várias instruções de "não recriar" / "não gerar" espalhadas pelo resto deste pacote **não são uma proibição geral de criar coisas.** Cada uma trava um alvo específico e nomeado — nunca "não criar peças de marca":

| O que é proibido recriar/gerar do zero | O que continua liberado para gerar normalmente |
|---|---|
| O logotipo e o Spark em si (sempre usar o arquivo oficial) | Um deck, slide, post ou documento inteiro que *usa* o logotipo oficial |
| Os assets protegidos do Human First (logo, Inky Spark, hand-lettering) — só fora do escopo Human First | Qualquer peça de marca geral (fora do escopo Human First) |
| Um asset que não existe neste pacote nem no brand kit completo (ex.: header azul, ícone hand-drawn de categoria) | Uma peça usando os assets que **existem** — a lacuna trava só o asset específico faltante, não a peça inteira |
| Ilustração customizada em estilo de contorno (feita por designer humano) | Composições, layouts e textos usando os elementos de design já disponíveis (supergraphic, halftone, hand-drawn existente) |

Se uma tarefa não aparece explicitamente em uma das proibições nomeadas acima ou nos "watch-outs" de cada seção, **ela é permitida por padrão.** Na dúvida, o padrão é gerar aplicando as regras — não recusar por precaução.

## Isto é um pacote autossuficiente — leia isto primeiro

Ao contrário de uma versão anterior deste material, **este pacote não depende de acesso a nenhuma pasta externa, OneDrive ou brand kit completo.** Tudo que ele referencia está dentro dele mesmo, na subpasta `assets/`. Pode ser copiado, zipado, enviado a qualquer agente/ferramenta que não tenha acesso ao ambiente do Tom, e ainda assim funcionar para as decisões que ele cobre.

Tamanho total: ~48MB (28MB de identidade + 20MB da galeria de exemplos aplicados, seção `15`). **Não contém vídeo, nem os arquivos de template (.pptx/.key), nem a biblioteca completa de texturas/supergraphics.** Isso é intencional — o objetivo aqui é o logo oficial, a paleta, a tipografia, uma amostra representativa dos demais elementos, e agora também um catálogo visual amplo de peças já aplicadas — não uma cópia 1:1 do brand kit de 1,4GB.

## Propósito

Injetar no contexto de agentes (design, apresentação, social, documento) que precisam **gerar ou avaliar peças de marca VML** as regras normativas do guideline oficial (specs numéricas, hex/CMYK/PMS, tamanhos mínimos) junto com os assets físicos mínimos necessários para aplicar essas regras de verdade — sem depender de infraestrutura externa.

## Estrutura do pacote

**Sem acesso a arquivo local?** Todo item abaixo tem link público equivalente em [`LINKS_PUBLICOS.md`](LINKS_PUBLICOS.md) — raw (para agente ler/baixar) e/ou página do site (para humano abrir).

| Item | Conteúdo | Quando consultar |
|---|---|---|
| `01_principios_e_filosofia.md` | Atributos de marca (Human/Confident/Premium) | Antes de qualquer decisão de tom/estilo |
| `02_logo.md` | Logotipo, Spark, hierarquia, tamanhos mínimos — **logo oficial completo incluído** | Qualquer peça que use o logo |
| `03_cor.md` | Paleta core, grayscale, secundária — hex/RGB/CMYK/PMS + swatches `.ase` incluídos | Qualquer decisão de cor |
| `04_tipografia.md` | Snowflake Sans (todos os pesos) + Inline — fontes incluídas | Qualquer peça com texto |
| `05_layout_e_grid.md` | The Square, digital collage, sistema de grid (sem asset associado) | Qualquer layout/composição |
| `06_elementos_de_design.md` | Supergraphics, Spark halftone, hand-drawn — regras + 1-2 exemplos de cada | Elementos gráficos de apoio |
| `07_human_first.md` | Sub-sistema Human First — regras + logo e Inky Spark oficiais incluídos | Só quando a peça é especificamente Human First |
| `08_ambientes_fisicos.md` | Aplicação em escritórios/sinalização (sem asset) | Só para ambientes físicos |
| `09_headshots.md` | Padrão de foto de perfil (sem asset) | Fotografia de pessoas |
| `10_social_media.md` | Regras de headers de redes sociais + 2 exemplos incluídos | Social media |
| `11_templates_apresentacao.md` | Manifesto de layouts de cada .pptx/.key — **só os nomes de layout, arquivos não incluídos** | Apresentações e decks |
| `12_video_institucional.md` | Regras de vídeo institucional — **nenhum arquivo de vídeo incluído neste pacote** | Vídeo institucional |
| `asset_manifest.json` | Catálogo machine-readable de tudo que está fisicamente incluído em `assets/`, mais a lista do que foi deliberadamente deixado de fora | Lookup programático de qualquer asset |
| `13_checklist_qa.md` | Checklist de verificação antes de entregar qualquer peça | Sempre, como último passo |
| `14_contatos_e_governanca.md` | Regras de propriedade de asset, quem aprova o quê | Casos que exigem aprovação humana |
| `15_galeria_de_exemplos.md` | **44 peças reais aplicadas** — ambientes, papelaria, merchandise, digital/social, e-mail, Human First — extraídas da seção "Gallery" do guideline (p.78–118, nunca extraída antes de 2026-07-22) | Antes de gerar qualquer peça, para ver como o sistema fica aplicado de verdade, não só descrito |
| `assets/` | Os arquivos físicos: logo (todos os formatos, preto e branco), cores `.ase`, fontes `.otf`, pasta `exemplos/` com amostras leves de Human First/supergraphic/halftone/social, e pasta `galeria/` com as 44 peças aplicadas da seção 15 | Sempre que uma regra pedir para "usar o arquivo X" |

## O que NÃO está neste pacote (e por quê)

| Categoria excluída | Motivo | Onde encontrar se precisar |
|---|---|---|
| Vídeos (ident animado, backgrounds animados, vídeo institucional, vídeo Anthemic Human First) | Pesados, fora do escopo pedido | Brand kit completo, pastas `01_logo/ident_animado`, `04_elementos_de_design/*_animado`, `05_human_first/video`, `08_video_institucional` |
| Templates `.pptx` / `.key` completos | 339MB no total, só os nomes de layout foram catalogados em `11_templates_apresentacao.md` | Brand kit completo, pasta `06_templates/` |
| Biblioteca completa de Spark halftone (dezenas de variações de cor) | Só 1 exemplo foi incluído | Brand kit completo, `04_elementos_de_design/spark_halftone_texture/` |
| Biblioteca completa de supergraphics (12 combinações de cor) | Só 1 exemplo foi incluído | Brand kit completo, `04_elementos_de_design/supergraphics_estatico/` |
| PDF do guideline original (519MB) | Conteúdo já extraído integralmente para os `.md` deste pacote — não há perda de regra, só do arquivo-fonte | Brand kit completo, `00_guideline/` |
| Ícones de Inky Spark além do "Fingerprint" (versões numeradas maiores) | Só o ícone principal foi incluído como exemplo | Brand kit completo, `05_human_first/icones_inky_spark/` |
| Headers sociais além de 2 exemplos (existem 21 no total: 3 plataformas × 7 variantes de cor) | Regra de seleção de cor já documentada em `10_social_media.md`; arquivos completos não incluídos | Brand kit completo, `07_social/` |

Se um agente precisar de algo desta lista, a ação correta é **sinalizar a necessidade** (dizer explicitamente "preciso do template X" ou "preciso da variante de cor Y do halftone") — não recriar o elemento a partir do exemplo disponível.

## Como um agente deve usar isto

1. Carregar `01` a `07` como contexto base sempre que a tarefa envolver qualquer peça de marca VML.
2. Carregar `08`–`10` só se a tarefa for especificamente ambiente físico, headshot ou social.
3. Consultar `asset_manifest.json` para resolver o path exato de um asset dentro de `assets/` — nunca inventar um nome de arquivo.
4. Rodar `13_checklist_qa.md` como gate final antes de considerar a peça pronta.
5. Se a tarefa exigir algo listado na tabela "O que NÃO está neste pacote", parar e sinalizar — não gerar substituto improvisado.

## Ordem de prioridade quando várias regras se aplicam ao mesmo pedido

Um teste real com agente de IA (2026-07-22) mostrou que pedidos comuns acionam mais de uma seção ao mesmo tempo (ex.: um cover slide aciona `03_cor.md` e `11_templates_apresentacao.md` simultaneamente) e o pacote, até então, não dizia qual checar primeiro. Ordem a seguir, sempre nesta sequência:

1. **Gaps de asset/acesso primeiro.** Antes de aplicar qualquer regra de estilo, verificar se a peça depende de algo listado em "O que NÃO está neste pacote" (templates `.pptx/.key`, vídeo, biblioteca completa de texturas) ou de um asset que não existe em lugar nenhum (ex.: header social azul, ícones hand-drawn por categoria). Se sim, **parar e sinalizar isso antes de decidir qualquer outra coisa** — não faz sentido resolver cor/layout de uma peça que não pode ser montada de verdade.
2. **Proibições duras (watch-outs) em segundo lugar.** Se o pedido violar uma regra de "não fazer" de qualquer seção (ex.: Spark repetido como padrão, lockup próprio, elementos Human First fora de contexto), recusar/alertar — isso trava a peça independentemente de cor ou layout estarem corretos.
3. **Regras positivas de aplicação em terceiro** — cor (`03`), tipografia (`04`), layout (`05`), elementos (`06`) — para o que sobrar dentro do permitido pelos passos 1–2.
4. **`13_checklist_qa.md` como gate final**, sempre por último, mesmo que os passos 1–3 já pareçam ter resolvido tudo.

Resumindo: **falta de material > proibição > regra de estilo > QA final.** Nunca decidir estilo antes de confirmar que a peça é sequer viável com o que está disponível.

## Limitações conhecidas (declaradas, não omitidas)

- Este pacote é uma **seleção curada**, não um espelho do brand kit. Ele cobre bem logo, cor e tipografia (100% dos formatos oficiais); para elementos de design, templates e vídeo, ele documenta a regra mas inclui só amostras.
- Os valores hex/RGB/CMYK/PMS vêm do texto oficial do guideline (não dos binários `.ase`, que também estão incluídos para uso direto em Illustrator/Photoshop/InDesign).
- Não foi feita engenharia reversa de fontes `.otf` além dos nomes de arquivo e do que o guideline declara sobre pesos e uso.
