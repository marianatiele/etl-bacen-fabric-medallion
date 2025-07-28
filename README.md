# ETL Bacen com Microsoft Fabric e Arquitetura Medallion

Este projeto realiza um pipeline de dados completo usando a API do Banco Central (Bacen), desenvolvido na plataforma Microsoft Fabric com a arquitetura Medallion (Bronze, Silver e Gold). O objetivo é extrair, tratar e organizar dados financeiros para análises e relatórios.

---

## 🔧 Tecnologias Utilizadas

- **Microsoft Fabric**
- **API do Banco Central (Bacen)**
- **Spark (Notebooks no Fabric)**
- **Lakehouse com arquitetura Medallion**
- **Power BI**

---

## 📊 Arquitetura do Projeto

A arquitetura Medallion é dividida em três camadas principais:

- **Bronze**: Dados brutos extraídos da API do Bacen
- **Silver**: Dados limpos e estruturados
- **Gold**: Dados prontos para análise e consumo em dashboards

> Veja o fluxo completo na imagem abaixo:  
<img width="759" height="328" alt="image" src="https://github.com/user-attachments/assets/33a6cf00-91c2-4ee9-a990-f582fcd9c105" />


---

## 📦 Pipeline de ETL

1. **Extração**: Coleta de dados da API do Bacen via chamadas REST
2. **Transformação**: Tratamento e organização com Spark no Fabric
3. **Carga**: Salvamento dos dados tratados nas camadas Silver e Gold do Lakehouse

---

## ▶️ Como Executar

1. Clone este repositório
2. Configure o notebook no Microsoft Fabric
3. Execute as etapas do pipeline
4. Visualize os dados no Power BI (opcional)

---



