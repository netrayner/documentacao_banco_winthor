# 📊 Tabela: PCLOGINVENTARIOWMS

### Estrutura de Colunas e Restrições

            Tabela         Coluna Tipo/Tamanho                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGINVENTARIOWMS      CODFILIAL  VARCHAR2(2)                                     Código da filial.            OPERACIONAL                        NaN
PCLOGINVENTARIOWMS CODPARAMINVENT NUMBER(10,0) Código do parâmetro usado na montagem do inventário..            OPERACIONAL                        NaN
PCLOGINVENTARIOWMS      NUMINVENT NUMBER(10,0)                                 Número do inventário.            OPERACIONAL                        NaN
PCLOGINVENTARIOWMS    CODENDERECO NUMBER(10,0)                                   Código do endereço.            OPERACIONAL                        NaN
PCLOGINVENTARIOWMS          QTANT NUMBER(20,8)                                  Quantidade anterior.            OPERACIONAL                        NaN
PCLOGINVENTARIOWMS       QTINVENT NUMBER(20,8)                              Quantidade inventariada.            OPERACIONAL                        NaN
PCLOGINVENTARIOWMS       DTVALANT         DATE                            Data de validade anterior.            OPERACIONAL                        NaN
PCLOGINVENTARIOWMS    DTVALINVENT         DATE                        Data de validade inventariada.            OPERACIONAL                        NaN
PCLOGINVENTARIOWMS        CODPROD NUMBER(10,0)             Indica o código do produto do inventário.            OPERACIONAL                        NaN
PCLOGINVENTARIOWMS        NUMLOTE VARCHAR2(15)                Indica o número do lote de inventário.            OPERACIONAL                        NaN
PCLOGINVENTARIOWMS         VERSAO    NVARCHAR2                                     IVERSAO DA ROTINA            OPERACIONAL                        NaN
PCLOGINVENTARIOWMS      CODROTINA  NUMBER(6,0)                                      CODIGO DA ROTINA            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*