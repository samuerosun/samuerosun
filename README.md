<p align=center> <a href="http://portal.math.marketing"> <img width="200" src="http://portal.math.marketing/assets/img/logo-math-home.png"/> </a> <br> <br>   
  <span>API de importação de dados do Google Analitycs do cliente, que apresenta, em um data frame, as dimensões e métricas da campanhas e as insere num banco de dados SQL.
  Peça integrante do produto de gestão de marketing desenvolvido pela <a href= "https://math.management/">Math</a></span> 
  
<p align=center> 
  <a href="https://www.python.org/downloads/release/python-3107/" rel="nofollow"><img alt="python" src="https://img.shields.io/badge/Python-3.10-blue.svg"></a> 
  <a href="https://learn.microsoft.com/pt-br/azure/azure-functions/functions-run-local?tabs=v4%2Cwindows%2Ccsharp%2Cportal%2Cbash#v2" rel="nofollow"><img alt="azure" src="https://img.shields.io/badge/Azure Functions-4.x-blue.svg"></a> 
  <a href="https://www.microsoft.com/pt-br/sql-server/sql-server-downloads" rel="nofollow"><img alt="sql_server" src="https://img.shields.io/badge/SQL Server-ODBC Driver %5E17-blue.svg"></a> 
  <a href="" rel="nofollow"><img alt="GCP" src="https://img.shields.io/badge/Google Cloud Platform--blue.svg"></a> 
<br> </p> </p>

# Sobre o Projeto

Math Manangement -  Aplicativo de acompanhamento e gestão de campanhas de mídia baseado em brandformance, desempenho e comportamento de usuários, atribuição e jornadas de conversão.

# Funcionalidades

- Dimensões e Métricas ajustáveis para cada cliente.
- TimeTrigger scheduler embedded. <br>
- Conexão com Google Cloud Platform. <br>
- Conexão com SQL Server.

# Instalação

```
# clonar o repositório
$ git clone https://mathops.visualstudio.com/Math_AdsTech/_git/Importadores%20Python

# instale Virtualenv
$ py -m venv .venv

# ative a '.venv'
$ ./.venv/Scripts/activate

# instale o arquivo 'requirements.txt'
$ pip install -m requirements.txt

# caso tenha problemas na instalação das bibliotecas do arquivo, instale manualmente as 3 bibliotecas necessárias para esta rotina:
$ pip install --upgrade google-api-python-client
$ pip install oauth2client
$ pip install SQLAlchemy==1.4.32

```  
# Licença
<font style="arial"> MIT © Portal Math<br/> Criador Original - <a href= "https://github.com/Lukkas76">Lucas Moreira</a> </font>

<!--  -->
