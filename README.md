<h1 align="center" style="font-weight: bold;">SAP S/4HANA</h1>
<h2 align="center" style="font-weight: bold;">Introduction</h2>

O **ERP SAP** é um dos sistemas de planejamento de recursos empresariais mais robustos e amplamente utilizados no mundo. Ele é projetado para integrar diferentes áreas de uma empresa, promovendo eficiência, padronização e visibilidade em processos de negócios. Vamos abordar suas principais características e responder às suas perguntas:

#### **1. Como funciona?**

O **ERP SAP** centraliza os dados e processos de uma organização em sistema único, eliminando redundâncias e promovendo a colaboração entre departamentos. Ele funciona com base em módulos que refletem diferentes funções e áreas de negócios, todas interligadas. Isso garante que informações sejam compartilhadas em tempo real, permitindo melhor tomada de decisão e eficiência operacional.

#### **2. Em quantos módulos é separado?**

O SAP é dividido em vários módulos, que podem ser classificados em **funcionais** e **técnicos**:

**Módulos Funcionais:**

Estes estão diretamente relacionados aos processos de negócios:

- **FI (Financial Accounting):** Gerencia contabilidade financeira, como balanços, demonstrações de resultados e contabilidade geral.
- **MM (Material Management):** Trata de compras, gestão de estoques e movimentação de materiais.
- **SD (Sales and Distribution):** Abrange vendas, faturamento e distribuição de produtos.
- **PP (Production Planning):** Planejamento e controle de produção.
- **QM (Quality Management):** Gerencia processos de controle de qualidade.
- **PM (Plant Maintenance):** Manutenção de equipamentos e gestão de plantas.
- **HCM (Human Capital Management):** Gerenciamento de recursos humanos, incluindo folha de pagamento e recrutamento.
- **WM (Warehouse Management):** Gerenciamento de armazéns e estoques.
- **CS (Customer Service):** Suporte e atendimento ao cliente.

**Módulos Técnicos:**

Estes dão suporte à infraestrutura e personalização do sistema:

- **ABAP (Advanced Business Application Programming):** Linguagem de programação usada para personalizações no SAP.
- **BASIS:** Administração técnica do sistema, como gestão de usuários e servidores.
- **PI/PO (Process Integration/Process Orchestration):** Integração de sistemas internos e externos.
- **Fiori/UI5:** Interface de usuário para aplicações modernas baseadas na web.

#### **3. Conceito e finalidade de cada módulo**

Os módulos SAP são construídos para refletir as áreas funcionais de uma organização, permitindo que cada departamento trabalhe de forma integrada. Por exemplo:

- O **FI** interage com o **MM** para registrar entradas de mercadorias e ajustar o livro contábil.
- O **SD** está integrado ao **FI**, garantindo que vendas gerem registros financeiros automaticamente.
- O **PP** utiliza dados do **MM** para gerenciar materiais necessários na produção.

Essa integração cria um ambiente em que diferentes funções compartilham dados sem a necessidade de sistemas paralelos ou redundância.

#### **4. Características do ERP SAP**

- **Modularidade:** A empresa pode implementar os módulos conforme suas necessidades.
- **Integração:** Dados são compartilhados entre módulos em tempo real.
- **Escalabilidade:** Adequado para empresas de todos os tamanhos.
- **Flexibilidade:** Oferece diversas opções de personalização e parametrização.
- **Conformidade:** Apoia a conformidade regulatória com diferentes legislações e normas contábeis.
- **Localização Global:** Pode ser configurado para atender legislações específicas de diferentes países.

#### **5. Linguagem e arquitetura de software** 

- **Linguagem:** O SAP foi originalmente desenvolvido em ABAP, uma linguagem de programação proprietária da SAP, mas também suporta **Java** para algumas soluções específicas.

- **Arquitetura:**
	- Tradicionalmente baseado em uma arquitetura cliente-servidor, evoluiu para o **modelo em nuvem** como o SAP S/4HANA.
	- O **SAP S/4HANA** utiliza a plataforma **HANA**, que é um banco de dados em memória, proporcionando maior desempenho em análises e processamento.

#### **6. Principais benefícios do SAP**

