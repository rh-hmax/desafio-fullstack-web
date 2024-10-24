# Criação de API com NestJs e Frontend Angular

## História
Precisamos de uma API para cadastro de produtos para uma loja genérica e um Frontend para interagir com esta API, que permita que o gerente da loja acesse e faça modificações, e que um cliente da loja possa ver a lista de produtos disponíveis.

### Requisitos funcionais
1. Como gerente gostaria de INCLUIR um novo produto ao catálogo da loja
2. Como gerente gostaria de EDITAR um produto existente no catálogo
3. Como gerente gostaria de REMOVER o produto do meu catálogo da loja
4. Como gerente gostaria de recuperar uma LISTA com os produtos disponíveis
5. Como gerente gostaria de BUSCAR produtos pela sua DESCRIÇÃO
6. Como gerente preciso que os resultados sejam PAGINADOS
7. Como gerente quero que apenas pessoas com permissão possam: adicionar, editar remover produtos
8. Como CLIENTE quero VIZUALIZAR a lista de produtos

### Requisitos não funcionais
1. A API deve usar [NestJs](https://nestjs.com/) com Typescript
2. A API deve seguir um padrão [REST](https://cloud.google.com/apis/design)
3. A API deve ter pelo menos 3 testes unitários com [JEST](https://jestjs.io/pt-BR/)
4. A API deve usar o [Prisma ORM](https://www.prisma.io/)
4. A API deve usar preferencialmente o banco de dados NoSQL MongoDB, não sendo possível, utilizar PostgreSQL _(ver documentação do Prisma)_
6. O Frontend deve ser desenvolvido em [Angular](https://angular.dev/)
4. O Frontend deve usar componentes [Angular Material](https://material.angular.io/)

### Entrega
	- Um repositório GitHub
	- Um ambiente rodando a aplicação

### Critérios de avaliação
	- Entendimento dos requisitos
	- Afinidade com a ferramenta utilizada
	- Testes unitários
	- Estrutura de arquivos
	- Padrão de escrita do código
	- Utilização de boas práticas
