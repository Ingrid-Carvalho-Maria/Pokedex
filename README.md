# Projeto de Arquitetura de Software

Repositório criado para desenvolvimento e analisar o sistema proposto denominado Pokedex.

## Pokedex:
Projeto ensinado por Manual DEV: 
https://www.youtube.com/watch?v=SjtdH3dWLa8.

##Gerador de Favicons: 
https://www.websiteplanet.com/pt-br/webtools/favicon-generator/

##Documentação da API: 
https://pokeapi.co/

E acreditamos que cada parte da arquitetura da Pokédex em JavaScript foi escolhida por ser leve, compatível com todos os navegadores e eficiente para criar uma aplicação web interativa sem depender de frameworks. Isso garante que o sistema funcione bem, seja fácil de manter e possa ser acessado em diferentes dispositivos, mesmo com recursos limitados. 
A camada de apresentação (frontend) usa HTML5, CSS3 e JavaScript, que são as principais tecnologias da web. 
O HTML5 organiza o conteúdo da página de forma clara e acessível, com elementos como <main>, <form> e <button>. Isso ajuda na leitura por ferramentas de acessibilidade e na indexação por buscadores. O CSS3 cuida do visual da interface, tornando-a responsiva com o uso de Flexbox, Media Queries e estilos modernos como gradientes e sombras 3D. O uso de tamanhos relativos, como clamp() e %, permite que a interface se adapte a diferentes telas, começando pelos celulares (mobile-first).
Toda a lógica da aplicação é feita com JavaScript, que permite atualizar a tela em tempo real conforme o usuário interage. Funções como fetchPokemon() e renderPokemon() fazem buscas na API e mostram as informações dos Pokémons. Eventos como submit e click controlam ações como a busca por nome ou número e a navegação entre Pokémons. Essa estrutura facilita futuras atualizações no código. 
A PokeAPI foi escolhida como fonte de dados. Ela é uma API pública que traz informações completas dos Pokémons (nome, ID, tipos, habilidades, imagens) em formato JSON. Usar essa API evita ter que criar e manter um banco de dados próprio, e ainda garante que a Pokédex esteja sempre atualizada com os dados oficiais. Uma melhoria futura sugerida é usar o localStorage para salvar localmente os Pokémons já buscados. Isso evita chamadas repetidas à API e torna o carregamento mais rápido, melhorando a experiência do usuário. O projeto também se preocupa com acessibilidade e SEO.
Foram adotadas boas práticas como uso de alt em imagens, contraste de cores adequado, aria-label em botões e meta tags como viewport. Isso garante que o sistema seja acessível a todos e bem posicionado em buscadores. Assim, a arquitetura escolhida usa tecnologias simples, eficientes e fáceis de entender, resultando em uma Pokédex leve, interativa e acessível.
