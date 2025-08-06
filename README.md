# gpfake.py
#Olá professor! Aqui minha atividade do gpfake, dataframe.
import streamlit as st
import pandas as pd

# Estrutura da página
st.set_page_config(page_title="Gestão Patrimônio Fake", layout="wide")
st.markdown("""Esta é minha vigésima tentativa, sem o professor.""")

# Criando três colunas: esquerda, centro, direita
col1, col2, col3 = st.columns([1, 2, 1])

# Colocando o título na coluna do meio
with col2:
    st.title("Gestão Patrimonio Fake")
    st.title("")
    
#DAtaframe 

# Lê o arquivo CSV
df = pd.read_csv("dados.csv")

#formatação das palavras
import pandas as pd

# Carrega o CSV
df = pd.read_csv("dados.csv")


# Mostra a tabela de forma interativa
st.dataframe(df)
