# 📊 Tabela: PCEQUIPAMENTO

### Estrutura de Colunas e Restrições

       Tabela           Coluna Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEQUIPAMENTO   CODEQUIPAMENTO NUMBER(10,0)                                              NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCEQUIPAMENTO        CODFILIAL  VARCHAR2(2)                                              NaN            OPERACIONAL                        NaN
PCEQUIPAMENTO          CODPROD  NUMBER(6,0)                                              NaN            OPERACIONAL                        NaN
PCEQUIPAMENTO      NUMTRANSENT NUMBER(10,0)                                              NaN            OPERACIONAL                        NaN
PCEQUIPAMENTO    NUMTRANSVENDA NUMBER(10,0)                                              NaN            OPERACIONAL                        NaN
PCEQUIPAMENTO     IDPATRIMONIO VARCHAR2(75)                                              NaN            OPERACIONAL                        NaN
PCEQUIPAMENTO     DTFABRICACAO         DATE                                              NaN            OPERACIONAL                        NaN
PCEQUIPAMENTO       DTEXCLUSAO         DATE                                              NaN            OPERACIONAL                        NaN
PCEQUIPAMENTO         VOLTAGEM VARCHAR2(20)                                              NaN            OPERACIONAL                        NaN
PCEQUIPAMENTO         VIDAUTIL  NUMBER(6,0)                                              NaN            OPERACIONAL                        NaN
PCEQUIPAMENTO FATORDEPRECIACAO NUMBER(18,6)                                              NaN            OPERACIONAL                        NaN
PCEQUIPAMENTO             OBS1 VARCHAR2(75)                                              NaN            OPERACIONAL                        NaN
PCEQUIPAMENTO             OBS2 VARCHAR2(75)                                              NaN            OPERACIONAL                        NaN
PCEQUIPAMENTO             OBS3 VARCHAR2(75)                                              NaN            OPERACIONAL                        NaN
PCEQUIPAMENTO  CODFUNCEXCLUSAO  NUMBER(8,0)                                              NaN            OPERACIONAL                        NaN
PCEQUIPAMENTO CODFUNCALTERACAO  NUMBER(8,0)                                              NaN            OPERACIONAL                        NaN
PCEQUIPAMENTO  CODFUNCINCLUSAO  NUMBER(8,0)                                              NaN            OPERACIONAL                        NaN
PCEQUIPAMENTO       DTINCLUSAO         DATE                                              NaN            OPERACIONAL                        NaN
PCEQUIPAMENTO      DTDEVOLUCAO         DATE                                              NaN            OPERACIONAL                        NaN
PCEQUIPAMENTO      DTALTERACAO         DATE                                              NaN            OPERACIONAL                        NaN
PCEQUIPAMENTO            MARCA VARCHAR2(40)                                              NaN            OPERACIONAL                        NaN
PCEQUIPAMENTO           MODELO VARCHAR2(40)                                              NaN            OPERACIONAL                        NaN
PCEQUIPAMENTO     DTVENCIMENTO         DATE                  Data de vencimento do comodato.            OPERACIONAL                        NaN
PCEQUIPAMENTO         SITUACAO  VARCHAR2(1)          Indica a situação atual do equipamento.            OPERACIONAL                        NaN
PCEQUIPAMENTO      VLAQUISICAO NUMBER(18,6)      Valor unitário da aquisição do equipamento.            OPERACIONAL                        NaN
PCEQUIPAMENTO      DTAQUISICAO         DATE                Data da aquisição do equipamento.            OPERACIONAL                        NaN
PCEQUIPAMENTO       STATUS_DMS  VARCHAR2(5)                            Status DMS - Unilever            OPERACIONAL                        NaN
PCEQUIPAMENTO    CODLOCCLI_DMS  VARCHAR2(5) Código de Localização da conservadora no cliente            OPERACIONAL                        NaN
PCEQUIPAMENTO        CODMODELO VARCHAR2(20)                  Código do modelo do equipamento            OPERACIONAL                        NaN
PCEQUIPAMENTO          PROPRIO  VARCHAR2(1)                            Equipamento proprio ?            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*