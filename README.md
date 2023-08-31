# Automatizador-de-despesas
![image](https://github.com/herobruno/Automatizador-de-despesas/assets/125412241/c86cf252-c47e-4719-8a7d-1aec0d939d42)


O código apresentado é um pequeno exemplo de algoritmo de cálculo de pagamento, onde são coletados valores de aluguel, água, luz, internet e possivelmente IPTU, e então são realizados cálculos para determinar o montante a ser pago ,dividico por 2 pessoas

# Desenvolvimento
Declaração de Variáveis:
As variáveis são declaradas para armazenar informações como IPTU falso, valores monetários (aluguel, luz, água, internet), e os resultados intermediários e finais dos cálculos.
Entrada de Dados:
O algoritmo solicita que o usuário insira os valores do aluguel, água, luz e internet. Também pergunta se o usuário possui IPTU falso.
Cálculo de Resultados:
O algoritmo entra em um bloco condicional. Se o usuário indicar que possui IPTU falso, ele calculará resultadoprimeiro como a média entre o aluguel e o IPTU dividido por 2. Caso contrário, calculará resultadoprimeiro como a média entre o aluguel dividido por 2.
Cálculos Adicionais:
O algoritmo calcula resultadosecundario como a média entre os valores de luz, água e internet divididos por 2. Ele também calcula resultadofinal como a soma de resultadoprimeiro e resultadosecundario.
Resultados Individuais:
O algoritmo imprime o valor que José deve pagar (resultadoprimeiro) e o valor que José deve receber (resultadosecundario), além do valor que Vera deve pagar (resultadosecundario) e o valor que Vera deve receber (resultadoprimeiro).
Finalização:
O algoritmo chega ao fim.

# Benefícios da Automatização de Tarefas:
No contexto do exemplo de código, a automatização desses cálculos permite a José e Vera (ou qualquer outras pessoa usando o código) obter rapidamente o valor que ele deve pagar, eliminando a necessidade de fazer manualmente esses cálculos repetitivos. Isso economiza tempo e reduz erros, demonstrando os benefícios práticos da programação na automatização de tarefas cotidianas.
