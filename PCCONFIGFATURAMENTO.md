# 📊 Tabela: PCCONFIGFATURAMENTO

### Estrutura de Colunas e Restrições

             Tabela                    Coluna   Tipo/Tamanho                                                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONFIGFATURAMENTO           CODCONFIGURACAO    NUMBER(6,0)                                                                          Identificador da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCCONFIGFATURAMENTO                 CODFILIAL    VARCHAR2(2)                                                                                 Código da filial            OPERACIONAL                        NaN
PCCONFIGFATURAMENTO                 AUTOMACAO    VARCHAR2(1) Campo destinada a identificar se a configuracao será aplicada ao faturamento de forma automática            OPERACIONAL                        NaN
PCCONFIGFATURAMENTO            GATILHOINICIAL    NUMBER(4,0)                                  Gatilho utilizado para realizar faturamento de forma automática            OPERACIONAL                        NaN
PCCONFIGFATURAMENTO             GATILHOFILIAL    NUMBER(4,0)                                         Gatilho destinado para encerrar o faturamento automatico            OPERACIONAL                        NaN
PCCONFIGFATURAMENTO               CODCOBRANCA    VARCHAR2(4)                                                                               Código de cobranca            OPERACIONAL                        NaN
PCCONFIGFATURAMENTO         CODTRANSPORTADORA    NUMBER(6,0)                                                                         Código da transportadora            OPERACIONAL                        NaN
PCCONFIGFATURAMENTO           TIPOFATURAMENTO    VARCHAR2(3)                                                     Tipo do faturamento Ex: Pedido = P Carga = C            OPERACIONAL                        NaN
PCCONFIGFATURAMENTO              COMPLEMENTO1 VARCHAR2(4000)                                                                     Complemento do faturamento 1            OPERACIONAL                        NaN
PCCONFIGFATURAMENTO              COMPLEMENTO2 VARCHAR2(4000)                                                                     Complemento do faturamento 2            OPERACIONAL                        NaN
PCCONFIGFATURAMENTO              COMPLEMENTO3 VARCHAR2(4000)                                                                     Complemento do faturamento 3            OPERACIONAL                        NaN
PCCONFIGFATURAMENTO             CODCONFERENTE    NUMBER(8,0)                                                               Código do conferente da mercadoria            OPERACIONAL                        NaN
PCCONFIGFATURAMENTO                CODUSUARIO    NUMBER(8,0)                              Código do usuário com permissão a realizar o faturamento automático            OPERACIONAL                        NaN
PCCONFIGFATURAMENTO VALIDAGATILHOINDEPENDENTE    VARCHAR2(1)   Validar gatilhos da tabela PCCONFIGFATURAMENTOGATILHO independente do gatilho inicial ou final            OPERACIONAL                        NaN
PCCONFIGFATURAMENTO                 QTDMAXFAT    NUMBER(3,0)                        Definir em dias o prazo para considerar vendas no faturamento automatico             OPERACIONAL                        NaN
PCCONFIGFATURAMENTO          VALIDAGATILHORCA    VARCHAR2(1)   Validar gatilhos da tabela PCCONFIGFATURAMENTOGATILHO independente do gatilho inicial ou final            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*