- **Padronização:** Reduz variações nos processos empresariais.
- **Automação:** Automatiza tarefas repetitivas e melhora a eficiência.
- **Visibilidade:** Fornece insights em tempo real por meio de relatórios e análises.
- **Redução de custos:** Minimiza erros manuais e aumenta a produtividade.
- **Competitividade:** Ajuda as empresas a se adaptarem rapidamente às mudanças do mercado.

<hr>

<h3 align="center" style="font-weight: bold;">Detalhamento dos módulos e aspectos</h3>

#### **1. FI (Financial Accounting)**

O módulo **FI** é a espinha dorsal das operações financeiras no SAP. Ele conecta todas as transações financeiras e assegura conformidade com padrões contábeis locais e internacionais.

- **Submódulos**
	- **Contabilidade Geral (GL):**  Mantém registros de contas principais.
	- **Contas a Pagar (AP):** Gerencia pagamentos a fornecedores.
	- **Contas a Receber (AR):** Gerencia pagamentos a clientes.
	- **Contabilidade de Ativos Fixos:** Rastreia e deprecia ativos.
	- **Gestão de Balanço:** Criação de balanços e demonstrações financeiras.

**Finalidade:** Fornecer relatórios financeiros precisos e cumprir requisitos legais.

<hr>

#### **2. CO (Controlling)**

O **CO** é focado em controladoria e análise interna, garantindo que os custos sejam atribuídos corretamente e otimizados.

- **Submódulos**
	- **Centros de Custo:** Distribui custo entre unidades negócios.
	- **Contabilidade de Ordem Interna:** Registra custos de projetos ou atividades.
	- **Análise de Rentabilidade (CO-PA):** Mede a lucratividade por produto, cliente ou região.
	- **Gestão de Lucros:** Realiza planejamentos financeiros detalhados.

**Finalidade:** Ajudar no planejamento financeiro e controle de custos.

<hr>

#### **3. MM (Materials Management)**

O módulo **MM** gerencia o clico de suprimentos, desde a aquisição até o consumo.

- **Submódulos**
	- **Compras:** Integra as solicitações, ordens de compra e contratos.
	- **Gestão de Estoque:** Rastreia movimentações de materiais.
	- **Avaliação de Estoque:** Determina o valor de estoque com base em custos.
	- **Verificação de Faturas:** Confirma pagamentos baseados em ordens de compra.

**Finalidade:** Otimizar o gerenciamento de materiais e reduzir custos operacionais.

<hr>

#### **4. SD (Sales and Distribution)**

O **SD** é responsável pelo ciclo de vendas, desde a criação de pedidos até o faturamento.

- **Submódulos**
	- **Gestão de Pedidos:** Gerencia pedidos de clientes.
	- **Expedição:** Organiza a entrega de mercadorias.
	- **Faturamento:** Processa documentos fiscais.
	- **Gestão de Crédito:** Avalia riscos de inadimplência.

**Finalidade:** Maximizar a eficiência no atendimento ao cliente e nas vendas.

<hr>

#### **5. PP (Production Planning)**

O módulo **PP** foca no planejamento e execução da produção.

- **Submódulos**
	- **Planejamento de Necessidades de Material (MRP):** Garante que materiais estejam disponíveis para produção.
	- **Gestão de Capacidade:** Alinha recursos de produção com demandas.
	- **Controle de Produção:** Monitora e otimiza processos produtivos.

**Finalidade:** Melhorar a produtividade e reduzir desperdícios.

<hr>

#### **6. QM (Quality Management)**

O módulo **QM** assegura que produtos e processos estejam em conformidade com padrões de qualidade.

- **Submódulos**
	- **Controle de Qualidade:** Monitora a qualidade durante a produção.
	- **Planejamento de Qualidade:** Define parâmetros e inspeções.
	- **Gestão de Reclamações:** Lida com não conformidades e devoluções.

**Finalidade:** Minimizar erros e maximizar a satisfação dos clientes.

<hr>

#### **7. HCM (Human Capital Management)**

O **HCM** gerencia processos de RH, desde a contratação até o desenvolvimento de carreira.

- **Submódulos**
	-  **Administração de Pessoal:** Cadastro de Empregados.
	- **Folha de Pagamento:** Processamento de salários.
	- **Gestão de Benefícios:** Gerencia benefícios corporativos.
	- **Recrutamento e Treinamento:** Atrai e desenvolve talentos.

