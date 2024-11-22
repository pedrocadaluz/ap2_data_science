# Streamlit Finance: Visualização e Análise de Indicadores para Seleção de Ações e Geração de Gráficos
Uma ferramenta interativa para análise e visualização de dados financeiros, que permite a comparação de ações baseada em indicadores de rentabilidade e desconto.

## 📝 Sobre o Projeto
Este projeto foi uma prova da disciplina de Projetos de Ciência de Dados I e tem como objetivos permitir:

1) A visualização de ações e indicadores financeiros numa data determinada pelo usuário.
2) A geração de uma carteira, formada por um número de ações determinado pelo usuário, utilizando indicadores financeiros e o cálculo do retorno dessa carteira num período.
3) O cálculo do retorno do Ibovespa num período.
4) A comparação do retorno da carteira gerada e do Ibovespa num mesmo período, com visualização através de gráficos.

## Tecnologias Utilizadas
Este projeto foi desenvolvido utilizando as seguintes tecnologias:

* Python - Linguagem de programação.
* Streamlit - Biblioteca Python para o compartilhamento de aplicativos da web

## 💹 Indicadores Financeiros
### 📈 Indicadores de Rentabilidade
- ROE (Return on Equity): Mede a eficiência da empresa em gerar lucro com o capital próprio.
- ROIC (Return on Invested Capital): Avalia a rentabilidade sobre o capital total investido, incluindo dívidas.
- ROC (Return on Capital): Calcula a eficiência na utilização de todo o capital disponível.
### 💰 Indicadores de Desconto
- Earning Yield: Mede o retorno gerado pelos lucros em relação ao preço da ação.
- Dividend Yield: Indica a rentabilidade dos dividendos pagos pela empresa em relação ao preço da ação.
- P/VP (Preço sobre Valor Patrimonial): Compara o valor de mercado da empresa com seu valor contábil.
### 📊 Comparativos Gráficos
- Gráficos Comparativos: Mostram a performance das ações selecionadas com base nos indicadores.
- Ibovespa: O principal índice da Bolsa de Valores do Brasil, que mede o desempenho médio das ações mais negociadas. A aplicação permite visualizar o Ibovespa isoladamente ou compará-lo com as ações selecionadas.


## 🚀 Execução do Projeto

### ⚙️ Passo 1: Iniciar o Ambiente Virtual
Antes de executar o projeto, inicie um ambiente virtual para garantir que as dependências sejam instaladas de forma isolada:

Criar o ambiente virtual:
- Abra o seu prompt
- python -m venv nome_ambiente_virtual

Ativar o ambiente virtual:
 No Windows:
 - cmd
 - nome_ambiente_virtual\Scripts\activate

No Linux/Mac:
 bash
 - source nome_ambiente_virtual/bin/activate


### 📦 Passo 2: Instalar Dependências
Com o ambiente virtual ativado, instale as dependências listadas no arquivo requirements.txt:

- cmd
- pip install -r requirements.txt


### 🛠️ Passo 3: Como acessar a API

1- Acesse o site https://laboratoriodefinancas.com/home e faça seu cadastro para gerar o Token de acesso;
2- Copie o token e crie um arquivo .env e armazene essa informação dentro nele no formato: token = 'seu token aqui';
3- Selecione o período desejado de análise nos parâmetros das API's no arquivo api.py;
4- Rode o código e verifique a análise da carteira, ação e comparações.


### ▶️ Passo 4: Executar a Aplicação
Para iniciar a aplicação, execute o arquivo principal app.py utilizando o Streamlit:

- cmd
- streamlit run app.py
Após isso, a aplicação estará disponível no navegador no endereço padrão:
🌐 http://localhost:8501

## 🌟 Conclusão
Com este projeto, você pode analisar ações de forma intuitiva e comparar seus desempenhos com base nos principais indicadores financeiros. Com a geração de gráficos claros e informativos, fica mais fácil compreender e visualizar os dados. Explore, analise e tome decisões mais embasadas! 🚀


## 📘 Este é um trabalho desenvolvido pelos alunos de Ciência de Dados do Ibmec - DF
### 👩‍💻 Alunos responsáveis pelo projeto:

### 🚀 Emanuel Marques Pereira
📧 Email: emanuelaluno.ti@gmail.com
🐈‍ GitHub: emanuelmarqs
🔗 LinkedIn: Emanuel Marques

### 🌟 Júlia Félix Giannandrea
📧 Email: juliafgiannandrea@gmail.com
🐈‍ GitHub: juliafgiannandrea
🔗 LinkedIn: Júlia Félix Giannandrea

### 🚀 Pedro Arthur da Luz Miranda
📧 Email: pedrocadaluz@gmail.com
🐈‍ GitHub: pedrocadaluz
🔗 LinkedIn: Pedro Arthur da Luz Miranda
