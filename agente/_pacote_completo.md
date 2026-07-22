# Base de Conhecimento de Marca — VML (arquivo único concatenado)

Gerado a partir dos 14 arquivos markdown desta pasta, para colar de uma vez em agentes/chats que não aceitam upload de múltiplos arquivos ou navegação de pasta.

**Importante:** este arquivo cobre só o texto normativo. Os assets físicos (logo em SVG/AI/EPS/PNG, cores `.ase`, fontes `.otf`) NÃO estão embutidos aqui — precisam ser anexados separadamente da pasta `assets/` quando a tarefa exigir inserir o arquivo de verdade (nunca recriar a partir da descrição textual).

---

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

Tamanho total: ~28MB. **Não contém vídeo, nem os arquivos de template (.pptx/.key), nem a biblioteca completa de texturas/supergraphics.** Isso é intencional — o objetivo aqui é o logo oficial, a paleta, a tipografia e uma amostra representativa dos demais elementos, não uma cópia 1:1 do brand kit de 1,4GB.

## Propósito

Injetar no contexto de agentes (design, apresentação, social, documento) que precisam **gerar ou avaliar peças de marca VML** as regras normativas do guideline oficial (specs numéricas, hex/CMYK/PMS, tamanhos mínimos) junto com os assets físicos mínimos necessários para aplicar essas regras de verdade — sem depender de infraestrutura externa.

## Estrutura do pacote

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
| `assets/` | Os arquivos físicos: logo (todos os formatos, preto e branco), cores `.ase`, fontes `.otf`, e uma pasta `exemplos/` com amostras leves de Human First, supergraphic, halftone e social | Sempre que uma regra pedir para "usar o arquivo X" |

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

---

# 01. Princípios de Marca

Fonte: Guideline oficial, seções "Overview" e "New Brand Principles" (p.2-6). Seção sem asset associado — só regra.

## Contexto

A VML anunciou a marca em 2023 com presença grande e ousada. A versão de Jan/2026 do guideline marca a "próxima era": equilibrar tecnologias transformadoras com a humanidade necessária para criar marca e experiência de qualidade, alinhado à filosofia criativa **Human First**.

Propósito declarado do documento: dar um look, feel e tom claros e unificados à identidade VML. Os exemplos do guideline são referência de design, não execuções finais obrigatórias — ou seja, há espaço de interpretação dentro dos limites declarados, mas os "watch-outs" (do's/don'ts) de cada seção são normativos.

## Os três atributos de design (aplicam-se a TODA peça VML)

Estes atributos setam o tom visual geral. Todo agente que gerar uma peça deve conseguir justificar a peça em termos destes três atributos:

**Human** — textura, calor, hand-drawn, colagem digital, desalinhamento intencional (sutil, não bagunça).

**Confident** — presença sem esforço aparente ("effortless"), discreta, não gritante ("unshowy, quiet presence").

**Premium** — minimalismo refinado, cor reduzida/comedida, tipografia "quieta" (não gritante).

## Regra de ouro implícita

Na dúvida entre "mais" ou "menos" (mais cor, mais elemento gráfico, mais peso tipográfico, mais Spark), o guideline consistentemente resolve para **menos**. Essa é a leitura correta em toda ambiguidade de aplicação: o guideline está migrando a marca de uma fase "grande e ousada" (2023) para uma fase mais contida e premium (2026). Qualquer execução que pareça "a versão antiga e mais chamativa da VML" está desalinhada com este guideline, mesmo que tecnicamente use os assets corretos.

---

# 02. Logo

Fonte: Guideline oficial, seção 02 Logo (p.7-19).

## Regra zero — antes de qualquer outra coisa

**O logotipo e o Spark nunca são gerados, desenhados ou reconstruídos a partir de descrição textual.** Este documento não contém geometria suficiente para recriar o logo com fidelidade, e mesmo que contivesse, recriar não é permitido — é sempre o arquivo binário original (`.svg`, `.ai`, `.eps`, `.png`, `.jpg`, incluídos em `assets/logo/`) que deve ser inserido/referenciado na peça final.

Fluxo correto para qualquer agente:
1. Resolver o path exato do arquivo em `asset_manifest.json` ou na tabela "Assets disponíveis" abaixo.
2. Inserir/colar/importar esse arquivo diretamente na peça (documento, slide, imagem, HTML).
3. Nunca usar um gerador de imagem (Canva, DALL-E, SVG escrito à mão, etc.) para produzir uma versão nova do logotipo ou do Spark, mesmo "só para preencher espaço" ou como placeholder.

Isso vale mesmo quando o resultado pareceria visualmente idêntico: o guideline proíbe explicitamente criar logos/lockups próprios (ver "Watch-outs" abaixo) — a regra é sobre proveniência do arquivo, não só sobre aparência final.

## Mudança de direção (importante para não usar material antigo como referência)

A VML está migrando de "Spark grande + logotipo pequeno em lockup" para **logotipo como asset dominante**, com o símbolo Spark em uso secundário e comedido. Não é mais correto usar o lockup Spark+wordmark como forma padrão. Se uma peça de referência antiga mostra Spark grande dominando a composição, ela está desatualizada frente a este guideline.

Regra de restrição: o Spark **não precisa aparecer em toda execução**. Ele é opcional/secundário — usar com moderação.

## Hierarquia de uso
1. **Logotipo sozinho** (`Logotype only`) — uso encorajado em aplicações de propriedade/branded da VML. É a forma preferencial.
2. **Logotipo + Spark separados** — quando se deseja um elemento gráfico de marca adicional. Usar como elementos distintos, não como lockup fundido.
3. **Spark sozinho** — como assinatura secundária, ex.: só na primeira/última página de um deck, ou no rodapé de um site. Também serve em comunicação interna quando o logotipo completo seria redundante.

Regra de cor do logo: usar versão **preta ou branca** na maioria das representações. Evitar preencher logotipo e Spark com cores diferentes na mesma peça.

## Tamanhos mínimos (não escalar abaixo disso)

| Elemento                                                          | Impresso | Digital |
| ----------------------------------------------------------------- | -------- | ------- |
| Logotipo primário                                                 | 0,5"     | 24px    |
| Spark (símbolo)                                                   | 0,5"     | 24px    |
| Logo de programas/estúdios/especialidades (com sublinha "AT VML") | 0,25"    | 50px    |

## Regras de proporção entre logotipo e Spark (quando usados separados, não em lockup)

- Alinhados no eixo X: o Spark geralmente casa com a altura do logotipo (100%).
- Alinhados no eixo Y: ponto de partida é Spark = 50% da altura do logo, especialmente quando o logo está grande.
- Quando o logo está pequeno na composição: usar Spark a 75% do tamanho do logo.
- Regra geral (watch-out): evitar que o Spark fique maior que a altura do logotipo quando usados como elementos separados.
- Não usar padrões repetidos de Sparks nem depender demais do Spark como elemento gráfico recorrente.

## Arquitetura de marca (hierarquia oficial — não inventar variações)

- Marca-mãe (parent brand)
- Nomes com "VML" (endorsement)
- Nomes com linha de endosso (endorser line)
- Logos de aquisição com linha de endosso
- Programas, estúdios, práticas — usam sublinha "AT VML"
- Branding local de escritório (regional) — **uso casual apenas**, nunca substitui a assinatura primária da marca

Regra dura: **não criar logos ou lockups próprios**. Qualquer solicitação de novo lockup deve ser encaminhada ao time de Brand Design (ver `14_contatos_e_governanca.md`).

### Logos regionais

Servem para identidade/orgulho de escritório/região; podem ser usados em marketing de escritório regional. **Não podem substituir** a assinatura VML como marca primária. Ao montar um logo regional com o símbolo Spark, usar exclusivamente a fonte **Snowflake Sans Black** (incluída em `assets/tipografia/`).

## Watch-outs (não fazer)

- Não usar o lockup Spark + wordmark como forma padrão (ver "mudança de direção" acima).
- Não usar o Spark em tamanho grande e "bold" como expressão central da marca.
- Não deixar o Spark maior que a altura do logotipo quando separados.
- Não usar padrões repetidos de Sparks nem depender do Spark como elemento gráfico decorativo recorrente.
- Não preencher logotipo e Spark com cores diferentes na mesma peça.
- Não criar logos/lockups próprios — encaminhar ao time de Brand Design.

## Assets disponíveis neste pacote (`assets/logo/`)

Logo oficial completo, ambas as cores, todos os formatos — nada foi omitido aqui, é o conjunto integral.

| Variante                                  | Path                                        | Formatos incluídos                  |
| ----------------------------------------- | ------------------------------------------- | ----------------------------------- |
| Wordmark + Ícone Snowflake, versão preta  | `assets/logo/vmlblack/{AI,EPS,JPG,PNG,SVG}` | AI, EPS, JPG, PNG, SVG — CMYK e RGB |
| Wordmark + Ícone Snowflake, versão branca | `assets/logo/vmlwhite/{AI,EPS,JPG,PNG,SVG}` | AI, EPS, JPG, PNG, SVG — CMYK e RGB |

Regra de seleção de arquivo por agente: usar **SVG ou AI** para qualquer aplicação que escale (web, apresentação vetorial); usar **PNG** para inserção rápida em documentos/slides rasterizados; usar **EPS** apenas quando o destino exigir formato legado; escolher **CMYK** para produção offset/impressão profissional e **RGB** para tudo em tela.

Não incluído neste pacote: o ident animado (vídeo de abertura com o logo) — ver `12_video_institucional.md`.

---

# 03. Cor

