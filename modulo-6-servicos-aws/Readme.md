# Módulo 6 – Infraestrutura como Código (IaC) com AWS CloudFormation e Serviços AWS

Repositório do Módulo 6, com foco na aplicação prática de infraestrutura como código (IaC) utilizando AWS CloudFormation para o provisionamento de serviços como RDS, EC2, ECS, EKS e mais.

---

## 🧠 Objetivos

- Compreender a infraestrutura global da AWS e o AWS Well-Architected Framework.
- Entender os fundamentos de IaC, DevOps e SRE.
- Aplicar CI/CD e boas práticas de provisionamento.
- Criar templates do AWS CloudFormation para diversos serviços.
- Trabalhar com banco de dados (RDS), máquinas virtuais (EC2) e conteinerização (ECS, EKS).
- Aplicar conceitos de segurança com IAM (users, roles, policies).
- Praticar automação de ambientes em nuvem com foco em escalabilidade, confiabilidade e eficiência.

---

## 📚 Conteúdos Abordados

### Fundamentos e Ferramentas
- Infraestrutura Global da AWS
- AWS Well-Architected Framework
- Conceitos de DevOps, CI/CD e SRE
- Ferramentas: Draw.io, Visual Studio Code

### Segurança e Acesso
- IAM (User, Role, Policy)
- Roles para EC2/SSM
- Controle de acesso via políticas

### Serviços AWS Provisionados
- **RDS:** PostgreSQL, conexão com PgAdmin
- **EC2:** Instâncias Linux e Windows via AMIs
- **ECR:** Repositório de imagens Docker
- **ECS:** Com Fargate e EC2 (Cluster, Tasks, Load Balancer, Autoscaling)
- **EKS:** Kubernetes gerenciado (Cluster, Nodes, Networking)

### Infraestrutura como Código (IaC)
- Templates com AWS CloudFormation
- Criação e gerenciamento de pilhas (stacks)
- Provisionamento de ambientes completos via código

---

## 📖 Bibliografia e Recursos

- 📘 [AWS CloudFormation – Documentação Oficial](https://docs.aws.amazon.com/cloudformation/)
- 📘 [AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/)
- 📘 [Livro: Site Reliability Engineering (SRE)](https://sre.google/books/)
- 🛠️ Ferramentas:
  - AWS Console
  - AWS CLI
  - Draw.io Online
  - Visual Studio Code

---

## 🧪 Metodologia

- Aulas expositivas com demonstrações práticas
- Pesquisa ativa na documentação da AWS
- Listas de exercícios individuais com desafios progressivos

---

## 📊 Avaliação

- Listas de exercícios
- Prova teórico-prática
- Autoavaliação

---

## 📅 Plano de Aulas

| Aula | Tema | Conteúdos Principais |
|------|------|-----------------------|
| 1 | Visão Geral de Cloud e AWS | Infraestrutura Global AWS, Well-Architected Framework |
| 2 | Cultura DevOps e SRE | CI/CD, SRE, Grafana, Prometheus, AppDynamics |
| 3 | RDS e EC2 – Introdução | Provisionamento de PostgreSQL e EC2 via Console |
| 4 | RDS com CloudFormation | IaC com CloudFormation para banco de dados |
| 5 | EC2 com CloudFormation | AMIs Linux/Windows, provisionamento via templates |
| 6 | Conteinerização na AWS | ECR, ECS, EKS – conceitos e práticas iniciais |
| 7 | ECS com Fargate/EC2 | Cluster, Tasks, Load Balancer, VPC via CloudFormation |
| 8 | Kubernetes com EKS | Cluster, Nodes, Storage, Network com IaC |

---

## ✍️ Autor

Este repositório foi desenvolvido como parte do curso *Vem Ser Tech - DevOps*, oferecido pela *Ada Tech* e ministrado pelos professores *Renata e André*.

