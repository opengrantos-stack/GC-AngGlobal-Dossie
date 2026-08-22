# 04 — Produto e Funcionalidades

## 4.1. Descrição do produto

O GC-AngGlobal é uma plataforma digital de comércio e encomendas desenvolvida para permitir que vendedores apresentem produtos e serviços e que compradores encontrem ofertas e realizem pedidos através de uma interface simples.

A primeira versão do produto está orientada para a utilização através de dispositivos móveis e para as necessidades do comércio local.

O sistema está a ser desenvolvido de forma incremental, permitindo validar funcionalidades antes da expansão para uma infraestrutura comercial de maior escala.

---

## 4.2. Funcionalidades atualmente implementadas

A versão atual do produto já possui funcionalidades essenciais para a operação inicial.

### Publicação de produtos e serviços

O administrador pode publicar produtos ou serviços através de um formulário próprio.

Cada publicação pode conter:

- tipo;
- nome;
- descrição;
- preço;
- imagem.

Isso permite criar um catálogo digital organizado.

---

### Edição de produtos e serviços

Os produtos e serviços publicados podem ser editados pelo administrador.

A funcionalidade permite atualizar informações sem necessidade de eliminar e publicar novamente o item.

Podem ser alterados dados como:

- tipo;
- nome;
- descrição;
- preço;
- imagem.

Essa funcionalidade é importante para manter o catálogo atualizado.

---

### Eliminação de produtos e serviços

O administrador pode eliminar uma publicação.

Antes da eliminação, o sistema apresenta uma confirmação para reduzir o risco de remoção acidental.

Após a confirmação, o item é removido através da operação administrativa correspondente.

---

### Autenticação administrativa

As operações administrativas são protegidas por autenticação.

As funcionalidades de gestão são disponibilizadas apenas quando o utilizador está autenticado como administrador.

Entre as operações protegidas encontram-se:

- publicação;
- edição;
- eliminação.

A autenticação será posteriormente evoluída para um sistema de contas e permissões adequado ao modelo multiutilizador.

---

### Catálogo de produtos e serviços

Os produtos e serviços publicados são apresentados numa interface de catálogo.

Cada item apresenta informações essenciais para o comprador, incluindo:

- imagem;
- nome;
- descrição;
- preço;
- ação de compra ou solicitação de serviço.

---

### Carrinho e pedidos

A plataforma possui mecanismos para adicionar produtos ao pedido.

Para serviços, a interface utiliza uma ação específica de solicitação.

Essa estrutura permite que o sistema evolua posteriormente para um processo mais completo de encomendas.

---

## 4.3. Gestão de imagens

A plataforma permite associar imagens aos produtos e serviços.

A interface de publicação foi estruturada para disponibilizar duas formas de obter uma imagem:

### Escolher foto

O utilizador pode selecionar uma imagem existente no dispositivo, através da galeria ou do seletor de ficheiros do sistema.

### Tirar foto

O utilizador pode utilizar a câmara do dispositivo para tirar uma nova fotografia e associá-la à publicação.

Essa funcionalidade é especialmente importante para vendedores que utilizam o telemóvel como principal ferramenta de trabalho.

---

## 4.4. Processamento de imagens

Para reduzir o tamanho das imagens e facilitar o armazenamento e carregamento, a aplicação realiza processamento da imagem antes da publicação.

As imagens podem ser redimensionadas para uma dimensão máxima definida pela aplicação.

Essa abordagem procura equilibrar:

- qualidade visual;
- tamanho do ficheiro;
- velocidade de carregamento;
- consumo de armazenamento;
- experiência do utilizador.

---

## 4.5. Interface orientada para dispositivos móveis

A experiência do produto está a ser desenvolvida com foco em smartphones.

Isso permite que um comerciante possa utilizar a plataforma diretamente a partir do seu telemóvel para:

- publicar produtos;
- adicionar imagens;
- atualizar informações;
- eliminar publicações;
- consultar a oferta;
- receber pedidos.

A orientação mobile-first será mantida durante a evolução do produto.

---

## 4.6. Arquitetura inicial

O sistema utiliza uma arquitetura web composta por uma interface pública e um servidor responsável pelas operações da aplicação.

A aplicação utiliza uma API para comunicação entre a interface e o servidor.

Entre as operações principais encontram-se:

- criação de produtos;
- consulta de produtos;
- atualização de produtos;
- eliminação de produtos.

A arquitetura foi concebida para permitir a evolução posterior para uma solução multiutilizador.

---

## 4.7. Modelo atual e evolução para multiutilizador

A versão atual utiliza uma estrutura administrativa inicial para validar o funcionamento do produto.

No modelo comercial definitivo, essa estrutura será substituída ou ampliada para suportar múltiplos vendedores.

Cada vendedor deverá possuir uma conta própria e acesso às suas funcionalidades comerciais.

A evolução deverá permitir:

- registo de vendedores;
- autenticação individual;
- perfil comercial;
- gestão dos próprios produtos;
- gestão dos próprios serviços;
- consulta de pedidos;
- histórico;
- planos de assinatura.

---

## 4.8. Funcionalidades planejadas

A evolução do GC-AngGlobal deverá incluir novas funcionalidades de acordo com as necessidades do mercado.

### Para vendedores

- conta comercial;
- perfil da loja;
- catálogo próprio;
- gestão de produtos;
- gestão de serviços;
- gestão de encomendas;
- histórico de pedidos;
- estatísticas;
- notificações;
- promoção de produtos;
- diferentes planos de assinatura.