Fonte: Guideline oficial, seção 03 Color (p.20-30).

## Princípio central

A VML está migrando de um uso de cor "ousado e saturado, vale tudo" para uma paleta **curada e comedida**, sinalizando premium. A marca é primariamente preto-e-branco; cor é usada com moderação e intenção — como flood dominante ou como acento, nunca como decoração aleatória.

Regra dura: **usar uma família de cor por vez**. Não misturar múltiplas famílias de cor secundária na mesma peça/comunicação.

Regra de pareamento: preto VML + cor = tom mais premium/pesado. Branco VML + cor = tom mais leve. Evitar competir com vermelho saturado de concorrentes (risco de confusão de marca em imprensa/indústria) — evitar vermelho forte especialmente na assinatura de marca ou no Spark.

Combinações tonal (tone-on-tone, logo e fundo na mesma família de cor) só devem ser usadas quando legibilidade é secundária a um efeito ambiente/reservado (ex.: texturas, backgrounds) — não usar tone-on-tone quando legibilidade importa.

## Cores core (base da marca)

| Nome | HEX | RGB | CMYK |
|---|---|---|---|
| VML White | `#F5F5F5` | 245, 245, 245 | 1, 1, 3, 0 |
| VML Black | `#191919` | 25, 25, 25 | 74, 52, 71, 90 |

Nota: estes tons são adaptados de preto e branco puros (100%) — não usar `#000000`/`#FFFFFF` puros como substituto.

## Escala de cinza (6 degraus, do preto ao branco)

| Nome | HEX | RGB | CMYK |
|---|---|---|---|
| VML Black | `#191919` | 25, 25, 25 | 74, 52, 71, 90 |
| Dark Gray | `#363732` | 54, 55, 50 | 63, 57, 56, 70 |
| Med Gray | `#53544A` | 83, 84, 74 | 59, 48, 58, 44 |
| Gray | `#8B8C81` | 139, 140, 129 | 39, 29, 36, 9 |
| Light Gray | `#C2C4B8` | 194, 196, 184 | 23, 15, 22, 0 |
| VML White | `#F5F5F5` | 245, 245, 245 | 1, 1, 3, 0 |

## Paleta secundária (5 famílias × 3 tons: Light / Base / Dark)

Usar **uma família por vez**, combinada com VML Black e/ou VML White.

### Bronze
| Tom | HEX | RGB | CMYK | PMS |
|---|---|---|---|---|
| Light Bronze | `#FCC7B4` | 252, 199, 180 | 1, 25, 19, 0 | 7520 C |
| Bronze | `#CC7D57` | 204, 125, 87 | 6, 51, 58, 12 | 7591 C |
| Dark Bronze | `#983F03` | 152, 63, 3 | 0, 71, 100, 38 | 1535 C |

### Gold
| Tom | HEX | RGB | CMYK | PMS |
|---|---|---|---|---|
| Light Gold | `#F9D28C` | 249, 210, 140 | 0, 13, 50, 0 | 1345 C |
| Gold | `#D3A34A` | 211, 163, 74 | 6, 24, 71, 9 | 7407 C |
| Dark Gold | `#B37A00` | 179, 122, 0 | 0, 36, 100, 30 | 7551 C |

### Green
| Tom | HEX | RGB | CMYK | PMS |
|---|---|---|---|---|
| Light Green | `#B5BF9B` | 181, 191, 155 | 27, 14, 38, 2 | 5793 C |
| Green | `#859166` | 133, 145, 102 | 38, 22, 61, 18 | 5773 C |
| Dark Green | `#546232` | 84, 98, 50 | 49, 22, 85, 58 | 574 C |

### Blue
| Tom | HEX | RGB | CMYK | PMS |
|---|---|---|---|---|
| Light Blue | `#98AAAF` | 152, 170, 175 | 34, 15, 12, 0 | 2176 C |
| Blue | `#5E889C` | 94, 136, 156 | 58, 26, 22, 9 | 2178 C |
| Dark Blue | `#104B68` | 16, 75, 104 | 98, 43, 20, 52 | 2182 C |

### Plum
| Tom | HEX | RGB | CMYK | PMS |
|---|---|---|---|---|
| Light Plum | `#B1A0B0` | 177, 160, 176 | 29, 32, 15, 2 | 2358 C |
| Plum | `#9E7696` | 158, 118, 150 | 34, 53, 13, 7 | 5145 C |
| Dark Plum | `#723065` | 114, 48, 101 | 45, 95, 0, 25 | 7657 C |

## Cor e o logo

- Fundo colorido → logo preto ou branco (regra padrão, prioriza legibilidade e contraste).
- Combinação tom-sobre-tom (logo e fundo na mesma família) → só quando legibilidade for prioridade menor que efeito ambiente (ex: texturas/fundos de apoio), nunca em uso hero.
- Preto e branco → devem ser os fundos mais usados, especialmente em execuções hero (web, social, capa).
- Uso em co-branding: se a presença da VML deve ser dominante, seguir a paleta padrão; se a presença do cliente for central, "a VML pode ser reduzida" — usar logo preto ou branco discreto.

### Tabela de contraste logo × fundo (regra derivada — ver nota)

**Nota de proveniência:** o guideline oficial só declara o princípio geral ("prioriza legibilidade e contraste") — não traz uma tabela cor-a-cor. Um teste real com agente de IA (2026-07-22) mostrou que, sem uma tabela explícita, dois agentes podem decidir diferente na mesma situação. A tabela abaixo formaliza o princípio de forma determinística, calculada por luminância perceptual (Y = 0,299R + 0,587G + 0,114B; Y ≥ 128 → fundo claro → logo preto; Y < 128 → fundo escuro → logo branco). Ela é uma inferência nossa a partir da regra oficial, não uma cópia do texto do guideline — em caso de dúvida real, um humano do time de Brand Design decide.

| Fundo | Y (luminância) | Logo a usar |
|---|---|---|
| VML White `#F5F5F5` | 245 | **Preto** |
| VML Black `#191919` | 25 | **Branco** |
| Dark Gray `#363732` | 54 | **Branco** |
| Med Gray `#53544A` | 83 | **Branco** |
| Gray `#8B8C81` | 138 | **Preto** |
| Light Gray `#C2C4B8` | 194 | **Preto** |
| Light Bronze `#FCC7B4` | 213 | **Preto** |
| Bronze `#CC7D57` | 144 | **Preto** |
| Dark Bronze `#983F03` | 83 | **Branco** |
| Light Gold `#F9D28C` | 214 | **Preto** |
| Gold `#D3A34A` | 167 | **Preto** |
| Dark Gold `#B37A00` | 125 | **Branco** |
| Light Green `#B5BF9B` | 184 | **Preto** |
| Green `#859166` | 137 | **Preto** |
| Dark Green `#546232` | 88 | **Branco** |
| Light Blue `#98AAAF` | 165 | **Preto** |
| Blue `#5E889C` | 126 | **Branco** |
| Dark Blue `#104B68` | 61 | **Branco** |
| Light Plum `#B1A0B0` | 167 | **Preto** |
| Plum `#9E7696` | 134 | **Preto** |
| Dark Plum `#723065` | 74 | **Branco** |

Regra prática: todo tom "Light" da paleta secundária → logo preto. Todo tom "Dark" → logo branco. Nos tons "Base" (meio-termo), a decisão varia por família — usar a tabela acima, não presumir por analogia com outra família (ex.: Blue Base pede branco, mas Bronze Base pede preto — a luminância percebida das duas cores não é igual apesar de ambas serem tons "Base").

## Cor em apresentações

Para a maioria dos decks VML: **preto e branco predominantes**, com uso limitado de cores de apoio para manter o tom premium. Não colorir slides "para dar vida" — isso vai contra a diretriz.

## Watch-outs (não fazer)

- Não usar cor em excesso ou sem intenção — VML Black/White devem ser a expressão de cor primária.
- Não misturar múltiplas famílias de cor secundária na mesma peça/comunicação.
- Tone-on-tone só para fundo/textura, nunca quando legibilidade importa.
- Cuidado com vermelho saturado forte (risco de confusão com marcas concorrentes) — evitar especialmente na assinatura e no Spark.
- Não preencher logotipo e Spark com cores diferentes na mesma peça.

## Assets disponíveis neste pacote (`assets/cor/`)

- `assets/cor/VML-Brand-Colors-CMYK.ase` — swatches Adobe (CMYK) para Illustrator/InDesign/Photoshop.
- `assets/cor/VML-Brand-Colors-RGB.ase` — swatches Adobe (RGB).
- `assets/cor/paleta_referencia/VML_Color_Primary_BW_Grays_2.jpeg` — referência visual da escala de cinza.
- `assets/cor/paleta_referencia/VML_Color-SecondaryColors_2.jpeg` — referência visual da paleta secundária.

Conjunto completo, nada foi omitido nesta categoria (é leve por natureza). Para geração de CSS/design tokens, usar diretamente os valores HEX desta tabela — são a fonte primária, extraídos do texto oficial do guideline.

---

# 04. Tipografia

Fonte: Guideline oficial, seção 04 Typography (p.31-35).

## Fonte primária: Snowflake Sans

Fonte proprietária/custom da VML, desenhada para harmonizar com a geometria do símbolo Spark. Usar para **quase tudo, em quase todo lugar**.

- Peso padrão: **Medium**, em title case ou sentence case (mistura de maiúsculas/minúsculas — isso por si só já cria o tom tipográfico discreto da marca).
- Caixa alta (uppercase) é permitida só se o design/conceito exigir.
- Pesos adicionais servem para textura/hierarquia, não como padrão.
- Tamanhos extra-grandes: só para ênfase pontual, não usar em excesso.
- Em escalas grandes: apertar tracking/leading. Em corpo de texto: abrir leading para legibilidade.

