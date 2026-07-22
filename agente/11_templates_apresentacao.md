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
