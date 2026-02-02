# 🎮 Análise Preditiva de Sucesso: Mercado Global de Videogames

## 1. Objetivo do Projeto
Identificação de padrões de sucesso comercial para a loja online Ice através da análise de dados históricos de vendas, avaliações de especialistas e classificações etárias (ESRB). O projeto visa prever tendências para o planeamento de campanhas publicitárias em 2017, mapeando o ciclo de vida das plataformas e as variações de consumo entre as regiões da América do Norte, Europa e Japão.

## 2. Resultado
### Mapeamento de Ciclo de Vida
Constatação de que as plataformas de videojogos possuem uma vida útil média de 5 a 10 anos até à obsolescência, com a PS4 e Xbox One a liderarem o volume de vendas no período analisado.

### Inteligência de Mercado Regional
Identificação de discrepâncias culturais significativas; enquanto o mercado ocidental (NA/EU) prioriza géneros de Ação e Tiro, o mercado japonês (JP) demonstra uma preferência consolidada por RPGs e consolas portáteis (3DS).

### Fatores de Conversão
Verificação de que as pontuações dos críticos possuem uma correlação positiva moderada com as vendas, sendo um indicador mais fiável para o sucesso comercial do que as notas dos usuários.

### Impacto da Classificação ESRB
Demonstração de que classificações etárias específicas influenciam diretamente a quota de mercado dependendo da região geográfica.

## 3. Ferramentas Utilizadas
- **Linguagem**: Python
- **Bibliotecas Principais**: Pandas (Limpeza e Processamento), Matplotlib e Seaborn (Visualização Exploratória)
- **Estatística Avançada**: SciPy.stats (Execução de testes de hipóteses)
- **Ambiente**: VS Code e Jupyter Notebook

## 4. O que Aprendi (Competências Desenvolvidas)
- **Normalização de Dados**: Padronização de nomes de colunas (snake_case) e conversão de tipos de dados para otimização de memória
- **Tratamento de Inconsistências (TBD)**: Gestão da abreviação "TBD" (to be determined) através da conversão para valores nulos (NaN), permitindo a execução de cálculos estatísticos sem corrupção da amostra
- **Análise Comparativa Regional**: Construção de perfis de usuário detalhados por região (AN, UE, JP)
- **Testes de Hipóteses Científicas**: Aplicação do Teste t de Student para validar as seguintes suposições:
  - Hipótese 1: As classificações médias dos usuários das plataformas Xbox One e PC são iguais ($H_0: \mu_1 = \mu_2$)
  - Hipótese 2: As classificações médias de usuários para os géneros Action e Sports são diferentes ($H_0: \mu_1 = \mu_2$ vs $H_1: \mu_1 \neq \mu_2$)

## 5. Melhorias Futuras
- **Análise de Churn de Plataformas**: Previsão de quando os usuários migrarão totalmente para as consolas de próxima geração
- **Web Scraping**: Integração de dados em tempo real via API do Metacritic para enriquecer a análise de pontuações
- **Análise de Preços**: Inclusão do impacto de promoções e preços de lançamento na velocidade de vendas (sell-through)
