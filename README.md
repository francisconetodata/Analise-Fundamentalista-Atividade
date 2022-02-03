# Proposta de script para artigo da disciplina de análise fundamentalista - 02/02/2022

## PROPOSTA:

### TÍTULO: A INFLUÊNCIA DAS CRISES HÍDRICAS NOS INDICADORES FUNDAMENTALISTAS DAS EMPRESAS DO SETOR ELÉTRICO DISPOÍNVEIS NA BOLSA DE VALORES. 

### MOTIVAÇÃO  

Nos anos de 2020 e de 2021, o Brasil enfrentou a maior estiagem em 91 anos[1]. A precipitação é um possível indicador para medir a quantidade de chuvas no Brasil ao longo do tempo e poderia ser comparada com os principais indicadores fundamentalistas das principais empresas no mercado de ações brasileiro. Existem dados históricos presentes no Instituto Nacional de Meteorologia (INMET)[2].  

Os dados das empresas de energia podem ser obtidos por duas formas: a primeira são pacotes disponíveis em bibliotecas do Python e a segunda é por meio de procedimento de extração HTML WebScrapping (“Raspagem Web”). Além do uso de algumas ferramentas para tratamento dos dados presentes em bibliotecas do Python. 

Os dados de precipitação foram já tratados por mim e estão disponíveis no link na nota de rodapé3. Os arquivos em CSV disponibilizam a precipitação em mm e por mês. Os dados foram tratados e, também, determinada algumas estatísticas. Com posse desses dados, podem ser determinados a correlação da precipitação no Brasil e na região sudeste com variáveis fundamentalistas. 

Existe um pacote que faz a coleta de preços diários de ações pelo Python e um exemplo de uso está disponível em meu GitHub4. Além disso, no link [3] existe um arquivo chamado “Exemplo de coleta de dados CVM automático” que mostra um exemplo de coleta automatizada dos relatórios financeiros das empresas listadas na B3.  

#### Objetivos propostos 

Em primeiro lugar, será feito o tratamento dos dados para que seja feitas as análises posteriores. Será, de início, coletados dados apenas da Cemig e da Taesa para uma primeira validação. Depois de eventual validação, pode ser adaptado o algoritmo Python para que seja feito automaticamente para demais empresas, apenas sendo necessário colocar o período e análise e as empresas de interesse. 

A proposta é investigar a relação da precipitação média no Brasil e no Sudeste e alguns indicadores fundamentalistas das empresas que atuam no setor elétrico. Os indicadores que serão levantados são P/L, EVA, receita, dívida, patrimônio. Os objetivos secundários podem ser construídos com o andamento da pesquisa, sendo que outras variáveis ambientais podem ser colocadas para verificar correlação. 

#### Referencial bibliográfico inicial 

ASSAF NETO, Alexandre. Mercado Financeiro. 12. ed. São Paulo: Atlas, 2014. 400 p. 

B3: A BOLSA DO BRASIL (org.). A Bolsa do Brasil (B3). Disponível em: http://www.b3.com.br/pt_br/. Acesso em: 16 mar. 2021. 

B3: A BOLSA DO BRASIL (org.). Índice de Energia Elétrica (IEE B3). Disponível em: http://www.b3.com.br/pt_br/market-data-e-indices/indices/indices-de-segmentos-e-setoriais/indice-de-energia-eletrica-iee.htm. Acesso em: 31 mar. 2021. 

BODIE, Zvi; KANE, Alex; MARCUS, Alan. Investimentos. 10. ed. Porto Alegre: Amgh, 2014. 952 p. Tradução: Beth Honorato e Revisão Técnica: Samy Dana. 

DEBASTIANI, Carlos Alberto; RUSSO, Felipe Augusto. Avaliando empresas, investindo em ações: a aplicação prática da análise fundamentalista na avaliação de empresas. São Paulo: Novatec, 2008. 224 p. 

REIS, Tiago Guitián dos; TOSETTO, Jean Vitor Mantei. Guia suno de contabilidade para investidores: conceitos contábeis fundamentais para quem investe na bolsa. São Paulo: Cla Cultural, 2019. 118 p. 


#### Links mencionados:
[1] https://diariodocomercio.com.br/economia/brasil-experimenta-a-maior-crise-hidrica-em-91-anos/ (acessado em 16 de janeiro de 2022) 

[2] https://portal.inmet.gov.br/dadoshistoricos (acessado em 16 de janeiro de 2022) 

[3] Algoritmo e dados disponíveis em: https://drive.google.com/drive/folders/1GBLGHhf19_NkY_Y36eWkKXlRizThaKkm?usp=sharing 

[4] Exemplo em meu GitHub: https://github.com/francisconetodata/finance_python/blob/main/analise.ipynb 
