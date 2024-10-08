﻿# Teste Técnico Analytics - Identity & Risk Management Platform

**Motivação**:

Avaliar as habilidades técnicas + visão analítica + capacidade de tomar decisões com base em insights gerados a partir de dados pelos candidatos ao time de Analytics Identity & Risk Management Platform.

## Teste Técnico - Limites transacionais:
Uma Instituição de Pagamento disponibiliza Contas de Pagamento para seus clientes como produto de Banking, e em dado momento a existência de Limites Transacionais se tornou uma feature necessária para o produto.

Dado isso, precisamos criar um plano de ação para disponibilizar limites transacionais para clientes que já estão na base de clientes, de maneira a garantir um bom equilíbrio (trade off) entre:

1. permitir as movimentações financeiras do cliente e 

2. impedir movimentações além do “risco” que queremos correr com nossos clientes (inclui evitar transações fraudulentas de cash-out).

Dado este contexto, temos a base transacional dos últimos 5 meses de cash-out de nossos clientes em suas Contas de Pagamento, e precisamos:

1. Proposta inicial de limites transacionais desses clientes

    a. Explique suas estratégias e decisões

    b. Mostre numeros que ajudem a evidenciar que suas decisões foram assertivas
    
  2. Sugestão de proximos passos de evolução (inclusive estruturante) para os limites transacionais

      a. Quais proximos passos você daria na “estratégia de limites transacionais”?  
      
        + Por que?



## Catalogo de Dados:
Base de dados transacional de cash-out 

`transacoes.csv`

* id_transacao

* conta_pagamento

* ts_transacao

* nome_transacao

* canal_transacao

* valor_transacao



 

Base de dados com as transações que foram contestadas por fraude, e seus feedbacks de fraude (sim ou não)

`transacoes_fraude.csv`


* id_transacao

* feedback_contestacao 



 

Base cadastral de clientes

`faturamento.csv`

* conta_pagamento

* faturamento_anual


