# LeadPulse AI

![Equipe 10 AI Logo](https://via.placeholder.com/200x80?text=LeadPulse+AI)

## Visão Geral

Equipe 10 AI AI é um sistema de inteligência artificial projetado para a Equipe 10 de Marketing & Comercial, focado na estratificação, qualificação e gerenciamento eficiente de leads do LinkedIn. A plataforma utiliza algoritmos avançados para analisar, categorizar e priorizar leads, fornecendo insights valiosos e recomendações personalizadas para abordagens comerciais.

## Funcionalidades Principais

### 🎯 Estratificação e Qualificação de Leads

- Extração automática de dados do LinkedIn
- Algoritmo de pontuação (score) baseado em múltiplos critérios
- Classificação por temperatura (Hot, Warm, Med, Cool, Cold, New)
- Priorização inteligente de leads com maior potencial

### 📊 Mapa de Calor de Leads

- Visualização matricial de leads por potencial x engajamento
- Identificação rápida de zonas com maior probabilidade de conversão
- Filtros por setor, região e período
- Análise visual de tendências e padrões

### 📑 Geração de Dossiês Automáticos

- Criação de relatórios detalhados para cada lead qualificado
- Informações de contato e dados corporativos
- Histórico de interações e engajamento
- Tópicos de interesse identificados
- Recomendações personalizadas para abordagem

### ⚡ Otimização de Processos Comerciais

- Redução significativa no tempo de triagem
- Aumento na assertividade das abordagens iniciais
- Métricas de desempenho em tempo real
- Dashboard completo com KPIs relevantes

## Tecnologias Utilizadas

- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: Node.js, Express
- **IA/ML**: TensorFlow, Natural Language Processing
- **Banco de Dados**: MongoDB
- **API**: LinkedIn API, OpenAI API
- **Visualização de Dados**: D3.js

## Instalação e Configuração

### Pré-requisitos

- Node.js (v14 ou superior)
- MongoDB
- Conta na LinkedIn API
- Credenciais da OpenAI API

### Passos para Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/equipe10/leadpulse-ai.git
   cd leadpulse-ai
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Configure as variáveis de ambiente no arquivo `.env`:
   ```
   LINKEDIN_API_KEY=sua_chave_aqui
   OPENAI_API_KEY=sua_chave_aqui
   MONGODB_URI=sua_uri_aqui
   PORT=3000
   ```

4. Inicie o servidor de desenvolvimento:
   ```bash
   npm run dev
   ```

5. Acesse a aplicação em `http://localhost:3000`

## Uso da Aplicação

### Dashboard

O dashboard principal apresenta uma visão geral de todos os leads, estatísticas importantes e ações rápidas:
- Cards com métricas-chave (Leads Totais, Qualificados, Dossiês)
- Gráfico de categorização por temperatura
- Mapa de calor de leads
- Lista de leads prioritários com ações rápidas

### Extração de Leads

1. Acesse a página "Leads LinkedIn"
2. Clique em "Extrair Leads"
3. Defina os critérios de extração (opcional)
4. Aguarde o processamento e aprovação dos novos leads

### Qualificação

1. Acesse a página "Qualificação"
2. Ajuste os critérios conforme necessário:
   - Cargo Estratégico
   - Tamanho da Empresa
   - Engajamento em Publicações
   - Conexões em Comum
3. Clique em "Aplicar" para requalificar os leads

### Acessando Dossiês

1. Encontre o lead desejado na tabela
2. Clique em "Ver Dossiê" para acessar as informações completas
3. Explore as seções:
   - Informações do Contato
   - Dados da Empresa
   - Histórico de Interações
   - Recomendações de Abordagem
   - Tópicos de Interesse

## Casos de Uso

### Cenário 1: Qualificação de Leads de Tecnologia

A equipe comercial precisa focar em prospects do setor de tecnologia com cargos de diretoria ou superior:
1. Filtrar o mapa de calor por setor "Tecnologia"
2. Identificar a zona mais "quente" com alto potencial
3. Acessar os dossiês dos leads prioritários
4. Utilizar as recomendações personalizadas nas abordagens

### Cenário 2: Campanha para Leads Frios

Reativação de leads com pouco engajamento recente:
1. Filtrar leads classificados como "Cold"
2. Analisar tópicos de interesse comuns
3. Desenvolver campanha direcionada com conteúdo relevante
4. Monitorar respostas e reclassificar conforme engajamento

## Roadmap de Desenvolvimento

### Versão 1.1 (Próximo Lançamento)
- Integração com CRM
- Análise de sentimento em interações
- Expansão de fontes de dados (além do LinkedIn)

### Versão 1.2
- Previsões de conversão baseadas em ML
- Recomendações automatizadas de conteúdo
- Sistema de alertas para oportunidades de alta prioridade

### Versão 2.0
- Automação completa de abordagens iniciais
- Análise competitiva de leads
- Dashboard personalizado por usuário

## Contribuição

Para contribuir com o projeto:

1. Faça um fork do repositório
2. Crie uma branch para sua feature (`git checkout -b feature/nova-funcionalidade`)
3. Faça commit das alterações (`git commit -m 'Adiciona nova funcionalidade'`)
4. Faça push para a branch (`git push origin feature/nova-funcionalidade`)
5. Abra um Pull Request



---

Desenvolvido pela Equipe 10 - Marketing & Comercial © 2025
