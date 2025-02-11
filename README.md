# Desafio BTG [iOS]

Seja bem-vindo! Este é o seu primeiro passo para fazer parte do time de desenvolvimento do maior banco de investimentos da América Latina. 

#### LEIA AS INSTRUÇÕES POR COMPLETO ANTES DE COMEÇAR

O Desafio consiste no desenvolvimento de um app bem simples que consome a [API](https://developers.themoviedb.org/3/getting-started/introduction) do [TheMovieDB](https://www.themoviedb.org/?language=en).

Você não precisa se preocupar tanto com o design. Esse não é o objetivo do desafio. Tenha em mente que seu código e app serão avaliados em todos os aspectos, então cada detalhe conta. Faça disso uma oportunidade pra mostrar todo o seu conhecimento.

O único pré requisito é que o app seja feito em Swift, mas atente-se aos seguintes pontos:
* Prefere-se a utilização de ferramentas nativas;
* Caso opte por usar libs externas, prefira CocoaPods; ✅
* É preferível que a interface seja feita utilizando Xibs;

## NOTAS:
 Testado no iOS 13 e iphone7;
 Editado para rodar no iOS 10.0 e testado no iphone 5

## Features
### Obrigatórias:
* Tab bar com dois ítens: Filmes e Favoritos, sendo a principal a tab de Filmes;
* A tela de Filmes deverá conter:
	* Uma lista dos [filmes populares](https://developers.themoviedb.org/3/movies/get-popular-movies) da API; ✅
	* Cada elemento da lista deve conter o poster, o nome e o ano que o filme foi produzido; ✅
	* Ao clicar em um ítem, deve ser apresentada a tela de detalhes (tela descrita abaixo);✅
	* Search bar para pesquisar filmes por nome; ✅
* A tela de favoritos deverá conter:
	* A lista de favoritos persistidos no app entre sessões; ✅
	* Search bar para pesquisar favoritos por nome e ano; ✅
	* Ao clicar em um ítem, deve ser apresentada a tela de detalhes (tela descrita abaixo); ✅
* A tela de detalhes deve apresentar os seguintes dados do filme: *(não necessariamente nessa ordem)*
	* Poster; ✅
	* Botão para favoritar/desfavoritar; ✅
	* Título; ✅
	* Sinopse; ✅
	* Nota do filme; ✅
	* E os gêneros por extenso. ✅
* É necessário fazer tratamento de erros e dos fluxos de exceção, como busca vazia, carregando e outros erros que possam ocorrer. ✅
  
### Opcionais:
#### Não necessário, porém contam pontos.
* Desenvolver o App seguindo a arquitetura Clean;
* Desenvolver testes unitários e/ou funcionais;
* botão de favoritar/desfavoritar nos item das listas;
* Pull-to-refresh nas listas;
* Paginação na tela principal;
* Opções de filtro e ordenação nas listas;
* Pipeline automatizado.

## Processo de submissão
Para submeter o seu desafio, faça um fork deste projeto, desenvolva o desafio **no seu fork** abrindo um pull request até a data limite estabelecida.

### Boa sorte.
