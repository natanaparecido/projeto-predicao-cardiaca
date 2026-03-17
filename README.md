# 🫀 Predição de Doenças Cardíacas com Machine Learning

> Projeto acadêmico desenvolvido para a disciplina de Projeto e Aplicação de Mineração de Dados

![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-success)
![Azure](https://img.shields.io/badge/Azure-ML%20Studio-0078D4)

---

## 📋 Sobre o Projeto

Este projeto utiliza **Machine Learning** para prever a presença de doenças cardíacas em pacientes, baseando-se em dados clínicos.

**Desenvolvido por:** Natan Aparecido  
**Instituição:** Universidade Cidade de São Paulo  
**Curso:** Ciência de Dados

---

## 🎯 Resultados Obtidos

| Métrica | Valor |
|---------|-------|
| **Acurácia** | 84.6% |
| **Precisão** | 86.8% |
| **Recall** | 78.6% |
| **F1-Score** | 82.5% |
| **AUC-ROC** | 93.1% ⭐ |

---

## 📊 Base de Dados

- **Fonte:** [UCI Machine Learning Repository - Heart Disease](https://archive.ics.uci.edu/dataset/45/heart+disease)
- **Dataset:** Cleveland Database
- **Registros:** 303 pacientes
- **Atributos:** 14 variáveis clínicas

---

## 🛠️ Tecnologias

- **Plataforma:** Microsoft Azure Machine Learning Studio
- **Algoritmo:** Two-Class Logistic Regression
- **Tipo:** Classificação Binária

---

## 🔄 Pipeline de ML

1. ✅ Carregamento dos dados
2. ✅ Limpeza de valores faltantes (Clean Missing Data)
3. ✅ Transformação da variável target (Apply Math Operation)
4. ✅ Configuração de metadados (Edit Metadata)
5. ✅ Divisão treino/teste - 70%/30% (Split Data)
6. ✅ Treinamento do modelo (Train Model)
7. ✅ Predição (Score Model)
8. ✅ Avaliação (Evaluate Model)

---

## 📁 Estrutura do Repositório
```
projeto-predicao-cardiaca/
├── README.md                    # Você está aqui!
├── relatorio.pdf               # Relatório completo do projeto
├── images/                     # Imagens do pipeline e resultados
│   ├── pipeline-completo.png
│   ├── resultados-metricas.png
│   └── dataset-final.png
└── data/                       # Dataset utilizado
    └── processed.cleveland.data
```

---

## 💡 Aplicação Prática

Este modelo pode ser integrado a sistemas hospitalares como:
- 🏥 Ferramenta de triagem de pacientes
- ⚕️ Sistema de suporte à decisão clínica
- 📈 Dashboard de monitoramento de risco cardiovascular

---

## 📄 Documentação Completa

Para ver todos os detalhes técnicos, metodologia e análises, consulte o [relatório completo em PDF](relatorio.pdf).

---

## 📫 Contato

Se tiver dúvidas ou sugestões sobre o projeto, fique à vontade para entrar em contato!

---

⭐ **Se este projeto foi útil para você, considere dar uma estrela!**
```
