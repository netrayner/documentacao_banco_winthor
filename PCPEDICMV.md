# 📊 Tabela: PCPEDICMV

### Estrutura de Colunas e Restrições

   Tabela       Coluna  Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPEDICMV       NUMPED  NUMBER(10,0)                             Número do pedido    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDICMV      CODPROD   NUMBER(6,0)                            Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDICMV       NUMSEQ  NUMBER(20,0) Número de sequência do item dentro do pedido    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDICMV   CODFORMULA VARCHAR2(200)                  Código da fórmula utilizado            OPERACIONAL                        NaN
PCPEDICMV   CMVFORMULA          CLOB          Fórmula utilizado no cálculo do CMV            OPERACIONAL                        NaN
PCPEDICMV   CMVMEMORIA          CLOB                    Memória de cálculo do CMV            OPERACIONAL                        NaN
PCPEDICMV CMVVARIAVEIS          CLOB         Variáveis de usado no cálculo do CMV            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*