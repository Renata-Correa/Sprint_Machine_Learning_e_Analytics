# Ciencia de Dados e Analytics
*Este é um conjunto de dados de faixas do Spotify abrangendo 125 gêneros diferentes. Cada faixa possui alguns recursos de áudio associados. Os dados estão no formato CSV, que é tabular, e pode ser carregado rapidamente.*

## Sobre o Conjunto de Dados
### Uso
*O conjunto de dados pode ser usado para:*
Construir um Sistema de Recomendação com base em alguma entrada ou preferência do usuário. Finalidades de classificação com base em recursos de áudio e gêneros disponíveis. Qualquer outra aplicação que você possa imaginar. Sinta-se à vontade!

### Descrição da coluna

- **track_id** : O ID do Spotify para a faixa.
- **artists** : Os nomes dos artistas que executaram a faixa. Se houver mais de um artista, eles serão separados por um **;** .
- **album_name** : O nome do álbum em que a faixa aparece.
- **track_name** : Nome da faixa.
- **popularity** : A popularidade de uma faixa é um valor entre 0 e 100, sendo 100 o mais popular. A popularidade é calculada por algoritmo e se baseia, em grande parte, no número total de reproduções da faixa e em quão recentes essas reproduções são. De modo geral, músicas que estão sendo muito tocadas agora terão uma popularidade maior do que músicas que foram muito tocadas no passado. Faixas duplicadas (por exemplo: a mesma faixa de um single e de um álbum) são classificadas de forma independente. A popularidade do artista e do álbum é derivada matematicamente da popularidade da faixa.
- **duration_ms** : A duração da trilha em milissegundos.
- **explicit** : Se a faixa tem ou não letras explícitas (verdadeiro = sim, tem; falso = não, não tem OU desconhecido).
- **danceability** : A dançabilidade descreve o quão adequada uma faixa é para dançar com base em uma combinação de elementos musicais, incluindo andamento, estabilidade rítmica, força da batida e regularidade geral. Um valor de 0,0 é o menos dançante e 1,0 o mais dançante.
- **energy** : Energia é uma medida de 0,0 a 1,0 e representa uma medida perceptual de intensidade e atividade. Normalmente, faixas energéticas parecem rápidas, altas e barulhentas. Por exemplo, o death metal tem alta energia, enquanto um prelúdio de Bach tem pontuação baixa na escala.
- **key** : A chave em que a faixa está. Os números inteiros são mapeados para alturas usando a notação padrão de Classe de Altura. Ex 0 = C.: , 1 = C♯/D♭, 2 = D, e assim por diante. Se nenhuma chave for detectada, o valor será -1.
- **loudness** : A intensidade sonora geral de uma faixa em decibéis (dB).
- **mode** : O modo indica a modalidade (maior ou menor) de uma faixa, o tipo de escala da qual seu conteúdo melódico é derivado. Maior é representado por 1 e menor por 0.
- **speechiness** : Speechiness detecta a presença de palavras faladas em uma faixa. Quanto mais exclusivamente semelhante à fala for a gravação (por exemplo: talk show, audiolivro, poesia), mais próximo de 1,0 será o valor do atributo. Valores acima de 0,66 descrevem faixas que provavelmente são compostas inteiramente de palavras faladas. Valores entre 0,33 e 0,66 descrevem faixas que podem conter música e fala, em seções ou em camadas, incluindo casos como rap. Valores abaixo de 0,33 provavelmente representam música e outras faixas que não se assemelham à fala.
- **acousticness** : Uma medida de confiança de 0,0 a 1,0 para determinar se a faixa é acústica. 1,0 representa alta confiança de que a faixa é acústica.
- **instrumentalness** : Prevê se uma faixa não contém vocais. Sons de "Ooh" e "aah" são tratados como instrumentais neste contexto. Faixas de rap ou palavra falada são claramente "vocais". Quanto mais próximo o valor de instrumentalidade estiver de 1,0, maior a probabilidade de a faixa não conter conteúdo vocal.
- **liveness** : Detecta a presença de público na gravação. Valores mais altos de liveness representam uma probabilidade maior de que a faixa tenha sido gravada ao vivo. Um valor acima de 0,8 fornece uma forte probabilidade de que a faixa seja ao vivo.
- **valence** : Uma medida de 0,0 a 1,0 que descreve a positividade musical transmitida por uma faixa. Faixas com alta valência soam mais positivas (por exemplo: felizes, alegres, eufóricas), enquanto faixas com baixa valência soam mais negativas (por exemplo: tristes, deprimidas, raivosas).
- **tempo** : O tempo estimado geral de uma faixa em batidas por minuto (BPM). Na terminologia musical, o tempo é a velocidade ou o ritmo de uma determinada peça e deriva diretamente da duração média da batida.
- **time_signature** : Uma fórmula de compasso estimada. A fórmula de compasso (métrica) é uma convenção de notação para especificar quantas batidas existem em cada compasso. A fórmula de compasso varia de 3 a 7, indicando fórmulas de compasso de 3/4, a 7/4.
- **track_genre** : O gênero ao qual a faixa pertence.
  # 
