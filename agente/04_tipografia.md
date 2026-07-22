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
