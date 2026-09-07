# 📊 Tabela: PCEXCTABESCRSPED

### Estrutura de Colunas e Restrições

          Tabela       Coluna Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEXCTABESCRSPED    SEQUENCIA NUMBER(10,0)               Vínculo com a tabela PCTABESCRSPED CHAVE ESTRANGEIRA (FK)              PCTABESCRSPED
PCEXCTABESCRSPED          NCM VARCHAR2(20)             NCM - Nomenclatura Comum do Mercosul            OPERACIONAL                        NaN
PCEXCTABESCRSPED    CODEXTIPI  VARCHAR2(3)                                   Código EX TIPI            OPERACIONAL                        NaN
PCEXCTABESCRSPED        VALOR VARCHAR2(20) Valor para ser usado em outros tipos de exceções            OPERACIONAL                        NaN
PCEXCTABESCRSPED TIPOEXCESSAO  VARCHAR2(5)       Tipo de excessão 1 Excessão por NCM e TIPI            OPERACIONAL                        NaN
PCEXCTABESCRSPED   PRIORIDADE NUMBER(10,0)            Prioridade de verificação da excessão            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*