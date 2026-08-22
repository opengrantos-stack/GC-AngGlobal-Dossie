# 20 — Tecnologia, Produto e Roadmap de Funcionalidades

## 20.1. Visão tecnológica

O GC-AngGlobal será uma plataforma digital desenvolvida para permitir que múltiplos negócios utilizem uma infraestrutura tecnológica comum.

A arquitetura será evoluída progressivamente para suportar o crescimento do número de empresas, produtos, serviços, compradores e encomendas.

---

## 20.2. Produto existente

O projeto já possui uma versão funcional em desenvolvimento e testes.

A versão atual permite validar conceitos fundamentais do produto, incluindo:

- apresentação de produtos;
- apresentação de serviços;
- cadastro;
- publicação;
- edição;
- eliminação;
- utilização de imagens;
- gestão administrativa;
- comunicação com a API.

A existência do MVP reduz o risco associado à fase inicial de desenvolvimento.

---

## 20.3. Arquitetura

A plataforma utiliza uma arquitetura baseada em aplicação web e API.

Os principais componentes incluem:

- interface web;
- servidor;
- API;
- base de dados;
- armazenamento;
- autenticação;
- área administrativa.

A arquitetura poderá ser modificada conforme aumentarem as necessidades de escala.

---

## 20.4. Interface

A interface deverá ser simples e adaptada principalmente a dispositivos móveis.

A experiência deverá permitir que o utilizador consiga realizar as principais tarefas sem conhecimento técnico avançado.

---

## 20.5. Produtos

O sistema deverá permitir aos negócios publicar informações como:

- nome;
- descrição;
- preço;
- imagem;
- tipo;
- outras informações comerciais.

A estrutura poderá ser ampliada futuramente.

---

## 20.6. Serviços

Além de produtos físicos, a plataforma poderá permitir a apresentação de serviços.

Isso amplia o mercado potencial para profissionais e empresas que não comercializam produtos físicos.

---

## 20.7. Imagens

A plataforma deverá permitir diferentes formas de adicionar imagens.

No ambiente móvel, o utilizador poderá:

- escolher uma imagem da galeria;
- tirar uma nova fotografia através da câmara.

Essa funcionalidade facilita a publicação diretamente a partir do telemóvel.

---

## 20.8. Gestão administrativa

A plataforma possui funcionalidades destinadas à administração dos conteúdos.

Entre elas:

- publicação;
- edição;
- eliminação;
- gestão de produtos e serviços.

O acesso às funções administrativas deverá ser protegido.

---

## 20.9. API

A API será responsável pela comunicação entre a interface e o servidor.

Ela permitirá operações relacionadas com:

- produtos;
- serviços;
- publicação;
- edição;
- eliminação;
- consulta.

A API poderá ser ampliada à medida que novas funcionalidades forem adicionadas.

---

## 20.10. Base de dados

A plataforma deverá utilizar uma base de dados adequada para armazenar informações de forma estruturada.

Os dados poderão incluir:

- utilizadores;
- empresas;
- produtos;
- serviços;
- pedidos;
- assinaturas;
- pagamentos;
- configurações.

A estrutura definitiva deverá evoluir conforme os requisitos do produto.

---

## 20.11. Multi-tenant

Como o objetivo comercial é permitir que muitos negócios utilizem a mesma plataforma, o sistema deverá evoluir para uma arquitetura multi-tenant.

Isso significa que vários negócios poderão utilizar a mesma infraestrutura, mantendo os seus dados e operações devidamente separados.

Essa arquitetura será fundamental para o modelo SaaS.

---

## 20.12. Escalabilidade

A tecnologia deverá ser preparada para crescimento progressivo.

A capacidade poderá ser ampliada através de:

- servidores mais robustos;
- otimização da aplicação;
- otimização da base de dados;
- armazenamento escalável;
- cache;
- monitorização;
- distribuição de carga quando necessária.

---

## 20.13. Segurança

A segurança deverá ser incorporada desde as primeiras fases.

Serão considerados:

- autenticação;
- autorização;
- proteção de credenciais;
- validação de dados;
- controlo de acesso;
- backups;
- atualizações;
- monitorização.

---

## 20.14. Responsividade

A plataforma deverá funcionar adequadamente em:

- telemóveis;
- tablets;
- computadores.

A prioridade inicial será a experiência móvel devido à importância dos dispositivos móveis no acesso à internet.

---

## 20.15. Roadmap — Fase 1

### MVP

Funcionalidades principais:

- cadastro;
- publicação;
- produtos;
- serviços;
- imagens;
- edição;
- eliminação;
- administração.

Objetivo:

**validar o produto.**

---

## 20.16. Roadmap — Fase 2

### Experiência comercial

Funcionalidades previstas:

- perfis empresariais;
- categorias;
- pesquisa;
- filtros;
- melhores páginas de produto;
- informações comerciais;
- melhorias de navegação.

Objetivo:

**melhorar a experiência de compradores e vendedores.**

---

## 20.17. Roadmap — Fase 3

### Encomendas

Funcionalidades previstas:

