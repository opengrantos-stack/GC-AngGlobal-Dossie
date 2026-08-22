# 10 — Plano de Operações

## 10.1. Objetivo

O plano de operações define como o GC-AngGlobal será administrado diariamente, desde a aquisição de clientes até ao suporte, manutenção da plataforma e gestão das assinaturas.

A operação será inicialmente simples e de baixo custo, evoluindo à medida que a base de clientes crescer.

---

## 10.2. Estrutura operacional

A operação inicial será coordenada pela Geração Calueio – COMÉRCIO E SERVIÇOS, LDA.

As principais áreas serão:

- gestão;
- tecnologia;
- vendas;
- atendimento;
- marketing;
- administração financeira.

Durante a fase inicial, uma mesma pessoa poderá desempenhar mais de uma função.

Com o crescimento, as funções serão distribuídas por uma equipa.

---

## 10.3. Gestão do produto

A gestão do produto terá como responsabilidade:

- acompanhar o funcionamento da plataforma;
- analisar feedback;
- definir prioridades;
- acompanhar novas funcionalidades;
- corrigir problemas;
- avaliar indicadores.

As decisões deverão considerar tanto os objetivos comerciais quanto as necessidades dos utilizadores.

---

## 10.4. Entrada de novos clientes

O processo de entrada de um negócio poderá seguir as seguintes etapas:

1. contacto;
2. apresentação;
3. demonstração;
4. escolha do plano;
5. criação da conta;
6. configuração do negócio;
7. publicação inicial;
8. ativação da assinatura;
9. acompanhamento.

O objetivo será tornar o processo simples.

---

## 10.5. Configuração do negócio

Após a adesão, o negócio deverá fornecer as informações necessárias para a sua presença na plataforma.

Dependendo do plano, poderão ser solicitados:

- nome comercial;
- descrição;
- contacto;
- localização;
- imagem;
- produtos;
- serviços;
- informações comerciais.

A quantidade de informação poderá variar de acordo com o plano contratado.

---

## 10.6. Publicação de produtos

O vendedor deverá conseguir publicar produtos através de uma interface simples.

As informações principais poderão incluir:

- nome;
- descrição;
- preço;
- imagem;
- categoria;
- disponibilidade.

A plataforma deverá procurar reduzir o número de etapas necessárias para realizar uma publicação.

---

## 10.7. Gestão de serviços

Além de produtos físicos, o GC-AngGlobal poderá suportar serviços.

Um prestador poderá apresentar:

- nome do serviço;
- descrição;
- preço ou orçamento;
- imagem;
- contacto;
- disponibilidade.

Isso permite ampliar o mercado para negócios que não vendem produtos físicos.

---

## 10.8. Gestão dos pedidos

Uma evolução importante será a gestão estruturada de pedidos.

O fluxo poderá ser:

**comprador → pedido → vendedor → confirmação → execução/entrega → conclusão.**

O sistema deverá permitir acompanhar o estado do pedido.

Possíveis estados:

- novo;
- recebido;
- confirmado;
- em preparação;
- pronto;
- enviado;
- concluído;
- cancelado.

---

## 10.9. Atendimento ao cliente

O atendimento será importante para retenção.

Inicialmente poderá ser realizado através de:

- WhatsApp;
- telefone;
- email;
- canais digitais.

Com o crescimento, poderá ser criado um sistema de suporte com tickets.

---

## 10.10. Suporte aos vendedores

Os vendedores poderão necessitar de ajuda para:

- criar a conta;
- publicar produtos;
- alterar informações;
- gerir pedidos;
- compreender planos;
- resolver problemas.

A empresa deverá produzir materiais simples de orientação.

---

## 10.11. Suporte aos compradores

Os compradores poderão procurar ajuda relacionada com:

- pedidos;
- contas;
- pagamentos;
- problemas técnicos;
- comunicação com vendedores.

A empresa deverá estabelecer claramente quais problemas são responsabilidade da plataforma e quais dependem diretamente do vendedor.

---

## 10.12. Manutenção técnica

A equipa técnica será responsável por:

- corrigir erros;
- atualizar dependências;
- melhorar desempenho;
- realizar backups;
- monitorizar o servidor;
- proteger a aplicação;
- implementar novas funcionalidades.

As alterações deverão ser testadas antes de serem disponibilizadas.

---

## 10.13. Deploy e atualizações

O código deverá ser mantido num sistema de controlo de versões.

As atualizações poderão seguir:

**desenvolvimento → teste → commit → deploy → verificação.**

Esse processo reduz o risco de introduzir alterações defeituosas diretamente no ambiente de produção.

---

## 10.14. Monitorização

À medida que a plataforma crescer, deverão ser acompanhados:

- disponibilidade;
- erros;
- tempo de resposta;
- utilização;
- tráfego;
- consumo de armazenamento;
- utilização da base de dados.

A monitorização permitirá identificar problemas antes que afetem grande quantidade de utilizadores.

---

## 10.15. Segurança operacional

A operação deverá considerar:

