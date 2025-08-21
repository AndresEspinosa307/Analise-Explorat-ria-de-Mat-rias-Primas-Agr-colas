# Desvendando os Mercados de Matérias-Primas Agrícolas: Uma Análise Profunda de Preços e Variações
Este notebook Jupyter (Analise_Exploratoria_de_Matérias_Primas_Agrícolas.ipynb) apresenta uma análise exploratória de dados (EDA) focada na dinâmica dos preços e variações percentuais de diversas matérias-primas agrícolas ao longo do tempo. O objetivo é fornecer insights valiosos para investidores, produtores e formuladores de políticas, explorando tendências, correlações e padrões de volatilidade neste mercado.

**Visão Geral do Projeto**
A compreensão do mercado de matérias-primas agrícolas é crucial devido à sua volatilidade e impacto em diversas cadeias de valor. Este projeto visa desmistificar essa dinâmica através de uma abordagem de análise de dados, desde o carregamento e limpeza até a visualização de correlações de preços.

**Estrutura do Notebook**
O notebook está organizado nas seguintes seções principais:

**Configuração do Ambiente e Carregamento de Dados:**

* Importação das bibliotecas Python necessárias (numpy, pandas, seaborn, matplotlib).
* Definição de configurações de estilo para visualizações.
* Carregamento do conjunto de dados agricultural_raw_material.csv em um DataFrame do Pandas.

**Visão Geral e Exploração Inicial dos Dados:**

* Exibição das primeiras linhas do DataFrame para uma compreensão rápida da estrutura.
* Utilização de df.info() para verificar tipos de dados e contagem de valores não nulos.
* Geração de estatísticas descritivas (df.describe()) para um resumo quantitativo das colunas numéricas.

**Tratamento de Dados Ausentes, Incorretos e Inválidos:**

* Verificação e identificação de valores nulos em cada coluna.
* Limpeza de dados, incluindo a remoção de caracteres especiais (%, , e -) que impedem a conversão numérica.
* Substituição de strings vazias e valores inconsistentes ('MAY90') por NaN.
* Remoção de linhas contendo valores NaN para garantir a integridade da análise.
* Conversão de colunas de preço e variação percentual para o tipo de dado float.

**Formatação da Coluna de Data e Hora:**

Conversão da coluna 'Month' para o formato datetime.
Definição da coluna 'Month' como o índice do DataFrame, essencial para análises de séries temporais.
**Análise Exploratória e Visualização (EDA):**

* Mapa de Calor de Correlação de Preços: 
Geração de um mapa de calor para visualizar a correlação entre os preços das diferentes matérias-primas, identificando padrões de movimento conjunto.
* Análise de Preços e Variações da Lã Grossa: 
Visualização das tendências de preço e variação percentual da lã grossa ao longo do tempo. (Esta seção pode ser expandida para outras matérias-primas conforme a análise avança).

**Conjunto de Dados**
* O conjunto de dados agricultural_raw_material.csv contém informações sobre os preços e as variações percentuais de diversas matérias-primas agrícolas ao longo do tempo. A fonte original do dataset deve ser referenciada aqui, se aplicável.

**Contribuições**
* Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests para melhorias, correções de bugs ou novas análises.

**Licença**
* Este projeto está licenciado sob a Licença MIT. (Crie um arquivo LICENSE no seu repositório se ainda não tiver um).
