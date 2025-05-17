# Módulo 5 – AWS Elastic Beanstalk e Integração com Serviços AWS

Repositório do Módulo 5, com foco no provisionamento, monitoramento, escalabilidade, segurança e integração de aplicações utilizando o AWS Elastic Beanstalk e os principais serviços da AWS.

---

## 🧠 Objetivos

- Compreender a infraestrutura global da AWS e os conceitos do Elastic Beanstalk.
- Configurar ambientes e aplicações no Beanstalk.
- Trabalhar com escalabilidade, resiliência e políticas de deploy.
- Realizar integrações com serviços AWS como RDS, S3, CloudFront, Secrets Manager e outros.
- Aplicar práticas de segurança, monitoramento e controle de custos.
- Provisionar VPCs e conectar com bancos de dados.
- Executar e gerenciar aplicações distribuídas e microserviços.

---

## 📚 Conteúdos Abordados

### Fundamentos
- Infraestrutura global da AWS
- Uso do AWS Management Console e AWS CLI
- Conceitos de IaaS vs PaaS

### Elastic Beanstalk
- Criação de aplicações e ambientes
- Suporte a múltiplas plataformas
- Configuração de variáveis de ambiente
- Deploy: All at Once, Rolling, Immutable e Blue/Green
- Uso de arquivos `.ebextensions`
- Rollbacks e versões

### Escalabilidade e Resiliência
- Auto Scaling Group (ASG)
- Elastic Load Balancer (ELB)
- Health checks e backups

### Segurança e Acesso
- IAM: users, policies, roles
- AWS Cognito
- Security Groups
- Criptografia SSL/TLS
- Modelo de responsabilidade compartilhada

### Monitoramento e Performance
- CloudWatch (métricas, logs e alarmes)
- AWS X-Ray (rastreamento de requisições)
- Billing e AWS Cost Explorer

### Integrações e Avançado
- Amazon RDS (MySQL)
- VPC personalizada
- AWS Secrets Manager e Systems Manager
- Amazon EFS e CloudFront
- API Gateway: deploy, monitoramento e stages
- Tags de recursos e controle de custos

---

## 📖 Bibliografia e Recursos

- 📘 [Documentação Oficial AWS – Elastic Beanstalk](https://docs.aws.amazon.com/elasticbeanstalk/)
- 📘 [Documentação AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-welcome.html)
- 🛠️ Ferramentas:
  - AWS Console
  - AWS CLI
  - Draw.io
  - CloudWatch
  - X-Ray
  - API Gateway

---

## 🧪 Metodologia

- Aulas expositivas e práticas
- Exercícios de fixação guiados
- Estudo de caso prático com integração de serviços AWS
- Exploração da documentação oficial

---

## 📊 Avaliação

- Listas de exercícios
- Prova teórico-prática
- Autoavaliação

---

## 📅 Plano de Aulas

| Aula | Tema | Conteúdos Principais |
|------|------|-----------------------|
| 1 | Introdução ao Elastic Beanstalk | IaaS x PaaS, configuração de ambiente, variáveis, IAM |
| 2 | Configuração do Cognito | Criação de grupos e autenticação com Cognito |
| 3 | Escalabilidade e Resiliência | Auto Scaling, ELB, backups, health checks |
| 4 | Formas de Deploy e Rollback | All at once, Rolling, Immutable, Blue/Green |
| 5 | Integração com Serviços AWS | Secrets Manager, Systems Manager, EFS, CloudFront |
| 6 | Segurança e Configurações Avançadas | .ebextensions, SSL/TLS, CloudTrail |
| 7 | API Gateway | Configuração, stages, monitoramento via CloudWatch |
| 8 | Monitoramento e Custos | CloudWatch, X-Ray, métricas, billing |

## ✍️ Autor

Este repositório foi desenvolvido como parte do curso *Vem Ser Tech - DevOps*, oferecido pela *Ada Tech* e ministrado pelos professores *André e Renata*.