### Pesos disponíveis neste pacote (`assets/tipografia/`)

Conjunto completo, nada foi omitido nesta categoria (é leve por natureza).

| Arquivo | Peso/estilo |
|---|---|
| `SnowflakeSans-Light.otf` | Light |
| `SnowflakeSans-LightItalic.otf` | Light Italic |
| `SnowflakeSans-Book.otf` | Book (peso "regular" da família) |
| `SnowflakeSans-Italic.otf` | Book Italic (itálico "regular") |
| `SnowflakeSans-Medium.otf` | Medium — **peso padrão de uso** |
| `SnowflakeSans-MediumItalic.otf` | Medium Italic |
| `SnowflakeSans-Bold.otf` | Bold |
| `SnowflakeSans-BoldItalic.otf` | Bold Italic |
| `SnowflakeSans-Black.otf` | Black — uso restrito (ex.: logos regionais com Spark) |
| `SnowflakeSans-BlackItalic.otf` | Black Italic |

### Família Inline (uso restrito, não usar como texto corrido)

| Arquivo | Peso/estilo |
|---|---|
| `SnowflakeInline-Inlinex1.otf` | Inline variante 1 |
| `SnowflakeInline-Inlinex2.otf` | Inline variante 2 |

Regra dura: **evitar usar os pesos Snowflake Sans Inline** para manter um visual limpo e consistente — são decorativos/display, não para corpo de texto ou títulos padrão.

## Fonte de sistema (fallback)

**Arial** — usar somente quando Snowflake Sans não estiver disponível (ex.: Google Slides, assinatura de e-mail). Não incluída neste pacote (é fonte de sistema, já disponível em qualquer ambiente). Pesos: Regular, Regular Italic, Bold, Bold Italic.

Regra prática para agentes: ao gerar HTML/e-mail/Google Slides onde Snowflake Sans não pode ser embutida, usar Arial como fallback declarado — não substituir por outra fonte (Helvetica, system-ui, etc.) sem necessidade técnica real.

## Watch-outs (não fazer)

- Não usar tipografia grande, bold e all-caps como estilo primário, a menos que o conceito exija.
- Cuidado com legibilidade ao usar pesos leves (Light) em escala pequena.
- Não usar outras famílias tipográficas como expressão de marca primária.
- Evitar tipografia excessivamente estilizada ou difícil de ler.

## Aplicação prática (agentes que geram documentos/slides/web)

- Definir Snowflake Sans Medium (`assets/tipografia/SnowflakeSans-Medium.otf`) como peso-base do corpo de texto e títulos em qualquer template (docx, pptx, HTML).
- Reservar Black/Bold para destaques pontuais e hierarquia, não como padrão de título.
- Nunca usar Inline em corpo de texto, parágrafos ou títulos funcionais.
- Em ambientes sem suporte a fontes customizadas, aplicar Arial e documentar a substituição como fallback técnico, não como escolha de estilo.

---

# 05. Layout e Grid

Fonte: Guideline oficial, seção 05 Layout (p.36-44). Seção sem asset associado — só regra.

## Princípios de layout

- Uso predominante do **quadrado e formas retilíneas**, sempre com ângulos retos de 90°.
- Layouts devem parecer feitos por humanos, como uma colagem — casual, limpo, sem esforço aparente ("effortless").
- Composições simples e editoriais, com sobreposição (layering) sutil quando necessário.
- Espaço negativo generoso e contraste de escala entre elementos para gerar interesse visual.
- Na dúvida: simplificar.

## The Square (elemento gráfico primário)

O quadrado ecoa a solidez e simetria do símbolo Spark — é o elemento que estabelece ritmo e consistência entre layouts e mídias.

Regras duras:
- **Não usar cantos arredondados nem círculos.**
- Usar apenas quadrados e retângulos com ângulos de 90° exatos.
- O quadrado pode ser pareado com outros formatos quando necessário em layout: proporções citadas no guideline incluem **9:16, 16:9 e 4:5** como formatos companheiros.

## Sistema "digital collage" (colagem digital)

Categorias de composição citadas no guideline, usadas como ponto de partida (não como grade obrigatória fixa):

- **Grid** — organização em grade.
- **Layer** — sobreposição de elementos.
- **Path** — composição ao longo de um caminho/trajetória.
- **Random** — distribuição aparentemente aleatória, mas estruturada.
- **Singular** — um elemento central dominante.
- **Abstract graphic** — elemento gráfico abstrato.

Checklist ao montar um layout customizado:
- Uso proeminente de quadrado e retângulos.
- Composições simples, em camadas, editoriais.
- Espaço negativo generoso.
- Contraste de escala ou repetição controlada de elementos.
- Estruturado, mas sem alinhamento perfeito/mecânico (o desalinhamento leve é intencional e faz parte do tom "Human").

Se o agente não tiver capacidade de design custom, o guideline recomenda usar os **templates de apresentação** oficiais como ponto de partida (ver `11_templates_apresentacao.md` — arquivos não incluídos neste pacote portátil, ver nota de exclusão).

## Dois usos do digital collage

1. **Housing imagery** — usar quadrados/formas retilíneas como moldura/container de imagens.
2. **Graphic element** — usar quadrados/formas retilíneas como elemento gráfico autônomo (sem imagem dentro).

## Watch-outs (não fazer)

- Evitar layouts excessivamente complexos — simplicidade facilita a compreensão da mensagem.
- Não usar outras formas geométricas quando um quadrado/retângulo resolveria.
- Não usar cantos arredondados — sempre 90°.
- Não sobrecarregar comunicações com muito conteúdo com excesso de elementos gráficos simultâneos.

---

# 06. Elementos de Design

Fonte: Guideline oficial, seção 06 Design Elements (p.45-57).

**Nota de escopo deste pacote portátil:** as categorias abaixo têm bibliotecas grandes no brand kit completo (dezenas de variações de cor/textura). Aqui só há 1-2 exemplos por categoria, o suficiente para um agente entender o estilo visual — não a biblioteca inteira. Se uma peça precisar de uma variação específica não incluída, sinalizar a necessidade em vez de recriar a partir do exemplo.

## Princípio central

**Não usar todos os elementos ao mesmo tempo.** Existe variedade de elementos justamente para escolher o mais adequado a cada necessidade — não empilhar supergraphic + halftone + hand-drawn + ilustração na mesma peça.

Priorizar sempre o uso do quadrado e outras formas retilíneas antes de qualquer elemento decorativo.

## 1. Quadrado singular (Singular square)

Sem asset — é uma forma geométrica simples (quadrado com ângulo de 90°), não um arquivo de marca. Usos: formatos quadrados (botões, coasters), detalhes quadrados (em gráficos, listas com marcadores).

## 2. Square supergraphic (fundos)

Fundos monocromáticos em cores de marca — forma simples de simular "digital collage" sem montar do zero. Disponíveis, no brand kit completo, em VML Black sobre fundos de cor escura, tom-sobre-tom monocromático, e monocromático em VML Black/cinzas/VML White (12 combinações no total).

Regra de legibilidade: ao sobrepor texto, usar a versão de **menor contraste** do supergraphic para não competir com o texto.

Exemplo incluído neste pacote: `assets/exemplos/exemplo_supergraphic_VMLBlack-on-DarkGreen.png`. As outras 11 combinações de cor (Blue-on-DarkBlue, Green-on-DarkGreen, LightGold-on-Gold, etc.) não estão incluídas — mesma lógica de seleção de cor de `03_cor.md` se aplica: escolher uma família por vez.

## 3. Spark halftone texture

Tratamento textural que cria um look de marca aplicado a imagens — usado majoritariamente como fundo tonal abstrato, mas também pode ser aplicado a algum assunto/imagem específica.

Watch-out técnico: **vibração de padrão em telas digitais** — para mitigar, aumentar a escala do elemento ou usar um pareamento de cor de menor contraste. Ao sobrepor texto, usar versão de menor contraste, igual ao supergraphic.

No brand kit completo existem dezenas de variações por família de cor (Black, Blue, Bronze, Gold, Gray, Green, Plum). Exemplo incluído neste pacote: `assets/exemplos/exemplo_spark_halftone_Green-Sky.jpg`.

## 4. Hand-drawn toolkit

Elementos renderizados à mão, estilo de linha/contorno gestual simples. **Não recriar nem gerar em estilo diferente** — usar exclusivamente os arquivos existentes. Uso com moderação, como detalhe sutil/tonal.

### 4a. Core values illustration (Heart, Brains, Courage)

Ilustrações de contorno simples para os valores da empresa. Usos citados: key art, fundos de Teams, pôsteres, cabeçalho de e-mail. **Não alterar nem recriar em estilo diferente.** Não incluídas neste pacote (não fazem parte do recorte "logo + exemplos leves" solicitado) — disponíveis no brand kit completo.

### 4b. Ícones hand-drawn (categorias temáticas)

O guideline cita um conjunto de ícones para substituir stock icons em decks (People/Global, Comms, Data Insights, Creative, Strategy, Technology, Journey/Timeline, Social, Misc, Health), com tamanho recomendado **máximo 120px, mínimo 50px**.

