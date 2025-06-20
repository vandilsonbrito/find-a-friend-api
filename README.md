### Find A Frined API.

#### RFs (Requisitos Funcionais - funcionalidades da aplicação, o que o usuário pode fazer na aplicação).

- [ ] - Deve ser possível se cadastrar como uma ORG;

- [ ] - Deve ser possível realizar login como uma ORG;

- [ ] - Deve ser possível cadastrar um pet;

- [ ] - Deve ser possí­vel adicionar fotos do pet;

- [ ] - Deve ser possível listar todos os pets disponíveis (não adotados) para adoção em uma cidade;

- [ ] - Deve ser possível filtrar pets por suas características;

- [ ] - Deve ser possível visualizar detalhes de um pet para adoção;



#### RNs (Regras de Negócio - condições aplicadas às funcionalidades. Quando/como tal funcionalidade deve acontecer).

- [ ] - Para uma ORG acessar a aplicação como admin (cadastrar, editar ou remover seus pets), ela precisa estar logada;

- [ ] - Para listar os pets, obrigatoriamente é preciso informar a cidade;

- [ ] - Uma ORG precisa ter um endereço e um número de WhatsApp;

- [ ] - Um pet deve estar ligado a uma ORG;

- [ ] - Um pet pode ter status "disponível" ou "adotado";

- [ ] - O usuário que quer adotar, entrará em contato com a ORG via WhatsApp;

- [ ] - Todos os filtros, além da cidade, são opcionais;

  
#### RNFs (Requisitos Não-Funcionais - pensado pelo desenvolvedor, quais tecnologias e estratégias usar)

- [ ] - A senha do usuário precisa estar criptografada;

- [ ] - Os dados da aplicação precisam estar persistidos em um banco PostgreSQL;

- [ ] - Todas listas de dados precisam estar paginadas com 20 itens por página;

- [ ] - O usuário deve ser identificado por um JWT (JSON Web Token);

- [ ] - Implementar Rate Limiting para proteger contra abusos na API;

- [ ] - Utilizar Soft Delete nos pets (não apagar do banco, apenas colocar como inativo);