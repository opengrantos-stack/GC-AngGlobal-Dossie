# 09 — Produto e Tecnologia

## 9.1. Visão geral

O GC-AngGlobal é uma plataforma digital de comércio desenvolvida pela Geração Calueio – COMÉRCIO E SERVIÇOS, LDA.

O produto foi concebido inicialmente como uma aplicação web acessível através de dispositivos móveis e computadores.

O objetivo tecnológico é disponibilizar uma infraestrutura que permita a diferentes negócios apresentar produtos e serviços, receber pedidos e gerir a sua presença comercial digital.

---

## 9.2. Estado atual do produto

O projeto já possui uma versão funcional do produto.

O desenvolvimento inicial permitiu implementar e testar funcionalidades essenciais para a operação de uma plataforma comercial.

Entre as funcionalidades já desenvolvidas encontram-se:

- publicação de produtos;
- publicação de serviços;
- apresentação de produtos;
- apresentação de serviços;
- descrição;
- preço;
- imagem;
- edição de produtos;
- edição de serviços;
- eliminação de produtos;
- eliminação de serviços;
- área administrativa;
- autenticação administrativa;
- gestão básica dos conteúdos publicados;
- publicação através de dispositivos móveis.

A versão atual representa uma base tecnológica para evolução do produto.

---

## 9.3. MVP

O produto encontra-se numa fase de MVP — Minimum Viable Product.

O objetivo do MVP não é disponibilizar imediatamente todas as funcionalidades de uma grande plataforma comercial.

O objetivo é disponibilizar as funcionalidades essenciais para:

1. testar a proposta;
2. obter utilizadores;
3. recolher feedback;
4. validar o modelo de negócio;
5. desenvolver novas funcionalidades com base em necessidades reais.

---

## 9.4. Arquitetura inicial

A plataforma utiliza uma arquitetura web composta por:

- frontend;
- backend;
- API;
- base de dados;
- armazenamento de imagens;
- autenticação administrativa.

O frontend é responsável pela interface utilizada pelos visitantes e administradores.

O backend processa as operações e disponibiliza os endpoints da API.

A base de dados será responsável pelo armazenamento estruturado das informações da plataforma.

---

## 9.5. Tecnologias

A versão atual utiliza tecnologias web modernas e uma arquitetura baseada em JavaScript.

Entre os componentes utilizados encontram-se:

- HTML;
- CSS;
- JavaScript;
- Node.js;
- Express;
- API REST;
- PostgreSQL.

A arquitetura poderá evoluir à medida que aumentarem as necessidades de escala.

---

## 9.6. Interface

A interface foi pensada para funcionar em dispositivos móveis e computadores.

A experiência móvel é especialmente importante porque o mercado inicial será Angola.

Os utilizadores deverão conseguir realizar operações básicas utilizando principalmente o smartphone.

---

## 9.7. Publicação de produtos

O administrador consegue introduzir informações como:

- tipo;
- nome;
- descrição;
- preço;
- imagem.

O sistema processa esses dados e publica o conteúdo na plataforma.

---

## 9.8. Publicação de imagens

A plataforma permite trabalhar com imagens dos produtos.

A experiência foi adaptada para dispositivos móveis, incluindo duas possibilidades:

### Escolher foto

O utilizador pode selecionar uma imagem existente no dispositivo.

### Tirar foto

O utilizador pode utilizar a câmara do dispositivo para tirar uma nova fotografia.

Essa funcionalidade reduz a necessidade de utilizar computador para publicar produtos.

---

## 9.9. Edição

Os produtos e serviços publicados podem ser editados pelo administrador.

A edição permite corrigir ou atualizar informações como:

- nome;
- descrição;
- preço;
- imagem;
- tipo.

Essa funcionalidade é importante porque os dados comerciais mudam frequentemente.

---

## 9.10. Eliminação

O administrador também pode eliminar produtos ou serviços.

A operação é protegida por autenticação administrativa.

Antes da eliminação, o sistema solicita confirmação.

Essa medida reduz o risco de eliminar um conteúdo por engano.

---

## 9.11. Autenticação

