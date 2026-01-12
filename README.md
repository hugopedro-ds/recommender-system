# Sistema de Recomendação — Open Finance — QuantumFinance

> **Recommender System (PoC)** usando dados de Open Finance para sugerir produtos/serviços financeiros relevantes aos clientes.  
> Abordagem: **User-Based Collaborative Filtering** com **Similaridade do Cosseno** e **Correlação de Pearson**.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ypiJz4l5GtgyZQM-fty0Rh8cxRwpa_vJ?usp=sharing)


---

## 📌 Visão Geral
Este projeto implementa um **Sistema de Recomendação (SR)** para a fintech **QuantumFinance**, explorando dados consentidos do ecossistema **Open Finance** para gerar recomendações personalizadas.

**Objetivo de negócio**
- Aumentar relevância das ofertas (cross-sell/upsell)
- Melhorar experiência do cliente com sugestões contextualizadas
- Criar base para evolução (híbrido, conteúdo, online learning, A/B tests)

---

## 🧠 Técnica Implementada
- **Filtragem Colaborativa Baseada em Usuários (User-Based CF)**
- **Similaridade do Cosseno** (0 a 1)
- **Correlação de Pearson** (-1 a 1)

**Por que esta técnica?**
- Boa para **prova de conceito** quando há sobreposição de produtos entre clientes
- É **interpretável** e fácil de explicar para stakeholders
- Baixo custo computacional para cenários pequenos/médios

---

## 📁 Estrutura do Repositório
```open-finance-recommender/
├── notebooks/
│   └── recommendations_systems.ipynb   # Notebook principal (EDA + SR + recomendações)
├── README.md
└── .gitignore
```

## 🚀 Como executar (rápido)

### Opção A — Abrir no Google Colab
Abra o notebook principal:
- [`notebooks/recommendations_systems.ipynb`](./notebooks/recommendations_systems.ipynb)

> Dica: adicione aqui o botão **Open in Colab** para execução 1-click.



