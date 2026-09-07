# 📊 Tabela: PCRESTRICAODESCVALOR

### Estrutura de Colunas e Restrições

              Tabela           Coluna Tipo/Tamanho                                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRESTRICAODESCVALOR CODRESTRICAODESC NUMBER(10,0)                                  Código da restrição de desconto por valor de pedido.    CHAVE PRIMÁRIA (PK)                        NaN
PCRESTRICAODESCVALOR        CODFILIAL  VARCHAR2(2)                                                          Código da Filial (opcional).            OPERACIONAL                        NaN
PCRESTRICAODESCVALOR        NUMREGIAO  NUMBER(4,0)                                                          Número da Região (opcional).            OPERACIONAL                        NaN
PCRESTRICAODESCVALOR          CODPROD  NUMBER(6,0)                                                                    Código do Produto.            OPERACIONAL                        NaN
PCRESTRICAODESCVALOR  CODFUNCCADASTRO  NUMBER(8,0)          Código do funcionário que criou a restrição de desconto por valor de pedido.            OPERACIONAL                        NaN
PCRESTRICAODESCVALOR       DTCADASTRO         DATE                                     Data de criação da restrição: gravar data e hora.            OPERACIONAL                        NaN
PCRESTRICAODESCVALOR  CODFUNCULTALTER  NUMBER(8,0) Código do último funcionário que alterou a restrição de desconto por valor de pedido.            OPERACIONAL                        NaN
PCRESTRICAODESCVALOR       DTULTALTER         DATE                Data da última alteração na restrição de desconto por valor de pedido.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*