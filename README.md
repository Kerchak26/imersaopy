# Imersão Python - Dashboard de Salários na Área de Dados

Este projeto faz parte do conteúdo inicial da Imersão Python e apresenta um dashboard interativo para análise de salários na área de dados.

## 📌 Sobre o projeto

O aplicativo utiliza um conjunto de dados de salários em tecnologia e apresenta visualizações com filtros dinâmicos. A ideia é explorar as etapas básicas da imersão:

- carregar dados com `pandas`
- criar filtros e layout com `streamlit`
- gerar gráficos interativos com `plotly`
- trabalhar com análise exploratória e métricas simples

## 🚀 Como rodar o projeto

1. Abra o terminal na pasta do projeto:

```powershell
cd "c:\Users\Admin\OneDrive\Área de Trabalho\imersaopy"
```

2. Ative o ambiente virtual (caso ainda não esteja ativo):

```powershell
& ".venv\Scripts\Activate.ps1"
```

3. Instale as dependências:

```powershell
pip install -r requirements.txt
```

4. Execute a aplicação Streamlit:

```powershell
streamlit run app.py
```

5. Abra o endereço exibido no terminal (normalmente `http://localhost:8501`).

## 🧰 Stacks utilizadas

- Python
- Streamlit
- Pandas
- Plotly

## 📁 Arquivos principais

- `app.py` - aplicativo Streamlit com filtros, métricas e gráficos
- `requirements.txt` - dependências do projeto

## 💡 Sugestões de melhorias

- adicionar tratamento de erros quando o `DataFrame` estiver vazio ou quando a conexão com a fonte de dados falhar
- permitir carregar dados de um arquivo local em vez de depender de uma URL externa
- adicionar mais gráficos, como evolução de salários ao longo do tempo ou comparação por localidade
- melhorar a interface com seções explicativas e dicas de uso dos filtros
- incluir testes simples para validação dos dados e das funções de análise
- criar uma versão com exportação de relatórios ou download de tabelas filtradas

---

### Observação

O `app.py` carrega os dados diretamente de um arquivo CSV hospedado no GitHub, portanto é necessário acesso à internet para rodar o dashboard corretamente.
