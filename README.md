# CPU Simulator

Simulador visual de uma CPU com acumulador, feito para estudar arquitetura de computadores na prática.

**Demonstração:** https://joaolusca.github.io/CPU-simulator/

## Como funciona

O programa é uma lista de instruções executada sobre um único registrador, o acumulador (`AC`):

| Instrução | O que faz |
|---|---|
| `LOAD n` | Carrega o valor `n` no acumulador |
| `ADD n` | Soma `n` ao acumulador |
| `SUB n` | Subtrai `n` do acumulador |
| `PRINT` | Exibe o valor atual do acumulador no console |

Você pode adicionar instruções ao programa e escolher entre executar tudo ou avançar uma instrução por vez (**Step**). Durante a execução, a linha atual fica destacada, como em um depurador, e o valor do `AC` é atualizado na tela.

## Tecnologias

HTML, CSS e JavaScript puro, sem bibliotecas, em um único arquivo (`index.html`).