**Finalidade:** Automatizar processos de RH e melhorar a gestão de pessoas.

<hr>

#### **8. WM (Warehouse Management)**

O **WM** otimiza o gerenciamento de armazéns e estoques.

- **Submódulos**
	- **Gestão de Localização:** Organiza materiais em armazéns.
	- **Movimentação de Estoque:** Rastreia entrada e saída de itens.
	- **Relatórios de Inventário:** Proporciona controle detalhado de estoques.

**Finalidade:** Reduzir custos operacionais em armazéns.

<hr>

#### **9. PM (Plant Maintenance)**

O módulo **PM** gerencia a manutenção de equipamentos e plantas industriais.

- **Submódulos**
	- **Manutenção Preventiva:** Planeja inspeções regulares.
	- **Manutenção Corretiva:** Responde a falhas e reparos.
	- **Gestão de Documentos:** Rastreia manuais e históricos de manutenção.

**Finalidade:** Maximizar o tempo de atividade dos equipamentos.

<hr>

<h3 align="center" style="font-weight: bold;">Integração</h3>

A **integração** é um dos pilares mais importantes do ERP SAP, permitindo que diferentes módulos compartilhem dados em tempo real e eliminem silos de informação dentro de uma organjização. Isso resulta em processos fluídos e consistentes, maior eficiência operacional e suporte para tomadas de decisão baseadas em dados.

#### **1. O que é integração no SAP?**

A integração no SAP conecta os diferentes módulos funcionais e técnicos, criando um sistema unificado onde todas as áreas de uma empresa se comunicam. Em vez de operar como sistemas isolados, os módulos trocam informações automaticamente, garantindo que mudanças em um módulo reflitam nos outros.

Por exemplo:

- Um pedido de venda criado no módulo **SD** (Sales and Distribution) gera automaticamente uma ordem de entrega no **MM** (Materials Management) e uma entrada financeira no **FI** (Financial Accounting).

- Um planejamento de produção no **PP** (Production Planning) atualiza automaticamente os níveis de estoque no **MM**, acionando processos de reabastecimento.

<hr>

#### **2. Benefícios da integração no SAP**

- **Eliminação de Redundâncias:** Não é necessário registrar dados em vários sistemas, reduzindo erros manuais.
-  **Visão Unificada:** Fornece um panorama em tempo real das operações empresariais.
-  **Processos Otimizados:** Automação de tarefas interdepartamentais, como pedidos, pagamentos e produção.
-  **Compliance e Auditoria:** Garante que todas as áreas estejam alinhadas aos requisistos regulatórios.
-  **Decisões Estratégicas:** Dados atualizados em tempo real permitem análises precisas.

<hr>

#### **3. Exemplos práticos de integração**


**1. SD com FI e MM**

1.1. **Pedido de Venda (SD):**
	Um cliente faz um pedido.<br>
1.2. **Conexão com Estoque (MM):**
	O sistema verifica a disponibilidade dos itens no estoque.<br>
1.3. **Impacto Financeiro (FI):**
	Assim que o pedido é faturado, o sistema registra automaticamente a receita na contabilidade.<br>

**2. PP com MM e CO**

2.1. **Planejamento de Produção (PP):**
	A produção é programada para atender a demandas futuras.<br>
2.2 **Materiais Requisitados (MM):**
	O MRP calcula os materiais necessários e emite solicitações de compra.<br>
2.3. **Custos Calculados (CO):**
	O custo da produção é alocado aos centros de custo apropriados.<br>

**3. HCM com FI**

3.1. **Folha de Pagamento (HCM):**
	Processa salários dos funcionários.<br>
3.2. **Impacto Contábil (FI):**
	Os valores são lançados automaticamente na contabilidade, com segregação por centro de custo.<br>

<hr>

#### **4. Mecanismos de integração no SAP**

**1. Camada Interna**

No núcleo do SAP, a integração é feita de forma nativa. Todos os módulos compartilham o mesmo banco de dados centralizado, garantindo que dados sejam consistentes e acessíveis.

**2. SAP PI/PO (Process Integration/Process Orchestration)**

