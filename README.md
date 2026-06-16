# 🚀 DIO | Relatório de Implementação de Serviços AWS para Engenharia de Dados

![Arquitetura AWS Mold Industries](https://github.com/leandrorosa-n/dio-lab-cenarios-aws-cloud/blob/main/Mold-Industries.png)

## 📋 Sobre o Projeto

Este projeto foi desenvolvido como parte do desafio da Digital Innovation One (DIO), com o objetivo de propor uma arquitetura baseada em serviços AWS capaz de reduzir custos operacionais, aumentar a escalabilidade, fortalecer a segurança dos dados e garantir conformidade regulatória para uma empresa fictícia do setor farmacêutico.

**Empresa:** Mold Industries Ltda (Fictícia)  
**Responsável:** Leandro Rosa  
**Data:** 09/04/2026

---

## 🎯 Objetivo

O objetivo deste projeto é demonstrar como a adoção de serviços gerenciados da AWS pode contribuir para a modernização da infraestrutura tecnológica da empresa, proporcionando:

- Redução de custos operacionais;
- Escalabilidade sob demanda;
- Alta disponibilidade dos sistemas;
- Maior segurança da informação;
- Governança de dados;
- Conformidade regulatória;
- Apoio à tomada de decisões baseada em dados.

---

## 🏗️ Arquitetura da Solução

A arquitetura proposta foi dividida em três etapas estratégicas:

### Etapa 1 — Armazenamento e Banco de Dados

**Serviços AWS Utilizados**

- Amazon RDS
- Amazon S3

#### Objetivo

Modernizar o armazenamento de dados corporativos e documentos críticos.

#### Caso de Uso

O Amazon RDS é utilizado para hospedar bancos de dados críticos da organização, incluindo sistemas ERP, CRM e dados de pesquisas clínicas, garantindo alta disponibilidade, replicação automática e backups gerenciados.

O Amazon S3 é utilizado para armazenar documentos regulatórios, relatórios médicos e arquivos multimídia com criptografia, versionamento e alta durabilidade.

#### Benefícios

- Alta disponibilidade
- Escalabilidade automática
- Redução de custos com infraestrutura física
- Backups automatizados
- Armazenamento seguro e confiável

---

### Etapa 2 — Integração e Analytics

**Serviços AWS Utilizados**

- AWS Glue
- Amazon Redshift

#### Objetivo

Centralizar e transformar dados para geração de informações estratégicas.

#### Caso de Uso

O AWS Glue é responsável pela automação dos processos de ETL (Extração, Transformação e Carga), integrando dados provenientes de diferentes sistemas corporativos.

O Amazon Redshift atua como Data Warehouse corporativo, permitindo análises avançadas, dashboards executivos e relatórios financeiros de alta performance.

#### Benefícios

- Automação de pipelines de dados
- Centralização das informações corporativas
- Redução de redundâncias
- Consultas analíticas de alta performance
- Melhoria na tomada de decisão

---

### Etapa 3 — Inteligência Artificial e Governança

**Serviços AWS Utilizados**

- Amazon SageMaker
- AWS Lake Formation

#### Objetivo

Implementar governança de dados e inteligência artificial para otimização dos processos corporativos.

#### Caso de Uso

O Amazon SageMaker é utilizado para desenvolvimento e treinamento de modelos de Machine Learning voltados para:

- Previsão de demanda;
- Otimização da cadeia de suprimentos;
- Análise de eficácia de medicamentos.

O AWS Lake Formation é responsável pela criação de um Data Lake seguro e governado, oferecendo controle granular de acesso e suporte às exigências regulatórias.

#### Benefícios

- Governança centralizada dos dados
- Segurança reforçada
- Conformidade com LGPD
- Conformidade com FDA
- Aplicação de inteligência artificial em escala

---

## ☁️ Serviços AWS Utilizados

| Serviço | Finalidade |
|----------|------------|
| Amazon RDS | Banco de dados relacional gerenciado |
| Amazon S3 | Armazenamento seguro de objetos |
| AWS Glue | ETL e integração de dados |
| Amazon Redshift | Data Warehouse corporativo |
| AWS Lake Formation | Governança e Data Lake |
| Amazon SageMaker | Machine Learning |

---

## 📈 Resultados Esperados

Com a implementação da arquitetura proposta, espera-se alcançar:

- Redução imediata dos custos operacionais;
- Aumento da eficiência dos processos internos;
- Escalabilidade para crescimento do negócio;
- Maior disponibilidade dos sistemas críticos;
- Melhoria na qualidade das análises corporativas;
- Segurança e governança dos dados;
- Conformidade regulatória;
- Maior competitividade no setor farmacêutico.

---

## 🔒 Segurança e Conformidade

A arquitetura foi planejada seguindo boas práticas da AWS para segurança e governança:

- Criptografia de dados em repouso e em trânsito;
- Controle de acesso baseado em permissões;
- Gestão centralizada de dados;
- Conformidade com LGPD;
- Conformidade com regulamentações do setor farmacêutico.

---

## 📚 Referências

- https://aws.amazon.com/
- https://docs.aws.amazon.com/
- https://www.dio.me/

---

## 👨‍💻 Autor

**Leandro Rosa**

Projeto desenvolvido como parte dos estudos em Computação em Nuvem e Engenharia de Dados na AWS através da plataforma DIO (Digital Innovation One).