As operações administrativas utilizam autenticação.

O sistema verifica a existência de uma credencial administrativa antes de permitir determinadas operações.

A autenticação deverá evoluir para uma arquitetura mais robusta antes da expansão comercial em grande escala.

---

## 9.12. API

A plataforma utiliza uma API para comunicação entre a interface e o servidor.

Entre as operações principais encontram-se:

- criação de produtos;
- consulta de produtos;
- atualização de produtos;
- eliminação de produtos.

A utilização de uma API permite separar a interface da lógica do servidor.

Isso facilita futuras integrações.

---

## 9.13. Base de dados

O projeto está preparado para utilizar PostgreSQL como base de dados.

A utilização de uma base de dados relacional permitirá estruturar informações como:

- utilizadores;
- empresas;
- produtos;
- serviços;
- pedidos;
- comentários;
- pagamentos;
- assinaturas;
- histórico.

A estrutura definitiva será desenvolvida progressivamente.

---

## 9.14. Escalabilidade

O objetivo comercial é permitir que muitos negócios utilizem a mesma plataforma.

Por isso, a arquitetura deverá evoluir para suportar múltiplos clientes de forma segura e organizada.

A escalabilidade deverá considerar:

- número de utilizadores;
- número de negócios;
- quantidade de produtos;
- quantidade de pedidos;
- armazenamento;
- tráfego;
- consultas à base de dados;
- segurança.

---

## 9.15. Arquitetura multiutilizador

O modelo SaaS exige que diferentes negócios possam utilizar a mesma infraestrutura.

A evolução da plataforma deverá implementar uma arquitetura multiutilizador.

Cada negócio deverá ter os seus próprios:

- dados;
- produtos;
- serviços;
- utilizadores autorizados;
- pedidos;
- configurações.

Os dados de um negócio não deverão ser expostos a outro.

---

## 9.16. Segurança

A segurança será um dos pilares do desenvolvimento.

A evolução tecnológica deverá incluir:

- autenticação segura;
- autorização por função;
- proteção de endpoints;
- validação de dados;
- proteção contra ataques comuns;
- gestão segura de sessões;
- utilização de HTTPS;
- proteção da base de dados;
- backups;
- monitorização.

As credenciais e informações sensíveis nunca deverão ser armazenadas de forma insegura.

---

## 9.17. Escala de infraestrutura

Durante a fase inicial, a plataforma poderá utilizar infraestrutura de baixo custo.

À medida que o número de clientes crescer, será possível aumentar os recursos.

A infraestrutura poderá evoluir em etapas:

### Fase inicial

Servidor e base de dados de baixo custo.

### Fase de crescimento

Recursos superiores e maior capacidade de armazenamento.

### Fase de escala

Infraestrutura preparada para elevada quantidade de tráfego e operações simultâneas.

O crescimento da infraestrutura deverá acompanhar o crescimento da receita.

---

## 9.18. Armazenamento de imagens

O armazenamento de imagens será um componente importante.

À medida que o número de vendedores aumentar, a quantidade de imagens poderá crescer significativamente.

Por isso, a arquitetura futura poderá utilizar armazenamento especializado para ficheiros e imagens.

Isso permitirá separar:

- dados estruturados;
- ficheiros;
- imagens;
- backups.

---

## 9.19. Funcionalidades futuras

A plataforma poderá evoluir para incluir:

### Conta de vendedor

Cada negócio terá a sua própria conta.

### Conta de comprador

Os compradores poderão criar perfis.

### Comentários

Utilizadores poderão comentar produtos e serviços.

### Avaliações

Compradores poderão avaliar experiências.

### Favoritos

Produtos poderão ser guardados.

### Carrinho

O comprador poderá organizar vários produtos antes de realizar um pedido.

### Pedidos

O sistema poderá gerir pedidos de forma estruturada.

### Notificações

Vendedores e compradores poderão receber notificações.

### Pagamentos

Poderão ser integrados métodos de pagamento adequados ao mercado.

### Assinaturas

A plataforma poderá gerir planos e pagamentos recorrentes dos vendedores.

---

## 9.20. Roadmap tecnológico

