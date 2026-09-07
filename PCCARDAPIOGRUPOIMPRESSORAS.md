# 📊 Tabela: PCCARDAPIOGRUPOIMPRESSORAS

### Estrutura de Colunas e Restrições

                    Tabela       Coluna Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCARDAPIOGRUPOIMPRESSORAS  CODGRUPOIMP  NUMBER(6,0)                          Codigo Grupo Impressora    CHAVE PRIMÁRIA (PK)                        NaN
PCCARDAPIOGRUPOIMPRESSORAS     CODGRUPO  NUMBER(6,0)                                     Codigo Grupo CHAVE ESTRANGEIRA (FK)            PCCARDAPIOGRUPO
PCCARDAPIOGRUPOIMPRESSORAS    CODFILIAL  VARCHAR2(2)                                    Codigo Filial CHAVE ESTRANGEIRA (FK)                   PCFILIAL
PCCARDAPIOGRUPOIMPRESSORAS       CODIMP  NUMBER(6,0)                                   Cod.Impressora CHAVE ESTRANGEIRA (FK)              PCIMPRESSORAS
PCCARDAPIOGRUPOIMPRESSORAS    CODIMPANT  NUMBER(4,0)                                              NaN CHAVE ESTRANGEIRA (FK)              PCIMPRESSORAS
PCCARDAPIOGRUPOIMPRESSORAS CODIMPMOBILE  NUMBER(6,0) Cód. impressora quando solicitado por Disp.móvel CHAVE ESTRANGEIRA (FK)              PCIMPRESSORAS

---
*Documentação gerada automaticamente.*