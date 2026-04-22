# 🧮 Calculadora Simples em Python

Este projeto consiste em uma função de calculadora básica que realiza operações aritméticas fundamentais entre dois números. É uma demonstração prática de como utilizar **funções**, **parâmetros** e **estruturas condicionais** em Python.

## 📝 Resumo
O projeto utiliza uma função para processar cálculos matemáticos com base em operadores fornecidos pelo usuário através do terminal.

## 🚀 Funcionalidades

O script suporta as quatro operações básicas:
* **Soma** (`+`)
* **Subtração** (`-`)
* **Multiplicação** (`*`)
* **Divisão** (`/`)

> **Nota:** Caso um operador inválido seja digitado, o sistema retornará o valor `0`.

## 🛠️ Como Usar

1.  Certifique-se de ter o Python instalado.
2.  Execute o script:
    ```bash
    python calculadora.py
    ```
3.  Insira o primeiro número, o segundo número e o símbolo da operação desejada quando solicitado.

## 💻 Exemplo de Código

```python
def calculadora(num1, num2, op):
    if op == "+":
        return num1 + num2
    # ... outras operações
```

---
*Projeto desenvolvido para fins didáticos sobre lógica de programação e funções.*
