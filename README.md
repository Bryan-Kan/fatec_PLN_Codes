# Fatec Processamento de Linguagem Natural (PLN)

Este repositório contém os códigos das aulas pratricas de PLN da FATEC Mauá, sob as orientações do professor Rodolfo Lovera.

## Funcionalidades:

Fundamentos de PLN: Tokenização, segmentação e semântica;

Pré-processamento de texto: Limpeza, normalização, remoção de stopwords, stemming e lematização;

Representação de texto: Técnicas de Bag of Words, TF-IDF e embeddings (Word2Vec, GloVe, FastText).

## Tecnologias e Ferramentas:

Linguagem: Python

Bibliotecas: spaCy, NLTK, Gensim, re e scikit-learn

Ambiente: Google Colab

## Estrutura do Repositório e Descrição das Aulas

Cada pasta do contem uma aula que esta feita no google colab, que contem as atividades práticas realizadas no dia.

## Resumo do Conteudo

Aula 2 - Fundamentos da linguística: exemplos práticos de tokenização, segmentação e semântica. Utiliza as bibliotecas spaCy, NLTK, e Gensim para analisar texto em inglês e português (spaCy), tokenizar sentenças e palavras (NLTK) e treinar modelos Word2Vec para vetorização semântica (Gensim). Os exemplos incluem processamento de textos e construção de modelos semânticos simples.

Aula 3 - Bibliotecas e Corpora: Uso da biblioteca NLTK para manipulação de corpora (Machado e Brown), contagem e análise de frequências de palavras, remoção de palavras irrelevantes e tokenização de duas formas diferentes (word_tokenize e TweetTokenizer). Os exemplos no código demonstram técnicas básicas para análise de texto em PLN.

Aula 4 - Limpeza de dados textuais: Limpeza e normalização de textos para remover ruídos, eliminar caracteres especiais e ajustar letras maiúsculas e minúsculas. Abrange tokenização, remoção de stopwords e aplicação de stemming e lematização para simplificar palavras. Inclui exemplos práticos de preparação de textos em PLN.

Aula 5 - Representação de texto: Representação de textos com Bag of Words (BoW) usando CountVectorizer para criar matrizes de frequência de palavras. Comparação entre BoW e TF-IDF com TfidfVectorizer para calcular frequências ponderadas. Integração da limpeza de dados com a representação BoW para gerar matrizes vetorizadas. Inclui exemplos práticos utilizando scikit-learn, NLTK e re.

Aula 6 - Representação de texto com Embeddings: Técnicas de embeddings com Word2Vec, GloVe e FastText para representar palavras em vetores e analisar relações semânticas. Inclui treinamento de embeddings em português para calcular similaridades (Word2Vec), uso de embeddings pré-treinados em inglês para identificar relações e listar palavras próximas (GloVe) e análise de similaridade com embeddings pré-treinados em português (FastText).

## Como Executar os Códigos do Repositório

Recomenda-se a utilização da plataforma Google Colab para a execução dos notebooks. Para executar os códigos presentes no repositório:

Acesse um dos notebooks dentro das pastas do repositório;
No topo do notebook, clique em Open in Colab;
Clique no botão de play à esquerda dos trechos de código;
Se solicitado, fazer login com uma conta do Google.
Com o login realizado, você pode executar o código já escrito ou realizar alterações temporárias para testar as funcionalidades. Caso queira salvar uma cópia do código para você:

No topo superior esquerdo, clique em Copiar para o Drive.
Com uma cópia salva no Google Drive, quaisquer alterações que você realizar serão salvas automaticamente na sua conta do Google.

Desenvolvido por Bryan Braggion Pimentel de Lima.