### Para compradores

- conta de comprador;
- pesquisa;
- categorias;
- filtros;
- carrinho;
- histórico de encomendas;
- favoritos;
- avaliações;
- comentários;
- notificações.

---

## 4.9. Sistema de comentários e avaliações

Uma das evoluções previstas é permitir que compradores possam comentar e avaliar produtos ou serviços.

Essa funcionalidade poderá aumentar a confiança entre compradores e vendedores e gerar informação útil sobre a qualidade das ofertas.

O sistema deverá ser desenvolvido com mecanismos de moderação e regras de utilização adequadas.

---

## 4.10. Gestão de encomendas

A gestão de encomendas constitui uma das principais etapas de evolução.

O sistema poderá permitir acompanhar diferentes estados de um pedido, por exemplo:

- pedido recebido;
- pedido confirmado;
- em preparação;
- pronto;
- entregue;
- concluído;
- cancelado.

Essa estrutura permitirá transformar o catálogo atual numa solução de comércio digital mais completa.

---

## 4.11. Notificações

A plataforma poderá futuramente disponibilizar notificações para informar os utilizadores sobre acontecimentos relevantes.

Exemplos:

- nova encomenda;
- alteração do estado do pedido;
- confirmação;
- mensagem;
- comentário;
- atualização de conta.

As tecnologias utilizadas serão escolhidas de acordo com a evolução da arquitetura e das necessidades do produto.

---

## 4.12. Planos de assinatura

O modelo SaaS permitirá criar diferentes níveis de utilização.

Um modelo futuro poderá incluir:

### Plano básico

Destinado a pequenos vendedores que necessitam apenas das funcionalidades essenciais.

### Plano profissional

Destinado a negócios que necessitam de maior capacidade de gestão e promoção.

### Plano empresarial

Destinado a empresas com necessidades comerciais mais avançadas.

Os preços e limites de cada plano serão definidos após validação do mercado.

---

## 4.13. Administração da plataforma

A empresa promotora deverá possuir uma área administrativa central para gerir a plataforma.

Essa área poderá incluir:

- gestão de utilizadores;
- gestão de vendedores;
- gestão de compradores;
- gestão de publicações;
- gestão de assinaturas;
- estatísticas;
- denúncias;
- moderação;
- suporte;
- configurações da plataforma.

---

## 4.14. Segurança

A segurança será tratada como requisito permanente do produto.

A evolução deverá incluir:

- autenticação segura;
- proteção de contas;
- controlo de permissões;
- proteção da API;
- validação de dados;
- proteção contra acessos não autorizados;
- armazenamento seguro de informações;
- cópias de segurança;
- monitorização.

As credenciais e mecanismos de autenticação utilizados durante o desenvolvimento inicial deverão ser substituídos por mecanismos apropriados ao ambiente de produção multiutilizador.

---

## 4.15. Escalabilidade tecnológica

O produto será desenvolvido para permitir crescimento gradual.

A infraestrutura poderá evoluir conforme o número de utilizadores aumente.

A evolução poderá envolver:

- servidores com maior capacidade;
- bases de dados geridas;
- armazenamento externo de imagens;
- CDN;
- sistemas de cache;
- monitorização;
- backups automatizados;
- separação de serviços;
- otimização da API.

A arquitetura deverá acompanhar o crescimento comercial da plataforma.

---

## 4.16. Roadmap funcional

A evolução do produto poderá seguir quatro grandes etapas.

### Fase 1 — Validação

Objetivo:

- validar o catálogo;
- validar publicação;
- validar edição;
- validar eliminação;
- validar pedidos;
- recolher feedback.

### Fase 2 — Multiutilizador

Objetivo:

- criar contas;
- permitir vendedores independentes;
- criar perfis comerciais;
- separar dados por utilizador;
- criar sistema de assinatura.

### Fase 3 — Plataforma comercial

Objetivo:

- gestão avançada de encomendas;
- avaliações;
- comentários;
- notificações;
- estatísticas;
- promoção.

### Fase 4 — Escala

Objetivo:

- aumentar a capacidade da infraestrutura;
- integrar pagamentos;
- melhorar automação;
- desenvolver aplicações complementares;
- preparar expansão para outros mercados.

---

## 4.17. Princípio de desenvolvimento

O GC-AngGlobal será desenvolvido segundo um princípio de evolução progressiva.

Em vez de construir inicialmente uma plataforma excessivamente complexa, a empresa pretende:

1. construir;
2. testar;
3. disponibilizar;
4. recolher feedback;
5. corrigir;
6. medir utilização;
7. melhorar;
8. escalar.

Esse processo reduz o risco de investir grandes recursos em funcionalidades que ainda não foram validadas pelo mercado.

---

## 4.18. Conclusão

O GC-AngGlobal já possui uma base funcional capaz de demonstrar o conceito do produto.

As funcionalidades atuais permitem validar a publicação, apresentação e gestão básica de produtos e serviços.

A próxima grande etapa tecnológica consiste em transformar essa estrutura inicial numa plataforma verdadeiramente multiutilizador, na qual diferentes vendedores possam possuir as suas próprias contas, gerir os seus catálogos e pagar uma mensalidade pela utilização do serviço.

Essa evolução constitui a ponte entre o protótipo funcional atual e o modelo SaaS comercial pretendido pela Geração Calueio – COMÉRCIO E SERVIÇOS, LDA.
