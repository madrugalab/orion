# orion
API capaz de gerenciar os restaurantes e os produtos do seu cardápio.

### Instruções

- **Objetivo do Projeto:** Criar uma API RESTful capaz de gerenciar os restaurantes e os produtos do seu cardápio.
- **Tecnologia:** Node.js com banco de dados relacional.

### Desafio

- A sua API deverá ser capaz de:
    - Listar todos os restaurantes
    - Cadastrar novos restaurantes
    - Listar os dados de um restaurante
    - Alterar os dados um restaurante
    - Excluir um restaurante
    - Listar todos os produtos de um restautante
    - Criar um produto de um restaurante
    - Alterar um produto de um restaurante
    - Excluir um produto de um restaurante

- O cadastro do restaurante precisa ter os seguintes campos:
    - Foto do restaurante
    - Nome do restaurante
    - Endereço do restaurante
    - Horários de funcionamento do restaurante (ex.: De Segunda à Sexta das 09h as 18h e de Sabado à Domingo das 11h as 20h).
    
- O cadastro de produtos do restaurante precisa ter os seguintes campos:
    - Foto do produto
    - Nome do produto
    - Preço do produto
    - Categoria do produto (ex.: Doce, Salgados, Sucos...)
    - Quando o Produto for colocado em promoção, precisa ter os seguintes campos:
        - Descrição para a promoção do produto (ex.: Chopp pela metade do preço)
        - Preço promocional
        - Dias da semana e o horário em que o produto deve estar em promoção
##### Formato de horários
- É necessário tratar os campos que indicam horários de funcionamento e horário para as promoções dos produtos. 
- Os campos devem possuir o formato `HH:mm`. 
- Os horários devem possuir intervalo mínimo de 15 minutos.

### Dicas

- Documente seu projeto em arquivos markdown explicando a estrutura, processo de setup e requisitos.
- Tenha sempre um mindset de usabilidade, escalabilidade e colaboração.
- A organização das branches e os commits no repositório falam muito sobre como você organiza seu trabalho.
- Os testes unitários são mais do que desejados.
- O design/estrutura do código da aplicação deve ser *production ready*.
- Tenha em mente os conceitos de *SOLID, KISS, YAGNI e DRY*.
- Use boas práticas de programação.
- Considere que não sabemos nada sobre os seus conhecimentos, então quanto mais você mostrar e o quão mais descritiva for sua documentação, melhor =]

#### Qual banco de Dados devo usar?

Escolha entre MySQL e PostgreSQL. 

#### Posso usar um ORM?

O uso de ORM é permitido apenas para **estabelecer a conexão com o banco de dados.** No entanto, para podermos avaliar os seus conhecimentos em SQL pedimos que **não use ORM nas consultas ao banco.** As bibliotecas normalmente possuem métodos que permitem consultas diretamente em SQL (raw queries) mesmo através do ORM.


