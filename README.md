# Robotics Project – Maze Escape with a Differential Drive Robot

🇺🇸 English | 🇧🇷 [Português](#projeto-de-robótica--fuga-de-labirinto-com-robô-de-direção-diferencial)

Robotics course project (completed on April 6, 2021) using the virtual differential drive robot in [CoppeliaSim](https://www.coppeliarobotics.com/).

## About the project

The base assignment (**Kinematics**) consisted of programming the locomotion control of CoppeliaSim's virtual differential drive robot, provided in the scene `Projeto1.ttt`, using CoppeliaSim's Remote API in C++ or Python. The controller is correct when the robot drives to any pose (x, y, θ) indicated by moving the *Target* object in the scene — for example, pushing each ball into the corner of the same color.

Building on that, **this project puts the robot inside a maze that it must escape on its own, using pathfinding / maze-solving algorithm strategies**.

<!-- TODO: describe the strategy used, e.g. wall follower (left/right hand rule), Tremaux, BFS, A*, etc., and which sensors were used -->

## Technologies

* [CoppeliaSim](https://www.coppeliarobotics.com/) (EDU V4.1.0)
* C++ <!-- TODO: or Python -->
* [CoppeliaSim Remote API](http://www.coppeliarobotics.com/helpFiles/en/remoteApiOverview.htm)
  * [C++ functions](http://www.coppeliarobotics.com/helpFiles/en/remoteApiFunctions.htm)
  * [Python functions](http://www.coppeliarobotics.com/helpFiles/en/remoteApiFunctionsPython.htm)

## How to run (C++)

1. Configure the `Makefile`, setting the path to the `programming` folder inside your CoppeliaSim installation folder. Example:

   ```makefile
   COPPELIA_DIR=/home/hans/Programs/CoppeliaSim_Edu_V4_1_0_Ubuntu20_04/programming
   ```

2. Open the scene `Projeto1.ttt` in CoppeliaSim. <!-- TODO: change if the maze has its own scene file -->

3. Compile and run:

   ```bash
   make clean
   make
   ./robot
   ```

## Authors

* [julianadamurie](https://github.com/julianadamurie)
* [EduardoBrito97](https://github.com/EduardoBrito97)

---

# Projeto de Robótica – Fuga de Labirinto com Robô de Direção Diferencial

🇺🇸 [English](#robotics-project--maze-escape-with-a-differential-drive-robot) | 🇧🇷 Português

Projeto da disciplina de Robótica (concluído em 6 de abril de 2021) utilizando o robô virtual de direção diferencial do [CoppeliaSim](https://www.coppeliarobotics.com/).

## Sobre o projeto

A atividade base (**Cinemática**) consistia em programar o controle de locomoção do robô de direção diferencial virtual do CoppeliaSim, fornecido na cena `Projeto1.ttt`, utilizando a API de programação remota do Coppelia em C++ ou Python. O controle está correto quando o robô se dirige para qualquer posição (x, y, θ) indicada movendo o objeto *Target* na cena — por exemplo, levando cada bola até a quina de mesma cor.

A partir disso, **este projeto coloca o robô dentro de um labirinto do qual ele precisa sair sozinho, utilizando estratégias de algoritmos de busca / resolução de labirintos**.

<!-- TODO: descrever a estratégia usada, ex.: seguidor de parede (regra da mão esquerda/direita), Tremaux, BFS, A*, etc., e quais sensores foram usados -->

## Tecnologias

* [CoppeliaSim](https://www.coppeliarobotics.com/) (EDU V4.1.0)
* C++ <!-- TODO: ou Python -->
* [API Remota do CoppeliaSim](http://www.coppeliarobotics.com/helpFiles/en/remoteApiOverview.htm)
  * [Funções em C++](http://www.coppeliarobotics.com/helpFiles/en/remoteApiFunctions.htm)
  * [Funções em Python](http://www.coppeliarobotics.com/helpFiles/en/remoteApiFunctionsPython.htm)

## Como executar (C++)

1. Configure o `Makefile` indicando o caminho para a pasta `programming` dentro da sua pasta de instalação do Coppelia. Exemplo:

   ```makefile
   COPPELIA_DIR=/home/hans/Programs/CoppeliaSim_Edu_V4_1_0_Ubuntu20_04/programming
   ```

2. Abra a cena `Projeto1.ttt` no Coppelia. <!-- TODO: alterar se o labirinto tiver uma cena própria -->

3. Compile e execute:

   ```bash
   make clean
   make
   ./robot
   ```

## Autores

* [julianadamurie](https://github.com/julianadamurie)
* [EduardoBrito97](https://github.com/EduardoBrito97)
