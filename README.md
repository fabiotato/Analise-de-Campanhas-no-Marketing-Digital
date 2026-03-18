# 📈 Análise de Performance de Campanhas de Marketing Digital

[![Portfolio](https://img.shields.io/badge/Portfolio-F%C3%A1bio%20Luiz%20de%20Oliveira-%23f093fb)](https://portfolio-analista-dados-azure.vercel.app)
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Excel](https://img.shields.io/badge/Excel-217346?logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/pt-br/microsoft-365/excel)
[![Estatística](https://img.shields.io/badge/Estat%C3%ADstica-Analytics-%23ff6b6b)](https://www.scipy.org/)
[![Data Viz](https://img.shields.io/badge/Data%20Viz-Visualization-%234d69ff)](https://www.chartjs.org/)

## 📋 Visão Geral

Análise completa de **200 campanhas de tráfego pago** em 4 plataformas digitais: **Facebook Ads**, **Instagram Ads**, **Google Ads** e **LinkedIn Ads**. O projeto identifica padrões de performance, inconsistências nos ROIs e propõe recomendações estratégicas para otimização de orçamento.

### 🎯 Objetivo do Projeto

Analisar a performance de campanhas de marketing digital para:

- Identificar **padrões de sucesso e fracasso** entre campanhas
- Detectar **inconsistências nos ROIs** por canal e criativo
- Propor **recomendações estratégicas** para otimização de orçamento
- Maximizar o **retorno sobre investimento** em marketing

---

## 📊 Números Gerais da Análise

| Métrica | Valor | Descrição |
|---------|-------|-----------|
| **Total de Campanhas** | 200 | Campanhas analisadas |
| **Orçamento Total** | R$ 553.937,62 | Valor total investido |
| **Receita Gerada** | R$ 1.309.451,96 | Receita total atribuída |
| **ROI Geral** | 136% | Retorno sobre investimento médio |
| **Total de Leads** | 283.859 | Leads capturados |
| **Total de Conversões** | 13.600 | Conversões realizadas |

---

## ⚠️ Problema Identificado: Inconsistência nos ROIs

### 1. Alta Variabilidade
- **Coeficiente de variação médio superior a 150%** em todos os canais
- Resultados **extremamente inconsistentes** entre campanhas do mesmo canal
- Indica falta de padronização em estratégias e execução

### 2. ROI Negativo
| Métrica | Valor |
|---------|-------|
| **Campanhas com ROI Negativo** | 56 de 200 (28%) |
| **Valor Desperdiçado** | R$ 158.867,55 |
| **Percentual do Orçamento** | ~28,7% |

### 3. Distribuição Desigual
- **Facebook Ads**: Lidera com ROI médio de **158,55%**
- **Criativos Carrossel**: Melhor performance com **185,94%** de ROI
- **LinkedIn Ads**: Segundo colocado com **147,34%** de ROI

---

## 📈 Performance por Canal

### Comparativo de Métricas

| Canal | Campanhas | ROI Médio | CTR Médio | CPC Médio | Conv. Média | CV ROI |
|-------|-----------|-----------|-----------|-----------|-------------|--------|
| **Facebook Ads** | 54 | 158,55% | 8,11% | R$ 2,64 | 4,93% | 164,8% |
| **LinkedIn Ads** | 54 | 147,34% | 8,19% | R$ 2,64 | 5,01% | 148,7% |
| **Instagram Ads** | 46 | 132,18% | 7,85% | R$ 2,89 | 4,67% | 151,2% |
| **Google Ads** | 46 | 112,45% | 6,92% | R$ 3,12 | 4,21% | 178,5% |

### 🏆 Top Performers

#### Melhores ROIs por Canal
1. **Facebook Ads - Carrossel**: 185,94%
2. **LinkedIn Ads - Sponsored Content**: 162,30%
3. **Instagram Ads - Stories**: 148,75%
4. **Google Ads - Search**: 128,90%

#### Piores ROIs por Canal
1. **Google Ads - Display**: 45,20%
2. **Instagram Ads - Reels**: 67,80%
3. **Facebook Ads - Vídeo**: 78,45%
4. **LinkedIn Ads - Text Ads**: 82,15%

---

## 🔍 Análise de Criativos

### Performance por Formato de Criativo

| Formato | ROI Médio | CTR Médio | CPC Médio | Conversão |
|---------|-----------|-----------|-----------|-----------|
| **Carrossel** | 185,94% | 9,2% | R$ 2,45 | 5,8% |
| **Imagem Única** | 142,30% | 7,8% | R$ 2,78 | 4,9% |
| **Vídeo** | 98,45% | 6,5% | R$ 3,20 | 3,8% |
| **Stories** | 125,60% | 8,1% | R$ 2,95 | 4,5% |

### 💡 Insights de Criativos

1. **Carrossel** tem **2x mais engajamento** que vídeo
2. **Vídeos** têm **CPC 30% maior** que imagens estáticas
3. **Stories** têm **CTR elevado** mas conversão moderada

---

## 📊 Análise Estatística

### Distribuição de ROIs

| Estatística | Valor |
|-------------|-------|
| **Média** | 136% |
| **Mediana** | 128% |
| **Desvio Padrão** | 87,5% |
| **Mínimo** | -45% |
| **Máximo** | 425% |
| **Q1 (25%)** | 72% |
| **Q3 (75%)** | 195% |

### Correlações

| Variável | Correlação com ROI |
|----------|-------------------|
| **CTR** | 0,72 (Forte) |
| **CPC** | -0,45 (Moderada Inversa) |
| **Orçamento** | 0,18 (Fraca) |
| **Frequência** | -0,32 (Fraca Inversa) |

---

## 🎯 Recomendações Estratégicas

### 1. Otimização de Orçamento

#### Aumentar Investimento
- ✅ **Facebook Ads - Carrossel**: ROI de 185,94%
- ✅ **LinkedIn Ads - Sponsored Content**: ROI de 162,30%
- ✅ **Instagram Ads - Feed**: ROI de 145,20%

#### Reduzir/Pausar
- ⚠️ **Google Ads - Display**: ROI de 45,20%
- ⚠️ **Instagram Ads - Reels**: ROI de 67,80%
- ⚠️ **Facebook Ads - Vídeo**: ROI de 78,45%

### 2. Melhoria de Criativos

#### Para Vídeos
- Reduzir duração para **15-30 segundos**
- Adicionar **legendas** (85% assistem sem som)
- Incluir **CTA claro** nos primeiros 5 segundos

#### Para Carrossel
- Manter **3-5 cards** (performance ótima)
- Primeiro card deve ter **proposta de valor clara**
- Último card com **CTA direto**

### 3. Segmentação de Público

#### Lookalike Audiences
- Criar audiences baseadas em **top 10% de clientes**
- Testar **similaridade de 1%, 3% e 5%**
- Validar com **A/B testing**

#### Retargeting
- Implementar **sequências de 3-5 anúncios**
- Segmentar por **nível de funil**
- Personalizar mensagem por **comportamento anterior**

### 4. Testes Contínuos

#### A/B Testing Priorities
1. **Criativos**: Imagem vs. Vídeo vs. Carrossel
2. **Copy**: Longa vs. Curta
3. **CTAs**: "Saiba Mais" vs. "Compre Agora" vs. "Cadastre-se"
4. **Públicos**: Interesses vs. Comportamentos vs. Demográfico

---

## 🛠️ Ferramentas Utilizadas

| Ferramenta | Finalidade |
|------------|------------|
| **Python (pandas, numpy)** | Análise estatística e manipulação de dados |
| **Excel** | Validação e análise complementar |
| **Chart.js** | Visualizações interativas |
| **Facebook Ads Manager** | Fonte de dados Meta Ads |
| **Google Ads Editor** | Fonte de dados Google Ads |
| **LinkedIn Campaign Manager** | Fonte de dados LinkedIn Ads |

---

## 📁 Estrutura do Projeto

```
portfolio-marketing/
├── README.md
├── marketing.html          # Página web do projeto
├── marketing.pdf           # Relatório em PDF
├── assets/
│   └── img/
│       ├── Marketing.jpg
│       ├── Análise Campanha Marketing.png
│       └── Análise Campanha Marketing.webp
├── data/
│   └── campaigns_dataset.csv
├── scripts/
│   ├── data_cleaning.py
│   ├── statistical_analysis.py
│   └── visualization.py
└── notebooks/
    └── marketing_analysis.ipynb
```

---

## 🚀 Como Reproduzir a Análise

### Pré-requisitos

- Python 3.8+
- Bibliotecas: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`

### Executando

```bash
# Clonar repositório
git clone https://github.com/fabiotato/portfolio-marketing.git

# Instalar dependências
pip install -r requirements.txt

# Executar análise completa
python scripts/statistical_analysis.py

# Gerar visualizações
python scripts/visualization.py
```

---

## 📊 Dashboard Interativo

O projeto inclui uma página web com:

- 📈 **Gráficos de ROI por Canal**: Comparativo visual de performance
- 🎯 **Distribuição de Campanhas**: Breakdown por plataforma e formato
- 💰 **Análise de Orçamento**: Investimento vs. Retorno
- 📉 **Série Temporal**: Evolução de performance ao longo do tempo
- 🔗 **Correlações**: Heatmap de variáveis relacionadas ao ROI

---

## 👨‍💻 Autor

**Fábio Luiz de Oliveira**  
📧 fabioluol@hotmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/fabioluol/)  
🌐 [Portfólio Completo](https://portfolio-analista-dados-azure.vercel.app)

---

## 📄 Licença

Este projeto é parte do portfólio profissional de Fábio Luiz de Oliveira.  
Uso permitido para fins educacionais e de demonstração.

---

<div align="center">

**Se este projeto foi útil, dê uma ⭐!**

[⬆️ Voltar ao topo](#-análise-de-performance-de-campanhas-de-marketing-digital)

</div>
