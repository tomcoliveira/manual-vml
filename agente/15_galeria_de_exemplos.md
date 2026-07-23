# 15. Galeria de Exemplos Aplicados

Fonte: guideline oficial, seção "10 Gallery" (p.78–118) + páginas finais não numeradas por seção (p.119–122). **Esta seção não existia neste pacote até 2026-07-22** — a extração original tinha parado na página 77 (headshots); as 44 páginas seguintes (quase um terço do documento) nunca tinham sido abertas. Foram renderizadas diretamente do PDF oficial (519MB, não incluído neste pacote) e catalogadas aqui pela primeira vez.

## Por que esta seção importa mais que as outras

Todas as seções `01`–`14` são regra abstrata (specs, hex, tamanhos mínimos, watch-outs). Esta seção é o oposto: **peça pronta, aplicando a regra na prática.** Um agente que só leu regra abstrata tende a gerar algo tecnicamente correto mas sem o "jeito" da marca; ver a peça pronta é o atalho para isso. Use esta seção como referência visual de precedente — "a peça que estou montando se parece com algum destes exemplos?" — não como catálogo de assets para extrair peça a peça.

**Importante: nenhuma destas imagens é um asset de produção.** São renders/fotos de página de PDF em qualidade de tela (120dpi, JPG), suficientes para entender composição, hierarquia e tom — não para reimportar num arquivo final. Se uma peça precisar literalmente de um desses templates (o `.pptx` do deck, o arquivo de embroidery do boné, etc.), esse arquivo-fonte não está neste pacote — ver `11_templates_apresentacao.md` e sinalizar a necessidade do brand kit completo.

## Categorias

### Ambientes e sinalização (`assets/galeria/ambientes/`, 7 imagens)
Fachada de vidro com logo 3D iluminado, entrada de loja com Spark vazado na porta de vidro, recepção com logo+Spark+plantas, parede de ripas de madeira com logo+Spark em relevo, parede tom-sobre-tom com logo em relevo sutil, recepção com tela de fundo em halftone abstrato, placa de sala de reunião em madeira com QR code ("Stratocruiser Meeting Room"). Complementa `08_ambientes_fisicos.md` — mostra exatamente o que esse arquivo só descreve em texto.

### Papelaria (`assets/galeria/papelaria/`, 2 imagens)
Cartões de visita espalhados (preto, branco, cinza-oliva — uma cor por cartão, nunca misturada no mesmo cartão) e um set de papelaria (letterhead + envelope + cartão) em cinza claro.

### Merchandise (`assets/galeria/merchandise/`, 18 imagens)
Pins/ímãs quadrados em várias cores da paleta secundária (única peça do pacote inteiro onde múltiplas famílias de cor aparecem juntas — é um produto de coleção, não uma peça de comunicação, então não conflita com a regra de "uma família por vez" de `03_cor.md`), tote bags (2), meias com padrão de texto repetido, porta-copos, skate deck, boné com bordado, moletom, crachá/lanyard de identificação, garrafa d'água, camiseta manga longa com Spark pequeno, caixa de fósforos, capa em relevo (blind emboss), cadernos/journals (2 variações), canecas (2 cores), copos térmicos (2 cores), caneta.

### Digital e social (`assets/galeria/digital_social/`, 11 imagens)
Mockup de post quadrado num iPhone na mão ("The Future 100"), grade de layouts de template de apresentação (confirma visualmente os nomes catalogados em `11_templates_apresentacao.md`: Cover, Keynote Cover Slide Title, Section Divider, Our Team, Interior Collage etc.), slide de capa de deck detalhado ("Welcome to VML"), pôsteres impressos emoldurados (aplicação OOH/print — case studies reais tipo "Have what she's having", "An icon stays iconic", "Limits are lifted"), cards de campanha em grid (o sistema "digital collage" de `05_layout_e_grid.md` aplicado de verdade, com foto real + headline + halftone + Spark), mockup de laptop com website de campanha, posts de Instagram com ilustração hand-drawn de contorno simples (confirma o estilo descrito em `06_elementos_de_design.md` item 5 "Ilustração customizada" — dolphin/lion para Cannes, retrato para prêmio, aperto de mão para "AI in the workplace"), laptop com página de blog/insights.

### Assinatura de e-mail (`assets/galeria/email/`, 1 imagem)
Template completo preenchido: nome, cargo, pronome (com marcador quadrado ▪ em vez de bullet redondo — nota de consistência com a regra de "só quadrado" de `05_layout_e_grid.md`), time, telefone, endereço. Referência direta de formatação para gerar assinaturas de e-mail novas.

### Human First (`assets/galeria/human_first/`, 4 imagens)
Laptop com headline "Human First and the rest will follow.", ambiente de escritório com manifesto hand-lettered aplicado direto na parede, tríptico de celular (headshot com hand-lettering sobreposto ao nome/cargo + tela de lockup "VML / Human First"), laptop mostrando a página "Our Core Values" com três ícones de contorno simples (cabeça, coração, mão) lado a lado com os textos.

**Atualização de gap conhecido:** `06_elementos_de_design.md` (seção 4a "Core values illustration") dizia que os ícones Heart/Brains/Courage "não foram localizados como arquivo separado". Isso continua verdadeiro para o arquivo-fonte isolado (vetor exportável) — mas agora temos confirmação visual de como esses três ícones se parecem e como são usados juntos (`assets/galeria/human_first/gallery_p118.jpg`), o que já ajuda a reconhecer/avaliar o padrão mesmo sem ter o arquivo pronto para inserir.

### Outros (`assets/galeria/outros/`, 1 imagem)
Mapa mostrando conexão entre escritórios (New York, Kansas City, Guatemala, Belo Horizonte) sob o título "Digital Products & Platforms" — não é um exemplo de estilo de peça, é conteúdo institucional específico (provavelmente de um case/apresentação de capacidades). Incluído por completude, não como referência de padrão visual.

## Índice de arquivos

| Página do PDF | Categoria | Arquivo |
|---|---|---|
| 79–85 | ambientes | `gallery_p079.jpg` … `gallery_p085.jpg` |
| 86–87 | papelaria | `gallery_p086.jpg`, `gallery_p087.jpg` |
| 88–105 | merchandise | `gallery_p088.jpg` … `gallery_p105.jpg` |
| 106–112, 114, 120–122 | digital_social | `gallery_p106.jpg` … (ver pasta) |
| 113 | email | `gallery_p113.jpg` |
| 115–118 | human_first | `gallery_p115.jpg` … `gallery_p118.jpg` |
| 119 | outros | `gallery_p119.jpg` |

## Como um agente deve usar esta seção

1. Antes de montar uma peça, checar se existe um exemplo aqui na mesma categoria (ambiente, merch, digital/social, e-mail, Human First) — usar como referência de tom e composição, não copiar literalmente.
2. Nunca tratar estas imagens como asset final a inserir numa peça — são referência visual, não arquivo de produção.
3. Se uma peça pedir algo muito parecido com um destes exemplos (ex.: "quero uma assinatura de e-mail" ou "quero um post estilo card de campanha"), usar o exemplo correspondente como modelo de estrutura, aplicando as regras normativas das seções `01`–`14` para os detalhes (cor, tipografia, tamanho).
4. Se a tarefa for gerar um asset de merchandise físico (boné, caneca etc.) para produção real, sinalizar que isso depende de arquivo de produção (embroidery file, gabarito de impressão) que não existe neste pacote nem foi extraído do brand kit completo — a imagem aqui é só referência de como o produto final se parece.
