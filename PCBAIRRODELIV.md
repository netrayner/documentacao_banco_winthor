# 📊 Tabela: PCBAIRRODELIV

### Estrutura de Colunas e Restrições

       Tabela         Coluna  Tipo/Tamanho                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBAIRRODELIV         CODIGO   NUMBER(6,0)                   Codigo sequencial do bairro    CHAVE PRIMÁRIA (PK)                        NaN
PCBAIRRODELIV         BAIRRO VARCHAR2(150)                     Nome do bairro de entrega            OPERACIONAL                        NaN
PCBAIRRODELIV      CODFILIAL   VARCHAR2(2)                              Código da Filial            OPERACIONAL                        NaN
PCBAIRRODELIV      CODCIDADE   NUMBER(6,0)                              Código da Cidade            OPERACIONAL                        NaN
PCBAIRRODELIV             UF   VARCHAR2(2)                                            UF            OPERACIONAL                        NaN
PCBAIRRODELIV    VLTXENTREGA   NUMBER(7,2)                      Valor da Taxa de Entrega            OPERACIONAL                        NaN
PCBAIRRODELIV         STATUS   VARCHAR2(1)                        A - Ativo; I - Inativo            OPERACIONAL                        NaN
PCBAIRRODELIV      DTINATIVO          DATE             Data que o cadastro foi inativado            OPERACIONAL                        NaN
PCBAIRRODELIV CODFUNCINATIVO   NUMBER(6,0) Código do Funcionário que inativou o cadastro            OPERACIONAL                        NaN
PCBAIRRODELIV  MOTIVOINATIVO  VARCHAR2(60)                          Motivo da inativação            OPERACIONAL                        NaN
PCBAIRRODELIV      DTALTERC5  TIMESTAMP(6)                             Data de alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*