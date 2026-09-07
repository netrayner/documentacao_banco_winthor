# 📊 Tabela: PCVALORFRETEPORFAIXAKM

### Estrutura de Colunas e Restrições

                Tabela          Coluna Tipo/Tamanho Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVALORFRETEPORFAIXAKM    FAIXAINICIAL  NUMBER(8,4)       Faixa Inicial            OPERACIONAL                        NaN
PCVALORFRETEPORFAIXAKM      FAIXAFINAL  NUMBER(8,4)         Faixa Final            OPERACIONAL                        NaN
PCVALORFRETEPORFAIXAKM VALORREFERENCIA  NUMBER(8,4)    Valor Referência            OPERACIONAL                        NaN
PCVALORFRETEPORFAIXAKM     CODFILIALNF  VARCHAR2(2)              Filial CHAVE ESTRANGEIRA (FK)               PCTRIBOUTROS
PCVALORFRETEPORFAIXAKM       UFDESTINO  VARCHAR2(2)          UF Destino CHAVE ESTRANGEIRA (FK)               PCTRIBOUTROS

---
*Documentação gerada automaticamente.*