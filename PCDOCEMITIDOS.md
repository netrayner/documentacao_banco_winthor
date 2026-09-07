# 📊 Tabela: PCDOCEMITIDOS

### Estrutura de Colunas e Restrições

       Tabela          Coluna Tipo/Tamanho                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDOCEMITIDOS       CODFILIAL  VARCHAR2(2)                             Código da filial.            OPERACIONAL                        NaN
PCDOCEMITIDOS        NUMCAIXA  NUMBER(4,0)                              Número do caixa.            OPERACIONAL                        NaN
PCDOCEMITIDOS  NUMCAIXAFISCAL  NUMBER(4,0)            Número do emissor de cupom fiscal.            OPERACIONAL                        NaN
PCDOCEMITIDOS   NUMSERIEEQUIP VARCHAR2(20)               Número de série do equipamento.            OPERACIONAL                        NaN
PCDOCEMITIDOS            DATA         DATE                              Data de emissão.            OPERACIONAL                        NaN
PCDOCEMITIDOS     MFADICIONAL  VARCHAR2(1)             Letra indicativa de MF adicional.            OPERACIONAL                        NaN
PCDOCEMITIDOS       MODELOECF VARCHAR2(20)            Modelo do emissor de cupom fiscal.            OPERACIONAL                        NaN
PCDOCEMITIDOS   NUMEROUSUARIO  NUMBER(4,0)            Número do usuário do cupom fiscal.            OPERACIONAL                        NaN
PCDOCEMITIDOS             COO  NUMBER(6,0)       Contador de ordem de operação do cupom.            OPERACIONAL                        NaN
PCDOCEMITIDOS             GNF  NUMBER(6,0)        Contador geral de operação não fiscal.            OPERACIONAL                        NaN
PCDOCEMITIDOS             GRG  NUMBER(6,0)        Contador geral de relatório gerencial.            OPERACIONAL                        NaN
PCDOCEMITIDOS             CDC  NUMBER(6,0) Ccontador de comprovante de débito e crédito.            OPERACIONAL                        NaN
PCDOCEMITIDOS     DENOMINACAO  VARCHAR2(2)              Símbolo referente ao doc.fiscal.            OPERACIONAL                        NaN
PCDOCEMITIDOS            HORA  VARCHAR2(6)                        Hora final de emissão.            OPERACIONAL                        NaN
PCDOCEMITIDOS        EXPORTOU  VARCHAR2(1)                                    Exportado.            OPERACIONAL                        NaN
PCDOCEMITIDOS      ROTINALANC VARCHAR2(48)                ROTINA QUE GRAVOU A INFORMACAO            OPERACIONAL                        NaN
PCDOCEMITIDOS DATAHORAEMISSAO         DATE           Data e hora de emissão de documento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*