Esses componentes são usados para integrar o SAP com sistemas externos ou para conectar módulos dentro de arquiteturas complexas. Eles utilizam tecnologias como:

- **IDocs:** Mensagens padronizadas para troca de dados entre sistemas SAP.
- **APIs OData:** Interface para conectar o SAP a outras aplicações, como portais web ou aplicativos móveis.

**3. Fiori e UI5**

Essas interfaces modernas permitem que diferentes áreas usem o SAP em um ambiente unificado, melhorando a usabilidade e garantindo que dados de diversos módulos sejam apresentados de forma integrada.

<hr>

#### **5. Casos de uso interessantes**

- **Indústria Automotiva:**

  O SAP conecta a gestão de estoques, controle de produção e gestão de vendas em tempo real. Quando uma peça é solicitada, a produção é automaticamente ajustada para manter o fluxo contínuo.

- **Varejo:**

  No varejo, a integração entre o SD, MM e FI permite a reposição automática de mercadorias e a emissão de relatórios financeiros instantâneos após vendas.

<hr>

#### **6. Integração no SAP S/4HANA**

O **SAP S/4GANA** eleva a integração para outro nível com o banco de dados em memória **HANA**. Benefícios incluem:

- Processamento em tempo real, eliminando atrasos em atualizações entre módulos.
- Redução de redundâncias com tabelas otimizadas.
- Melhor suporte para integrações externas através de APIs modernas.

<hr>

<h3 align="center" style="font-weight: bold;">Customizações no SAP ERP</h3>

A customização no SAP permite que as empresas adaptem o sistema às suas necessidades específicas, sem comprometer a estrutura padrão. Embora o SAP já forneça funcionalidades robustas, as organizazções frequentemente precisam ajustar fluxo, relatórios ou integrações para refletir processos únicos. 

<br>

#### **1. O que são customizações no SAP?**

Customizações são alterações feitas no sistema para atender a requisitos específicos de negócios. Elas podem variar de configurações simples (parametrizações) a desenvolvimentos técnicos avançados que envolvem a criação de novos relatórios, transações, integrações ou até mesmo módulos inteiros.

Existem dois tipos principais de customizações:

- **Configuração/Parametrização:** Ajustes dentro das opções padrão do SAP.
- **Desenvolvimento Técnico:** Uso de ferramentas como ABAP, Fiori/UI5 ou integrações com APIs para criar soluções personalizadas.

<hr>

#### **2. Por que customizar o SAP?**

2.1. **Processos únicos:** Empresas de diferentes setores possuem operações específicas que não são comtempladas no modelo padrão do SAP.
2.2. **Melhoria de experiência:** Adaptação da interface ou funcionalidades para facilitar o uso pelos colaboradores.
2.3. **Integração com sistemas legados:** Necessidade de integrar o SAP com ferramentas internas ou externas.
2.4. **Automação:** Otimizar tarefas repetitivas ou complexasa.

<hr>

#### **3. Exemplos de customizações**

**3.1. Relatórios Personalizados**

- No módulo **FI**, pode-se criar relatórios específicos para atender a legislações locais ou padrões de auditoria.
- Com **ABAP**, é possível desenvolver relatórios que combinam dados de vários módulos, como estoque (MM) e vendas (SD).

**3.2. Criação de Transações Personalizadas**

- Empresas podem criar transações exclusivas para tarefas repetitivas. Por exemplo, uma transação personalizada que automatiza a criação de ordens de produção no **PP** com base em dados externos.

**3.3. Integrações**

- Conectar o SAP a plataformas como CRM ou sistemas de logísticas, usando **SAP PI/PO, APIs RESTful**, ou **IDocs**.

**3.4. Extensões da Interface**

- Usando o **Fiori/UI5**, é possível criar aplicativos móveis ou intefaces web intuitivas que atendam necessidades específicas, como relatórios em tempo real oi acesso remoto a pedidos de compra.

<hr>

#### **4. Ferramentas e métodos de customização**

**4.1. ABAP (Advanced Business Application Programming)**

O **ABAP** é a principal linguagem de programação do SAP, usada para criar:

