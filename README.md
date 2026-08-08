# Semana da Cultura Japonesa

Página de divulgação de um evento fictício de culinária e cultura japonesa.

Projeto desenvolvido para a atividade de Desenvolvimento Web, utilizando HTML5 e CSS3, sem frameworks, bibliotecas ou JavaScript.

## Sobre o evento

A Semana da Cultura Japonesa é um evento fictício realizado nos dias 17 e 18 de novembro de 2026, no Pátio das Lanternas, em São Paulo.

A página apresenta a programação do evento, cardápio, galeria de imagens, trilha sonora, opções de ingresso e informações de contato.

## Requisitos técnicos

### HTML

- **HTML5:** documento estruturado com `doctype`, `head` e `body`.
- **Tags semânticas:** uso de `header`, `nav`, `main`, `section`, `article`, `figure`, `figcaption`, `footer`, `address` e `time`.
- **Hierarquia de títulos:** um `h1` para o título principal, `h2` para as seções e `h3` para conteúdos internos.
- **Imagens:** utilização de imagens JPG, PNG e SVG com atributos `alt`.
- **Áudio:** elemento `<audio controls>` na seção de trilha sonora.
- **SEO:** utilização de `title`, `meta description`, `charset`, `lang` e `viewport`.

### CSS

- **Seletores:** uso de seletores de tipo, classe e ID.
- **Seletores compostos:** uso de seletores descendente, filho direto, adjacente e de atributo.
- **Pseudo-classes:** utilização de `:hover`, `:first-child` e `:last-child`.
- **Pseudo-elementos:** utilização de `::before` e `::first-letter`.
- **Cascata e herança:** definição de estilos gerais no `body`, com sobrescritas pontuais em elementos e classes específicas.
- **Fontes:** uso de Google Fonts com fontes alternativas para fallback.
- **Layout:** utilização de Flexbox e CSS Grid.
- **Responsividade:** uso de media queries para adaptar a página a diferentes tamanhos de tela.

## Estrutura da página

- **Cabeçalho:** identidade do evento e navegação entre as seções.
- **Apresentação:** descrição do evento, data, local e informações de entrada.
- **Programação:** atividades dos dois dias do evento.
- **Cardápio:** pratos e bebidas típicas utilizando `figure` e `figcaption`.
- **Galeria:** imagens relacionadas à culinária e à ambientação do evento.
- **Trilha sonora:** áudio ambiente utilizando o elemento `<audio>`.
- **Ingressos:** opções de entrada e informações sobre participação.
- **Rodapé:** local, inscrição e contato.

## Responsividade

A página utiliza três configurações principais:

- **Desktop:** layout padrão.
- **Tablet:** ajustes na disposição das colunas e dos elementos.
- **Mobile:** reorganização do cabeçalho, informações do evento, galeria e espaçamentos.

A responsividade foi implementada utilizando media queries em `css/style.css`.
