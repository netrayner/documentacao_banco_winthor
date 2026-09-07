# 📊 Tabela: PCGMSUBSTITUTO

### Estrutura de Colunas e Restrições

        Tabela                Coluna Tipo/Tamanho                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGMSUBSTITUTO                CODIGO NUMBER(10,0)         Código de identificação, sequencial de cadastro    CHAVE PRIMÁRIA (PK)                        NaN
PCGMSUBSTITUTO             MATRICULA  NUMBER(8,0) Matricula do funcionário substituto utilizada na PCEMPR            OPERACIONAL                        NaN
PCGMSUBSTITUTO                  NOME VARCHAR2(40)                          Nome do funcionário substituto            OPERACIONAL                        NaN
PCGMSUBSTITUTO              SITUACAO  VARCHAR2(1)                       Situação ativa "A" ou inativa "I"            OPERACIONAL                        NaN
PCGMSUBSTITUTO          DATACADASTRO         DATE                                        Data do cadastro            OPERACIONAL                        NaN
PCGMSUBSTITUTO          DATAEXCLUSAO         DATE                            Data da exclusão do cadastro            OPERACIONAL                        NaN
PCGMSUBSTITUTO           DATAINICIAL         DATE                             Data inicio de substituição            OPERACIONAL                        NaN
PCGMSUBSTITUTO             DATAFINAL         DATE                                Data fim da substituição            OPERACIONAL                        NaN
PCGMSUBSTITUTO            COD_CADRCA  NUMBER(4,0)                            Código de rca do substituido            OPERACIONAL                        NaN
PCGMSUBSTITUTO           SUBSTITUIDO VARCHAR2(40)                                     Nome do substituido            OPERACIONAL                        NaN
PCGMSUBSTITUTO MATRICULA_SUBSTITUIDO  NUMBER(8,0)                                Matricula do substituido            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*