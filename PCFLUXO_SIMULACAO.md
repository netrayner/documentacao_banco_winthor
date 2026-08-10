# 📊 Tabela: PCFLUXO_SIMULACAO

### Estrutura de Colunas e Restrições

           Tabela            Coluna  Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFLUXO_SIMULACAO       DATAEMISSAO          DATE                      Data de emissão            OPERACIONAL                        NaN
PCFLUXO_SIMULACAO        VLARECEBER  NUMBER(14,2)                      Valor a receber            OPERACIONAL                        NaN
PCFLUXO_SIMULACAO          VLAPAGAR  NUMBER(14,2)                        Valor a pagar            OPERACIONAL                        NaN
PCFLUXO_SIMULACAO HISTORICO_RECEBER VARCHAR2(200) Histórico do fluxo no dia especifico            OPERACIONAL                        NaN
PCFLUXO_SIMULACAO   HISTORICO_PAGAR VARCHAR2(200) Histórico do fluxo no dia especifico            OPERACIONAL                        NaN
PCFLUXO_SIMULACAO         CODFILIAL   VARCHAR2(2)                     Código da Filial            OPERACIONAL                        NaN
PCFLUXO_SIMULACAO      CODSIMULACAO  NUMBER(10,0)                     Código da Filial    CHAVE PRIMÁRIA (PK)                        NaN
PCFLUXO_SIMULACAO          DATAVENC          DATE                   Data de vencimento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*