# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 10 de março de 2026
Empresa: Farmácia Virtual Fictícia
Responsável: Ronan Farias

## Introdução

Este relatório apresenta o processo de concepção e implementação de uma plataforma virtual para uma farmácia fictícia, utilizando a infraestrutura da AWS. O projeto foi realizado por Ronan, com o objetivo de aprofundar o conhecimento sobre os serviços da AWS através de uma experiência prática. A plataforma visa simular um e-commerce farmacêutico, enfrentando desafios reais para aplicar conceitos teóricos em um cenário dinâmico.

## Descrição do Projeto

O projeto de implementação da plataforma virtual foi dividido em 3 etapas, cada uma focando em um serviço AWS essencial para a construção de uma aplicação web escalável e segura. A seguir, serão descritas as etapas do projeto:

Etapa 1: Amazon S3 para Armazenamento de Arquivos

- Nome da ferramenta: Amazon S3 (Simple Storage Service)
- Foco da ferramenta: Armazenamento de objetos estáticos, como imagens de produtos farmacêuticos, documentos e backups.
- Descrição de caso de uso: Utilizado para hospedar imagens de medicamentos, catálogos e arquivos estáticos da plataforma, garantindo alta disponibilidade e baixo custo.

Etapa 2: AWS Lambda para Backend Serverless

- Nome da ferramenta: AWS Lambda
- Foco da ferramenta: Execução de código sem servidor, ideal para APIs e processamento de eventos.
- Descrição de caso de uso: Implementação de funções serverless para gerenciar operações como listagem de produtos, processamento de pedidos e autenticação de usuários, permitindo escalabilidade automática.

Etapa 3: Amazon DynamoDB para Banco de Dados

- Nome da ferramenta: Amazon DynamoDB
- Foco da ferramenta: Banco de dados NoSQL rápido e escalável para aplicações de alta performance.
- Descrição de caso de uso: Armazenamento de dados de produtos, usuários e pedidos, com suporte a consultas rápidas e integração com o backend Lambda para uma experiência de usuário fluida.

## Conclusão

A implementação da plataforma virtual na Farmácia Virtual Fictícia tem como esperado redução de custos operacionais, escalabilidade automática e alta disponibilidade, o que aumentará a eficiência e a produtividade da simulação de um negócio farmacêutico online. Recomenda-se a continuidade da utilização dos serviços AWS implementados e a exploração de tecnologias adicionais, como Amazon API Gateway e AWS CloudFront, para melhorar ainda mais os processos e a experiência do usuário.

## Anexos

- Diagrama de arquitetura da plataforma
- Código de exemplo das funções Lambda
- Documentação dos serviços AWS utilizados
- Planilha de custos estimados

Assinatura do Responsável pelo Projeto:

Ronan Farias
