# blog-container-apps
Projeto prático de aplicação de blog com Azure Container Apps - DIO Cloud Native

## Sobre o Projeto

Este projeto prático faz parte da trilha **Microsoft Azure Cloud Native** da DIO (Digital Innovation One) e demonstra a criação de uma aplicação de blog utilizando **Azure Container Apps**.

## O que são Azure Container Apps?

Plataforma para executar aplicações em contêineres com foco em simplicidade e escalabilidade automática. Azure Container Apps oferece:

- **Serviço PaaS** para hospedar apps na Azure
- **Ajusta recursos automaticamente** conforme uso
- **Ambiente isolado** para testes de novas versões
- **Automatiza build e deploy** de aplicações

## Conceitos Principais Abordados

### 1. Docker e Containerização
- Criação de Dockerfile para empacotar a aplicação
- Construção de imagens Docker otimizadas
- Best practices de containerização

### 2. Azure Container Registry (ACR)
- Armazenamento de imagens de container privado
- Integração com Azure Container Apps
- Autenticação e segurança de imagens

### 3. Escalabilidade
- Dimensionamento automático de recursos
- Configuração de limites e requisições
- Monitoramento de performance

### 4. Deploy Contínuo
- CI/CD pipelines
- Slots de Deployment
- Atualizações sem downtime

## Insights e Aprendizados

- Azure Container Apps simplifica significativamente o deploy de aplicações containerizadas
- A escalabilidade automática elimina preocupações com dimensionamento manual
- O isolamento de ambientes facilita testes e atualizações de versões
- Docker é fundamental para qualquer desenvolvedor cloud-native
- A integração com CI/CD é crucial para DevOps eficiente

## Possibilidades Futuras

- Integração com bancos de dados gerenciados (Azure SQL, Cosmos DB)
- Implementação de API Management
- Monitoramento com Application Insights
- Implementação de múltiplas regiões para alta disponibilidade
- Integração com Azure DevOps para automação completa

## Como Executar

1. Clone este repositório
2. Instale Docker
3. Crie um Container Registry no Azure
4. Build da imagem Docker
5. Deploy para Azure Container Apps

## Referências

- [Azure Container Apps Documentation](https://learn.microsoft.com/en-us/azure/container-apps/)
- [Digital Innovation One - DIO](https://www.dio.me)
- [Docker Documentation](https://docs.docker.com/)

---

**Desenvolvido durante a trilha Cloud Native da DIO** ✍️
