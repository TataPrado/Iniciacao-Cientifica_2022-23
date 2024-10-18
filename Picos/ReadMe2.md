"Com os gráficos de Azimutal versus 2θ, extraídos do tratamento de imagens com o repositório já existente no Git Hub, 
o foco posterior foi a análise em função do eixo azimutal pensada com o intuito de observar a orientação preferencial, 
comparando intensidades relativas dos picos com intensidades teóricas e a distribuição desses no eixo azimutal. 
Todo material policristalino é composto por grãos individuais, ou seja, cristais com uma estrutura ordenada. A maneira
como esses grãos se organizam pode resultar em uma distribuição não aleatória de suas orientações cristalográficas, ou
seja, certas direções ou planos cristalográficos são mais frequentemente orientados em uma determinada direção. 
Orientações preferenciais afetam as propriedades elétricas, magnéticas e mecânicas do material, disso se dá a importância 
de se analisar tal parâmetro.

Os dados retirados pelo gráfico foram colocados em formato de tabela, com cada linha sendo uma das 360
seções (1 seção = 1 grau) dos anéis (eixo azimutal) e cada coluna sendo uma das divisões do valor de 2θ. Com
a tabela extraı́da, figura 6, a determinação dos picos para um valor 2θ fixo foi feita através da biblioteca scipy
do Python, onde os picos seriam os maiores valores em colunas sequenciais somadas da tabela. A partir disso,
foi extraı́do um gráfico de Intensidade versus Azimutal para cada pico encontrado e definido sua fase e plano
cristalográfico."

Além dos gráficos que deixam os resultados mais intuitivos, "A partir dos gráficos de Intensidade versus 2θ, 
é possı́vel encontrar informações que são essenciais paraanálises cristalográficas. Primeiramente, o FWHM ou 
Full Width at Half Maximum é uma medida da largura de um pico de difração em um espectro [...] o FWHM pode 
ser relacionado com a densidade de defeitos cristalinos no material. 2θ, é o ângulo de difração dos raios X 
e é medido entre o raio incidente e o raio difratado. As posições angulares dos picos de difração estão 
relacionadas com as distâncias interatômicas na estrutura cristalina. Sua análise, portanto, permite determinar
as distâncias interatômicas na rede cristalina. Por fim, a área do pico de difração é uma medida da quantidade 
total de intensidade difratada para cada pico e é proporcional à quantidade do material que contribui para a 
difração naquele ângulo. Portanto, a área dos picos é usada para quantificar a fração das fases cristalinas 
em uma amostra. Todos esses valores são passı́veis de análise nos gráficos de Intensidade versus 2θ e foram a
base para a utilização do método de Williamson-Hall." Método de Williamson-Hall apresentado na outra pasta do 
repositório.
