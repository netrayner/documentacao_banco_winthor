# 📊 Tabela: PCENDERECO

### Estrutura de Colunas e Restrições

    Tabela              Coluna Tipo/Tamanho                                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCENDERECO         CODENDERECO NUMBER(10,0)                                                                           NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCENDERECO            DEPOSITO  NUMBER(3,0)                                                                           NaN            OPERACIONAL                        NaN
PCENDERECO                 RUA  NUMBER(5,0)                                                                           NaN            OPERACIONAL                        NaN
PCENDERECO              PREDIO  NUMBER(5,0)                                                                           NaN            OPERACIONAL                        NaN
PCENDERECO               NIVEL  NUMBER(5,0)                                                                           NaN            OPERACIONAL                        NaN
PCENDERECO                APTO  NUMBER(5,0)                                                                           NaN            OPERACIONAL                        NaN
PCENDERECO           TIPOENDER  VARCHAR2(2)                                                                           NaN            OPERACIONAL                        NaN
PCENDERECO             TIPOPAL  NUMBER(2,0)                                                                           NaN            OPERACIONAL                        NaN
PCENDERECO            BLOQUEIO  VARCHAR2(1)                                                                           NaN            OPERACIONAL                        NaN
PCENDERECO            SITUACAO  VARCHAR2(1)                                                                           NaN            OPERACIONAL                        NaN
PCENDERECO             CODPROD  NUMBER(6,0)                                                   Indica o código do produto.            OPERACIONAL                        NaN
PCENDERECO      CODARMAZENAGEM  NUMBER(2,0)                                                                           NaN            OPERACIONAL                        NaN
PCENDERECO        CODESTRUTURA  NUMBER(2,0)                                                                           NaN            OPERACIONAL                        NaN
PCENDERECO            NUMBONUS NUMBER(10,0)                                                                           NaN            OPERACIONAL                        NaN
PCENDERECO          DTULTALTER         DATE                                                                           NaN            OPERACIONAL                        NaN
PCENDERECO     CODFUNCULTALTER  NUMBER(8,0)                                                                           NaN            OPERACIONAL                        NaN
PCENDERECO         PCKROTATIVO  VARCHAR2(1)                                                                           NaN            OPERACIONAL                        NaN
PCENDERECO              STATUS  VARCHAR2(1)                                                                           NaN            OPERACIONAL                        NaN
PCENDERECO          CODFUNCSEP  NUMBER(8,0)                                                                           NaN            OPERACIONAL                        NaN
PCENDERECO           NUMINVENT  NUMBER(8,0)                                                                           NaN            OPERACIONAL                        NaN
PCENDERECO             ESTACAO  NUMBER(3,0)                                                                           NaN            OPERACIONAL                        NaN
PCENDERECO             NUMLOTE VARCHAR2(15)                                                                           NaN            OPERACIONAL                        NaN
PCENDERECO            QTRESERV NUMBER(20,8)                                                                           NaN            OPERACIONAL                        NaN
PCENDERECO                  QT NUMBER(20,8)                                                                           NaN            OPERACIONAL                        NaN
PCENDERECO               DTVAL         DATE                                                                           NaN            OPERACIONAL                        NaN
PCENDERECO           CODFORNEC NUMBER(10,0)                                                                           NaN            OPERACIONAL                        NaN
PCENDERECO POSSUIELEVADORCARGA  VARCHAR2(1)                                                                           NaN            OPERACIONAL                        NaN
PCENDERECO   DIGITOVERIFICADOR  NUMBER(9,0)                                            Descricao coluna DIGITOVERIFICADOR            OPERACIONAL                        NaN
PCENDERECO           CODFILIAL  VARCHAR2(2)                                                    Indica o código da filial.            OPERACIONAL                        NaN
PCENDERECO       QTPALETEENDER  NUMBER(3,0) Campo responsável por armazenar a quantidad de palete enderecavei por filial.            OPERACIONAL                        NaN
PCENDERECO              RUAENT  NUMBER(5,0)                                                            Rua para Push-back            OPERACIONAL                        NaN
PCENDERECO           PREDIOENT  NUMBER(5,0)                                                         Prédio para Push-back            OPERACIONAL                        NaN
PCENDERECO     CODMOTIVOAVARIA  NUMBER(4,0)                                                    Códido do motivo de avaria            OPERACIONAL                        NaN
PCENDERECO               ATIVO  VARCHAR2(1)                                                       Ativo ou não o endereço            OPERACIONAL                        NaN
PCENDERECO     FILIALGESTAOWMS  VARCHAR2(2)                                                     Dígito verificador do box            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*