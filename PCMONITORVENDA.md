# 📊 Tabela: PCMONITORVENDA

### Estrutura de Colunas e Restrições

        Tabela        Coluna Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMONITORVENDA        CODIGO  NUMBER(6,0)      Indice o código do monitor de venda.    CHAVE PRIMÁRIA (PK)                        NaN
PCMONITORVENDA        PERCOM  NUMBER(8,4)          Indice o percentual de comissão.            OPERACIONAL                        NaN
PCMONITORVENDA          NOME VARCHAR2(60)                 Indica o nome do monitor.            OPERACIONAL                        NaN
PCMONITORVENDA CODSUPERVISOR  NUMBER(4,0) Indica o código do supervisor do monitor.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*