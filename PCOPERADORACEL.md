# 📊 Tabela: PCOPERADORACEL

### Estrutura de Colunas e Restrições

        Tabela            Coluna  Tipo/Tamanho                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCOPERADORACEL CODOPERRECARGACEL  NUMBER(14,0)                                      Cód de retorno da operadora de celular.    CHAVE PRIMÁRIA (PK)                        NaN
PCOPERADORACEL         OPERADORA VARCHAR2(100)                             Nome da Operadora de Celular(vivo, tim, etc...).            OPERACIONAL                        NaN
PCOPERADORACEL          CODCONTA  NUMBER(10,0)                                        Codigo da Conta gerencial da PCCONTA.            OPERACIONAL                        NaN
PCOPERADORACEL           CODHIST   NUMBER(4,0)                                               Codigo do Historico da PCHIST.            OPERACIONAL                        NaN
PCOPERADORACEL         HISTCOMPL VARCHAR2(200)                            Complemento do historico a ser lançado na PCLANC.            OPERACIONAL                        NaN
PCOPERADORACEL         CODFORNEC   NUMBER(6,0)                                Codigo do Fornecedor a ser lançado na PCLANC.            OPERACIONAL                        NaN
PCOPERADORACEL             PRAZO   NUMBER(4,0)                               Prazo de vencimento a ser informado na PCLANC.            OPERACIONAL                        NaN
PCOPERADORACEL          PERCDESC   NUMBER(5,2) Percentual do valor da recarga a ser repassado para o fornecedor do serviço.            OPERACIONAL                        NaN
PCOPERADORACEL     TIPOOPERADORA   VARCHAR2(3)                                               Tipo de Operadora de recargar             OPERACIONAL                        NaN
PCOPERADORACEL     DIAMESRECARGA   NUMBER(2,0)                                                  Dia do mês para recarga gás            OPERACIONAL                        NaN
PCOPERADORACEL  DIASEMANARECARGA  VARCHAR2(15)                                                    Dia da semana recarga gás            OPERACIONAL                        NaN
PCOPERADORACEL        TIPOCORBAN   VARCHAR2(4)                                               Layout correspondente bancário            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*