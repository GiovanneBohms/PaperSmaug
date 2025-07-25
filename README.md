# Smaug

## O que é a aplicação?  
Smaug é um robô de análise quantitativa que varre o mercado da B3 em busca de ineficiências. Seu diferencial é o sistema de gerenciamento de risco, importado do projeto Ouroboros, já validado anteriormente. Com isso, a aplicação é capaz de indicar quais ativos comprar, quando comprar, qual a taxa de acerto esperada e a rentabilidade projetada.

## Problema que resolve  
As estratégias de trading dependem de variáveis que se comportam de maneira diferente em cada ativo financeiro. Para encontrar os melhores parâmetros para cada ativo, é necessário realizar diversos backtests. Como o objetivo é aplicar esse processo em todos os ativos com determinada liquidez, a carga de processamento é alta. O robô automatiza essa tarefa, identificando as melhores oportunidades de forma eficiente e escalável.

## Público-alvo  
Devido ao equilíbrio de Nash, um sistema eficiente tende a perder eficácia se amplamente divulgado. A vantagem competitiva está na exclusividade, portanto o Smaug é restrito ao uso dos seus desenvolvedores.

## Funcionalidades mínimas da primeira versão  
- Análise diária dos dados OHLC (Open, High, Low, Close) dos ativos.  
- Coleta manual das séries históricas anuais da B3, armazenadas em pasta específica.  
- Conversão dos dados para banco SQLite via script Python.  
- Aplicação de filtros, como liquidez mediana diária.  
- Implementação de uma estratégia inicial.  
- Geração de tabela classificando ativos do mais ao menos lucrativo.  
- Interface simples para visualização, ainda a definir entre web ou desktop.

## Interface gráfica  
A interface gráfica ainda não está definida. A prioridade inicial é o backend e automação, com a interface visando simplicidade e facilidade de uso.

## Plataforma final  
Desktop.

## Linguagem base  
Python.

## Meta de performance e volume de dados  
Inicialmente, o Smaug processará entre 200 e 300 ativos da B3. Futuramente, o sistema será expandido para mercados como Forex, criptomoedas, ações americanas ou qualquer ativo com liquidez mínima.

O projeto passará por mais duas etapas:  
- A próxima etapa será a análise intraday dos ativos, utilizando dados OHLC de 1 hora.  
- Após a validação dessa funcionalidade, a etapa final será a análise com dados OHLC de 5 minutos.

## Natureza do projeto  
Produto real, de uso exclusivo dos desenvolvedores. Os desenvolvedores podem incluir o projeto em seus currículos e apresentar suas funcionalidades, desde que não divulguem regras internas do sistema de trading.
