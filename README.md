<h1 align="center">Web Scraping- Análise de Indicadores Econômicos do Brasil 
</h1>

<p align="center">
  <img alt="logo" title="" src="https://hasdata.com/assets/cache_image/assets/components/images/blog/web-scraping_2560x1067_819.webp" width="400px"/>
</p>

---

#### 📘 Repositório do Trabalho

Este repositório foi desenvolvido como parte do segundo período do curso de Gestão de Dados da Universidade Federal do Piauí (UFPI), na disciplina de Análise de Dados.

---

#### 🎯 Proposta

O objetivo deste trabalho é realizar a análise dos indicadores econômicos do Brasil disponíveis no portal do [IBGE](https://www.ibge.gov.br/indicadores.html). Utilizamos técnicas de raspagem de dados (web scraping) com Python e BeautifulSoup para coletar informações como IPCA, INPC, PIB, entre outros. A automação deste processo elimina erros humanos, como o esquecimento de valores ou zeros.

---

#### 🛠️ Etapas

1. **Importação de Bibliotecas e Raspagem de Dados:**
   - BeautifulSoup para análise HTML 🖥️
   - Requests para requisições HTTP 🌐
   - Html5lib como analisador HTML 📄
   - Pandas para manipulação e estruturação dos dados 📊

2. **Raspagem de Dados por Indicador:**
   - Para cada indicador econômico, seguimos um padrão de raspagem, obtendo valores como o último valor, valor anterior, valor nos últimos 12 meses e valor no ano.

3. **Combinação dos Dados em um DataFrame Único:**
   - Os dados coletados foram combinados em um único DataFrame para facilitar a análise e manipulação.

4. **Exportação dos Dados:**
   - Os dados coletados são exportados para um arquivo CSV 📤

---

#### 📈 Tomada de Decisão

Para gerenciar a volatilidade dos indicadores econômicos, é fundamental implementar um sistema robusto de monitoramento contínuo e análise frequente. Bancos centrais e investidores podem se beneficiar ao adaptar suas estratégias com base em indicadores-chave, como o IPCA.

---

#### 🚀 Estímulo ao Crescimento e Ações Recomendadas

**Dashboard de Indicadores:**

- **Power BI:** Os dados coletados são exportados para um arquivo CSV, que pode ser facilmente integrado ao Power BI para visualização e análise dos indicadores econômicos 📊

- **Dashboard Personalizado em Python:** Utilizando a biblioteca Matplotlib, é possível criar um dashboard customizado. Este pode ser implantado em um local estratégico da empresa, promovendo transparência e incentivando a equipe a melhorar seus indicadores corporativos, como OKRs (Objectives and Key Results).

**Medidas para Estímulo ao Crescimento:**

- **Investimentos em Infraestrutura:** Programas de infraestrutura, como construção de estradas, podem ser promovidos pelo governo para impulsionar o setor da construção civil e gerar empregos 🏗️

- **Incentivo à Pesquisa e Inovação:** Subsídios e apoio à pesquisa em setores de alta tecnologia, como TI, podem ser adotados para fomentar a inovação e impulsionar o crescimento econômico 🚀

---

#### 📚 Referências

1. [BeautifulSoup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
2. [Requests Documentation](https://docs.python-requests.org/en/latest/)
3. [Html5lib Documentation](https://html5lib.readthedocs.io/en/latest/)
4. [Pandas Documentation](https://pandas.pydata.org/docs/)
5. [IBGE - Portal de Indicadores Econômicos](https://www.ibge.gov.br/indicadores.html)

---
#### ✍️ Autoras

- Bruna Lorena
- Kedma Freire
  
#### 📜 Licença

Este projeto está sob as licenças:

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

---


