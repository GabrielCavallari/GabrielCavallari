# Gabriel Cavallari

**Desenvolvimento · Dados e BI · Automação**

Sou Analista de Informática e estudante de Análise e Desenvolvimento de Sistemas no IFSP. Gosto de transformar problemas do dia a dia em sistemas, análises e automações que tornam a informação mais organizada e os processos mais claros.

Este perfil reúne projetos profissionais, estudos e experimentos pessoais — o que construí, as decisões por trás de cada solução e o que sigo aprendendo.

## Trabalhos selecionados

| Projeto | O que explora | Apresentação |
| --- | --- | --- |
| Apontamento de Produção | Registro operacional, planejamento e rastreabilidade | [Conhecer o projeto](#apontamento-de-produção) |
| Marklt BI | Python, SQL e Power BI em um estudo de marketplace | [Conhecer o projeto](#marklt-bi) |
| Bot de Relatórios | Tratamento de imagens e arquivamento com confirmação | [Conhecer o projeto](#bot-de-relatórios) |
| Base Exata | Microaplicações com dados demonstrativos | [Conhecer o projeto](#base-exata) |
| Contrato Risk AI | Documentos, RAG e revisão humana | [Conhecer o projeto](#contrato-risk-ai) |
| Almoxarifado App | Requisições de conserto, prazos e documentos | [Conhecer o projeto](#almoxarifado-app) |

Os projetos corporativos são apresentados de forma resumida. Seus repositórios, dados internos e ambientes não são disponibilizados por este perfil. Estudos com dados simulados estão identificados como tais.

### Apontamento de Produção

**Sistema corporativo · código privado**

Sistema web para conectar o apontamento da operação ao acompanhamento da produção. Reúne registro em tablet, visões para PCP e liderança e histórico dos eventos.

- **Problema:** informações dispersas dificultam acompanhar ordens, etapas e paradas.
- **Solução:** registro das atividades e acompanhamento por setor em um fluxo integrado.
- **Decisões:** confirmação pelo servidor, acesso por perfil e preservação do histórico.
- **Tecnologias:** React, Node.js, Express, PostgreSQL e Prisma.

O fluxo de produção e os módulos de revisão/retrabalho têm escopos e liberações próprios. Código implementado não significa módulo ativado na operação.

### Marklt BI

**Estudo de caso · dados simulados**

Pipeline de BI para explorar buscas, compras e tempo de venda em um marketplace.

- **Preparação:** dados fictícios gerados com Python, Pandas e Faker.
- **Transformação:** views SQL no BigQuery para organizar as análises.
- **Apresentação:** dashboard no Power BI com composição visual no Figma.
- **Aprendizado:** indicadores precisam de contexto; conclusões sobre dados simulados não comprovam comportamento de clientes reais.

[Código e materiais públicos do estudo](https://github.com/GabrielCavallari/Marklt-BI-Analytics)

### Bot de Relatórios

**Automação corporativa · código privado**

Fluxo pelo Telegram para receber imagens de documentos, melhorar sua legibilidade e organizar o arquivamento.

- **Fluxo:** recebimento → tratamento → confirmação → PDF e arquivamento.
- **Recursos:** correção de perspectiva e contraste, preservação do original e organização por protocolo.
- **Confiabilidade:** fila recuperável e auditoria para lidar com falhas de armazenamento.
- **Tecnologias:** Python, OpenCV e SQLite.

O processamento documentado não utiliza OCR ou IA generativa.

### Base Exata

**Projeto pessoal · dados simulados**

Laboratório de microaplicações para explorar cenários de vendas, estoque, produção e relatórios.

- **Proposta:** tornar uma ideia compreensível por meio de uma aplicação demonstrável.
- **Estrutura:** demos independentes, com bases de exemplo e documentação de execução.
- **Tecnologias:** Python, Flask e SQLite.

Neste perfil, a Base Exata aparece como parte do meu trabalho técnico e dos meus experimentos.

[Código e demonstrações locais](https://github.com/GabrielCavallari/Base-Exata)

### Contrato Risk AI

**Aplicação privada · análise assistida**

Aplicação para organizar casos e documentos, consultar análises com IA e recuperar trechos de referência.

- **Recursos:** processamento de documentos, consulta com RAG, matriz de riscos e registro de revisão humana.
- **Decisões:** manter referências ao documento de origem e separar a integração de IA das regras da aplicação.
- **Tecnologias:** Next.js, FastAPI, PostgreSQL e Qdrant.

A análise é assistiva e pode conter erros. A avaliação e a decisão final permanecem humanas.

### Almoxarifado App

**Sistema corporativo · código privado**

Aplicação desktop para organizar requisições de conserto e acompanhar seu ciclo de vida.

- **Recursos:** controle de status e prazos, fornecedores, geração de PDF e notificações.
- **Foco:** substituir controles dispersos por registros consultáveis e acompanhamento mais claro.
- **Tecnologias:** Python, CustomTkinter, SQLite, SQLAlchemy e fpdf2.

## Em desenvolvimento

- **Base Exata Insights:** importação de planilhas e indicadores de vendas, com separação de dados por organização.
- **Painel de Revisão:** organização de filas e acompanhamento visual de uma operação industrial.

## Tecnologias presentes nos projetos

| Área | Ferramentas |
| --- | --- |
| Sistemas web | React, Next.js, Node.js, Express, FastAPI |
| Dados e BI | SQL, Power BI, Power Query, Python, Pandas, BigQuery |
| Persistência | PostgreSQL, SQLite, Prisma, SQLAlchemy |
| Automação e documentos | Python, OpenCV, geração de PDF, integrações |
| IA aplicada | RAG, Qdrant, integração com modelos, revisão humana |

Além dos projetos acima, mantenho exercícios e estudos neste GitHub como registro da minha evolução.
