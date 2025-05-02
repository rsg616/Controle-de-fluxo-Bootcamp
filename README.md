# 📘 DesafioControleFluxo

Este é um projeto simples em Java com o objetivo de praticar os conceitos de **controle de fluxo**, **tratamento de exceções personalizadas** e **entrada de dados via terminal**.

---

## 📋 Descrição

O sistema solicita dois números inteiros do usuário. Com base nesses números, ele realiza uma contagem e imprime no console quantas vezes for a diferença entre eles.

Se o **primeiro número for maior ou igual ao segundo**, o sistema lançará uma **exceção personalizada** chamada `ParametrosInvalidosException`, exibindo a mensagem:

> O segundo parâmetro deve ser maior que o primeiro

---

## 💡 Exemplo de funcionamento

**Entrada:**
```
Digite o primeiro parâmetro:
5
Digite o segundo parâmetro:
9
```

**Saída:**
```
Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3
Imprimindo o número 4
```

---

## ⚙️ Como executar

1. Compile o projeto:
```bash
javac Contador.java
```

2. Execute:
```bash
java Contador
```

---

## 🧠 Conceitos abordados

- Entrada de dados via `Scanner`
- Laço de repetição `for`
- Lançamento de exceção com `throw`
- Criação de exceção customizada (`ParametrosInvalidosException`)
- Estrutura de controle `try/catch`

---

## 🛠️ Possível aplicação

Este tipo de lógica pode ser aplicada em situações onde você precisa **validar faixas de entrada numérica antes de iniciar um processamento em lote**, como em **geração de relatórios**, **paginação de dados**, ou **controle de loops baseados em intervalos configuráveis**.

---

## 👨‍💻 Autor

Feito por [Seu Nome] — sinta-se à vontade para entrar em contato!

---

## 📄 Licença

Este projeto está licenciado sob a licença MIT.
