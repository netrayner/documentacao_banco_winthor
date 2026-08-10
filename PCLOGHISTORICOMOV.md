# 📊 Tabela: PCLOGHISTORICOMOV

### Estrutura de Colunas e Restrições

           Tabela            Coluna  Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGHISTORICOMOV            CODLOG   NUMBER(8,0)                                 Código do Log.    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGHISTORICOMOV              TIPO   VARCHAR2(1)                    Tipo de movimentação (E/S).            OPERACIONAL                        NaN
PCLOGHISTORICOMOV         CODFILIAL   VARCHAR2(2)                              Código da filial.            OPERACIONAL                        NaN
PCLOGHISTORICOMOV          DTINICIO          DATE                       Data inicial de geração.            OPERACIONAL                        NaN
PCLOGHISTORICOMOV             DTFIM          DATE                         Data final de geração.            OPERACIONAL                        NaN
PCLOGHISTORICOMOV           CODPROD   NUMBER(6,0)                             Codigo do produto.            OPERACIONAL                        NaN
PCLOGHISTORICOMOV SOMENTENAOGERADOS   VARCHAR2(1) Somente os registro não gerados anteriormente.            OPERACIONAL                        NaN
PCLOGHISTORICOMOV       DATAGERACAO          DATE                               Data da geração.            OPERACIONAL                        NaN
PCLOGHISTORICOMOV          TERMINAL VARCHAR2(200)                          Terminal de execução.            OPERACIONAL                        NaN
PCLOGHISTORICOMOV        OS_USUARIO  VARCHAR2(30)                Usuário do sistema operacional.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*