# Casos de uso

## Caso de uso 1: Pegar carta objetivo
### Escopo: 
#### Ação de jogo.
#
### Ator Principal: 
#### Jogador.
#
### interessados e Interesses: 
```
Jogador: O jogador resgatará no monte principal, no ínicio da partida, uma única carta de objetivo, que será sua referência para sua vitória.

Cartas objetivos: São uma série de cartas que expõem vários objetivos.
```
#
### Pré-condições: 
#### O jogo ter iniciado.
#
### Pós-condições: 
#### Revelar a condição de vitória do jogador.
#
### Garantia de sucesso: 
#### O jogador deve conseguir visualizar seu objetivo para sua vitória.
#

### Cenário de sucesso:
1. Jogo deve ser iniciado.
2. Ir ao montante de cartas de objetivo.
3. Pegar carta.

#
## Caso de uso 2: Pegar carta território
### Escopo: Ação de jogo.
#### 
#
### Ator Principal: 
#### Jogador
#
### interessados e Interesses: 
```
Jogador: O jogador quando conquistar um ou mais territórios deve pegar no monte de cartas territórios uma única carta.

Carta território: Deve ser entregue ao jogador

```
#
### Pré-condições: 
#### Quando conquistar um território.
#
### Pós-condições: 
#### O jogador deve ter uma carta território a mais em seu monte de cartas territórios.
#
### Garantia de sucesso: 
#### O jogador deve receber uma carta aleatória de qualquer território.
#

### Cenário de sucesso:
1. O turno deve ser iniciado.
2. Jogador realiza um ataque.
3. Jogador ganha um ou mais ataques.
4. Reclama uma carta.
5. Coloca a carta recebida no topo do monte.

#
## Caso de uso 3: Trocar cartas território.
### Escopo: Ação de jogo.
#### 
#
### Ator Principal: 
#### Jogador
#
### interessados e Interesses: 
```
- Jogador: O jogador tem a intenção de entregar as cartas para o monte e receber em troca algumas tropas.

- Cartas: Devem conter os símbolos todos iguais ou todos diferentes

- Tropas:  Devem ser entregues o número de tropas relacionadas a quantidade de trocas já realizadas pelo jogador.

```
#
### Pré-condições: 
#### O jogador deve ter um conjunto de cartas com todos os três simbolos iguais ou todos diferentes.
#
### Pós-condições: 
#### O jogador deve ter recebido as tropas necessárias. 
#
### Garantia de sucesso: 
#### O jogador deve receber o número de tropas relacionado a aquela troca. E distribuir as peças em seus territórios.
#

### Cenário de sucesso:
1. O turno deve ser iniciado
2. O jogador deve ter três cartas de um único símbolo ou os três diferentes.
3. Entregar suas cartas
4. Receber a quantidade certa de tropas
5. Distribuir tropas em seus territórios.

#
## Caso de uso 4: Atacar território
### Escopo: 
#### Ação de jogo.
#
### Ator Principal: 
#### Jogador(Atacante)
#
### interessados e Interesses: 
```
- Jogador(Atacante): O jogador que ataca tem como intenção conquistar um território e receber uma nova carta território para o seu monte.

- Jogador(Defensor): Temo como intenção defender seu território para auxiliar na conquista de seu objetivo.

```
#
### Pré-condições: 
#### Deve ser o turno do usúario
#
### Pós-condições: 
#### Dominar o território
#
### Garantia de sucesso: 
#### O jogador deve no final de sua ação deve ter conquistado um território e recebido sua carta território.
#

### Cenário de sucesso:
1. O turno deve ser iniciado
2. O jogador deve possuir territórios
3. O jogador deve possuir mais de uma tropa alocada naquele território.
4. O jogador só poderá atacar territórios adjacentes
5. O jogador deverá usar a quantidade de dados relacionada com a quantidade de tropas alocadas no território que irá atacar.
6. Os dados serão lançados.
    ```
    a. Em caso de vitória, o jogador defensor irá retirar a quantidade de peças de seu território igual a quantidade de dados que perdeu. 
    
    b. Em caso de derrota, o jogador atacante irá retirar a quantidade de peças de seu território igual a quantidade de dados que perdeu.

    c. Em caso de empate, o jogador defensor recebe a vantagem.

    Obs.: Este processo pode ser repetido até o jogador atacante ter uma tropa no território ou conquistar o território.
    ``` 

#
## Caso de uso 5: Defender território
### Escopo: 
#### Ação de jogo.
#
### Ator Principal: 
#### Jogador(Defensor)
#
### interessados e Interesses: 
```
- Jogador(Atacante): O jogador que ataca tem como intenção conquistar um território e receber uma nova carta território para o seu monte.

- Jogador(Defensor): Temo como intenção defender seu território para auxiliar na conquista de seu objetivo.

```
#
### Pré-condições: 
#### Deve ser o turno do usúario
#
### Pós-condições: 
#### Defender o seu território
#
### Garantia de sucesso: 
#### O jogador deve no final de sua ação deve ter defendido seu território.
#

### Cenário de sucesso:
1. O turno deve ser iniciado
2. O jogador deverá ser atacado
3. O jogador só poderá ser atacado por territórios adjacentes
4. O jogador deverá usar a quantidade de dados relacionada com a quantidade de tropas alocadas no território que irá atacar.
5. Os dados serão lançados.
    ```
    a. Em caso de vitória, o jogador defensor irá retirar a quantidade de peças de seu território igual a quantidade de dados que perdeu. 
    
    b. Em caso de derrota, o jogador atacante irá retirar a quantidade de peças de seu território igual a quantidade de dados que perdeu.

    c. Em caso de empate, o jogador defensor recebe a vantagem.

    Obs.: Este processo pode ser repetido até o jogador atacante ter uma tropa no território ou conquistar o território.
    ``` 

#
## Caso de uso 6: 
### Escopo: 
#### 
#
### Ator Principal: 
#### 
#
### interessados e Interesses: 
```

```
#
### Pré-condições: 
#### 
#
### Pós-condições: 
#### 
#
### Garantia de sucesso: 
#### 
#

### Cenário de sucesso:
1. 
2.
3.
4.
5.
6.

#
## Caso de uso 7: 
### Escopo: 
#### 
#
### Ator Principal: 
#### 
#
### interessados e Interesses: 
```

```
#
### Pré-condições: 
#### 
#
### Pós-condições: 
#### 
#
### Garantia de sucesso: 
#### 
#

### Cenário de sucesso:
1. 
2.
3.
4.
5.
6.

#
## Caso de uso 8: 
### Escopo: 
#### 
#
### Ator Principal: 
#### 
#
### interessados e Interesses: 
```

```
#
### Pré-condições: 
#### 
#
### Pós-condições: 
#### 
#
### Garantia de sucesso: 
#### 
#

### Cenário de sucesso:
1. 
2.
3.
4.
5.
6.