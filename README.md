# Gs_Devops

## Plataforma de Eficiência Energética para Prédios Inteligentes
## Descrição do Projeto
Este projeto é uma solução que monitora e controla o consumo energético de prédios inteligentes. O objetivo é reduzir desperdícios, priorizar o uso de fontes renováveis e fornecer insights baseados em dados históricos e previsões climáticas.

##  A arquitetura da solução inclui:

Frontend: Desenvolvido em .NET Core MVC, hospedado em uma VM Windows.
Backend: Uma API RESTful desenvolvida em .NET Core Web API, hospedada em uma VM Linux (Ubuntu 20.04).
Banco de Dados Oracle: Para persistência de dados relacionados ao consumo energético, alertas e previsões climáticas.

## Requisitos
.NET SDK: Versão 8.0.
Banco de Dados Oracle: Versão 19c.
Sistema Operacional:
Frontend: Windows Server 2022.
Backend: Ubuntu 20.04.


## Arquitetura do Projeto
Frontend (VM Windows):

Desenvolvido em .NET Core MVC.
Hospedado no IIS (Internet Information Services).
Comunica-se com o Backend via HTTP/HTTPS.

Backend (VM Linux):
Desenvolvido em .NET Core Web API.
Integração com o Banco de Dados Oracle para persistência de dados.
Gerencia dados de consumo energético, configurações de alertas e previsões climáticas.

Banco de Dados Oracle:
Utilizado para armazenamento e consulta de dados.
Conexão via porta 1521.

## Ferramentas Instaladas nas VMs
##Frontend (VM Windows)
Sistema Operacional: Windows Server 2022.
.NET SDK: Versão 8.0.
IIS (Internet Information Services): Para hospedagem da aplicação.
RDP (Remote Desktop Protocol): Porta 3389 para acesso remoto.

## Backend (VM Linux)
Sistema Operacional: Ubuntu 20.04.
.NET SDK: Versão 8.0.
Ferramentas de Conexão Oracle: Para integração com o banco de dados.
SSH (Secure Shell): Porta 22 para acesso remoto.

Configuração de Rede (NSG - Network Security Group)
As regras de segurança configuradas para as máquinas virtuais incluem:
