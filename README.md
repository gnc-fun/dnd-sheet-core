# Lista de funcionalidades:

- Cadastrar ficha
  - automatizada, mas nao bloqueie o usuário.
  - importar e exportar a ficha.
- Interações com a ficha
  - sistema de alias (nome -> rolagem existente OU rolagem independente)
    - descrição da ação e possibilidade de descrição randômica.
  - rollagem de dados
    - D20 [PHB 7]
      - teste de habilidade.
      	- iniciativa.
      - rolagem de ataque.
      - salvaguarda.
    - dano
    - rolagens independentes (qualquer dado, qualquer bonus)
    - testes contra a morte.
    - vantagem e desvantagem. [PHB 7]
  - descanso curto e longo.
  - controle de vida
    - dano.
    - cura.
    - pontos de vida temporários.
    - dados de vida.
  - controle de magias
    - slots disponiveis
    - lista de magias conhecidas / preparadas
    - CD da sua magia e modificador de ataque da magia
    - soltar magia (alias com descricao da magia)
  - level up

# Estratégia de desenvolvimento para a primeira versão

Ficha = Conjunto de variáveis.
Sistema de alias =
	- Dados
	- variáveis
	- modificador númerico
	- vantagem e desvantagem

variável = [IDENTIFICADOR - INTEIRO(positivo ou negativo)]
alias = [IDENTIFICADOR - roll - descricao]
roll = [1..+DADO 0..+variável 0..+modificador NORMAL|VANTAGEM|DESVANTAGEM]



Linguagens Formais e Automatos


@authors:
Caetano Alcantara borges
Guilherme Nunes Costa