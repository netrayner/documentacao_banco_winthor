# 📊 Tabela: PCESTADO

### Estrutura de Colunas e Restrições

  Tabela                 Coluna Tipo/Tamanho                                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCESTADO                     UF  VARCHAR2(2)                                                                         NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCESTADO                 ESTADO VARCHAR2(15)                                                                         NaN            OPERACIONAL                        NaN
PCESTADO                 CODIGO  VARCHAR2(2)                                                              Código da UF.             OPERACIONAL                        NaN
PCESTADO          IESUBSTTRIBUT VARCHAR2(20)                                                                         NaN            OPERACIONAL                        NaN
PCESTADO                CODIBGE NUMBER(10,0)                                                                         NaN            OPERACIONAL                        NaN
PCESTADO                CODPAIS  NUMBER(4,0)                                                                         NaN            OPERACIONAL                        NaN
PCESTADO     CALCVLCONTABILNFCF  VARCHAR2(1)  Indica se gera notas de cupom fiscal com valores zerados no livro fiscal.             OPERACIONAL                        NaN
PCESTADO   CODFORNECGERACAOGNRE  NUMBER(6,0)                                      Indica o código do fornecedor da GNRE.            OPERACIONAL                        NaN
PCESTADO   CODFORNECGERACAOFECP  NUMBER(6,0) Indica o código do fornecedor do FECP ¿ Fundo Estadual de Combate a Pobreza            OPERACIONAL                        NaN
PCESTADO CODFORNECGERACAOFUNCEP  NUMBER(6,0)                                        Código Fornecedor geração do FUNCEP.            OPERACIONAL                        NaN
PCESTADO            CODESTADUAL  NUMBER(6,0)                                                            Código estadual.            OPERACIONAL                        NaN
PCESTADO             DTMXSALTER         DATE                                                                         NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*