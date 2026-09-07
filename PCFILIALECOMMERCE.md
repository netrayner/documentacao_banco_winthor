# 📊 Tabela: PCFILIALECOMMERCE

### Estrutura de Colunas e Restrições

           Tabela              Coluna  Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFILIALECOMMERCE                  ID  NUMBER(10,0)                      Indentifcador de registro    CHAVE PRIMÁRIA (PK)                        NaN
PCFILIALECOMMERCE               TOKEN VARCHAR2(500)                                          Token            OPERACIONAL                        NaN
PCFILIALECOMMERCE            LINKLOJA VARCHAR2(150)                                   Link da loja            OPERACIONAL                        NaN
PCFILIALECOMMERCE               ATIVO   NUMBER(1,0)                          Informa se está ativo            OPERACIONAL                        NaN
PCFILIALECOMMERCE     USAMULTIESTOQUE   NUMBER(1,0) Define se filial usa processo de multi estoque            OPERACIONAL                        NaN
PCFILIALECOMMERCE     USAMULTIREMESSA   NUMBER(1,0) Define se filial usa processo de multi remessa            OPERACIONAL                        NaN
PCFILIALECOMMERCE CONVERTERESTOQUEKIT   NUMBER(1,0)      Flag para determinar conversão do estoque            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*