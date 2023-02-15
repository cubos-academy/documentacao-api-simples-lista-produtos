![](https://i.imgur.com/xG74tOh.png)

# API que retorna produtos (Sapatos)

Essa é uma api para fins pedagógicos, portanto esses dois end-points abaixo não necessitam de autenticação.

### URL da API: 
https://api-contacts.pedagogico.cubos.academy/

# ROTAS

## GET `/shoes`

Esse endpoint retorna uma lista com alguns produtos, que nesse caso são sapatos, veja abaixo o objeto retornado:

```json 

[
  {
    "id": 1,
    "image": "https://f004.backblazeb2.com/file/imagens-para-apis/shoe1.jpg",
    "name": "Sapato 1",
    "description": "description 1 description 1 description 1 description 1 description 1 description 1 description 1 description 1 description 1 ",
    "oldPrice": 400,
    "currentPrice": 279.9
  },
  {
    "id": 2,
    "image": "https://f004.backblazeb2.com/file/imagens-para-apis/shoe2.jpg",
    "name": "Sapato 2",
    "description": "description 2 description 2 description 2 description 2 description 2 description 2 description 2 description 2 description 2 ",
    "oldPrice": 450,
    "currentPrice": 289.9
  },
  {
    "id": 3,
    "image": "https://f004.backblazeb2.com/file/imagens-para-apis/shoe3.jpg",
    "name": "Sapato 3",
    "description": "description 3 description 3 description 3 description 3 description 3 description 3 description 3 description 3 description 3 ",
    "oldPrice": 475.8,
    "currentPrice": 299.9
  },
  {
    "id": 4,
    "image": "https://f004.backblazeb2.com/file/imagens-para-apis/shoe4.jpg",
    "name": "Sapato 4",
    "description": "description 4 description 4 description 4 description 4 description 4 description 4 description 4 description 4 description 4 ",
    "oldPrice": 229,
    "currentPrice": 179.9
  },
  {
    "id": 5,
    "image": "https://f004.backblazeb2.com/file/imagens-para-apis/shoe5.jpg",
    "name": "Sapato 5",
    "description": "description 5 description 5 description 5 description 5 description 5 description 5 description 5 description 5 description 5 ",
    "oldPrice": 245,
    "currentPrice": 149.9
  },
  {
    "id": 6,
    "image": "https://f004.backblazeb2.com/file/imagens-para-apis/shoe6.jpg",
    "name": "Sapato 6",
    "description": "description 6 description 6 description 6 description 6 description 6 description 6 description 6 description 6 description 6 ",
    "oldPrice": 800,
    "currentPrice": 579.9
  }
]

```

## GET `/shoes/:productId`

Esse endpoint retorna um produto específico, com todos os seus detalhes. Veja abaixo o exemplo de retorno:

Obs.: **productId** deve ser passado na url do endpoint

```json
{
  "id": 1,
  "image": "https://f004.backblazeb2.com/file/imagens-para-apis/shoe1.jpg",
  "name": "Sapato 1",
  "description": "description 1 description 1 description 1 description 1 description 1 description 1 description 1 description 1 description 1 ",
  "oldPrice": 400,
  "currentPrice": 279.9
}

```