- proteção das contas;
- controlo de acesso;
- proteção da base de dados;
- backups;
- atualização de software;
- HTTPS;
- gestão de credenciais;
- proteção dos endpoints.

A segurança será revista continuamente.

---

## 10.16. Backups

Os dados importantes deverão possuir cópias de segurança.

Os backups deverão abranger, conforme aplicável:

- base de dados;
- informações dos clientes;
- produtos;
- pedidos;
- configurações;
- documentos importantes.

A política definitiva de backup deverá definir frequência, retenção e recuperação.

---

## 10.17. Gestão de assinaturas

O modelo SaaS exige uma operação de cobrança recorrente.

A plataforma deverá evoluir para permitir:

- escolha do plano;
- ativação;
- pagamento;
- renovação;
- alteração do plano;
- cancelamento;
- suspensão por falta de pagamento.

O sistema deverá manter registo das assinaturas.

---

## 10.18. Planos comerciais

Os planos poderão ser estruturados de acordo com o tamanho e as necessidades do negócio.

Exemplo de estrutura:

### Plano Inicial

Para pequenos negócios.

### Plano Profissional

Para negócios com maior quantidade de produtos e necessidades adicionais.

### Plano Empresarial

Para empresas com necessidades superiores e funcionalidades avançadas.

Os preços definitivos serão estabelecidos depois da validação comercial.

---

## 10.19. Cobrança

A empresa deverá procurar disponibilizar métodos de pagamento adequados ao mercado angolano.

Poderão ser considerados:

- transferências bancárias;
- pagamentos digitais;
- integrações com provedores de pagamento;
- outros métodos legalmente disponíveis.

A cobrança deverá ser documentada e integrada ao sistema sempre que tecnicamente possível.

---

## 10.20. Gestão financeira

A operação deverá acompanhar:

- receita recorrente;
- despesas;
- custos de infraestrutura;
- custos de marketing;
- comissões;
- salários;
- impostos;
- lucro;
- fluxo de caixa.

A gestão financeira será fundamental para controlar o crescimento.

---

## 10.21. Recursos humanos

A equipa inicial deverá ser pequena.

As principais necessidades poderão incluir:

- gestão;
- desenvolvimento;
- suporte;
- vendas;
- marketing;
- administração.

A contratação deverá acompanhar o crescimento da receita.

---

## 10.22. Escala operacional

A operação deverá ser desenhada para crescer sem aumento proporcional dos custos.

Isso será possível através de:

- automação;
- autoatendimento;
- documentação;
- processos padronizados;
- software;
- suporte estruturado.

O objetivo do modelo SaaS é aumentar o número de clientes sem precisar aumentar a equipa na mesma proporção.

---

## 10.23. Operação local

A Geração Calueio – COMÉRCIO E SERVIÇOS, LDA poderá prestar suporte local aos clientes em Angola.

A presença local poderá facilitar:

- aquisição;
- formação;
- suporte;
- parcerias;
- compreensão do mercado.

---

## 10.24. Qualidade

A qualidade deverá ser acompanhada através de:

- erros reportados;
- reclamações;
- tempo de resposta;
- satisfação;
- cancelamentos;
- utilização;
- desempenho.

Os problemas recorrentes deverão ser transformados em prioridades de desenvolvimento.

---

## 10.25. Indicadores operacionais

A empresa deverá acompanhar:

- clientes ativos;
- clientes pagantes;
- novos clientes;
- cancelamentos;
- pedidos;
- produtos publicados;
- utilização;
- tickets de suporte;
- tempo médio de resposta;
- disponibilidade;
- erros técnicos.

Esses indicadores ajudarão a identificar gargalos.

---

## 10.26. Processo operacional resumido

O funcionamento comercial poderá ser representado como:

**Aquisição**

↓

**Adesão**

↓

**Configuração**

↓

**Publicação**

↓

**Utilização**

↓

**Pedidos**

↓

**Suporte**

↓

**Renovação**

↓

**Fidelização**

↓

**Indicação**

Esse ciclo deverá ser continuamente otimizado.

---

## 10.27. Evolução da operação

### Fase 1

Operação manual e acompanhamento próximo.

### Fase 2

Padronização de processos.

### Fase 3

Automação de pagamentos, suporte e gestão.

### Fase 4

Equipa especializada.

### Fase 5

Operação escalável para diferentes regiões.

---

## 10.28. Continuidade do negócio

A empresa deverá preparar mecanismos para manter a operação mesmo em caso de problemas técnicos.

Isso poderá incluir:

- backups;
- documentação;
- recuperação de dados;
- redundância;
- monitorização;
- procedimentos de emergência.

A continuidade será particularmente importante quando a plataforma tiver muitos clientes.

---

## 10.29. Conclusão

O modelo operacional do GC-AngGlobal será inicialmente simples, com uma equipa pequena e forte utilização de tecnologia.

À medida que a base de clientes crescer, os processos serão padronizados e automatizados.

A prioridade será garantir que o crescimento do número de clientes não provoque um crescimento desproporcional dos custos operacionais.

A operação deverá sustentar três objetivos:

**serviço estável + clientes satisfeitos + crescimento sustentável.**
