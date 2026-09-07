# 📊 Tabela: PCSPEDECFM312

### Estrutura de Colunas e Restrições

       Tabela    Coluna Tipo/Tamanho                                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSPEDECFM312        ID  NUMBER(8,0)                                 Identificador único do registro (PK)    CHAVE PRIMÁRIA (PK)                        NaN
PCSPEDECFM312    IDM310 NUMBER(22,0)  ID da conta contábil relacionada ao lançamento da parte A do LALUR  CHAVE ESTRANGEIRA (FK)              PCSPEDECFM310
PCSPEDECFM312   NUMLCTO VARCHAR2(50) Número do Lançamento Descrito na ECD (Escrituração Contábil Digital)            OPERACIONAL                        NaN
PCSPEDECFM312     LALUR      CHAR(1)                                                S = LALUR ou N = LACS            OPERACIONAL                        NaN
PCSPEDECFM312 DTCRIACAO         DATE                        Data de criação do registro no banco de dados            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*