# Xelanepo

Xelanepo is a web application that allows users to search for paper authors. Built with React, it provides an intuitive interface for discovering researchers, their work, and related publications.

## Features

- **Author Search:** Find paper authors by name, field, or keywords.
- **Detailed Profiles:** View author profiles with relevant information such as their publications, affiliations, and areas of expertise.
- **Responsive Design:** Optimized for both desktop and mobile devices.

## Technologies Used

- **Frontend:** React
- **State Management:** React Hooks / Context API
- **Styling:** CSS / TailwindCSS (Optional: Specify framework if used)
- **API Integration:** REST or GraphQL (Specify if an external API is used)
- **Testing:** Jest / React Testing Library (Optional)

## Installation

To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/xelanepo.git

2. Navigate to the project directory:
   ```bash
   cd xelanepo

3. Install the dependencies:
   ```bash
   npm install

4. Start the development server:
   ```bash
    npm run dev

## TODO

### Pesquisa
- Lembro que estava com problema, mas não lembro mais oque.

### ProfileHeader
- Estilização Geral 
- Pegar os dados de algum lugar = Provavelmente não vamos fazer por ser muito complicado e não ter muito tempo. Mas pode tentar se quiser
- image:  "./profilePLaceholder.svg" não esta funcionando na pagina Profile, apesar de funcionar na pagina de pesquisa

### Works
- Fazer uma paginação via scroll. Explicação: A request da api tem dois parâmetros: per_page e page, o ideal é não pegar todos os itens de uma vez e sim ir pegando por página, então tem que ser feito uma detecção de quando o usuário chegar no fim do scroll da div de works e fazer outro request com o parâmetro page incrementado de 1 unidade. Segue a documentação: https://docs.openalex.org/api-entities/works/get-lists-of-works#page-and-sort-works

### Languages
- Ainda não consegui fazer com que o hoover mostre a qual língua aquela porcentagem se refere. 
- Seria Interessante ter um div do lado do gráfico listando as línguas, com a cor e porcentagem correspondente

### InstitutionsMap
- Melhorar o estilo

### Mobile
- Tem que fazer. Vai ser bem chato. Home, Pesquisa e Perfil 
- Tem uma cacetada de warning no console, não sei como resolver