**Ausência confirmada (não apenas "não localizado"):** em 2026-07-22 foi feita uma busca direta por nome de arquivo e palavra-chave em toda a árvore do brand kit completo (`vml_brand_kit_2026-06-30/`, incluindo `04_elementos_de_design/`, templates `.pptx` e demais pastas) — nenhum arquivo separado correspondente a essas categorias foi encontrado. A hipótese mais provável é que esses ícones existam só como imagens embutidas dentro do PDF do guideline (519MB, não teve OCR/extração de imagem individual feita) ou dentro dos slides `.pptx` dos templates, não como assets exportados isoladamente. **Não inventar, não gerar com IA, e não tentar recriar a partir da descrição** — se uma peça precisar desses ícones, a ação correta é sinalizar ao usuário que o asset precisa ser extraído manualmente do PDF/template ou solicitado ao time de Brand Design (ver `14_contatos_e_governanca.md`).

### 4c. Detalhes adicionais (hand-drawn elements soltos)

Usar com moderação, como elemento de fundo; reduzir opacidade para efeito tonal. Não devem dominar o layout ou a mensagem. Tamanho máximo para uso pequeno: **40px**.

Exemplos incluídos neste pacote (formato GIF, leve): `assets/exemplos/exemplo_hand_drawn_checkmark.gif`, `assets/exemplos/exemplo_hand_drawn_arrow-up.gif`. No brand kit completo há mais variações (X, circle, rectangle, smiley face, arrow-forward) e versões em vídeo (.mov) — não incluídas aqui.

## 5. Ilustração customizada

Ilustrações de contorno simples sob encomenda, para visualizar ideias conceituais/editoriais que não podem ser comunicadas por fotografia. **Feitas internamente por um designer** — um agente não deve gerar essas ilustrações automaticamente; deve sinalizar a necessidade de contato com o time de Brand Design (ver `14_contatos_e_governanca.md`).

## Watch-outs gerais (não fazer)

- Não usar todos os elementos ao mesmo tempo numa única peça.
- Não usar elementos de marca em cores fora da paleta oficial.
- Não recriar um elemento se ele já existe no toolkit — usar o arquivo original.
- Não recriar ou imitar o estilo de ilustração sem contatar o time de marca.
- Não inventar uma variação de cor/textura que não esteja disponível neste pacote nem no brand kit completo.

---

# 07. Human First (filosofia criativa / sub-sistema visual)

Fonte: Guideline oficial, seção 07 (p.58-67) + `Human First Video Guidelines.pdf` (regras de vídeo; o arquivo de vídeo em si não está incluído neste pacote — ver `12_video_institucional.md`).

## Escopo de aplicação — LER ANTES DE USAR QUALQUER ASSET DESTA SEÇÃO

Human First é a filosofia criativa da VML, com um conjunto de assets visuais **dedicado e mais restrito** que o sistema de marca geral. Regra dura e não-negociável:

> **Não usar elementos Human First em comunicações que não sejam relacionadas a Human First.**

O logo Human First, o Inky Spark, o hand-lettering e o padrão de fundo **não são elementos decorativos genéricos** disponíveis para qualquer peça VML — são reservados para comunicações que tratam explicitamente da filosofia Human First.

## Logo Human First

Logo dedicado, em estilo "inky" (tinta) desenhado à mão.

- **Não recriar com fonte ou ferramenta de IA.** Traduções para outros idiomas só podem ser feitas de forma bespoke por um artista, com aprovação.
- Usar primariamente em VML Black e VML White.
- Usos: grande, para introduzir/apresentar a filosofia; como "tagline" em case study, pôster ou promoção; em headlines de apoio a mensagens Human First.

Assets incluídos neste pacote: `assets/exemplos/exemplo_human_first_logo_VMLBlack.png`, `assets/exemplos/exemplo_human_first_logo_VMLWhite.png` — são os arquivos oficiais completos (não recortes), só renomeados para clareza. Versões PSD/BMP de trabalho não incluídas (redundantes com o PNG para a maioria dos usos).

## Inky Spark (símbolo)

Conjunto dedicado de Sparks desenhados à mão. **Não recriar** — usar somente os arquivos existentes. Uso restrito a comunicações Human First.

Asset incluído neste pacote (1 exemplo por cor, o ícone "Fingerprint"): `assets/exemplos/exemplo_human_first_inky_spark_VMLBlack.png`, `assets/exemplos/exemplo_human_first_inky_spark_VMLWhite.png`. No brand kit completo há mais variações numeradas (2, 3) e um arquivo-fonte `.psd` grande — não incluídos aqui.

## Hand-lettering customizado

Deve ser usado apenas para apoiar expressões "Tier 1" de Human First. Deve ser feito de forma bespoke por um artista talentoso — **não gerar com IA ou fonte pronta**. Restrito a execuções centradas em Human First; não usar amplamente para a marca VML em geral. Sem arquivo associado (é produzido sob encomenda, caso a caso).

## Padrão de fundo (Background Pattern)

Gráfico hand-lettered customizado, usado como borda/textura adicional. Deve ser cortado (crop) para sangrar até as bordas da arte-final. Uso restrito a comunicações Human First.

Asset incluído neste pacote: `assets/exemplos/exemplo_human_first_padrao.png`.

## Encerramento (End Card)

Card de encerramento dedicado para vídeos Human First — é um arquivo de vídeo (`.mp4`), **não incluído neste pacote portátil** (ver `12_video_institucional.md`). Disponível no brand kit completo em `05_human_first/video/HumanFirst_EndCard.mp4`. **Não recriar.**

## Vídeo institucional "Anthemic" (Human First)

O arquivo de vídeo em si não está incluído neste pacote (ver nota de exclusão em `00_LEIA-ME_INSTRUCOES_PARA_AGENTES.md` e `12_video_institucional.md`). As regras de uso e adaptação abaixo, porém, valem integralmente e devem ser seguidas por qualquer agente que trabalhe com o vídeo a partir do brand kit completo:

- Vídeo dividido em 3 seções, com graus de flexibilidade diferentes:

| Seção | Tempo | Flexibilidade | Regra |
|---|---|---|---|
| Intro | 00:01–00:48 | **Não-flexível** | Manter exatamente como está: footage, mensagem e visuais originais. |
| Messaging Reel | 00:49–02:25 | **Flexível** | Pode substituir footage por trabalho local/regional/de cliente, mantendo estilo visual, abordagem de design e estrutura de copy do original. Estrutura obrigatória da frase: (1) "Human First and…" (2) mensagem-chave conectada ao trabalho. Idealmente destacar uma palavra-chave da segunda parte com tipografia manuscrita. |
| Ending | 02:25–02:53 | **Parcialmente flexível** | Recomendado manter como está; pode substituir footage para trabalho mais local, mas mensagem/visual/copy devem permanecer inalterados. Cenas centradas em pessoas. Usar as palavras HUMAN e FIRST como molduras/framing para destacar pessoas. |

- **Direitos de uso:** a versão original é a única aprovada para compartilhamento público. Tradução direta (sem edição de conteúdo) não precisa de aprovação prévia. Adaptações internas não precisam de aprovação prévia, mas a versão adaptada deve ser enviada para arquivo. **Qualquer adaptação para uso público externo exige aprovação prévia.** Contato: **alex.cree@vml.com**.

## Watch-outs (não fazer)

- Não usar elementos Human First em comunicações não relacionadas a Human First.
- Não fazer lockup do logo Human First com o logo VML.
- Não depender fortemente das cores secundárias da marca para materiais Human First — usar primariamente VML Black e VML White.
- Não alterar o logotipo VML para materiais Human First.
- Não replicar assets Human First, símbolos Inky Spark ou hand-lettering com renders de IA ou fontes prontas.
- Vídeo institucional: não alterar a seção Intro; não alterar mensagem/visual/copy da seção Ending; não publicar externamente uma adaptação sem aprovação prévia de alex.cree@vml.com.

---

# 08. Ambientes Físicos (escritórios, sinalização)

Fonte: Guideline oficial, seção 08 Environments (p.68-73). Seção sem asset associado — só regra.

Escopo: relevante só para tarefas de design de ambiente físico/sinalização/wayfinding, não para peças digitais/impressas comuns.

## Princípio

Escritórios devem reforçar Human/Confident/Premium, mas o design de marca **não deve definir sozinho** a estética do espaço — deve refletir também a cultura da região/equipe. O ambiente deve gerar sensação de calma, conforto, criatividade e foco.

## Função (sinalização/wayfinding)

- Simplicidade, consistência e facilidade de uso são obrigatórias nesses elementos.
- Entrada/recepção: branding simples, limpo e proeminente, em preto e branco. Priorizar o logo sobre o Spark, usados separadamente quando possível.
- Spark: uso secundário, sem exagero de escala — não deixar o Spark dominar o espaço de forma "barata"/vulgar. Manter premium.

## Forma (curadoria do espaço)

- Preferir arte emoldurada de alta qualidade e inspiração a murais gráficos genéricos ou mensagens de marca "kitsch".
- Reservar uma área para a filosofia Human First: logo, Inky Spark, linguagem de manifesto.
- Exibir os valores Brains, Heart e Courage usando os assets oficiais de ilustração (ver `07_human_first.md` e `06_elementos_de_design.md`).
- Mostrar exemplos de trabalho da agência emoldurados, como uma peça de arte.

## Cor e materiais

- Ao incorporar cor, partir primeiro da paleta de marca oficial (ver `03_cor.md`).
- Priorizar materiais, mobiliário e acabamentos premium.
- Manter sempre em mente: Human, Confident, Premium.

## Watch-outs (não fazer)

- Não deixar o design de marca definir sozinho a estética do espaço.
- Não deixar o espaço parecer frio, estéril ou sem inspiração.
- Não superusar ou superdimensionar o Spark no ambiente — manter premium.

---

