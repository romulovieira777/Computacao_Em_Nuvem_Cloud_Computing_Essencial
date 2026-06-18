# Seção 03 — Amazon Web Services (AWS)

Este README resume os pontos essenciais sobre Amazon Web Services (AWS) apresentados na aula e organiza materiais e atividades para estudo prático.

## Objetivos de aprendizagem

- Compreender o que é AWS e seu posicionamento no mercado de cloud.
- Conhecer a infraestrutura global (Regions, Availability Zones) e como isso impacta arquiteturas.
- Identificar os serviços fundamentais de compute, armazenamento, bancos de dados, rede e segurança.
- Aprender os conceitos de responsabilidade compartilhada, modelos de preços e boas práticas básicas.

## Visão geral

AWS é uma plataforma de serviços de cloud oferecida pela Amazon, com amplo portfólio que cobre IaaS, PaaS e serviços gerenciados. É líder de mercado e fornece serviços para desde startups até grandes empresas.

## Infraestrutura global

- Regiões (Regions): localizações geográficas onde a AWS opera (ex.: us-east-1, eu-west-1).
- Zonas de disponibilidade (Availability Zones, AZs): data centers isolados dentro de regiões para alta disponibilidade.
- Edge Locations: pontos de presença usados por CloudFront e serviços de baixa latência.

Considere proximidade de região ao armazenar dados sensíveis e otimizar latência.

## Serviços principais (resumo)

- Compute:
  - Amazon EC2 — máquinas virtuais configuráveis.
  - AWS Lambda — funções serverless.
  - Amazon ECS / EKS — containers gerenciados (ECS para containers, EKS para Kubernetes).

- Armazenamento e conteúdos:
  - Amazon S3 — armazenamento de objetos, durável e escalável.
  - Amazon EBS — blocos de armazenamento para EC2.
  - Amazon EFS — sistema de arquivos disponível para múltiplas instâncias.
  - Amazon CloudFront — CDN para distribuição de conteúdo.

- Bancos de dados:
  - Amazon RDS — bancos relacionais gerenciados (MySQL, PostgreSQL, SQL Server, etc.).
  - Amazon DynamoDB — banco NoSQL gerenciado e com baixa latência.
  - Amazon Aurora — banco relacional compatível e otimizado.

- Rede e entrega de aplicações:
  - Amazon VPC — rede virtual isolada.
  - Elastic Load Balancer (ALB/NLB) — balanceamento de carga.
  - Amazon Route 53 — DNS e roteamento.

- Segurança e identidade:
  - AWS IAM — gerenciamento de usuários, permissões e roles.
  - AWS KMS — gerenciamento de chaves criptográficas.
  - AWS Shield / WAF — proteção contra ataques e filtragem de tráfego.

- Observabilidade e operação:
  - Amazon CloudWatch — métricas, logs e alarmes.
  - AWS CloudTrail — auditoria de chamadas à API.

## Modelo de responsabilidade compartilhada

- Provedor (AWS): segurança da nuvem — infraestrutura física, hardware, virtualização e serviços básicos.
- Cliente: segurança na nuvem — configuração de serviços, gestão de identidade, criptografia de dados e políticas de acesso.

## Custos e pricing (breve)

- Modelo pay-as-you-go: paga-se pelo uso.
- Camada gratuita (Free Tier) oferece recursos limitados para testes.
- Há instâncias reservadas e savings plans para reduzir custos em workloads previsíveis.
- Ferramentas: AWS Pricing Calculator e Cost Explorer.

## Boas práticas rápidas

- Use múltiplas AZs para alta disponibilidade.
- Não use credenciais de root — crie usuários/roles com permissões mínimas (least privilege).
- Faça backups regulares (snapshots, versionamento S3).
- Monitore custos e defina alertas para uso anômalo.
- Habilite logs e auditoria via CloudTrail.

## Sugestões de atividades e exercícios

1. Crie uma conta na camada gratuita da AWS e explore o Console.
2. Hospede um site estático em Amazon S3 + CloudFront.
3. Lance uma instância EC2 Linux (t2.micro/t3.micro), conecte via SSH e instale um servidor web simples.
4. Implemente uma função simples com AWS Lambda e teste com o console ou API Gateway.
5. Configure um banco de dados RDS (MySQL ou PostgreSQL) e conecte-se a partir de uma EC2 na mesma VPC.
6. Crie políticas IAM com permissões mínimas para um usuário que só tenha acesso de leitura ao S3.
7. Use o AWS Pricing Calculator para estimar custos de um pequeno ambiente (1 EC2 + 1 RDS + S3).

## Recursos e referências

- Documentação oficial AWS: https://aws.amazon.com/documentation/
- Getting Started: https://aws.amazon.com/getting-started/
- Free Tier: https://aws.amazon.com/free/
- AWS Well-Architected Framework: https://aws.amazon.com/architecture/well-architected/

---
