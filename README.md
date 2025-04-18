# Limpeza-Dataset-Financeiro
Esse projeto teve como foco a análise exploratória e a limpeza de um dataset financeiro como:

O objetivo central foi preparar esse conjunto de dados para futuras análises preditivas, modelagem estatística e extração de insights relevantes para o negócio.

O que foi feito:

Exploração Inicial:

Verificação de dimensões do dataset e amostragem das colunas.

Conferência do dicionário de dados e tipagem das variáveis.

Identificação de IDs duplicados, inconsistências e registros inválidos.

Limpeza e Preparação:

Remoção de registros com valores zerados em todas as variáveis numéricas, indicando dados inválidos.

Conversão de tipos inconsistentes, como a coluna PAY_0 que continha valores não numéricos.

Substituição de categorias inválidas nas variáveis EDUCATION e MARRIAGE por categorias padrão.

Criação de variáveis categóricas descritivas e aplicação de One Hot Encoding, para tornar os dados prontos para análises mais avançadas.

Análise Exploratória:

Geração de estatísticas descritivas e distribuições (histogramas) para entender a dispersão dos dados.

Análises de frequência e comportamento das variáveis relacionadas a inadimplência.

Aplicação de transformações como logaritmo nos valores de pagamento para tratar a dispersão e facilitar futuras modelagens.

Impacto da Limpeza e Análise no Negócio:
Por que limpar os dados?
Em qualquer projeto de dados, dados sujos são sinônimo de decisões erradas. Um dado mal preenchido, duplicado ou inconsistente pode distorcer completamente análises, gerar falsos insights e comprometer decisões de crédito, cobrança e relacionamento com o cliente.

Benefícios Diretos para o Negócio:

Redução do risco de crédito: ao garantir dados íntegros, a análise de inadimplência fica muito mais precisa, o que permite à instituição financeira ajustar melhor seus critérios de concessão de crédito.

Otimização de campanhas de retenção e cobrança: sabendo exatamente o perfil de quem atrasa ou não paga, a empresa pode focar recursos de maneira mais eficiente.

Melhor segmentação de clientes: com categorização limpa e padronizada (ex: escolaridade, estado civil), é possível criar campanhas direcionadas, produtos personalizados e melhorar a experiência do cliente.

Base sólida para modelagem preditiva: dados bem tratados são a base para machine learning, score de crédito e previsões confiáveis.

Pandas: o herói silencioso
Nesse processo, o Pandas se mostrou uma ferramenta fenomenal — com poucos comandos, conseguimos:

Filtrar registros inválidos.

Detectar duplicatas.

Substituir, converter e mapear categorias.

Gerar estatísticas descritivas e transformar variáveis.

Integrar novas colunas e preparar o dataset final, pronto para qualquer tipo de análise ou modelagem.

Ele não só simplifica tarefas complexas como torna o código limpo, legível e altamente replicável, essencial em ambientes profissionais.


