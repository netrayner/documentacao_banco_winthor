# 📊 Tabela: PCWMSNUMSERIE

### Estrutura de Colunas e Restrições

       Tabela       Coluna Tipo/Tamanho                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCWMSNUMSERIE        NUMOS NUMBER(20,0)                      Indica o número da ordem de serviço.            OPERACIONAL                        NaN
PCWMSNUMSERIE      CODPROD  NUMBER(6,0)           Indica o código do produto da ordem de serviço.            OPERACIONAL                        NaN
PCWMSNUMSERIE         DATA         DATE                  Indica a data do lançamento do registro.            OPERACIONAL                        NaN
PCWMSNUMSERIE    CODFILIAL  VARCHAR2(2)                      Indica a filial da ordem de serviço.            OPERACIONAL                        NaN
PCWMSNUMSERIE  NUMEROSERIE VARCHAR2(50)  Indica o número de série do produto da ordem de serviço.            OPERACIONAL                        NaN
PCWMSNUMSERIE DTEXPORTACAO         DATE Indica a data da exportação do registro pela rotina 1742.            OPERACIONAL                        NaN
PCWMSNUMSERIE     SEMAFORO  NUMBER(1,0)                          Indica o controle de exportação.            OPERACIONAL                        NaN
PCWMSNUMSERIE           QT NUMBER(20,8)                   Campo referente a quantidade para serie            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*