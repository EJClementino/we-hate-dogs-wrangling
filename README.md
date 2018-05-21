### Udacity Nanodegree Fundamentos de Data Science 2 - Projeto 2 (Data Wrangling)

O projeto consiste no trabalho de coleta, análise e limpeza de dados da página [WeHateDogs](https://twitter.com/dog_rates) no Twitter, bem como a geração de alguns _insights_ para os dados limpos.

Principais características:
- Todo o trabalho foi realizado num Notebook [Jupyter](http://jupyter.org/) (`wrangle_act.ipynb`)
- Arquivos de dados pré-disponibilizados: 
  - base pré-processada de tweets do WeHateDogs (`twitter_archive_enhanced.csv`)
  - processamento das imagens dos respectivos tweets usando uma rede neural para determinar a raça de cada cão (`image_predictions.tsv`)
- Arquivo `tweet-json.txt` gerado usando a biblioteca [Tweepy](http://www.tweepy.org/) para acessar a API do Twitter e obter dados complementares ao arquivo `twitter_archive_enhanced.csv` (Ex: contagem de favoritos e retweets)
- Arquivo `twitter_archive_master.csv` gerado com os dados limpos
- Arquivos `wrangle_report.pdf` e `act_report.pdf` com relatórios sobre o processo de _wrangling_ e os _insights_ descobertos.

