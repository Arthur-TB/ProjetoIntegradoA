ENTREGA INDIVIDUAL - Arthur Teles - Parte A
Projeto Integrador "Numeros que Falam" - Indicador 1: Afazeres Domesticos - Turma 3B2

CONTEUDO
1. Codigo Python do modulo (ETL e estatisticas)
   - secoes/parte_a.py ....... secao do dashboard (graficos, KPIs, estatisticas, resposta a persona)
   - etl.py ................... leitura e limpeza da tabela do SIDRA/IBGE
   - estatisticas.py .......... media, mediana, moda, quartis, IQR, amplitude, variancia, desvio padrao, outliers
   - comum.py ................. upload, filtros, boxplot, noticias (compartilhado pelo grupo)
   - app_parte_a.py ........... roda somente esta secao
2. Base IBGE tratada
   - dados_tratados/tabela_7015_sexo_tratada.xlsx (e a versao .csv)
   - dados_brutos/ ............ arquivo original baixado do SIDRA
3. Analise descritiva
   - ANALISE_DESCRITIVA_Arthur_Teles_Parte_A.docx  <- RASCUNHO: revisar e reescrever com suas palavras

COMO RODAR
   pip install -r requirements.txt
   streamlit run app_parte_a.py

Fonte: IBGE - PNAD Continua Anual, 5a visita (SIDRA).