### Etapa 1 — MVP

Funcionalidades comerciais básicas.

**Estado:** desenvolvido.

### Etapa 2 — Gestão de vendedores

- contas;
- perfis;
- produtos por vendedor;
- gestão individual.

**Estado:** próxima fase de evolução.

### Etapa 3 — Compradores

- contas;
- histórico;
- favoritos;
- pedidos.

### Etapa 4 — Interação

- comentários;
- avaliações;
- notificações.

### Etapa 5 — Monetização

- planos;
- assinaturas;
- pagamentos;
- faturação.

### Etapa 6 — Escala

- infraestrutura;
- segurança;
- monitorização;
- otimização;
- automação.

---

## 9.21. Desenvolvimento contínuo

O desenvolvimento deverá utilizar ciclos curtos.

Cada funcionalidade deverá seguir aproximadamente:

**ideia → desenvolvimento → teste → lançamento → feedback → melhoria.**

Isso permite reduzir o risco de investir grandes recursos em funcionalidades que não apresentam procura suficiente.

---

## 9.22. Propriedade intelectual

O código-fonte e os componentes desenvolvidos especificamente para o projeto deverão ser organizados e controlados pela empresa promotora.

O projeto tecnológico deverá manter documentação sobre:

- código;
- arquitetura;
- bases de dados;
- APIs;
- documentação técnica;
- versões;
- alterações.

A proteção jurídica da propriedade intelectual deverá ser avaliada de acordo com a legislação aplicável.

---

## 9.23. Código-fonte e controlo de versões

O desenvolvimento utiliza controlo de versões através do Git.

O código é organizado em repositório próprio.

O controlo de versões permite:

- acompanhar alterações;
- recuperar versões;
- documentar desenvolvimento;
- colaborar;
- reduzir riscos de perda;
- organizar lançamentos.

---

## 9.24. Testes

Antes da disponibilização de novas funcionalidades, deverão ser realizados testes.

Os testes poderão incluir:

- testes funcionais;
- testes de API;
- testes de interface;
- testes em dispositivos móveis;
- testes de segurança;
- testes de carga;
- testes de compatibilidade.

A qualidade deverá aumentar progressivamente com a maturidade do produto.

---

## 9.25. Suporte técnico

A empresa deverá criar mecanismos de suporte para clientes.

O suporte poderá inicialmente ocorrer através de canais digitais.

À medida que a base de clientes crescer, poderá ser implementado um sistema estruturado de atendimento.

O objetivo será reduzir o tempo de resolução de problemas.

---

## 9.26. Vantagem tecnológica

A principal vantagem tecnológica inicial não está na utilização de tecnologias exclusivas.

Está na capacidade de desenvolver e adaptar rapidamente uma plataforma orientada para um mercado específico.

A empresa poderá controlar a evolução do produto e ajustar a tecnologia de acordo com o comportamento dos clientes.

---

## 9.27. Capacidade de evolução

A arquitetura baseada em API e tecnologias web permite que o produto evolua para diferentes interfaces e integrações.

No futuro, poderão ser desenvolvidos:

- aplicação Android;
- aplicação iOS;
- painel empresarial;
- API para parceiros;
- integrações de pagamento;
- integrações logísticas;
- ferramentas analíticas.

Essas extensões serão realizadas de acordo com a prioridade comercial.

---

## 9.28. Conclusão

O GC-AngGlobal já possui uma base tecnológica funcional que demonstra a viabilidade técnica inicial do projeto.

O produto atual permite publicar, editar e eliminar produtos e serviços e foi adaptado para utilização através de dispositivos móveis.

A próxima fase será transformar essa base administrativa num verdadeiro sistema SaaS multiutilizador, no qual diferentes negócios possam possuir contas independentes, gerir os seus próprios produtos e pagar mensalidades pelo acesso.

A evolução tecnológica será orientada pelo mercado.

O objetivo é construir uma infraestrutura segura, escalável e sustentável que possa crescer de acordo com o número de clientes.

**O GC-AngGlobal não parte apenas de uma ideia: já existe uma base funcional sobre a qual o negócio poderá ser construído.**
