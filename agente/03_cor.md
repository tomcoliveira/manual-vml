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
