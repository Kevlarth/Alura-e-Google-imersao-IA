## Sumarização e Extração de Trechos Relevantes de Artigos em PDF

Este script Python utiliza o Gemini Pro, um modelo de linguagem extenso do Google, para gerar resumos concisos de artigos em PDF e identificar trechos relevantes com base em um tópico de interesse fornecido pelo usuário.

**Funcionalidades:**

- Extrai texto de arquivos PDF.
- Pré-processa o texto utilizando NLTK e BeautifulSoup.
- Gera resumos de artigos utilizando o Gemini Pro.
- Calcula a similaridade lexical entre o tópico de interesse e o resumo do artigo usando TF-IDF e similaridade de cosseno.
- Identifica trechos relevantes no artigo com base na similaridade com o tópico de interesse.

**Bibliotecas Utilizadas:**

- PyPDF2
- beautifulsoup4
- nltk
- scikit-learn
- google-generativeai
- requests

**Como Usar:**

1. Certifique-se de ter todas as bibliotecas necessárias instaladas.
2. Configure sua chave de API do Google (`GOOGLE_API_KEY`).
3. Execute o script.
4. Insira o tópico de interesse e a URL do artigo em PDF.

**Saída:**

O script irá apresentar a similaridade lexical entre o tópico de interesse e o resumo do artigo, seguido pelos trechos relevantes identificados no artigo.

**Observação:**

Este script requer acesso à API do Gemini Pro.
