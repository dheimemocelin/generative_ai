# Projeto Didático: Explorando IA Generativa em um Pipeline de ETL com Python

Este projeto didático tem como objetivo demonstrar a aplicação de IA generativa em um pipeline de ETL (Extração, Transformação e Carregamento) usando a linguagem Python. A proposta é obter dados de usuários por meio da API da Santander Dev Week 2023 e, em seguida, gerar notícias de IA personalizadas para cada usuário com a API OpenAI. O resultado final será armazenado em um arquivo JSON e os dados atualizados serão enviados de volta para a API da Santander Dev Week.

## Bibliotecas Utilizadas

- [pandas](https://pandas.pydata.org/): Para manipulação de dados em formato de DataFrame.
- [requests](https://docs.python-requests.org/en/master/): Para fazer solicitações HTTP para a API.
- [json](https://docs.python.org/3/library/json.html): Para manipulação de dados JSON.
- [random](https://docs.python.org/3/library/random.html): Para seleção aleatória de mensagens de marketing.
- [openai](https://beta.openai.com/docs/): Para interagir com a API GPT-3.5-turbo da OpenAI.

## Passos do Projeto

### 1. Extração de Dados

- Lê uma planilha CSV contendo os IDs dos usuários.
- Utiliza a API da Santander Dev Week para obter detalhes dos usuários com base em seus IDs.
- Combina dados reais dos usuários com dados fictícios para criar uma lista completa de usuários.

### 2. Preparação de Mensagens de Marketing

- Seleciona aleatoriamente mensagens de marketing relacionadas a investimentos financeiros para cada usuário.

### 3. Geração de Notícias de IA Personalizadas

- Utiliza a API GPT-3.5-turbo da OpenAI para gerar notícias de IA personalizadas.
- As notícias são geradas com base no nome de cada usuário e na importância dos investimentos.

### 4. Armazenamento de Dados

- Salva os dados atualizados em um arquivo JSON.
- Os dados incluem informações dos usuários, mensagens de marketing e notícias de IA geradas.

### 5. Atualização dos Dados na API

- Envia os dados atualizados de volta para a API da Santander Dev Week para manter as informações dos usuários.

## Considerações Finais

Este projeto didático demonstra a aplicação de tecnologias como ETL, IA generativa e integração com APIs para criar um sistema que combina dados reais e fictícios de usuários bancários. É importante lembrar que os dados fictícios foram usados apenas para fins de ilustração e aprendizado.

**Observação:** Certifique-se de ter as bibliotecas instaladas e substitua as chaves de API e caminhos de arquivos pelos valores reais antes de executar o código.

Esperamos que este projeto seja útil para explorar a aplicação de IA generativa em pipelines de ETL e para aprimorar suas habilidades em Python.

*Este projeto é apenas didático e não deve ser utilizado em um ambiente de produção sem considerar questões de segurança e privacidade dos dados.*
