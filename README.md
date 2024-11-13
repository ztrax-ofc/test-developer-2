# Teste Desenvolvedor Pleno Ztrax

O objetivo deste teste é criar uma aplicação simples com backend e frontend que permita a criação e listagem de objetos em um banco de dados MongoDB. Você deve usar Node.js com NestJS ou Express para o backend e qualquer framework JavaScript ou bibliotecas desejadas (ou nenhuma) para o frontend.

## Instruções para o desenvolvimento e conclusão do teste

- Desenvolva usando a IDE e as ferramentas que se sentir mais a vontade.

- Crie um repositório público e compartilhe o link do resultado através do mesmo canal de comunicação que recebeu esse teste.

- O tempo para a entrega desse teste é de 3 dias após recebe-lo.
## Requisitos do Projeto
### 1. Backend (Node.js com NestJS ou Express)

**Decisão de Framework:** Escolha entre NestJS ou Express para construir o backend. Explique no README a razão da escolha e as vantagens dessa decisão para este tipo de projeto.

**Estrutura e Arquitetura:** Organize o projeto de acordo com boas práticas de arquitetura (ex.: camada de serviço, camada de controle, repositórios, etc.) e explique como pensou nessa estrutura e por que ela atende bem a este caso.

**Linguagem:** Use JavaScript ou TypeScript. Explique sua escolha e como ela beneficia o projeto.

**Endpoints:**

   `/create`: Endpoint para criar um novo objeto com dados padrão no banco de dados MongoDB (a criação pode ser automática, sem necessidade de envio de dados no corpo da requisição).

   `/list`: Endpoint para listar os objetos salvos no banco de dados.
    


**Banco de Dados:** Use MongoDB como banco de dados, configurado em um contêiner Docker.

   

### 2. Docker com MongoDB
Crie um contêiner Docker com uma instância de MongoDB e configure uma collection onde os dados serão armazenados.

Documente no **README** como configurar o Docker para rodar o MongoDB.

    

### 3. Frontend (página web simples)
 **Interface:**
   Crie uma página web que tenha:
   
- Um botão Criar, que chama o endpoint de criação para inserir um novo objeto no banco.
        
- Uma listagem para exibir todos os objetos criados, chamando o endpoint de listagem.
        
**Framework:** Você pode usar um framework como React ou Vue.js, ou simplesmente JavaScript puro para construir a página. Justifique a escolha de usar ou não um framework e explique como isso impacta a simplicidade e eficiência do projeto.

**Estrutura:** Explique como estruturou o código da página web e como isso facilita a manutenção ou escalabilidade.

### 4. Documentação

Crie um arquivo README.md detalhado que contenha:
        
- Justificativas de todas as decisões técnicas solicitadas.
- Instruções para executar a aplicação:
- Dependências necessárias.
- Passos para rodar o Docker e a aplicação.
- Como acessar o frontend e backend (endpoints e instruções de navegação).

## Requisitos Técnicos

**Tecnologias Obrigatórias:** Node.js, MongoDB, Docker.

**Linguagem:** JavaScript ou TypeScript.

**Opcional:** Framework para frontend (como React ou Vue.js), ou escolha de não usar um framework.

### Critérios de Avaliação

**Documentação**: Clareza e detalhamento das justificativas no README, explicando as decisões de arquitetura, linguagem e estrutura.

**Boas Práticas de Código**: Organização, legibilidade e qualidade do código, tanto no backend quanto no frontend.
   
**Conhecimento de Docker e MongoDB**: Capacidade de configurar um ambiente de desenvolvimento com MongoDB usando Docker.
    
**Experiência em Construir APIs REST**: Conhecimento na criação de endpoints e manipulação de dados.
    
**Estrutura do Frontend**: Simplicidade e funcionalidade da interface de criação e listagem.




## Considerações finais

Sinta-se livre para adicionar mais recursos e funcionalidades como desejar, aplicar padrões de projetos, conceitos de arquitetura e organização de código. 

Sinta-se à vontade também para explicar no README quaisquer outras decisões técnicas que tenha tomado além das citadas acima.
