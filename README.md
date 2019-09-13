# Exercícios

## Caieirasfy

Crie uma API Rest que simule o aplicativo do spotify. 
Para isso será necessário criar uma model Musica com os seguintes atributos:
1. Nome da Musica
1. Artista
1. Genero Musical
1. Link da musica. 

Os úsuarios comuns podem apenas visualizer as musicas, enquanto os usuarios logados poderão cadastrar ou excluir musicas no banco de dados.

A aplicação deve permitir buscar musicas, por nome do artista, nome da musica ou genero musical.

# Refatoração 

Faça uma API Rest para listar os artistas e suas músicas favoritas. Essa Api deve cadastrar um artista e cadastrar músicas vinculadas ao artista. 

A model do Artista deve conter:
1. Nome
1. Idade
1. Estilos musicais

A model de Musica deve conter:
1. Nome da Musica,
1. Tempo de reprodução 
1. Artista
1. Genero Musical

## EndPoints 

1. Artista deve conter um endpoint que exibi a lista de todos os artistas cadastrados. Essa lista deve conter apenas o **Nome e o Estilos musicais do artista.** 
1. O Artista deve ter um endpoint com os detalhes completos do artista; **Nome, idade, Estilos Musicais e suas Músicas.**

1. Para as musicas será necessario um endpoint para exibir a lista de músicas cadastradas. 
1. Nessa lista deverá aparecer o **Nome da musica, Duração e Genero Musical.**
1. A música deve ter um segundo endpoint para visualizar todos os detalhes da música; **Nome da Música, Tempo de Reprodução, Artista e Gênero Musical**

O sistema deve ter filtros por **Nome da Musica, Artista ou Genero Musical.**



