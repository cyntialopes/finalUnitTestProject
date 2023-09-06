# Teste Unitário para a Classe `Restaurant` e `IceCreamStand`

Projeto da disciplina de Teste Unitário da especialização em Testes Ágeis pela CESAR SCHOOL. 

O projeto consiste em implementar testes unitários para as classes `Restaurant` e `IceCreamStand`. Abaixo estão as instruções para configurar o ambiente, executar os testes e uma breve descrição das classes e dos testes.

## Descrição das Classes

### `Restaurant`

A classe `Restaurant` representa um restaurante simples e possui os seguintes métodos:

- `__init__(self, restaurant_name, cuisine_type)`: Inicializa a instância da classe com o nome do restaurante e o tipo de cozinha.
- `describe_restaurant(self)`: Retorna uma descrição do restaurante.
- `open_restaurant(self)`: Abre o restaurante.
- `close_restaurant(self)`: Fecha o restaurante.
- `set_number_served(self, total_customers)`: Define o número total de clientes atendidos.
- `increment_number_served(self, more_customers)`: Incrementa o número total de clientes atendidos.

### `IceCreamStand`

A classe `IceCreamStand` é uma subclasse de `Restaurant` e representa uma sorveteria. Ela adiciona um atributo `flavors` para armazenar os sabores de sorvete disponíveis e possui os seguintes métodos:

- `__init__(self, restaurant_name, cuisine_type, flavors_list)`: Inicializa a instância da sorveteria com o nome, tipo de cozinha e uma lista de sabores.
- `flavors_available(self)`: Retorna uma lista dos sabores de sorvete disponíveis.
- `find_flavor(self, flavor)`: Verifica se um sabor específico está disponível.
- `add_flavor(self, flavor)`: Adiciona um novo sabor ao estoque.

## Configurando o Ambiente

Antes de executar os testes, você precisa configurar o ambiente. Siga os passos abaixo:

1. Certifique-se de ter Python instalado no seu sistema. Se não tiver, faça o download e a instalação a partir do [site oficial do Python](https://www.python.org/downloads/).

2. Clone o repositório do projeto ou crie um ambiente virtual, se necessário.

3. Instale a biblioteca `unittest` se ainda não estiver instalada. Você pode instalar usando o seguinte comando:

   ```bash
   pip install unittest
   ```

## Executando os Testes

Para executar os testes unitários para as classes `Restaurant` e `IceCreamStand`, siga as instruções abaixo:

1. Navegue até o diretório do projeto.

2. Execute os seguintes comandos no terminal:

   Para testar a classe `Restaurant`:

   ```bash
   python -m unittest test_restaurant.py
   ```

   Para testar a classe `IceCreamStand`:

   ```bash
   python -m unittest test_ice_cream_stand.py
   ```

3. Os resultados dos testes serão exibidos no terminal. Certifique-se de que todos os testes passaram com sucesso.

## Conclusão

Este projeto demonstra a implementação de testes unitários para as classes `Restaurant` e `IceCreamStand`, garantindo que o código funcione conforme o esperado. A prática de testes unitários é essencial para identificar e corrigir problemas no código, melhorar a qualidade do software e garantir um desenvolvimento mais confiável.
