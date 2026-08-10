# 📊 Tabela: PCCONTATO

### Estrutura de Colunas e Restrições

   Tabela              Coluna   Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONTATO              CODCLI    NUMBER(6,0)                                          NaN            OPERACIONAL                        NaN
PCCONTATO         NOMECONTATO   VARCHAR2(40)                                          NaN            OPERACIONAL                        NaN
PCCONTATO         TIPOCONTATO    VARCHAR2(1)                                          NaN            OPERACIONAL                        NaN
PCCONTATO              CGCCPF   VARCHAR2(18)                                          NaN            OPERACIONAL                        NaN
PCCONTATO        DTNASCIMENTO           DATE                                          NaN            OPERACIONAL                        NaN
PCCONTATO              HOBBIE   VARCHAR2(50)                                          NaN            OPERACIONAL                        NaN
PCCONTATO                TIME   VARCHAR2(30)                                          NaN            OPERACIONAL                        NaN
PCCONTATO         NOMECONJUGE   VARCHAR2(40)                                          NaN            OPERACIONAL                        NaN
PCCONTATO       DTNASCCONJUGE           DATE                                          NaN            OPERACIONAL                        NaN
PCCONTATO            ENDERECO   VARCHAR2(40)                                          NaN            OPERACIONAL                        NaN
PCCONTATO              BAIRRO   VARCHAR2(30)                                          NaN            OPERACIONAL                        NaN
PCCONTATO              CIDADE   VARCHAR2(30)                                          NaN            OPERACIONAL                        NaN
PCCONTATO                 CEP    VARCHAR2(9)                                          NaN            OPERACIONAL                        NaN
PCCONTATO               CARGO   VARCHAR2(30)                                          NaN            OPERACIONAL                        NaN
PCCONTATO            TELEFONE   VARCHAR2(18)                                          NaN            OPERACIONAL                        NaN
PCCONTATO             CELULAR   VARCHAR2(18)                                          NaN            OPERACIONAL                        NaN
PCCONTATO               EMAIL   VARCHAR2(50)                                          NaN            OPERACIONAL                        NaN
PCCONTATO             AUTORCH    VARCHAR2(1)                                          NaN            OPERACIONAL                        NaN
PCCONTATO              ESTADO    VARCHAR2(2)                                          NaN            OPERACIONAL                        NaN
PCCONTATO                 DOC   VARCHAR2(20)                                          NaN            OPERACIONAL                        NaN
PCCONTATO          CODCONTATO    NUMBER(6,0)                                          NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTATO       PARTICIPSOCIO    NUMBER(5,2)                                          NaN            OPERACIONAL                        NaN
PCCONTATO         DTSOCIEDADE           DATE Data de entrada do socio no contrato social.            OPERACIONAL                        NaN
PCCONTATO                 OBS VARCHAR2(1000)             Indica a observação do contrato.            OPERACIONAL                        NaN
PCCONTATO           CGCCPFAUX   VARCHAR2(14)                 Indica CNPJ/CPF sem mascara.            OPERACIONAL                        NaN
PCCONTATO                  RG   VARCHAR2(20)      Registro geral para contato procurador.            OPERACIONAL                        NaN
PCCONTATO          AUTORIZADO    VARCHAR2(1)                           Contato autorizado            OPERACIONAL                        NaN
PCCONTATO            CODBANCO    NUMBER(4,0)                              Código do banco            OPERACIONAL                        NaN
PCCONTATO             AGENCIA    VARCHAR2(6)                                      Agência            OPERACIONAL                        NaN
PCCONTATO               CONTA   VARCHAR2(10)                               Conta corrente            OPERACIONAL                        NaN
PCCONTATO MOTIVONAOAUTORIZADO VARCHAR2(2000)                 Motivo de não ser autorizado            OPERACIONAL                        NaN
PCCONTATO          DTBLOQUEIO           DATE                             Data de bloqueio            OPERACIONAL                        NaN
PCCONTATO       DTDESBLOQUEIO           DATE                          Data de desbloqueio            OPERACIONAL                        NaN
PCCONTATO     CODFUNCBLOQUEIO    NUMBER(8,0)                 Cód. funcionário de bloqueio            OPERACIONAL                        NaN
PCCONTATO  CODFUNCDESBLOQUEIO    NUMBER(8,0)              Cód. funcionário de desbloqueio            OPERACIONAL                        NaN
PCCONTATO               SENHA   VARCHAR2(32)         Senha de login do contato do cliente            OPERACIONAL                        NaN
PCCONTATO          DTMXSALTER           DATE                                          NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*