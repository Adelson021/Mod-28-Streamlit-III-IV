# 🏦 Telemarketing Analysis

Este projeto é uma aplicação interativa construída com **Streamlit** para análise de dados de campanhas de telemarketing bancário. Permite upload de arquivos, aplicação de múltiplos filtros e visualização de métricas com gráficos e botões de download.

## LINK PARA APLICAÇÃO (LIVE)
https://mod-28-streamlit-iii-iv.onrender.com/

## 📌 Funcionalidades

- 📁 Upload de dados (`.csv` ou `.xlsx`)
- 🎯 Filtros dinâmicos com múltiplas seleções:
  - Idade (faixa etária)
  - Profissão
  - Estado civil
  - Default
  - Financiamento imobiliário
  - Empréstimo pessoal
  - Meio de contato
  - Mês da campanha
  - Dia da semana
- 📊 Visualizações com gráficos de **barras** ou **pizza**
- 💾 Download dos dados filtrados e das proporções de respostas
- 📷 Exibição de imagem na barra lateral (branding)

## 🧰 Tecnologias Utilizadas

- [Python](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [Pandas](https://pandas.pydata.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Pillow](https://python-pillow.org/)
- [xlsxwriter](https://pypi.org/project/XlsxWriter/)

## 🗂️ Estrutura Esperada dos Dados

Seu arquivo CSV ou Excel deve conter ao menos as seguintes colunas:

| Coluna         | Descrição                          |
|----------------|------------------------------------|
| `age`          | Idade do cliente                   |
| `job`          | Profissão                          |
| `marital`      | Estado civil                       |
| `default`      | Tem inadimplência?                 |
| `housing`      | Tem financiamento de imóvel?       |
| `loan`         | Possui empréstimo?                 |
| `contact`      | Meio de contato da campanha        |
| `month`        | Mês do último contato              |
| `day_of_week`  | Dia da semana do contato           |
| `y`            | Resultado da campanha (sim/não)    |

## 🚀 Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/telemarketing-analysis.git
cd telemarketing-analysis
```

2. Crie e ative um ambiente virtual:

```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

3. Instale as dependências:

```bash
pip install -r requirements.txt
```

4. Execute a aplicação:

```bash
streamlit run app.py
```

5. Acesse via navegador local: [http://localhost:8501](http://localhost:8501)

## 📦 Exemplo de `requirements.txt`

```text
streamlit
pandas
seaborn
matplotlib
Pillow
XlsxWriter
```

## 📊 Visualizações

- Gráfico de **barras** ou **pizza** para proporção de aceite (`y`)
- Comparativo entre dados **brutos** e **filtrados**
- Botões de download para as tabelas exibidas

## 🖼️ Branding

Se desejar, adicione uma imagem com o nome `Bank-Branding.jpg` na raiz do projeto para exibição na barra lateral.

## ✨ Melhorias Futuras

- Adição de novos filtros (por exemplo: educação, saldo)
- Integração com banco de dados para atualização contínua
- Exportação em PDF dos relatórios

## 👨‍💻 Autor

**Adelson** – Cientista de Dados  
🔗 [LinkedIn](https://linkedin.com/in/adelson21)  
🐙 [GitHub](https://github.com/Adelson021)

---

> Projeto feito com ❤️ para explorar dados de campanhas de telemarketing de forma simples e eficiente.


# Título do projeto

Um simples resumo do uso/propósito do projeto.

## Descrição do projeto

Um parágrafo aprofundando mais sobre o seu projeto e uma explicação geral do uso.



## Utilização

### Dependencias

* Descreve quaisquer prerequisitos, bibliotecas, versão do SO, etc., que é necessário para rodar o projeto.
* exemplo. Windows 10...

### Instalação

* Como/aonde fazer o download do seu projeto/programa
* Quaisquer modificação necessária nos arquivos/diretórios

### Executando o projeto

* Como rodar o projeto/programa
* Passo a passo em tópicos (bullet points)
```
bloco de código para os comandos necessários
```

## Ajuda

Qualquer ponto importante de problemas ou erros comuns
```
comando para rodar se o programa tiver uma informação de ajuda
```

## Autores

Nomes dos desenvolvedores do projeto e informação para entrar em contato.

ex. Lucas Serra  
ex. [@LucasSerra](https://www.linkedin.com/in/lucasserra03/)

## Histórico de versões.

* 0.2
	* Ajustes de diversos bugs e otimização
* 0.1
    * Primeira versão

## Licença de uso

Esse projeto possui licença de uso [NAME HERE] - acesse o arquivo LICENSE.md para mais detalhes.

## Fontes de inspiração

Inspiração, trechos de códigos utilizados, etc.
* [readme-template](https://gist.github.com/DomPizzie/7a5ff55ffa9081f2de27c315f5018afc)
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
* [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
* [dbader](https://github.com/dbader/readme-template)
* [zenorocha](https://gist.github.com/zenorocha/4526327)
* [fvcproductions](https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46)
