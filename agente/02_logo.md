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
