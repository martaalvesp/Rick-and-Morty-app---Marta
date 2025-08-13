# Aplicativo Rick & Morty - [Kobe Start]

## 📌 Introdução 

Este projeto foi desenvolvido como parte de um desafio técnico proposto pela Kobe Apps, com o objetivo de criar um aplicativo Flutter que consuma a API pública de Rick & Morty, apresentando uma lista de personagens com funcionalidades modernas e navegação fluida. 



## ✅ Funcionalidades implementadas 
- 🔄 Scroll infinito na lista de personagens 

- 🔍 Busca por nome completo ou parcial 

- 📄 Exibição de detalhes completos de cada personagem 

- 🧭 Navegação entre telas 

- ⚠️ Tratamento de erros e estados vazios

  

## 📱 Demonstração das telas 
### 🏠 Home Page 

A tela inicial exibe uma lista com scroll infinito dos personagens, utilizando cards clicáveis. A AppBar foi construída conforme o design proposto no Figma, contendo a logo fornecida, além dos ícones de person e menu. 

![scroll](rick_and_morty_kobe/lib/theme/scroll.mp4)

### 🔍 Busca (Search) 

Logo abaixo da AppBar, há um campo de busca que permite pesquisar personagens pelo nome. A busca aceita nomes completos ou parciais e retorna os resultados de forma dinâmica. 



### 👤 Detalhes do Personagem 

Ao selecionar um personagem, o usuário é redirecionado para uma nova tela com os seguintes detalhes: 

Nome 

Status (Vivo, Morto ou Desconhecido) 

Espécie 

Gênero (Masculino, Feminino ou Desconhecido) 

Origem do personagem 

Última localização conhecida 

Primeira aparição na série 

![Texto alternativo](rick_and_morty_kobe/lib/theme/details_page.jpg)


### 🔙 Navegação (Back) 

Após visualizar os detalhes, o usuário pode retornar à tela inicial para continuar explorando outros personagens, utilizando o botão de voltar na tela de detalhes. 


## 💻 Tecnologias utilizadas 

Flutter 

Dart 

API Rick and Morty   

## 👨‍💻 Autor 

Desenvolvido por Marta Alves Pinho. 

## 📎 Observações 

Este projeto foi criado com foco em boas práticas, conhecimentos adquiridos no workshop da Kobe, organização de código (camadas de models, pages, repositories e themes) e responsividade básica. O layout foi construído com base no design proposto no Figma pela Kobe Apps. 
 