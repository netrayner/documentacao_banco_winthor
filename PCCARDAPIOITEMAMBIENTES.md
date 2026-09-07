# 📊 Tabela: PCCARDAPIOITEMAMBIENTES

### Estrutura de Colunas e Restrições

                 Tabela          Coluna Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCARDAPIOITEMAMBIENTES CODITEMAMBIENTE  NUMBER(6,0)                          Codigo Grupo Impressora    CHAVE PRIMÁRIA (PK)                        NaN
PCCARDAPIOITEMAMBIENTES         CODITEM  NUMBER(6,0)                                     Codigo Grupo            OPERACIONAL                        NaN
PCCARDAPIOITEMAMBIENTES     CODAMBIENTE  NUMBER(6,0)                                    Codigo Filial CHAVE ESTRANGEIRA (FK)        PCCARDAPIOAMBIENTES
PCCARDAPIOITEMAMBIENTES          CODIMP  NUMBER(6,0)                                   Cod.Impressora CHAVE ESTRANGEIRA (FK)              PCIMPRESSORAS
PCCARDAPIOITEMAMBIENTES       CODIMPANT  NUMBER(4,0)                                              NaN CHAVE ESTRANGEIRA (FK)              PCIMPRESSORAS
PCCARDAPIOITEMAMBIENTES    CODIMPMOBILE  NUMBER(6,0) Cód. impressora quando solicitado por Disp.móvel CHAVE ESTRANGEIRA (FK)              PCIMPRESSORAS

---
*Documentação gerada automaticamente.*