# 📊 Tabela: PCPRESTACAOCONTADETALHE

### Estrutura de Colunas e Restrições

                 Tabela              Coluna Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRESTACAOCONTADETALHE CODPRESTACAODETALHE NUMBER(10,0)   Código Chave Primária da Item Despesa    CHAVE PRIMÁRIA (PK)                        NaN
PCPRESTACAOCONTADETALHE   NUMPRESTACAOCONTA NUMBER(10,0) Código Chave Extrangeira para Prestação CHAVE ESTRANGEIRA (FK)           PCPRESTACAOCONTA
PCPRESTACAOCONTADETALHE           DTDESPESA         DATE                         Data da Despesa            OPERACIONAL                        NaN
PCPRESTACAOCONTADETALHE            CODCONTA NUMBER(10,0)       Código Chave Extrangeira da Conta CHAVE ESTRANGEIRA (FK)                    PCCONTA
PCPRESTACAOCONTADETALHE           CODCIDADE  NUMBER(6,0)      Código Chave Extrangeira da Cidade CHAVE ESTRANGEIRA (FK)                   PCCIDADE
PCPRESTACAOCONTADETALHE        DETALHAMENTO VARCHAR2(50)               Descrição do Detalhamento            OPERACIONAL                        NaN
PCPRESTACAOCONTADETALHE       TIPODOCUMENTO  VARCHAR2(2)                       Tipo de Documento            OPERACIONAL                        NaN
PCPRESTACAOCONTADETALHE        NUMDOCUMENTO NUMBER(22,0)                     Número do Documento            OPERACIONAL                        NaN
PCPRESTACAOCONTADETALHE               VALOR NUMBER(12,2)                        Valor da Despesa            OPERACIONAL                        NaN
PCPRESTACAOCONTADETALHE       STATUSDESPESA  VARCHAR2(2)                       Status da Despesa            OPERACIONAL                        NaN
PCPRESTACAOCONTADETALHE       CODAPROVADOR1 NUMBER(10,0)               Código Primeiro Aprovador            OPERACIONAL                        NaN
PCPRESTACAOCONTADETALHE       CODAPROVADOR2 NUMBER(10,0)                Código Segundo Aprovador            OPERACIONAL                        NaN
PCPRESTACAOCONTADETALHE    STATUSAPROVADOR1  VARCHAR2(1)            Status do Primeiro Aprovador            OPERACIONAL                        NaN
PCPRESTACAOCONTADETALHE    STATUSAPROVADOR2  VARCHAR2(1)             Status do Segundo Aprovador            OPERACIONAL                        NaN
PCPRESTACAOCONTADETALHE    MOTIVOAPROVACAO1 VARCHAR2(50)            Motivo do Primeiro Aprovador            OPERACIONAL                        NaN
PCPRESTACAOCONTADETALHE    MOTIVOAPROVACAO2 VARCHAR2(50)             Motivo do Segundo Aprovador            OPERACIONAL                        NaN
PCPRESTACAOCONTADETALHE     DTHORAAPROVACAO         DATE                       Data da Aprovação            OPERACIONAL                        NaN
PCPRESTACAOCONTADETALHE CODUSUARIOALTERACAO NUMBER(10,0)                Código Usuário alteração            OPERACIONAL                        NaN
PCPRESTACAOCONTADETALHE     DTHORAALTERACAO         DATE                       Data da Alteração            OPERACIONAL                        NaN
PCPRESTACAOCONTADETALHE              RECNUM NUMBER(10,0)    Código Chave Extrangeira para PCLANC CHAVE ESTRANGEIRA (FK)                     PCLANC

---
*Documentação gerada automaticamente.*