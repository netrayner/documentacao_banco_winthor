# 📊 Tabela: PCCARDAPIOGRUPOAMBIENTES

### Estrutura de Colunas e Restrições

                  Tabela           Coluna Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCARDAPIOGRUPOAMBIENTES CODGRUPOAMBIENTE  NUMBER(6,0)                            Codigo Grupo Ambiente    CHAVE PRIMÁRIA (PK)                        NaN
PCCARDAPIOGRUPOAMBIENTES         CODGRUPO  NUMBER(6,0)                                     Codigo Grupo CHAVE ESTRANGEIRA (FK)            PCCARDAPIOGRUPO
PCCARDAPIOGRUPOAMBIENTES      CODAMBIENTE  NUMBER(6,0)                                  Codigo Ambiente CHAVE ESTRANGEIRA (FK)        PCCARDAPIOAMBIENTES
PCCARDAPIOGRUPOAMBIENTES           CODIMP  NUMBER(6,0)                                   Cod.Impressora CHAVE ESTRANGEIRA (FK)              PCIMPRESSORAS
PCCARDAPIOGRUPOAMBIENTES        CODIMPANT  NUMBER(4,0)                          Cod.Impressora Anterior CHAVE ESTRANGEIRA (FK)              PCIMPRESSORAS
PCCARDAPIOGRUPOAMBIENTES     CODIMPMOBILE  NUMBER(6,0) Cód. impressora quando solicitado por Disp.móvel CHAVE ESTRANGEIRA (FK)              PCIMPRESSORAS

---
*Documentação gerada automaticamente.*