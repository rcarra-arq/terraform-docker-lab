# Terraform Docker Lab – AWS Infrastructure Project

## Overview

This project is part of my transition into Cloud Computing, focusing on Infrastructure as Code (IaC), automation, and CI/CD fundamentals.

The goal is to design and deploy cloud infrastructure on AWS using Terraform, while developing practical experience with Git, GitHub, and modern DevOps workflows.

In this project, I provision an AWS EC2 instance using Terraform and deploy a Dockerized Nginx web server accessible via a public IP address.

---

## Technologies

* AWS (EC2, Security Groups, VPC networking)
* Terraform (Infrastructure as Code)
* Docker (Containerization)
* Git & GitHub (Version Control)
* GitHub Actions (CI automation)
* Linux (Ubuntu)

---

## Features

* Infrastructure provisioning on AWS using Terraform
* Automated EC2 deployment
* Docker container running Nginx web server
* Public access via EC2 IP (port 80)
* Version control with Git and GitHub
* CI validation using GitHub Actions

---

## Project Structure

```text
terraform-docker-lab/
├── terraform/
│   ├── main.tf
│   ├── variables.tf
│   ├── outputs.tf
│
├── .github/
│   └── workflows/
│       └── terraform-check.yml
│
├── README.md
└── .gitignore
```

---

## CI/CD (GitHub Actions)

This repository includes a GitHub Actions workflow that runs automatically on each push.

Current workflow:

* Checkout repository
* Validate Terraform configuration

---

## Learning Objectives

* Infrastructure as Code (Terraform)
* AWS cloud resource provisioning
* CI/CD fundamentals with GitHub Actions
* Docker container deployment
* Git-based development workflow

---

## Author

Renata C.
Cloud Computing career transition focused on AWS, Infrastructure, and DevOps practices.

---

PT/BR
# Terraform Docker Lab – Projeto de Infraestrutura na AWS

## Visão Geral

Este projeto faz parte da minha transição de carreira para Cloud Computing, com foco em Infraestrutura como Código (IaC), automação e fundamentos de CI/CD.

O objetivo é projetar e provisionar infraestrutura em nuvem na AWS utilizando Terraform, enquanto desenvolvo experiência prática com Git, GitHub e fluxos modernos de DevOps.

Neste projeto, eu provisiono uma instância EC2 na AWS com Terraform e realizo o deploy de um servidor Nginx em container Docker, acessível via IP público.

---

## Tecnologias

* AWS (EC2, Security Groups, rede VPC)
* Terraform (Infraestrutura como Código)
* Docker (Containerização)
* Git & GitHub (Controle de versão)
* GitHub Actions (Automação de CI)
* Linux (Ubuntu)

---

## Funcionalidades

* Provisionamento de infraestrutura na AWS com Terraform
* Deploy automatizado de instância EC2
* Execução de container Docker com Nginx
* Acesso público via IP da instância (porta 80)
* Versionamento com Git e GitHub
* Validação de configuração via GitHub Actions

---

## Estrutura do Projeto

```text id="7h9kq1"
terraform-docker-lab/
├── terraform/
│   ├── main.tf
│   ├── variables.tf
│   ├── outputs.tf
│
├── .github/
│   └── workflows/
│       └── terraform-check.yml
│
├── README.md
└── .gitignore
```

---

## CI/CD (GitHub Actions)

Este repositório inclui um workflow do GitHub Actions que é executado automaticamente a cada push.

Fluxo atual:

* Checkout do repositório
* Validação da configuração do Terraform

---

## Objetivos de Aprendizado

* Praticar Infraestrutura como Código (IaC)
* Aprimorar habilidades com Git e GitHub
* Aprender fundamentos de CI/CD
* Trabalhar com deploy em container (Docker)
* Simular um fluxo de trabalho DevOps real

---

## Próximos Passos

* Modularizar a infraestrutura com Terraform
* Implementar backend remoto (S3 + DynamoDB)
* Expandir pipeline CI/CD com validações adicionais
* Adicionar monitoramento (CloudWatch)
* Evoluir para arquitetura multi-serviço

---

## Autor

Renata C.
Profissional em transição de carreira para Cloud Computing, com foco em AWS, Infraestrutura e práticas de DevOps. Este projeto faz parte da minha jornada prática de aprendizado e construção de portfólio na área de tecnologia.


