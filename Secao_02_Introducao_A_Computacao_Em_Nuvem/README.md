# Seção 02 — Introdução à Computação na Nuvem

Este documento sumariza os conteúdos da Seção 02 do curso "Computação em Nuvem — Essencial", reúne os arquivos disponíveis na pasta e propõe atividades e leituras complementares para fixação.

## Objetivos de aprendizagem

- Entender o que é Computação na Nuvem (Cloud Computing).
- Conhecer as vantagens e desvantagens do uso de serviços em nuvem.
- Identificar os modelos de serviço (IaaS, PaaS, SaaS) e modelos de implantação (pública, privada, híbrida).
- Reconhecer os principais provedores de nuvem e seus produtos/serviços essenciais.

## Arquivos desta seção

A pasta contém os seguintes documentos (PDF):

- `01_O_Que_E_Computacao_Na_Nuvem_Cloud_Computing_V2.pdf` — Introdução e definição de Cloud Computing; conceitos básicos; motivação para adoção; histórico e evolução.
- `02_Vantagens_Da_Computacao_Na_Nuvem_V2.pdf` — Principais benefícios: escalabilidade, elasticidade, redução de custos, disponibilidade, resiliência, automação e agilidade.
- `03_Desvantagens_Da_Computacao_Na_Nuvem.pdf` — Riscos e limitações: dependência de terceiros, questões de segurança e privacidade, latência, conformidade regulatória e riscos de lock-in.
- `04_Principais_Provedores_De_Computacao_Na_Nuvem.pdf` — Visão geral dos provedores líderes de mercado e seus diferenciais (serviços, regiões, ecossistemas).
- `05_Principais_Provedores_De_Computacao_Na_Nuvem.pdf` — Material complementar sobre provedores (pode ser uma versão alternativa ou atualização).

> Observação: abra os PDFs para consultar o conteúdo completo. Este README apresenta um resumo e pontos-chave para estudo rápido.

## Resumo dos principais conceitos

- Definição: Computação na Nuvem é a entrega de recursos computacionais (servidores, armazenamento, bancos de dados, redes, software) como serviços sob demanda pela internet, com pagamento conforme uso.

- Modelos de serviço:
  - IaaS (Infrastructure as a Service): recursos de infraestrutura (VMs, storage, redes) gerenciados pelo provedor.
  - PaaS (Platform as a Service): plataforma gerenciada para desenvolvimento e execução de aplicações (ex.: runtimes, bancos de dados gerenciados).
  - SaaS (Software as a Service): aplicações prontas acessadas via internet (ex.: e-mail, CRM).

- Modelos de implantação:
  - Nuvem pública: provedores terceiros oferecem serviços via internet para múltiplos clientes.
  - Nuvem privada: infraestrutura dedicada a uma única organização, on‑premises ou hospedada.
  - Nuvem híbrida: combinação e integração entre nuvens públicas e privadas.

## Vantagens (resumido)

- Escalabilidade e elasticidade automáticas.
- Redução de CAPEX e transformação em OPEX (pague pelo que usar).
- Acesso global e rapidez no provisionamento de recursos.
- Serviços gerenciados que simplificam operação (backup, monitoramento, segurança).

## Desvantagens e riscos (resumido)

- Segurança e privacidade dos dados — responsabilidade compartilhada entre cliente e provedor.
- Dependência do provedor (vendor lock-in) e possíveis custos de migração.
- Latência e performance para aplicações sensíveis.
- Aspectos regulatórios e conformidade (dados sujeitos a leis locais).

## Principais provedores (visão geral)

- AWS (Amazon Web Services): amplo portfólio, líder de mercado, forte em IaaS/PaaS.
- Microsoft Azure: integração com ecossistema Microsoft (Windows, Office, Active Directory).
- Google Cloud Platform (GCP): destaque em dados, ML e infraestrutura de rede.
- Outros players: Oracle Cloud, IBM Cloud, Alibaba Cloud, provedores regionais.

## Como usar estes materiais

1. Leia `01_O_Que_E_Computacao_Na_Nuvem_Cloud_Computing_V2.pdf` para obter a base conceitual.
2. Confira `02_Vantagens_Da_Computacao_Na_Nuvem_V2.pdf` e `03_Desvantagens_Da_Computacao_Na_Nuvem.pdf` para avaliar trade-offs.
3. Estude `04_...` e `05_...` para comparar provedores e identificar serviços relevantes ao seu contexto.

## Sugestões de atividades e exercícios

