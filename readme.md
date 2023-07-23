# Análise do mercado de games
## Introdução
O presente projeto tem por objeto as avaliações de usuários e especialistas, gêneros, plataformas, por exemplo, Xbox ou PlayStation, e dados históricos sobre vendas de jogos estão disponíveis em fontes abertas. Tendo como intuito identificar padrões que determinam se um jogo tem sucesso ou não. Isso permitirá identificar potenciais grandes vencedores e planejar campanhas publicitárias.

O conjunto de dados contém a abreviatura ESRB. O Entertainment Software Rating Board avalia o conteúdo de um jogo e atribui uma classificação etária, como Adolescente ou Maduro.

# Descrição de dados:

- Name (nome);
- Platform (plataforma);
- Year_of_Release (Ano de lançamento);
- Genre(gênero);
- NA_sales (vendas norte-americanas em milhões de USD);
- EU_sales (vendas na Europa em milhões de USD);
- JP_sales (vendas no Japão em milhões de USD);
- Other_sales (vendas em outros países em em milhões de USD);
- Critic_Score - (Pontuação crítica) (máximo de 100);
- User_Score - (Pontuação do usuário) (máximo de 10);
- Classificação (ESRB).

# Preparação dos dados

- Substituir os nomes das colunas (transformar tudo em minúsculos).
- Converter os dados para os tipos necessários.
- Descrever as colunas onde os tipos de dados foram alterados e por quê.


# Análise dos dados

- Ver quantos jogos foram lançados em anos diferentes e se os dados de cada período são significativos?
- Ver como as vendas variaram de plataforma para plataforma.
- Escolher as plataformas com as maiores vendas totais e construir uma distribuição com base em dados para cada ano.
- Encontrar as plataformas que costumavam ser populares, mas agora não têm vendas.
- Quanto tempo leva para as novas plataformas aparecerem e as antigas desaparecerem?
- Determinar para qual período se deve pegar dados. 
- Os dados devem permitir construir um modelo para 2017.
- Quais plataformas estão liderando em vendas? Quais estão crescendo ou diminuindo? Selecione várias plataformas potencialmente lucrativas.
- As diferenças nas vendas são significativas? E quanto às vendas médias em várias plataformas? 

# Conclusão

Não houveram, dados o suficiente para embasar uma decisão a respeito da interferência das classificações dos jogos e a venda em determinadas regiões, em boa parte delas jogos com classificação pendente ("RP") estão na frente das vendas. Logo, fica obscura a análise de fator. Como demonstrado no gráfico de correlação e na matrix de correlação. 

E por último foram testadas 2 hipóteses a respeito das classificações médias dos usuários. As hipóteses foram: 

* 1) As classificações médias dos usuários das plataformas Xbox One e PC são iguais.
* 2) As classificações médias de usuários para os gêneros Action (ação) e Sports (esportes) são iguais.


A primeira hipótese foi rejeitada, enquanto a segunda não foi rejeitada, o que significa que as médias dos usuários dos jogos to gênero Action e Sports não possuem a média com diferenças estatisticamente significativas. 

Posto isso, concluí-se que os jogos da plataforma Playstation(Sony), são mais populares frente aos concorrentes. Os jogos do tipo Ação, Esportes e Tiro, geraram mais receitas no decorrer dos anos. Portanto, é interessante dar mais atenção a esses estilos, não esquecendo também de outros estilos como RPG, por exemplo, a depender da região.

As plataformas da Sony apresentam um comportamento mais estável que as outras plataformas, como por exemplo, nos números abordados pelos gráficos de linha onde os consoles das Sony, sempre mantiveram-se na vantagem economica, onde ou terminavam seu cíclo com maior receita, ou terminava seu cíclo anos após as outras plataformas, seja em lanãmentos como o caso do PS2 ou em receita. 