# 📊 Tabela: PCDOCEMITIDOSECF

### Estrutura de Colunas e Restrições

          Tabela          Coluna  Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDOCEMITIDOSECF     NUMSERIEECF  VARCHAR2(20)              Número de Série do ECF    CHAVE PRIMÁRIA (PK)                        NaN
PCDOCEMITIDOSECF       CODFILIAL   VARCHAR2(2)                    Código da Filial            OPERACIONAL                        NaN
PCDOCEMITIDOSECF        NUMCAIXA   NUMBER(3,0)                     Número do Caixa            OPERACIONAL                        NaN
PCDOCEMITIDOSECF           VALOR  NUMBER(14,2)                Valor do comprovante            OPERACIONAL                        NaN
PCDOCEMITIDOSECF             COO  NUMBER(10,0)                   Contador de ordem    CHAVE PRIMÁRIA (PK)                        NaN
PCDOCEMITIDOSECF             GNF  NUMBER(10,0)        Geral de operação não fiscal            OPERACIONAL                        NaN
PCDOCEMITIDOSECF             GRG  NUMBER(10,0)        Geral de relatório gerencial            OPERACIONAL                        NaN
PCDOCEMITIDOSECF             CDC  NUMBER(10,0)     Comprovante de débito e crédito            OPERACIONAL                        NaN
PCDOCEMITIDOSECF     DENOMINICAO   VARCHAR2(2)                 Tipo do Comprovante            OPERACIONAL                        NaN
PCDOCEMITIDOSECF            HORA   VARCHAR2(8)                 Hora do Comprovante            OPERACIONAL                        NaN
PCDOCEMITIDOSECF       EXPORTADO   VARCHAR2(1)            Exportação para Servidor            OPERACIONAL                        NaN
PCDOCEMITIDOSECF    DTEXPORTACAO          DATE  Data de Exportação para o Servidor            OPERACIONAL                        NaN
PCDOCEMITIDOSECF      ASSINATURA VARCHAR2(255)                        Código MD-5.            OPERACIONAL                        NaN
PCDOCEMITIDOSECF         TIPODOC   VARCHAR2(2)           Tipo do documento emitido            OPERACIONAL                        NaN
PCDOCEMITIDOSECF        ALTERADO   VARCHAR2(1)              Indica se foi alterado            OPERACIONAL                        NaN
PCDOCEMITIDOSECF     COOORIGINAL  NUMBER(10,0)              Número do COO original            OPERACIONAL                        NaN
PCDOCEMITIDOSECF      DATASTRING  VARCHAR2(20)                         Data string            OPERACIONAL                        NaN
PCDOCEMITIDOSECF          MD5PAF VARCHAR2(200)   Assinatura MD5 do registro do PAF            OPERACIONAL                        NaN
PCDOCEMITIDOSECF   NUMUSUARIOECF   NUMBER(4,0)   Indica o numero do usuario da ECF            OPERACIONAL                        NaN
PCDOCEMITIDOSECF            DATA          DATE              Data emissão documento            OPERACIONAL                        NaN
PCDOCEMITIDOSECF DATAHORAEMISSAO          DATE Data e hora de emissão de documento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*