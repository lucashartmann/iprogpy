# [Trilha Python](index.md)

## Desafio: Sprites e coordenadas


Um 'Sprite' é uma imagem que pode ser movida pela tela.

A cada momento da execução do programa o sprite está localizado em alguma coordenada da tela.

Mover um sprite consiste em mudar o valor das suas coordenadas (mudar sua posição na tela).

### Coordenadas

A posição na tela de um Sprite ou imagem é definida por um par de valores (`x`,`y`) chamado de "coordenadas".

![Coordenadas x e y](img/coordinate-grid.jpg)

Os valores de `x` iniciam em `0` (zero) e começam a ser contados da esquerda para a direita.

Os valores de `y` iniciam em `0` (zero) e são contados de cima para baixo.

### Problema do desafio

O *canto superior esquerdo* da tela tem coordenadas `(0, 0)`.

Quais são os os valores dos outros cantos?

![Pares de coordenadas](img/coordinate-results.jpg)


### Método de solução 

Vamos investigar isso e encontrar a solução movendo um Sprite pela tela.

#### Dados preliminares

1. No programa abaixo, a imagem da cobrinha tem 16x16 pixels.

2. Sua posição no início do progama é:

- x: 8
- y: 8

Sua posição é alterada usando-se a função `set_position(x,y)`
As coordenadas passadas para a função como parâmetro referem-se à posição do **centro do sprite**

```python
# centro do sprite é alterado para as coordenadas
# x = 8
# y = 8

cobrinha.set_position(8, 8)
```

#### Pergunta

Quais os valores das coordenadas de todos os 4 cantos da tela?

#### Para resolver
1. Carregue o programa exemplo abaixo

![Sprites e coordenadas](img/arcade-apy-sprites-e-coordenadas.png)

2. Posicione a cobrinha no canto inferior direito da tela. Use a função `set_position(x, y)`) e faça diversos testes até encontrar a combinação certa de valores de `x` e `y`.

3. Agora que você posicionou a cobrinha no canto inferior direito da tela, responda a pergunta.
 
`Dica:` Se você conseguiu posicionar a cobrinha no canto inferior direito **você já tem todos os dados necessários para responder**.

### [voltar](index.md)