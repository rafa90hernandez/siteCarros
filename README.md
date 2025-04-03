# Car Management Project

## Como Executar o Projeto

1. Vá até o diretório hotwheels:
cd hotwheels

2. Instale as dependências:
npm install


3. Inicie o servidor de desenvolvimento:
npm start

4. Acesse a aplicação em http://localhost:3000.

 
###Estrutura dos Componentes
NavBar: Barra de navegação com links para as diferentes páginas da aplicação.
HomePage: Página inicial da aplicação.
InfoPage: Página informativa sobre a aplicação.
AddCarPage: Página com formulário para adicionar um novo carro.
EditCarPage: Página com formulário para editar um carro existente.
CarListPage: Página que lista todos os carros, permitindo edição e exclusão.


###Conexão com a API
axiosConfig.js: Configuração do Axios para comunicação com a API REST.
As páginas AddCarPage, EditCarPage e CarListPage utilizam Axios para realizar operações CRUD na API.

###Executando a API
1. Clone o repositório da API:
git clone https://github.com/adsPucrsOnline/DesenvolvimentoFrontend.git

2. Acesse o diretório:
cd DesenvolvimentoFrontend/hotwheels-api/


3. Instale as dependências e inicie a API:
npm install
npm start

A API estará disponível em http://localhost:5000.



###Executando os Testes
Para executar os testes automatizados usando Cypress:

Abra um terminal na raiz do projeto.

Execute o seguinte comando para iniciar o Cypress em modo de linha de comando:

bash
Copiar código
npx cypress run --spec "cypress/integration/nome-do-arquivo-de-teste.spec.js"
Substitua "cypress/integration/nome-do-arquivo-de-teste.spec.js" pelo caminho correto do seu arquivo de teste Cypress.
Por exemplo:

bash
Copiar código
npx cypress run --spec "cypress/integration/example.spec.js"
O Cypress iniciará a execução dos testes e mostrará os resultados no terminal.

Executando Testes Interativamente (opcional)
Se preferir uma abordagem mais interativa:

Abra um terminal na raiz do projeto.

Execute o seguinte comando para abrir a interface gráfica do Cypress:

bash
Copiar código
npx cypress open
Isso abrirá a interface do Cypress, onde você pode selecionar e executar seus testes manualmente.

Detalhes Adicionais
Certifique-se de que todos os comandos são executados na raiz do projeto onde o arquivo package.json está localizado.
Verifique a documentação oficial do Cypress para mais informações sobre como escrever e executar testes.



