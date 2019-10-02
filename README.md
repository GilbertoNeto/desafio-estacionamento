# Desafio - Estacionamento de Carros

## Detalhamento do desafio
Criar uma API para gerenciamento de carros em um estacionamento, que deve ter pelo menos 16 vagas. 
Através dos métodos da API será possível ver quantas vagas estão disponíveis, estacionar um carro, realizar o pagamento do ticket e emitir um relatório de recebimentos.

Detalhamento dos valores a serem cobrados de acordo com a permanência:

|Permanência|Valor (R$)|
|-----------|---------:|
|Até 3 horas|7,00      |
|Hora extra |3,00      |

### Serviços a serem criados
- Consultar quantidade de vagas disponíveis - OK;
- Listar posição das vagas disponíveis - OK;
- Estacionar o veículo em vaga disponível - OK;
- Consultar valor do ticket a ser pago - OK
- Pagamento do ticket - OK;
- Relatório gerencial com quantidade de veículos estacionados e somatório dos pagamentos realizados (apenas dados em formato de JSON) - OK;

### Tecnologias utilizadas
- JDK 1.8+ OBS: O projeto foi desenvolvido utilizando a OpenJDK8 em ambiente Linux;
- Maven 3.3+;
- Banco de dados Mysql;
- Framework Spring;
- Angular 7+ (extra);

### O que avaliaremos
- Coesão do código-fonte
- Boas práticas e padrões;
- Aderência aos serviços solicitados;

### Instruções para execução do projeto Java
1. Criar um schema MySQL local com o nome estacionamento_conpay e senha+password = root 
2. Importar o projeto estacionamento no Eclipse ou Spring Tool Suite como um Maven Project.
3. Executar o maven build do projeto pai com base no pom.xml principal com os comandos mvn clean install para buildar os módulos dependentes na hierarquia do projeto.
4. Ir ao projeto estacionamento-controller e executar a classe EstacionamentoApplication como JavaApplication onde serão criadas 20 vagas para teste das funcionalidades junto com as APIs desenvolvidas.
4.1 As APIs desenvolvidas no back-end estão disponveis na url http://localhost:8080/swagger-ui.html.

### Instruções para execução do projeto Angular
1. Após o build do projeto pai (estacionamento), abrir a aplicação estacionamento-view localizada no diretório front-end do projeto estacionamento, utilizando ferramentas como VSCode, Atom, etc.
2. Acessar o diretório principal do projeto Angular e executar o comando ng serve para subir a aplicação no endereço localhost:4200
