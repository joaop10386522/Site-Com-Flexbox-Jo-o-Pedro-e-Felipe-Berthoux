# Mercado Virtual

Bem-vindo ao repositório do site "Mercado Virtual". Este projeto é um exemplo simples de um site com várias lojas, utilizando Flexbox para o layout. A seguir, explicamos os principais conceitos e o código utilizado no projeto.



## Estrutura do HTML

### `<head>`


O elemento `<head>` contém metadados e links para arquivos externos, como o CSS.

- **`<meta charset="UTF-8">`**: Define a codificação de caracteres para suportar acentuação e caracteres especiais.
- **`<meta name="viewport" content="width=device-width, initial-scale=1.0">`**: Faz com que o site se ajuste corretamente em dispositivos móveis.
- **`<title>Mercado Virtual</title>`**: Define o título da página que aparece na aba do navegador.
- **`<link rel="stylesheet" href="siteflexboxcss.css">`**: Conecta o arquivo CSS externo para estilizar a página.

### `<body>`

O elemento `<body>` contém o conteúdo visível da página.

- **`<header>`**: Seção no topo da página com o título e navegação.
- **`<nav>`**: Contém links para navegação entre seções da página.
- **`<main>`**: Seção principal da página com o conteúdo principal.
- **`<section id="home">`, `<section id="lojas">`, `<section id="contato">`**: Diferentes seções da página com IDs para navegação.
- **`<footer>`**: Seção no fundo da página com informações sobre os autores.

## Estilos CSS

### Reset Básico

- Remove margens e preenchimentos padrão de todos os elementos e define `box-sizing` para garantir que padding e bordas não alterem o tamanho total do elemento.

### Estilos Gerais

- Define a fonte padrão para o corpo do texto.

### Cabeçalho

- Define um fundo escuro para o cabeçalho e texto branco. Centraliza o texto e os links de navegação.

### Seções Principais

- Adiciona um espaçamento padrão ao redor das seções e define o espaçamento para os títulos (`h2`).

### Layout de Lojas

- **`display: flex;`**: Usa Flexbox para organizar as lojas.
- **`flex-wrap: wrap;`**: Permite que as lojas se ajustem e quebrem em várias linhas, se necessário.
- **`gap: 1rem;`**: Define o espaçamento entre as lojas.
- **`flex: 1 1 45%;`**: Faz com que cada loja ocupe cerca de 45% da largura disponível, ajustando automaticamente para se ajustar à tela.

### Rodapé

- Define um fundo escuro e texto branco para o rodapé, centralizando o texto.



