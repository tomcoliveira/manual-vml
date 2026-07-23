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

Ilustrações de contorno simples para os valores da empresa. Usos citados: key art, fundos de Teams, pôsteres, cabeçalho de e-mail. **Não alterar nem recriar em estilo diferente.** O arquivo-fonte isolado (vetor exportável de cada ícone) não está neste pacote nem foi localizado no brand kit completo. Existe, porém, confirmação visual de como os três ícones se parecem aplicados juntos: `15_galeria_de_exemplos.md` → `assets/galeria/human_first/gallery_p118.jpg` (mockup de laptop com a página "Our Core Values", cabeça/coração/mão em contorno simples). Use essa imagem como referência de reconhecimento — não como arquivo para recortar/reinserir.

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