- Relatórios personalizados.
- Novas tabelas ou estruturas de dados.
- Programas para automação de processos.
- Extensões em módulos padrão.

**Exemplo:** Um cliente deseja que a fatura gerada no SD inclua campos personalizados, como o número do pedido interno do cliente. Isso pode ser feito criando uma ampliação no programa padrão via **Enhancement Points**.

**4.2. Fiori/UI5**

- Ferramenta moderna para criar interfaces web e móveis amigáveis.
- Ideal para empresas que precisam de interfaces simplificadas para usuários específicos, como técnicos de campo ou equipes de vendas.

**Exemplo:** Desenvolver um aplicativo para dispositivos móveis que permita consultar estoques em tempo real.

**4.3. SAP Screen Personas**

- Permite simplificar e personalizar telas padrão do SAP GUI.
- Ideal para eliminar campos irrelevantes ou agrupar informações importantes em uma única visão.

**Exemplo:** Remover campos não utilizados da transação de criação de pedidos no módulo SD.

**4.4. SAP BTP (Business Technology Platform)**

- Ferramenta para desenvolver extensões sem alterar o sistema principal.
- Ideal para empresas que desejam customizar processos enquanto mantêm a integridade do núcleo do SAP.

**Exemplo:** Criar um fluxo automatizado de aprovações conectado ao SAP através do SAP BTP.

![img.png](img.png)

ERP significa planejamento de recursos empresariais. Os sistemas ERP são o tipo de ferramenta de software usada para gerenciar os dados de uma empresa.

![img_1.png](img_1.png)

![img_2.png](img_2.png)

### Tradução:

Costumer = Cliente; <br>
Sales = Vendas; <br>
Inventory = Inventário; <br>
Production Planning = Planejamento de Produção; <br>
Purchasing = Comprando/Aquisição.

![img_3.png](img_3.png)

### Tradução:

Finance = Finanças; <br>
Purchasing = Comprando/Aquisição; <br>
Manufacturing = Fabricação; <br>
MRP (Material Requirements Planning) = Planejamento de Necessidades de Materiais; <br>
Inventory Management = Gestão de Estoque; <br>
CRM (Costumer Relationship Management) & Sales = Gestão de Relacionamento com o Cliente & Vendas; <br>
E-Commerce = Comércio Eletrônico; <br>
Service = Serviço; <br>
Job Costing = Custo do Trabalho; <br>
Project Management = Gerenciamento de Projetos; <br>
Human Resources = Recursos Humanos; <br>
Analytics & Reporting = Análises & Relatórios;

![img_4.png](img_4.png)

O **SAP S/4HANA** pode ser configurado tanto em um modelo **centralizado** quanto **descentralizado**, dependendo da necessidade da empresa.

### 🔹 SAP em um modelo Centralizado
No modelo tradicional, o SAP funciona de forma centralizada, integrando todos os módulos (Financeiro, Logística, Vendas, Produção, etc.) em um único sistema e banco de dados. Esse modelo garante: <br>
✔ **Dados unificados**: todas as áreas acessam a mesma base de dados em tempo real. <br>
✔ **Menos redundância**: elimina a necessidade de múltiplos sistemas. <br>
✔ **Maior controle**: gestão centralizada da informação. <br>

### 🔹 SAP em um modelo Descentralizado
Apesar de ser tradicionalmente centralizado, algumas empresas podem optar por um **modelo descentralizado**, onde diferentes unidades ou subsidiárias utilizam sistemas SAP independentes que podem ou não se comunicar entre si. Isso ocorre quando: <br>
✔ Há **unidades operando de forma independente**. <br>
✔ é necessário atender **diferentes legislações locais**. <br>
✔ A empresa usa um **modelo híbrido**, onde algumas funções são locais e outras centralizadas. <br>

### 🏆 Conclusão
* Se o SAP está rodando **em uma única instância**, com todos os módulos integrados, ele é centralizado. <br>
* Se a empresa utiliza **múltiplas instâncias do SAP (ou sistemas separados por unidade de negócio)**, então ele é **descentralizado**. <br>

Na prática, **grandes empresas costumam ter uma abordagem híbrida**, onde algumas funções são centralizadas (como finanças), enquanto outras (como produção) podem ser descentralizadas para melhor eficiência operacional.