# 09. Headshots (fotografia de perfil)

Fonte: Guideline oficial, seção 09 Headshots (p.74-77). Seção sem asset associado — só regra.

Escopo: uso interno, marketing geral, novos negócios. Padrão único de headshot para uniformidade entre comunicações; foi desenhado para ser **alcançável com smartphone ou webcam** — não exige estúdio fotográfico.

## Especificação obrigatória

- Coloração **preto e branco** (P&B).
- Fundo branco natural.
- Enquadramento cabeça e ombros, com o topo da cabeça **não cortado**.
- Orientação retrato (vertical, tall).
- Iluminação natural e uniforme — **sem sombras duras**.
- Expressão natural e autenticamente positiva — sério ou descontraído, ambos válidos, desde que autêntico.
- Dica prática: usar o modo "portrait mode: high-key light mono" da câmera do smartphone, ou as ferramentas de efeito de fundo do Teams, para simular o fundo branco.

## Watch-outs (não fazer)

- Não usar imagem colorida em headshots.
- Evitar sombras duras ou iluminação ruim.
- Preferir fotografar contra fundo branco simples antes de tentar recortar/remover fundo digitalmente.

---

# 10. Social Media (headers)

Fonte: assets do brand kit, pasta `07_social/`. **Não há uma seção dedicada no guideline principal de 123 páginas para social media** — não invente regras específicas de social que não estejam no texto oficial. Aplicam-se as regras gerais de logo (`02`), cor (`03`) e elementos (`06`); esta página cataloga os headers prontos.

## Headers existentes no brand kit completo (não todos incluídos neste pacote)

Existem headers pré-desenhados para três plataformas — Facebook, LinkedIn e X — cada uma com 7 variantes de fundo: `corevalues`, `darkbronze`, `darkgold`, `darkgreen`, `darkplum`, `humanfirst_black`, `humanfirst_white`. 21 arquivos no total, todos PNG leves (1,5MB somados).

## Exemplos incluídos neste pacote

- `assets/exemplos/exemplo_social_linkedin_corevalues.png`
- `assets/exemplos/exemplo_social_linkedin_darkgreen.png`

As demais 19 combinações (Facebook, X, e as outras variantes de cor do LinkedIn) não foram incluídas — servem só para ilustrar o padrão visual. Se uma peça precisar de uma plataforma/variante específica não incluída, sinalizar a necessidade.

## Regra de seleção para agentes

1. Se a peça não é sobre Human First: escolher entre `corevalues`, `darkbronze`, `darkgold`, `darkgreen`, `darkplum` — **uma única variante de cor por peça/campanha**, nunca misturar famílias de cor secundária (regra geral de `03_cor.md`).
2. Se a peça é especificamente sobre a filosofia Human First: usar `humanfirst_black` ou `humanfirst_white`, nunca as variantes de cor secundária.
3. Não há variante "darkblue" nos headers sociais (apesar de "Blue" existir na paleta secundária) — limitação real do asset disponível. Se precisar de um header azul, sinalizar que é necessário criar o asset (ver `14_contatos_e_governanca.md`), não gerar uma versão própria a partir do zero sem aprovação.

---

# 11. Templates de Apresentação e Documentos

Fonte: inspeção direta dos arquivos `.pptx` no brand kit completo (python-pptx). **Os arquivos `.pptx`/`.key`/`.docx` em si NÃO estão incluídos neste pacote portátil** (339MB no total) — o que segue é o manifesto textual dos layouts existentes, para um agente saber o que pedir/procurar no brand kit completo, não para montar o deck localmente sem esses arquivos.

Regra geral: **sempre partir de um destes templates**, nunca de um slide em branco, quando a entrega for um deck ou documento com identidade VML.

## 1. Deck geral (uso comum, formato 4:3 widescreen 13.33"×7.5")

Arquivo (no brand kit completo): `06_templates/apresentacao/VML Template Feb 2026.pptx` — 2 masters (Light/Dark), 42 layouts cada, idênticos entre si:

`Cover 1.0` · `Cover 1.1 Image` · `Agenda` · `Team` · `Divider` · `Divider - No line` · `Divider - Statement` · `Interior 0.1` · `Interior 0.2` · `Interior 0.3` · `Interior 1.0` · `Interior 2.0` · `Interior 2.1` · `Interior 3.0` · `Interior 4.0` · `Interior 5.0` · `Interior 6.0` · `Interior 7.0` · `Interior 8.0` · `Interior Process 3` · `Interior Process 4` · `Interior Process 5` · `Interior Storyboard` · `Interior Picture Grid` · `Interior Collage 1.1` · `Interior Collage 1.2` · `Interior Collage 2.0` · `Interior Collage 3.0` · `Interior Collage 3.1` · `Interior Collage 3.2` · `Interior Collage 3.3` · `Interior Collage 3.4` · `Statement 1.0` a `Statement 6.0` · `End 1.0` a `End 3.0` · `Empty` · `Divider - Grey` · `Divider - No Line -Grey`

## 2. Cred deck global (formato widescreen grande, 26.67"×15")

Arquivo (no brand kit completo): `06_templates/apresentacao/VML Global Cred Deck R3 - May 2026.pptx` — layouts: `COVER 1 Photo A` · `Simple Divider 1` · `Simple Divider 2` · `1_Simple Divider 2` · `Simple Divider 1 Reduced Metadata` · `Simple Divider 2 Reduced Metadata` · `INTRO 4` · `INTERIOR 0.0 Reduced` · `INTERIOR 0.5` · `INTERIOR 0.5 Dark` · `INTERIOR 9` · `INTERIOR Full 9 Image Grid` · `INTERIOR Full 15 Image Grid` · `END 1B Dark` · `END 1B Light` · `END 2 DARK` · `END 2 Light` · `[BLANK] Black` · `[BLANK]` · `Team` · `Interior 1 Light` · `Interior 1 Dark` · `Interior 2 Dark` · `Interior 2 Light` · `Agenda 1` · `TOC`

Uso: deck institucional/comercial (credenciais da agência) para pitches — não usar para decks internos de projeto (usar o template geral acima).

## 3. Case Study Template (formato 4:3 widescreen 13.33"×7.5")

Arquivo (no brand kit completo): `06_templates/case_study/VML Case Study Template 2026.pptx` (também `.key`) — layouts: `Cover 1.0` · `Cover + Image` · `Cover with Image` · `Divider - Statement` · `Divider - Grey`/`Divider` · `Divider + Image 1` · `Divider + Image 2` · `Image` · `Video` · `Case Study Summary Board` · `Manifesto` · `Quote or Statement` · `Opportunity` · `Inspiration` · `Idea` · `Headline` · `Our Creative Philosophy` · `Human First` · `Headline + 3 Images` · `Headline + 4 Images` · `Image Collage 2` · `Image Collage 3` · `End 1.0` a `End 3.0` · `Empty`

Nota: layout `Human First` e `Our Creative Philosophy` — usar exclusivamente para a seção que trata da filosofia Human First (ver `07_human_first.md`).

Estrutura editorial sugerida: Cover → Divider/Opportunity → Inspiration → Idea → Our Creative Philosophy/Human First → Headline + Images / Image Collage → Case Study Summary Board → Quote or Statement → End.

## 4. Keynote (Apple)

Arquivo (no brand kit completo): `06_templates/apresentacao/VML-2026-JAN-Keynote-Template 1.key` — equivalente ao template geral.

## 5. Letterhead (papel timbrado)

No brand kit completo, `06_templates/letterhead/3-Final files/`: `VML_Letterhead.ai`/`.docx`/`.pdf` (formato padrão) e `VML_Letterhead_A4.ai`/`.docx`/`.pdf` (A4 — **usar a versão A4 para Brasil**). Pastas `1-Reference files` e `2-Working files` são material interno do time de design, não usar como fonte final.

## Regra de aplicação para agentes que geram apresentações/documentos automaticamente

1. Como os arquivos-fonte não estão neste pacote, o agente deve primeiro confirmar que tem acesso ao brand kit completo (ou solicitar que o arquivo específico seja fornecido) antes de montar o deck.
2. Identificar o tipo de entrega e escolher o arquivo-fonte correspondente acima — nunca partir de um layout genérico não-VML.
3. Duplicar o slide/layout mais próximo do conteúdo pretendido, preenchendo apenas os placeholders existentes — não criar elementos novos de master fora do template.
4. Escolher **um** master (Light ou Dark) por documento.
5. Ao usar `Statement` ou `Quote or Statement`, aplicar a regra de tipografia de `04_tipografia.md` e a regra "menos é mais" de `01_principios_e_filosofia.md`.

---

# 12. Vídeo Institucional

Fonte: assets do brand kit completo (`01_logo/ident_animado/`, `04_elementos_de_design/*_animado/`, `08_video_institucional/`) + `Human First Video Guidelines.pdf`.

**Nenhum arquivo de vídeo está incluído neste pacote portátil** (exclusão intencional, pedida pelo usuário). Este documento existe só para que um agente saiba que esses assets existem e onde encontrá-los no brand kit completo, e para preservar as regras de uso mesmo sem o arquivo físico à mão.

## Assets de vídeo existentes no brand kit completo, por finalidade

