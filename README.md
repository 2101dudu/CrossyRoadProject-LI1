<h1 align="center">Laboratórios de Informática I <img align="center" src="https://github.com/devicons/devicon/blob/master/icons/haskell/haskell-original.svg" target="_blank" title="Haskell" alt="Haskell" width="30" height="30"/></h1>

<h3 align="center"> Made using the Haskell programming language and Gloss Library during the 1st semester of the 1st year</h3> 

<h1 align="center">Final Grade: 19/20💎</h1>


## Preview

![Main Menu](ReadMe_Photos/Menu_Screen.png)

#

![Options Menu](ReadMe_Photos/Options__Screen.png)

#

![Example1](ReadMe_Photos/Game_Photo_1.png)

#

![Example2](ReadMe_Photos/Game_Photo_2.png)



## Repository

Run the command "ghc Main.hs" in the src directory. If it doesn't work, try "ghc Main.hs -package random." Then, run the command "./Main" to start the game.


If you have an SSH key configured on GitLab, you can clone using the following link:

```bash
$ git clone https://github.com/2101dudu/CrossyRoadProject-LI1.git
$ cd src
```

Alternatively, you can clone via HTTPS with the following link:

```bash
$ git clone https://gitlab.com/uminho-di/li1/2223/projetos/2022li1g018.git
$ cd src
```

## Interpreter

You can open the Haskell interpreter (GHCi) using Cabal or directly.

1. Using cabal

```bash
$ cabal repl
```

2. Using GHCi

```bash
$ ghci -i="src" -i="tests" src/Main.hs
```

## Tests

The project uses the [HUnit](https://hackage.haskell.org/package/HUnit) library for unit testing.

You can run the tests using one of the following alternatives:

1. Using `cabal`

```bash
$ cabal test
```

2. Using GHCi

```bash
$ ghci -i="src" -i="tests" tests/Spec.hs
>>> runTestsT1 -- Correr os testes tarefa 1
>>> runTestsT2 -- Correr os testes tarefa 2
>>> runTestsT3 -- Correr os testes tarefa 3
>>> runTestsT4 -- Correr os testes tarefa 4
>>> runTestsT5 -- Correr os testes tarefa 5
>>> main -- Correr todos os testes
```

3. Using the `runhaskell` wrapper

```bash
$ runhaskell -i="src" -i="tests" tests/Spec.hs
```

## Documentation

You can generate documentation with [Haddock](https://haskell-haddock.readthedocs.io/).

1. Using `cabal`

```bash
$ cabal haddock --haddock-all
```

2. Using `haddock` directly

```bash
$ haddock -h -o doc/html src/*.hs
```


## Group 18

- **A104353** Eduardo de Oliveira Sousa Faria;
- **A104089** Nuno Miguel Ribeiro da Silva;
