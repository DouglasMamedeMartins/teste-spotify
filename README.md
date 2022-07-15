# Teste para vaga de Estagiário Dev Web

O objetivo deste teste é entender o candidato, sua experiência e sua capacidade de resolução de problemas com dúvidas e detalhes que serão exigidos no dia-a-dia como Estagiário em Desenvolvimento Web.
O teste é baseado em questionamentos e problemas a serem resolvidos.

### Como será feito o teste?

O teste é dividido em 2 etapas:

- Questões teóricas.
- Projeto prático, quer seja correção de bug ou criação do mesmo.

O candidato precisa criar um repositório próprio com a seguinte estrutura:

- No README serão respondidas as questões teóricas (pergunta e resposta), de forma organizada e explicada.
- No próprio repositório estará o projeto prático, corrigido e/ou criado.

Após a finalização, o candidato deve enviar um e-mail para suporte@b7web.com.br com o link do repositório original (este) bem como o link do repositório pessoal com a resolução.

## Questões Teóricas

1. Qual a função do "head" no HTML?
   Tem a função de colocar tags que controlam o funcionamento do site bem como meta, links, script, style, title, entre outras.

2. Quando uma página é criada, ela automaticamente se adapta a todos os tipos de tela? Por que?
   Não, porém dependendo da forma como á pagina é feita ela pode se adaptar bem como utilizando a max-width ou medida REM, más é NECESSÁRIO utilizar a @media para manipular o acesso para dispositivos móveis.

3. O código HTML e CSS é renderizado no servidor e repassado para o navegador em forma de imagem? O código é renderizado e passado em forma de código e o navegador irá pegar o código e traduzir para o que foi feito, seja imagem ou coisas do tipo.

4. Qual a função das tags H (h1, h2, h3, etc) no HTML? Tem como a função de colocar um Título, a cada número menor da tag H o título irá diminuir, porém da uma importância na página, um destaque maior.

5. O que é SEO e como funciona?Search Engine Optimization, funciona como um mecanismo de busca, os sites que obter uma semântica boa será o site mais buscado, pois o SEO irá buscar os melhores sites com semâtinca.

6. O uso de media query é obrigatório em todas as páginas?
   Teoricamente não, porém na prática é extremamente necessário para manipular o uso do site para dispositivos móveis.

7. Qual a diferença entre CSS Inline e CSS em um arquivo?
   CSS inline é utilizado na própria linha do HTML, tendo uma especificidade priorizada, enquanto CSS em um arquivo(externo) é um css utilizado em qualquer outro lugar com a extenção .css podendo ser puxada pela tag link.
8. Como criar animações no CSS? Dê um exemplo.
   Animações no CSS pode ser feita após colocar @keyframes e dar um nome a mesma, feito isso coloque as propriedades a desejar. ex:
   @keyframes animation {
   0% {background-color: green;} }
   25% {background-color: red;} }
   50% {background-color: pink;} }
   75% {background-color: black;} }
   100% {background-color: blue;} }
   após isso utilize o nome da animação no elemento que desejar usando animation-name:(nome da animação);
   e uma duração como animation-duration: 10s;
9. Qual a diferença entre class e ID no CSS?
   Class pode ser utilizada várias vezes e tem uma especificidade menor que da ID, já ID tem uma especificidade maior porém só pode ser utilizada apenas uma vez o mesmo nome.
10. Quais os diferentes tipos de seletores CSS?
    existem varios tipos de seletores, como seletor por classe .classe, seletor por id #id, seletor de posição, como child ou last-child pegando pelo primeiro elemento ou o ultimo, além do poder da especificidade.

## Projeto prático

O candidato deve criar a página da imagem a seguir:
![Layout](https://i.ibb.co/Bydq2FZ/screencapture-spotify-br-2022-05-10-15-13-17.png)

Algumas observações importantes:

- Fazer a página responsiva não é obrigatório, mas a apresentação dos elementos deve ser o mais próximo possível da imagem.
- Todas as imagens necessárias estão neste repositório, na pasta "assets".
- Efeitos de hover não são obrigatórios, mas são um plus.

O candidato deve estar atento para obedecer principalmente as cores corretas e tamanhos aproximados.
