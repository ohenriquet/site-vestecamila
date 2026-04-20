Documento de Replicação — Site VesteCamila (Consultoria de Estilo)
1. Visão Geral
O site é uma landing page single-page para a marca VesteCamila, uma consultoria de estilo pessoal. O layout é vertical, com seções empilhadas, tom elegante e feminino, e foco em conversão (CTA para agendar consultoria). Foi construído em Framer. O idioma é português brasileiro.

2. Identidade Visual
2.1 Paleta de Cores
NomeCódigo RGBHex AproximadoUsoTerracotargb(219, 74, 43)#DB4A2BCor principal: CTAs, linhas decorativas, títulos de destaqueBege clarorgb(228, 226, 221)#E4E2DDFundos de seções, texto claro sobre imagens, navbarBrancorgb(255, 255, 255)#FFFFFFFundo de seções neutras (serviços)Cinza escurorgb(43, 43, 43)#2B2B2BTítulos de cards de serviço (h3), títulos sobre fundo claroCinza textorgb(51, 51, 51)#333333Texto de parágrafos
2.2 Tipografia
Fonte primária (headings): "EB Garamond", serif — Google Fonts. Usada em todos os títulos (H1 a H4), botões CTA e textos de destaque. Peso 400 (regular). Estilo elegante, serifada, editorial.
Fonte secundária (body): "Inter", sans-serif — Google Fonts. Usada em parágrafos e textos corridos. Peso 400. Limpa e moderna.
2.3 Logotipo
O logotipo é uma imagem PNG com o texto estilizado "VesteCamila." seguido de um ícone de check (coração/check em formato estilizado) e o subtítulo "CONSULTORIA DE ESTILO" abaixo. A cor do logotipo é terracota (#DB4A2B) sobre fundo bege. Dimensão original: 195×41px no header e 148×31px no footer (versão menor).

3. Estrutura da Página (Seções de Cima para Baixo)
3.1 Navbar (Header)

Fundo: Bege claro (#E4E2DD)
Altura: 64px
Largura: 100% da viewport
Conteúdo: Logo centralizado horizontal e verticalmente
Logo: imagem PNG linkada para a home (./)
Sem menu de navegação visível — apenas a logo

3.2 Hero Section

Altura: tela inteira (~100vh)
Imagem de fundo: foto em preto e branco de uma mulher jovem caminhando em uma faixa de pedestres, vestindo camiseta branca e calça estampada floral. A foto é originalmente P&B (não há filtro CSS de grayscale; a imagem em si já é monocromática).
Imagem ocupa 100% da largura e 100% da altura da seção, com object-fit: cover
Posição do conteúdo: texto posicionado na metade inferior direita da imagem
Alinhamento do texto: à esquerda (start)

Texto do H1:

Vestir é uma poderosa forma de expressão pessoal e de liberdade


Tag: <h1>
Fonte: EB Garamond, serif
Tamanho: 60px
Line-height: 72px
Peso: 400
Cor: Bege claro (#E4E2DD)
Estilo: Itálico visual (a fonte Garamond em si dá essa impressão; o fontStyle é normal)

Botão CTA (Hero):

Texto: "Desperte seu estilo autêntico"
Link: ./online
Fundo: Terracota com opacidade 80% — rgba(219, 74, 43, 0.8)
Border-radius: 10px
Padding: 5px 15px
Texto interno em <h4>: EB Garamond, 24px, peso 400, cor bege (#E4E2DD)
Largura: ~290px / Altura: ~44px

3.3 Seção "Dor" (Seção de Problema)

Fundo: Bege claro (#E4E2DD)
Altura: ~430px
Padding: 100px horizontal, vertical conforme necessário
Display: flex, column, centro horizontal e vertical
Layout interno: flex row com gap de 50px — duas colunas

Coluna esquerda — Título (H2):

Você está cansado de se perder na multidão, seguindo tendências que não refletem quem você realmente é?


Fonte: EB Garamond, serif
Tamanho: 33px
Line-height: 46.2px
Peso: 400
Cor: Cinza escuro (#2B2B2B)
Alinhamento: direita (right)

Coluna direita — Parágrafo:

Entendo que o verdadeiro estilo vem de dentro para fora, e estou aqui para ajudá-lo a descobrir o seu estilo pessoal único, sem se prender às imitações vazias das redes sociais.


Fonte: Inter, sans-serif
Tamanho: 19px
Line-height: 22.8px
Cor: Cinza texto (#333333)
Alinhamento: esquerda

3.4 Seção "Solução" (Por que contratar meu serviço?)

Fundo: Branco (#FFFFFF)
Padding: generoso (espaço em branco acima e abaixo)
Estrutura:

Linha decorativa superior:

Div de 100px × 1px, cor terracota (#DB4A2B), centralizada horizontalmente

Título da seção (H2):

Por que contratar o meu serviço?


Fonte: EB Garamond, serif
Tamanho: 33px
Cor: Terracota (#DB4A2B)
Alinhamento: center

Linha decorativa inferior:

Igual à superior: 100px × 1px, terracota, centralizada

Grid de 3 Cards (flex row, gap 31px, centralizado):
Cada card é uma coluna com texto centralizado contendo um título H3 e um parágrafo.
Card 1 — "Estilo genuíno, não imitado:"

H3: EB Garamond, 36px, peso 400, cor #2B2B2B
Parágrafo: "Meu compromisso é desenvolver um estilo que seja completamente seu, que ressoe com sua personalidade e individualidade. Adeus à mesmice dos looks copiados!"
Inter, 19px, #333333, centro

Card 2 — "Consultoria Personalizada:"

H3: EB Garamond, 36px, peso 400, cor #2B2B2B
Parágrafo: "Com a minha experiência e habilidade, ofereço uma consultoria personalizada para entender suas preferências, estilo de vida e objetivos. Cada recomendação é feita sob medida para você."
Inter, 19px, #333333, centro

Card 3 — "Empoderamento através do estilo:"

H3: EB Garamond, 36px, peso 400, cor #2B2B2B
Parágrafo: "Acredito que o seu estilo é uma expressão poderosa de quem você é. Ao descobrir e abraçar sua autenticidade, você ganha confiança e destaque em qualquer ambiente."
Inter, 19px, #333333, centro

3.5 Seção CTA Final

Altura: ~428px
Overflow: hidden
Posição: relative
Imagem de fundo: foto colorida de uma mulher morena apoiada em um carro, olhando pensativa, cabelos escuros longos, vestindo moletom branco. A imagem é posicionada absolutamente e ocupa toda a seção.
Conteúdo posicionado sobre a imagem, alinhado à esquerda

Título (H2):

Junte-se à Revolução do Estilo Autêntico!


EB Garamond, 33px, peso 400, cor bege (#E4E2DD), alinhamento esquerda

Parágrafo:

Diga adeus à pressão das tendências passageiras e abrace o verdadeiro estilo que é só seu. Estou aqui para ajudá-lo a descobrir e celebrar o seu estilo pessoal autêntico.


Inter, 19px, cor bege (#E4E2DD), alinhamento esquerda

Botão CTA:

Mesmo estilo do CTA do hero: "Desperte seu estilo autêntico"
Fundo terracota 80%, border-radius 10px, padding 5px 15px
Texto: EB Garamond, 24px, cor bege
Link: ./online

3.6 Footer

Fundo: Branco (ou transparente sobre branco)
Padding: 20px
Display: flex column, alinhamento centralizado
Altura: ~152px

Conteúdo:

Logo VesteCamila (versão menor, 148×31px) — linkado para home
Texto de copyright: "VesteCamila © 2024 - Todos os direitos reservados" — H4, EB Garamond, 20px, #333333, center
Crédito: "Desenvolvido por" + Logo "Casa Amarela" (imagem 142×29px) — linkado para https://agenciacasaamarela.com.br/


4. Comportamento e Interações

Links CTA apontam para a subpágina ./online (provavelmente uma página de agendamento/venda)
Não há menu de navegação — é uma landing page single-purpose
Não há animações complexas visíveis (scroll animations, parallax, etc.)
Responsividade: O site possui variantes mobile (há classes hidden-* e uma seção nomeada "Phone" indicando adaptação mobile). No mobile, os 3 cards se empilham verticalmente.
Tracking: Google Tag Manager (GTM-5G24CQSW) e Microsoft Clarity (p0md6qyngb) estão integrados


5. Tom de Voz e Copywriting
O tom é acolhedor, empoderador e pessoal, falando diretamente com a cliente em segunda pessoa. Características do copy:

Linguagem emotiva e aspiracional: fala sobre autenticidade, liberdade, expressão pessoal
Abordagem de problema-solução: primeiro apresenta a "dor" (seguir tendências que não refletem quem você é), depois a solução (consultoria personalizada)
Verbos de ação empoderadoras: "Desperte", "Junte-se", "Abrace", "Descubra"
Posicionamento anti-cópia: rejeita imitação e tendências passageiras; valoriza individualidade
Primeira pessoa (consultora): "Meu compromisso", "Acredito", "Estou aqui para ajudá-lo"
CTA motivacional: "Desperte seu estilo autêntico" — recorrente e consistente


6. Recursos Visuais e Imagens
ImagemDescriçãoTratamentoUsoHeroMulher jovem caminhando na faixa de pedestres, camiseta branca, calça floral/abstrataPreto e brancoFundo da seção Hero (fullscreen)CTA FinalMulher morena apoiada em carro, cabelos longos escuros, moletom brancoColoridaFundo da seção CTA finalLogo header"VesteCamila" + ícone checkTerracota sobre transparente (PNG)NavbarLogo footerMesmo logo, versão menorTerracota sobre transparente (PNG)FooterLogo Casa AmarelaLogo da agência desenvolvedoraOriginalFooter (crédito)

7. Especificações Técnicas para Replicação
Fontes para Importar (Google Fonts)
html<link href="https://fonts.googleapis.com/css2?family=EB+Garamond:wght@400&family=Inter:wght@400&display=swap" rel="stylesheet">
CSS Base Sugerido
css:root {
  --terracota: #DB4A2B;
  --terracota-80: rgba(219, 74, 43, 0.8);
  --bege: #E4E2DD;
  --branco: #FFFFFF;
  --cinza-escuro: #2B2B2B;
  --cinza-texto: #333333;
}

body {
  margin: 0;
  font-family: 'Inter', sans-serif;
  color: var(--cinza-texto);
  background: var(--branco);
}

h1, h2, h3, h4 {
  font-family: 'EB Garamond', serif;
  font-weight: 400;
}

.btn-cta {
  background: var(--terracota-80);
  border-radius: 10px;
  padding: 5px 15px;
  color: var(--bege);
  font-family: 'EB Garamond', serif;
  font-size: 24px;
  text-decoration: none;
  display: inline-block;
}

.linha-decorativa {
  width: 100px;
  height: 1px;
  background: var(--terracota);
  margin: 0 auto;
}
```

### Estrutura HTML Semântica Sugerida
```
<nav>  →  logo centralizado
<section class="hero">  →  imagem P&B fullscreen + H1 + CTA
<section class="dor">  →  fundo bege, 2 colunas (pergunta + resposta)
<section class="solucao">  →  fundo branco, linha + título + linha + 3 cards
<section class="cta-final">  →  imagem colorida + H2 + parágrafo + CTA
<footer>  →  logo + copyright + crédito

8. Checklist de Replicação

Importar fontes EB Garamond e Inter do Google Fonts
Configurar paleta de cores (terracota, bege, branco, cinzas)
Criar navbar com fundo bege e logo centralizado
Montar hero fullscreen com imagem P&B, título H1 serifado sobre a foto e botão CTA terracota
Criar seção bege com layout de 2 colunas: pergunta em Garamond à direita + parágrafo em Inter à esquerda
Criar seção branca com linhas decorativas terracota, título em terracota e grid de 3 cards
Criar seção CTA final com imagem colorida de fundo, título + parágrafo em bege e botão CTA
Criar footer com logo menor, copyright e crédito da agência
Garantir responsividade mobile (stack vertical nos cards, ajuste de fontes)
Manter tom de voz empoderador, pessoal e anti-tendências em todo o copy