| Finalidade | Path (brand kit completo) | Regra de uso |
|---|---|---|
| Abertura/ident de marca (logo animado) | `01_logo/ident_animado/VML_Ident_BlackOnWhite_v2_16x9.mp4`, `VML_Ident_WhiteOnBlack_v2_16x9.mp4` | Usar como abertura/vinheta de qualquer vídeo VML — escolher a versão conforme o fundo do vídeo. Não recriar a animação. |
| Fundo animado (textura) | `04_elementos_de_design/background_animado/VML25-{Black-Lights,Blue-Waves,Gold-Lights,Green-Sky,Grey-Lights}.mp4` | Usar como fundo em loop atrás de texto/logo, seguindo a regra de família de cor única de `03_cor.md`. |
| Supergraphic animado | `04_elementos_de_design/supergraphics_animado/VML25_Supergraphics_KV_*.mp4` | Mesma lógica do supergraphic estático (`06_elementos_de_design.md`), em versão em movimento. |
| Vídeo institucional "Anthemic" (Human First) | ver `07_human_first.md` | Regras de flexibilidade por seção e aprovação para uso público. |
| End card Human First | `05_human_first/video/HumanFirst_EndCard.mp4` | Só em vídeos Human First. |
| Brand sizzle reel | `08_video_institucional/VML_BrandSizzle2025_SizzleOnly_09-JF.mp4` | Reel de marca 2025 — material de referência/institucional geral. Não é o vídeo Anthemic; não segue as regras de seção do Human First Video Guidelines. |

## Regra de seleção para agentes que montam vídeo

1. Definir se o vídeo é institucional geral (ident + fundo/supergraphic animado) ou especificamente Human First (Anthemic + End Card) — não misturar os dois sistemas na mesma peça.
2. Como nenhum desses arquivos está neste pacote, o agente deve confirmar acesso ao brand kit completo (ou pedir que o arquivo seja fornecido) antes de montar qualquer vídeo — não improvisar um ident ou fundo animado próprio.
3. Se Human First: seguir à risca a tabela de flexibilidade por seção em `07_human_first.md`, e não publicar externamente sem aprovação de alex.cree@vml.com.

---

# 13. Checklist de QA — rodar antes de entregar qualquer peça VML

Este checklist é o gate final. Se qualquer item falhar, corrigir antes de considerar a peça pronta — não entregar com ressalva verbal ("está quase certo, mas...").

## Logo (`02_logo.md`)
- [ ] O logotipo/Spark é o **arquivo binário original** incluído em `assets/logo/` (ou resolvido via `asset_manifest.json`) — importado/inserido diretamente, não redesenhado, recriado em SVG à mão, gerado por IA de imagem, recolorido fora de preto/branco, distorcido ou com cantos alterados.
- [ ] Tamanho do logotipo ≥ 0,5" (impresso) ou ≥ 24px (digital). Tamanho do Spark segue a mesma regra.
- [ ] Se logo e Spark aparecem juntos e separados: Spark não é maior que a altura do logotipo.
- [ ] Logotipo e Spark não estão preenchidos com cores diferentes na mesma peça.
- [ ] Nenhum lockup novo foi inventado (nenhuma variação de logo fora do que existe no asset manifest).

## Cor (`03_cor.md`)
- [ ] A peça usa no máximo **uma** família de cor secundária (Bronze, Gold, Green, Blue ou Plum) além de VML Black/White.
- [ ] Nenhuma cor usada tem HEX fora da tabela oficial (core, grayscale, secundária).
- [ ] Combinações tom-sobre-tom só aparecem em contexto de fundo/textura, nunca em texto/logo que precisa ser lido com prioridade.
- [ ] Não há uso de vermelho saturado como cor de destaque na assinatura ou no Spark.

## Tipografia (`04_tipografia.md`)
- [ ] Fonte usada é Snowflake Sans (incluída em `assets/tipografia/`) ou Arial como fallback declarado, quando Snowflake Sans não está disponível no ambiente de destino.
- [ ] Peso padrão do corpo/títulos é Medium; Black/Bold restrito a destaques pontuais.
- [ ] Nenhum peso "Inline" foi usado em corpo de texto ou título funcional.

## Layout (`05_layout_e_grid.md`)
- [ ] Formas usadas são quadrados/retângulos com ângulos de 90° — nenhum canto arredondado ou círculo decorativo.
- [ ] Há espaço negativo suficiente; a composição não está sobrecarregada de elementos.
- [ ] O layout não parece "perfeitamente alinhado/mecânico" ao ponto de perder o tom humano, nem "bagunçado" ao ponto de perder o tom premium.

## Elementos de design (`06_elementos_de_design.md`)
- [ ] Não há mais de um tipo de elemento decorativo empilhado (ex.: supergraphic + halftone + hand-drawn na mesma peça).
- [ ] Se a variação de cor/textura necessária não está entre os exemplos incluídos em `assets/exemplos/`, isso foi sinalizado — não improvisado a partir do exemplo disponível.
- [ ] Nenhum elemento do toolkit foi recriado do zero quando já existe (ou deveria existir) um arquivo oficial equivalente.

## Human First (`07_human_first.md`) — só se aplicável
- [ ] A peça é genuinamente sobre a filosofia Human First (não é uso decorativo de conveniência).
- [ ] Nenhum asset Human First (logo, Inky Spark, hand-lettering, padrão de fundo, end card) foi usado fora desse escopo.
- [ ] Se envolve o vídeo Anthemic: a seção Intro está intocada; a seção Ending manteve mensagem/visual/copy; nenhuma adaptação externa foi publicada sem aprovação de alex.cree@vml.com. Nota: o arquivo de vídeo não está neste pacote — confirmar acesso ao brand kit completo antes de qualquer edição.

## Templates e vídeo (`11_templates_apresentacao.md`, `12_video_institucional.md`) — só se aplicável
- [ ] Antes de montar deck/documento/vídeo, foi confirmado acesso ao brand kit completo (esses arquivos-fonte não estão neste pacote portátil).
- [ ] O deck/documento parte de um dos templates oficiais catalogados, não de um slide/documento em branco genérico.
- [ ] Um único master (Light ou Dark) é usado de forma consistente no documento.
- [ ] Os nomes de layout usados existem de fato no template-fonte (conferir contra a lista em `11_templates_apresentacao.md`).

## Governança (`14_contatos_e_governanca.md`)
- [ ] Nenhuma peça que o guideline marca como "não recriar" ou "contatar Brand Design" foi gerada do zero por IA sem sinalizar a necessidade de aprovação humana.
- [ ] Se a peça é para uso público externo e envolve algo sinalizado como "requer aprovação prévia", isso foi explicitamente comunicado ao usuário antes da entrega, não decidido silenciosamente pelo agente.

---

# 14. Contatos e Governança

Fonte: Guideline oficial (contatos citados no rodapé e em seções específicas) + `Human First Video Guidelines.pdf`.

## Contatos oficiais citados no guideline

| Nome | E-mail | Escopo |
|---|---|---|
| Alex Cree | alex.cree@vml.com | Perguntas gerais sobre o guideline; aprovações e arquivos abertos do vídeo Anthemic/Human First |
| Rachel Mozena | rachel.mozena@vml.com | Perguntas gerais sobre o guideline |

Download oficial de logos, arquivos de cor (.ase) e demais assets atualizados: **my.vml.com** (fonte canônica — este pacote portátil é uma seleção pontual datada de 2026-06-30; em caso de dúvida sobre versão mais recente, my.vml.com é a fonte de verdade).

## Situações que exigem contato humano / aprovação — não resolver via geração automática

1. Criação de qualquer novo logo, lockup ou variação de arquitetura de marca não catalogada (`02_logo.md`).
2. Tradução ou recriação do logo Human First, Inky Spark, ou hand-lettering customizado (`07_human_first.md`) — exige artista bespoke com aprovação.
3. Ilustração customizada em estilo de contorno simples além do que já existe no toolkit (`06_elementos_de_design.md`) — feita internamente por um designer.
4. Qualquer adaptação do vídeo Anthemic/Human First destinada a **uso público externo** (`07_human_first.md`) — exige aprovação prévia via alex.cree@vml.com.
5. Qualquer necessidade de asset que não existe **neste pacote portátil nem no brand kit completo** (ex.: header social azul) — sinalizar a lacuna, não gerar substituto não oficial.
6. Qualquer necessidade de asset que existe no brand kit completo mas foi deliberadamente deixado fora deste pacote (templates `.pptx`, vídeos, biblioteca completa de texturas — ver `00_LEIA-ME_INSTRUCOES_PARA_AGENTES.md`) — sinalizar que é preciso acessar o brand kit completo, não recriar a partir dos exemplos incluídos.

## Regra de conduta para agentes

Quando uma tarefa esbarrar em qualquer item acima, o agente deve:
1. Parar antes de gerar a peça "por conta própria".
2. Informar ao usuário, explicitamente, qual regra do guideline está sendo acionada e por quê.
3. Sugerir o contato/canal correto (tabela acima) ou o caminho de acesso ao brand kit completo, conforme o caso.

Isso não é burocracia por burocracia: o guideline é claro que elementos como Human First e ilustração customizada dependem de execução artesanal específica para preservar autenticidade — uma versão gerada por IA nesses casos falha no objetivo declarado da marca, mesmo que visualmente pareça "parecida".

---

## Manifesto de assets (asset_manifest.json)