- criação de pedidos;
- gestão de pedidos;
- estado do pedido;
- notificações;
- histórico.

Objetivo:

**transformar a apresentação de produtos numa experiência comercial mais completa.**

---

## 20.18. Roadmap — Fase 4

### Contas e assinaturas

Funcionalidades previstas:

- contas empresariais;
- planos;
- assinaturas;
- controlo de acesso;
- renovação;
- suspensão;
- upgrade;
- gestão de clientes.

Objetivo:

**implementar plenamente o modelo SaaS.**

---

## 20.19. Roadmap — Fase 5

### Pagamentos

Funcionalidades futuras poderão incluir:

- pagamentos de assinaturas;
- integração com métodos de pagamento;
- confirmação de pagamentos;
- histórico;
- faturação.

Os métodos específicos serão definidos de acordo com a realidade do mercado.

---

## 20.20. Roadmap — Fase 6

### Ferramentas empresariais

Poderão ser adicionadas:

- estatísticas;
- relatórios;
- gestão avançada;
- múltiplos utilizadores;
- permissões;
- ferramentas de marketing.

Objetivo:

**aumentar o valor dos planos profissionais e empresariais.**

---

## 20.21. Roadmap — Fase 7

### Marketplace

Depois da existência de uma base significativa de negócios e compradores, a plataforma poderá evoluir para um marketplace.

Poderão ser adicionados:

- pesquisa avançada;
- categorias;
- avaliações;
- vendedores;
- compradores;
- encomendas;
- pagamentos;
- mecanismos de confiança.

---

## 20.22. Roadmap — Fase 8

### Ecossistema digital

A longo prazo, o GC-AngGlobal poderá integrar diferentes serviços relacionados com comércio e negócios.

Poderão ser considerados:

- logística;
- entregas;
- publicidade;
- serviços empresariais;
- ferramentas financeiras;
- integrações externas.

Essas funcionalidades dependerão da validação do mercado.

---

## 20.23. Prioridade de desenvolvimento

O desenvolvimento deverá seguir a seguinte ordem:

1. estabilidade;
2. segurança;
3. experiência do utilizador;
4. funcionalidades comerciais;
5. assinaturas;
6. pagamentos;
7. ferramentas avançadas;
8. marketplace;
9. ecossistema.

---

## 20.24. Desenvolvimento orientado pelo utilizador

Nenhuma funcionalidade deverá ser desenvolvida apenas porque parece interessante.

A prioridade deverá considerar:

- procura dos clientes;
- impacto comercial;
- dificuldade técnica;
- custo;
- segurança;
- potencial de receita.

---

## 20.25. Testes

Cada nova funcionalidade deverá ser testada antes de ser disponibilizada.

Os testes poderão incluir:

- funcionamento;
- interface;
- segurança;
- dispositivos móveis;
- desempenho;
- integração;
- regressão.

---

## 20.26. Atualizações

O produto deverá receber atualizações contínuas.

As atualizações poderão incluir:

- novas funcionalidades;
- correções;
- melhorias de desempenho;
- melhorias de segurança;
- melhorias de interface.

---

## 20.27. Monitorização

Com o crescimento da plataforma, deverão ser implementados mecanismos para acompanhar:

- disponibilidade;
- erros;
- desempenho;
- utilização;
- capacidade;
- falhas.

A monitorização permitirá identificar problemas antes que tenham impacto significativo nos clientes.

---

## 20.28. Propriedade tecnológica

O código e os componentes desenvolvidos especificamente para o GC-AngGlobal deverão ser organizados e documentados como ativos tecnológicos da empresa.

A propriedade intelectual deverá ser protegida de acordo com a legislação aplicável.

---

## 20.29. Documentação

A empresa deverá manter documentação sobre:

- arquitetura;
- API;
- base de dados;
- instalação;
- configuração;
- segurança;
- processos;
- funcionalidades.

A documentação facilitará a manutenção e a expansão da equipa.

---

## 20.30. Tecnologia como vantagem competitiva

A tecnologia própria permitirá à empresa adaptar o produto de acordo com as necessidades do mercado.

Isso poderá reduzir a dependência de soluções prontas e permitir maior controlo sobre:

- funcionalidades;
- experiência;
- dados;
- evolução;
- integração.

---

## 20.31. Objetivo tecnológico

O objetivo é construir uma infraestrutura tecnológica capaz de servir muitos negócios através de uma única plataforma.

O sistema deverá evoluir de um MVP funcional para uma plataforma SaaS escalável e, posteriormente, para um ecossistema digital de comércio e serviços.

---

## 20.32. Conclusão

O GC-AngGlobal já possui uma base funcional que permite validar as principais ideias do produto.

O desenvolvimento futuro será realizado por etapas, começando pela estabilidade e experiência de utilização e avançando posteriormente para assinaturas, pagamentos, ferramentas empresariais e marketplace.

A estratégia tecnológica será:

**construir → testar → validar → melhorar → escalar.**

O objetivo final será possuir uma plataforma tecnológica própria, escalável e adaptada às necessidades dos negócios angolanos.
