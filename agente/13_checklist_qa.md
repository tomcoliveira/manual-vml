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