```json
{
  "gerado_em": "2026-06-30",
  "tipo_de_pacote": "portatil_autossuficiente",
  "observacao": "Este manifesto cobre apenas os arquivos fisicamente incluídos na pasta assets/ deste pacote. A seção 'nao_incluido_no_pacote' documenta o que existe no brand kit completo mas foi deixado de fora, e onde encontrar caso necessário.",
  "total_arquivos_incluidos": 55,
  "assets_incluidos": [
    {
      "path_relativo": "assets/cor/VML-Brand-Colors-CMYK.ase",
      "categoria": "cor",
      "arquivo": "VML-Brand-Colors-CMYK.ase",
      "formato": "ase",
      "tamanho_bytes": 1820
    },
    {
      "path_relativo": "assets/cor/VML-Brand-Colors-RGB.ase",
      "categoria": "cor",
      "arquivo": "VML-Brand-Colors-RGB.ase",
      "formato": "ase",
      "tamanho_bytes": 1224
    },
    {
      "path_relativo": "assets/cor/paleta_referencia/VML_Color-SecondaryColors_2.jpeg",
      "categoria": "cor",
      "arquivo": "VML_Color-SecondaryColors_2.jpeg",
      "formato": "jpeg",
      "tamanho_bytes": 475629
    },
    {
      "path_relativo": "assets/cor/paleta_referencia/VML_Color_Primary_BW_Grays_2.jpeg",
      "categoria": "cor",
      "arquivo": "VML_Color_Primary_BW_Grays_2.jpeg",
      "formato": "jpeg",
      "tamanho_bytes": 276462
    },
    {
      "path_relativo": "assets/exemplos/exemplo_hand_drawn_arrow-up.gif",
      "categoria": "exemplo_ilustrativo",
      "arquivo": "exemplo_hand_drawn_arrow-up.gif",
      "formato": "gif",
      "tamanho_bytes": 167470
    },
    {
      "path_relativo": "assets/exemplos/exemplo_hand_drawn_checkmark.gif",
      "categoria": "exemplo_ilustrativo",
      "arquivo": "exemplo_hand_drawn_checkmark.gif",
      "formato": "gif",
      "tamanho_bytes": 173489
    },
    {
      "path_relativo": "assets/exemplos/exemplo_human_first_inky_spark_VMLBlack.png",
      "categoria": "exemplo_ilustrativo",
      "arquivo": "exemplo_human_first_inky_spark_VMLBlack.png",
      "formato": "png",
      "tamanho_bytes": 1452139
    },
    {
      "path_relativo": "assets/exemplos/exemplo_human_first_inky_spark_VMLWhite.png",
      "categoria": "exemplo_ilustrativo",
      "arquivo": "exemplo_human_first_inky_spark_VMLWhite.png",
      "formato": "png",
      "tamanho_bytes": 1452143
    },
    {
      "path_relativo": "assets/exemplos/exemplo_human_first_logo_VMLBlack.png",
      "categoria": "exemplo_ilustrativo",
      "arquivo": "exemplo_human_first_logo_VMLBlack.png",
      "formato": "png",
      "tamanho_bytes": 310628
    },
    {
      "path_relativo": "assets/exemplos/exemplo_human_first_logo_VMLWhite.png",
      "categoria": "exemplo_ilustrativo",
      "arquivo": "exemplo_human_first_logo_VMLWhite.png",
      "formato": "png",
      "tamanho_bytes": 306177
    },
    {
      "path_relativo": "assets/exemplos/exemplo_human_first_padrao.png",
      "categoria": "exemplo_ilustrativo",
      "arquivo": "exemplo_human_first_padrao.png",
      "formato": "png",
      "tamanho_bytes": 2635148
    },
    {
      "path_relativo": "assets/exemplos/exemplo_social_linkedin_corevalues.png",
      "categoria": "exemplo_ilustrativo",
      "arquivo": "exemplo_social_linkedin_corevalues.png",
      "formato": "png",
      "tamanho_bytes": 122546
    },
    {
      "path_relativo": "assets/exemplos/exemplo_social_linkedin_darkgreen.png",
      "categoria": "exemplo_ilustrativo",
      "arquivo": "exemplo_social_linkedin_darkgreen.png",
      "formato": "png",
      "tamanho_bytes": 20721
    },
    {
      "path_relativo": "assets/exemplos/exemplo_spark_halftone_Green-Sky.jpg",
      "categoria": "exemplo_ilustrativo",
      "arquivo": "exemplo_spark_halftone_Green-Sky.jpg",
      "formato": "jpg",
      "tamanho_bytes": 1761378
    },
    {
      "path_relativo": "assets/exemplos/exemplo_supergraphic_VMLBlack-on-DarkGreen.png",
      "categoria": "exemplo_ilustrativo",
      "arquivo": "exemplo_supergraphic_VMLBlack-on-DarkGreen.png",
      "formato": "png",
      "tamanho_bytes": 70120
    },
    {
      "path_relativo": "assets/logo/vmlblack/AI/VMLBLACK Icon Snowflake-CMYK.ai",
      "categoria": "logo_oficial_preto",
      "arquivo": "VMLBLACK Icon Snowflake-CMYK.ai",
      "formato": "ai",
      "tamanho_bytes": 1000847
    },
    {
      "path_relativo": "assets/logo/vmlblack/AI/VMLBLACK Icon Snowflake-RGB.ai",
      "categoria": "logo_oficial_preto",
      "arquivo": "VMLBLACK Icon Snowflake-RGB.ai",
      "formato": "ai",
      "tamanho_bytes": 161294
    },
    {
      "path_relativo": "assets/logo/vmlblack/AI/VMLBLACK Wordmark VML-CMYK.ai",
      "categoria": "logo_oficial_preto",
      "arquivo": "VMLBLACK Wordmark VML-CMYK.ai",
      "formato": "ai",
      "tamanho_bytes": 986131
    },
    {
      "path_relativo": "assets/logo/vmlblack/AI/VMLBLACK Wordmark VML-RGB.ai",
      "categoria": "logo_oficial_preto",
      "arquivo": "VMLBLACK Wordmark VML-RGB.ai",
      "formato": "ai",
      "tamanho_bytes": 147235
    },
    {
      "path_relativo": "assets/logo/vmlblack/EPS/VMLBLACK Icon Snowflake-CMYK.eps",
      "categoria": "logo_oficial_preto",
      "arquivo": "VMLBLACK Icon Snowflake-CMYK.eps",
      "formato": "eps",
      "tamanho_bytes": 870630
    },
    {
      "path_relativo": "assets/logo/vmlblack/EPS/VMLBLACK Icon Snowflake-RGB.eps",
      "categoria": "logo_oficial_preto",
      "arquivo": "VMLBLACK Icon Snowflake-RGB.eps",
      "formato": "eps",
      "tamanho_bytes": 876418
    },
    {
      "path_relativo": "assets/logo/vmlblack/EPS/VMLBLACK Wordmark VML-CMYK.eps",
      "categoria": "logo_oficial_preto",
      "arquivo": "VMLBLACK Wordmark VML-CMYK.eps",
      "formato": "eps",
      "tamanho_bytes": 2518422
    },
    {
      "path_relativo": "assets/logo/vmlblack/EPS/VMLBLACK Wordmark VML-RGB.eps",
      "categoria": "logo_oficial_preto",
      "arquivo": "VMLBLACK Wordmark VML-RGB.eps",
      "formato": "eps",
      "tamanho_bytes": 2524210
    },
    {
      "path_relativo": "assets/logo/vmlblack/JPG/VMLBLACK Icon Snowflake-RGB.jpg",
      "categoria": "logo_oficial_preto",
      "arquivo": "VMLBLACK Icon Snowflake-RGB.jpg",
      "formato": "jpg",
      "tamanho_bytes": 104713
    },
    {
      "path_relativo": "assets/logo/vmlblack/JPG/VMLBLACK Wordmark VML-RGB.jpg",
      "categoria": "logo_oficial_preto",
      "arquivo": "VMLBLACK Wordmark VML-RGB.jpg",
      "formato": "jpg",
      "tamanho_bytes": 143935
    },
    {
      "path_relativo": "assets/logo/vmlblack/PNG/VMLBLACK Icon Snowflake-RGB.png",
      "categoria": "logo_oficial_preto",
      "arquivo": "VMLBLACK Icon Snowflake-RGB.png",
      "formato": "png",
      "tamanho_bytes": 60099
    },
    {
      "path_relativo": "assets/logo/vmlblack/PNG/VMLBLACK Wordmark VML-RGB.png",
      "categoria": "logo_oficial_preto",
      "arquivo": "VMLBLACK Wordmark VML-RGB.png",
      "formato": "png",
      "tamanho_bytes": 170042
    },
    {
      "path_relativo": "assets/logo/vmlblack/SVG/VMLBLACK Icon Snowflake-RGB.svg",
      "categoria": "logo_oficial_preto",
      "arquivo": "VMLBLACK Icon Snowflake-RGB.svg",
      "formato": "svg",
      "tamanho_bytes": 707
    },
    {
      "path_relativo": "assets/logo/vmlblack/SVG/VMLBLACK Wordmark VML-RGB.svg",
      "categoria": "logo_oficial_preto",
      "arquivo": "VMLBLACK Wordmark VML-RGB.svg",
      "formato": "svg",
      "tamanho_bytes": 519
    },
    {
      "path_relativo": "assets/logo/vmlwhite/AI/VMLWHITE Icon Snowflake-CMYK.ai",
      "categoria": "logo_oficial_branco",
      "arquivo": "VMLWHITE Icon Snowflake-CMYK.ai",
      "formato": "ai",
      "tamanho_bytes": 1000458
    },
    {
      "path_relativo": "assets/logo/vmlwhite/AI/VMLWHITE Icon Snowflake-RGB.ai",
      "categoria": "logo_oficial_branco",
      "arquivo": "VMLWHITE Icon Snowflake-RGB.ai",
      "formato": "ai",
      "tamanho_bytes": 161298
    },
    {
      "path_relativo": "assets/logo/vmlwhite/AI/VMLWHITE Wordmark VML-CMYK.ai",
      "categoria": "logo_oficial_branco",
      "arquivo": "VMLWHITE Wordmark VML-CMYK.ai",
      "formato": "ai",
      "tamanho_bytes": 1000186
    },
    {
      "path_relativo": "assets/logo/vmlwhite/AI/VMLWHITE Wordmark VML-RGB.ai",
      "categoria": "logo_oficial_branco",
      "arquivo": "VMLWHITE Wordmark VML-RGB.ai",
      "formato": "ai",
      "tamanho_bytes": 161034
    },
    {
      "path_relativo": "assets/logo/vmlwhite/EPS/VMLWHITE Icon Snowflake-CMYK.eps",
      "categoria": "logo_oficial_branco",
      "arquivo": "VMLWHITE Icon Snowflake-CMYK.eps",
      "formato": "eps",
      "tamanho_bytes": 870590
    },
    {
      "path_relativo": "assets/logo/vmlwhite/EPS/VMLWHITE Icon Snowflake-RGB.eps",
      "categoria": "logo_oficial_branco",
      "arquivo": "VMLWHITE Icon Snowflake-RGB.eps",
      "formato": "eps",
      "tamanho_bytes": 876374
    },
    {
      "path_relativo": "assets/logo/vmlwhite/EPS/VMLWHITE Wordmark VML-CMYK.eps",
      "categoria": "logo_oficial_branco",
      "arquivo": "VMLWHITE Wordmark VML-CMYK.eps",
      "formato": "eps",
      "tamanho_bytes": 2518450
    },
    {
      "path_relativo": "assets/logo/vmlwhite/EPS/VMLWHITE Wordmark VML-RGB.eps",
      "categoria": "logo_oficial_branco",
      "arquivo": "VMLWHITE Wordmark VML-RGB.eps",
      "formato": "eps",
      "tamanho_bytes": 2524222
    },
    {
      "path_relativo": "assets/logo/vmlwhite/JPG/VMLWHITE Icon Snowflake-RGB.jpg",
      "categoria": "logo_oficial_branco",
      "arquivo": "VMLWHITE Icon Snowflake-RGB.jpg",
      "formato": "jpg",
      "tamanho_bytes": 49787
    },
    {
      "path_relativo": "assets/logo/vmlwhite/JPG/VMLWHITE Wordmark VML-RGB.jpg",
      "categoria": "logo_oficial_branco",
      "arquivo": "VMLWHITE Wordmark VML-RGB.jpg",
      "formato": "jpg",
      "tamanho_bytes": 94712
    },
    {
      "path_relativo": "assets/logo/vmlwhite/PNG/VMLWHITE Icon Snowflake-RGB.png",
      "categoria": "logo_oficial_branco",
      "arquivo": "VMLWHITE Icon Snowflake-RGB.png",
      "formato": "png",
      "tamanho_bytes": 60101
    },
    {
      "path_relativo": "assets/logo/vmlwhite/PNG/VMLWHITE Wordmark VML-RGB.png",
      "categoria": "logo_oficial_branco",
      "arquivo": "VMLWHITE Wordmark VML-RGB.png",
      "formato": "png",
      "tamanho_bytes": 170064
    },
    {
      "path_relativo": "assets/logo/vmlwhite/SVG/VMLWHITE Icon Snowflake-RGB.svg",
      "categoria": "logo_oficial_branco",
      "arquivo": "VMLWHITE Icon Snowflake-RGB.svg",
      "formato": "svg",
      "tamanho_bytes": 707
    },
    {
      "path_relativo": "assets/logo/vmlwhite/SVG/VMLWHITE Wordmark VML-RGB.svg",
      "categoria": "logo_oficial_branco",
      "arquivo": "VMLWHITE Wordmark VML-RGB.svg",
      "formato": "svg",
      "tamanho_bytes": 519
    },
    {
      "path_relativo": "assets/tipografia/SnowflakeInline-Inlinex1.otf",
      "categoria": "tipografia",
      "arquivo": "SnowflakeInline-Inlinex1.otf",
      "formato": "otf",
      "tamanho_bytes": 58148
    },
    {
      "path_relativo": "assets/tipografia/SnowflakeInline-Inlinex2.otf",
      "categoria": "tipografia",
      "arquivo": "SnowflakeInline-Inlinex2.otf",
      "formato": "otf",
      "tamanho_bytes": 73536
    },
    {
      "path_relativo": "assets/tipografia/SnowflakeSans-Black.otf",
      "categoria": "tipografia",
      "arquivo": "SnowflakeSans-Black.otf",
      "formato": "otf",
      "tamanho_bytes": 42916
    },
    {
      "path_relativo": "assets/tipografia/SnowflakeSans-BlackItalic.otf",
      "categoria": "tipografia",
      "arquivo": "SnowflakeSans-BlackItalic.otf",
      "formato": "otf",
      "tamanho_bytes": 43176
    },
    {
      "path_relativo": "assets/tipografia/SnowflakeSans-Bold.otf",
      "categoria": "tipografia",
      "arquivo": "SnowflakeSans-Bold.otf",
      "formato": "otf",
      "tamanho_bytes": 43096
    },
    {
      "path_relativo": "assets/tipografia/SnowflakeSans-BoldItalic.otf",
      "categoria": "tipografia",
      "arquivo": "SnowflakeSans-BoldItalic.otf",
      "formato": "otf",
      "tamanho_bytes": 43400
    },
    {
      "path_relativo": "assets/tipografia/SnowflakeSans-Book.otf",
      "categoria": "tipografia",
      "arquivo": "SnowflakeSans-Book.otf",
      "formato": "otf",
      "tamanho_bytes": 42208
    },
    {
      "path_relativo": "assets/tipografia/SnowflakeSans-Italic.otf",
      "categoria": "tipografia",
      "arquivo": "SnowflakeSans-Italic.otf",
      "formato": "otf",
      "tamanho_bytes": 42532
    },
    {
      "path_relativo": "assets/tipografia/SnowflakeSans-Light.otf",
      "categoria": "tipografia",
      "arquivo": "SnowflakeSans-Light.otf",
      "formato": "otf",
      "tamanho_bytes": 41516
    },
    {
      "path_relativo": "assets/tipografia/SnowflakeSans-LightItalic.otf",
      "categoria": "tipografia",
      "arquivo": "SnowflakeSans-LightItalic.otf",
      "formato": "otf",
      "tamanho_bytes": 41932
    },
    {
      "path_relativo": "assets/tipografia/SnowflakeSans-Medium.otf",
      "categoria": "tipografia",
      "arquivo": "SnowflakeSans-Medium.otf",
      "formato": "otf",
      "tamanho_bytes": 42992
    },
    {
      "path_relativo": "assets/tipografia/SnowflakeSans-MediumItalic.otf",
      "categoria": "tipografia",
      "arquivo": "SnowflakeSans-MediumItalic.otf",
      "formato": "otf",
      "tamanho_bytes": 43116
    }
  ],
  "nao_incluido_no_pacote": [
    {
      "categoria": "video",
      "descricao": "Ident animado, backgrounds animados, supergraphics animados, vídeo institucional, vídeo Anthemic Human First, end card Human First",
      "onde_encontrar": "brand kit completo: 01_logo/ident_animado, 04_elementos_de_design/*_animado, 05_human_first/video, 08_video_institucional"
    },
    {
      "categoria": "templates_apresentacao",
      "descricao": "Arquivos .pptx/.key/.docx completos (deck geral, cred deck, case study, keynote, letterhead) — só os nomes de layout foram catalogados em 11_templates_apresentacao.md",
      "onde_encontrar": "brand kit completo: 06_templates/"
    },
    {
      "categoria": "guideline_pdf_original",
      "descricao": "PDF original de 123 páginas (519MB) — conteúdo já extraído integralmente para os .md deste pacote",
      "onde_encontrar": "brand kit completo: 00_guideline/"
    },
    {
      "categoria": "biblioteca_completa_halftone",
      "descricao": "Dezenas de variações de Spark halftone texture por família de cor — só 1 exemplo incluído",
      "onde_encontrar": "brand kit completo: 04_elementos_de_design/spark_halftone_texture/"
    },
    {
      "categoria": "biblioteca_completa_supergraphics",
      "descricao": "12 combinações de cor de supergraphic — só 1 exemplo incluído",
      "onde_encontrar": "brand kit completo: 04_elementos_de_design/supergraphics_estatico/"
    },
    {
      "categoria": "hand_drawn_adicional",
      "descricao": "Variações X, circle, rectangle, smiley face, arrow-forward (e versões .mov) — só checkmark e arrow-up (.gif) incluídos",
      "onde_encontrar": "brand kit completo: 04_elementos_de_design/hand_drawn/"
    },
    {
      "categoria": "core_values_illustration",
      "descricao": "Ilustrações Heart, Brains, Courage — não incluídas neste recorte",
      "onde_encontrar": "brand kit completo: 04_elementos_de_design/ (ver guideline p.53)"
    },
    {
      "categoria": "human_first_inky_spark_adicional",
      "descricao": "Variações numeradas 2 e 3 do Inky Spark, e o arquivo-fonte .psd (75MB) — só o ícone 'Fingerprint' incluído por cor",
      "onde_encontrar": "brand kit completo: 05_human_first/icones_inky_spark/"
    },
    {
      "categoria": "social_media_completo",
      "descricao": "19 das 21 combinações de header social (Facebook, X, e demais variantes de cor do LinkedIn) — só 2 exemplos de LinkedIn incluídos",
      "onde_encontrar": "brand kit completo: 07_social/"
    }
  ]
}```
