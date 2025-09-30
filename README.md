![Imagem inicial](/content/IMG/analise_de_sentimento_img.png)
# 📊 Processamento de Linguagem Natural | Análise de Sentimentos.
#### ______________________________________________________________________________________________________________________
## 🔍 Objetivo do projeto:

* #### Este projeto tem como foco o aprimoramento de técnicas de Processamento de Linguagem Natural (NLP) aplicadas a dados textuais em DataFrames. Foram implementados os métodos Bag of Words e TF-IDF, a fim de transformar textos em representações numéricas adequadas para modelos de aprendizado de máquina.

Etapas Realizadas

Pré-processamento dos textos, incluindo:

remoção de pontuações e caracteres especiais;

normalização para caixa baixa (lowercasing);

eliminação de termos de baixa relevância semântica (stopwords, preposições e adjetivos pouco informativos).

Essas etapas têm como objetivo reduzir ruídos, melhorar a qualidade dos dados e potencializar a eficiência dos algoritmos de análise de sentimentos.


# 🌩️ Nuvem de Palavra Negativa

![gráfico de barras](h/content/IMG/nuvem_de_palavra_negativa.png)

#### A imagem acima demonstra uma série de palavras distribuidas em que foram destacadas em avaliações negativas. A frequência da palavra é diretamente proporcional ao tamanho da imagem acima.

# ☁️ Nuvem de Palavra Negativa

![gráfico de barras](/content/IMG/nuvem_de_palavra_positiva.png)

#### A imagem acima demonstra uma série de palavras distribuidas em que foram destacadas em avaliações positivas. A frequência da palavra é diretamente proporcional ao tamanho da imagem acima.

# 🛠️ Tratamento do texto

![gráfico de barras](/content/IMG/tratamentos.png)

### A imagem acima demontra os tratamentos realizados antes de aplicar o modelo.

* #### Tratamento 1.   Remoção de Stopwords.

* #### Tratamento 2.   Remoção de Pontuação.

* #### Tratamento 3.   Remoção de Acentuação.

* #### Tratamento 4.   Deixar o texto todo em caixa baixa.

* #### Tratamento 5.   Redução das palavras ao seu radical.

# 🛠️ Previsão dos Sentimentos

![gráfico de barras](/content/IMG/previsao_sentimento.png)

#### A imagem acima demonstra o modelo prevendo a avaliação de futuros comentários dos produtos por clientes.


# ✔️ Conclusão

Ao final do projeto, foram definidos os parâmetros ideais para o processamento de texto e implementado um pipeline automatizado. Esse fluxo realiza o pré-processamento dos dados, aplica a vetorização TF-IDF e utiliza o modelo treinado para gerar previsões de sentimento em novas atualizações de produtos.

Os resultados demonstraram que o modelo atingiu uma acurácia de 85,32%, classificando corretamente a maior parte dos dados inéditos. Esse desempenho comprova a robustez e capacidade de generalização do pipeline de NLP desenvolvido.

Além disso, essa etapa final evidencia a importância de manter um processo automatizado, escalável e reprodutível, garantindo consistência e eficiência em futuras atualizações de dados.
