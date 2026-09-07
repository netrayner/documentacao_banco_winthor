# 📊 Tabela: PCLOGENVIOEMAILSERVIDOR

### Estrutura de Colunas e Restrições

                 Tabela       Coluna  Tipo/Tamanho                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGENVIOEMAILSERVIDOR NUMTRANSACAO  NUMBER(10,0)                                   Número de transação            OPERACIONAL                        NaN
PCLOGENVIOEMAILSERVIDOR  DATAEMISSAO          DATE                              Date de emissão do danfe            OPERACIONAL                        NaN
PCLOGENVIOEMAILSERVIDOR    MOVIMENTO   VARCHAR2(1) Tipo de movimento do danfe (E - Entrada ou S - Saída)            OPERACIONAL                        NaN
PCLOGENVIOEMAILSERVIDOR     CHAVENFE  VARCHAR2(44)                                       Chave de acesso            OPERACIONAL                        NaN
PCLOGENVIOEMAILSERVIDOR       NUMCAR   NUMBER(8,0)                                Número de carregamento            OPERACIONAL                        NaN
PCLOGENVIOEMAILSERVIDOR    DATAENVIO          DATE                                Data de envio do email            OPERACIONAL                        NaN
PCLOGENVIOEMAILSERVIDOR        EMAIL VARCHAR2(300)                                                 Email            OPERACIONAL                        NaN
PCLOGENVIOEMAILSERVIDOR    DIRETORIO VARCHAR2(100)                     Diretorio aonde foi gravado o pdf            OPERACIONAL                        NaN
PCLOGENVIOEMAILSERVIDOR     TERMINAL VARCHAR2(100)                                              Terminal            OPERACIONAL                        NaN
PCLOGENVIOEMAILSERVIDOR      MAQUINA VARCHAR2(100)                                               Máquina            OPERACIONAL                        NaN
PCLOGENVIOEMAILSERVIDOR     PROGRAMA VARCHAR2(100)                                       Rotina emissora            OPERACIONAL                        NaN
PCLOGENVIOEMAILSERVIDOR      USUARIO VARCHAR2(100)                                    Usuário da maquina            OPERACIONAL                        NaN
PCLOGENVIOEMAILSERVIDOR    CODFILIAL   VARCHAR2(2)                                      Código da Filial            OPERACIONAL                        NaN
PCLOGENVIOEMAILSERVIDOR       CODIGO  NUMBER(10,0)                                                Código    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*