# Projeto Java - Cálculo de Áreas de Formas Geométricas

Este projeto implementa um sistema simples para calcular a área de formas geométricas como **círculos** e **retângulos**. Ele utiliza conceitos de herança e polimorfismo em Java, além da leitura de dados do usuário via console.

## Funcionalidades

- O usuário pode escolher entre criar círculos ou retângulos.
- As formas são criadas a partir de dados fornecidos pelo usuário, como cor, dimensões (largura, altura ou raio).
- As áreas de todas as formas são calculadas e exibidas.

## Estrutura do Projeto

O projeto está dividido em diferentes pacotes e classes:

### Pacote `entities`
- **`Shape`**: Classe abstrata que representa uma forma geométrica e define o método abstrato `area()`.
- **`Circle`**: Subclasse de `Shape` que implementa uma forma de círculo.
- **`Rectangle`**: Subclasse de `Shape` que implementa uma forma de retângulo.

### Pacote `enums`
- **`Color`**: Enum que define as cores possíveis das formas: BLACK, BLUE, RED.

### Pacote `application`
- **`Program`**: Classe principal que interage com o usuário e gera as formas baseadas nas entradas.