- Liste três casos de uso na sua organização ou projeto onde a nuvem traria benefício e explique por quê.
- Compare IaaS vs PaaS para um aplicativo web simples: quais componentes seriam gerenciados pelo provedor em cada modelo?
- Pesquise preços iniciais (camada gratuita ou instâncias de baixo custo) de AWS, Azure e GCP para um servidor Linux com 1 vCPU e 1–2 GB de RAM.
- Identifique requisitos de conformidade (ex.: LGPD no Brasil) que impactem a escolha de localidade/region de um provedor.

## Referências e leitura adicional

- Documentação oficial dos provedores (AWS, Azure, GCP).
- Artigos sobre modelos de responsabilidade compartilhada em nuvem.
- Materiais do curso e gravações da aula (se houver).

---

# Section 02 — Introduction to Cloud Computing

This document summarizes the content of Section 02 of the course "Cloud Computing — Essential", gathers the files available in the folder, and suggests complementary activities and readings for reinforcement.

## Learning objectives

- Understand what Cloud Computing is.
- Learn the advantages and disadvantages of using cloud services.
- Identify service models (IaaS, PaaS, SaaS) and deployment models (public, private, hybrid).
- Recognize the main cloud providers and their essential products/services.

## Files in this section

The folder contains the following PDF documents:

- `01_O_Que_E_Computacao_Na_Nuvem_Cloud_Computing_V2.pdf` — introduction and definition of Cloud Computing; basic concepts; motivation for adoption; history and evolution.
- `02_Vantagens_Da_Computacao_Na_Nuvem_V2.pdf` — key benefits: scalability, elasticity, cost reduction, availability, resilience, automation, and agility.
- `03_Desvantagens_Da_Computacao_Na_Nuvem.pdf` — risks and limitations: third-party dependence, security and privacy concerns, latency, regulatory compliance, and lock-in risks.
- `04_Principais_Provedores_De_Computacao_Na_Nuvem.pdf` — overview of the leading providers and their differentiators (services, regions, ecosystems).
- `05_Principais_Provedores_De_Computacao_Na_Nuvem.pdf` — supplemental provider material (possibly an alternative version or update).

> Note: open the PDFs to consult the full content. This README provides a summary and key points for quick study.

## Key concept summary

- Definition: Cloud Computing is the delivery of computing resources (servers, storage, databases, networks, software) as on-demand services over the internet, with pay-as-you-go pricing.

- Service models:
  - IaaS (Infrastructure as a Service): infrastructure resources (VMs, storage, networks) managed by the provider.
  - PaaS (Platform as a Service): managed platform for application development and execution (e.g., runtimes, managed databases).
  - SaaS (Software as a Service): ready-to-use applications accessed via the internet (e.g., email, CRM).

- Deployment models:
  - Public cloud: third-party providers offer services over the internet to multiple customers.
  - Private cloud: infrastructure dedicated to a single organization, on-premises or hosted.
  - Hybrid cloud: combination and integration of public and private clouds.

## Advantages (summary)

- Automatic scalability and elasticity.
- Reduced CAPEX and shift to OPEX (pay for what you use).
- Global access and faster resource provisioning.
- Managed services that simplify operations (backup, monitoring, security).

## Disadvantages and risks (summary)

- Data security and privacy — shared responsibility between customer and provider.
- Provider dependency (vendor lock-in) and possible migration costs.
- Latency and performance concerns for sensitive applications.
- Regulatory and compliance considerations (data subject to local laws).

## Main providers (overview)

- AWS (Amazon Web Services): broad portfolio, market leader, strong in IaaS/PaaS.
- Microsoft Azure: integration with the Microsoft ecosystem (Windows, Office, Active Directory).
- Google Cloud Platform (GCP): strong focus on data, ML, and network infrastructure.
- Other players: Oracle Cloud, IBM Cloud, Alibaba Cloud, regional providers.

## How to use these materials

1. Read `01_O_Que_E_Computacao_Na_Nuvem_Cloud_Computing_V2.pdf` to get the conceptual foundation.
2. Review `02_Vantagens_Da_Computacao_Na_Nuvem_V2.pdf` and `03_Desvantagens_Da_Computacao_Na_Nuvem.pdf` to evaluate trade-offs.
3. Study `04_...` and `05_...` to compare providers and identify services relevant to your context.

## Suggested activities and exercises

- List three use cases in your organization or project where cloud would help and explain why.
- Compare IaaS vs PaaS for a simple web application: which components would be managed by the provider in each model?
- Research starter pricing (free tier or low-cost instances) from AWS, Azure, and GCP for a Linux server with 1 vCPU and 1–2 GB RAM.
- Identify compliance requirements (e.g., LGPD in Brazil) that affect a provider's region/location choice.

## Additional references and reading

- Official provider documentation (AWS, Azure, GCP).
- Articles about shared responsibility models in cloud.
- Course materials and lesson recordings (if available).
