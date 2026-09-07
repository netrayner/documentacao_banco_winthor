# 📊 Tabela: PCLICITDOCUMENTOS

### Estrutura de Colunas e Restrições

           Tabela              Coluna  Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLICITDOCUMENTOS        CODDOCUMENTO  NUMBER(12,0)             Codigo Do Documento    CHAVE PRIMÁRIA (PK)                        NaN
PCLICITDOCUMENTOS           DESCRICAO VARCHAR2(200)          Descrição do documento            OPERACIONAL                        NaN
PCLICITDOCUMENTOS    CODTIPODOCUMENTO   NUMBER(6,0)     Codigo do tipo de documento            OPERACIONAL                        NaN
PCLICITDOCUMENTOS           CODFILIAL   VARCHAR2(2)                Codigo da filial            OPERACIONAL                        NaN
PCLICITDOCUMENTOS              CODCLI   NUMBER(6,0)               Codigo do cliente            OPERACIONAL                        NaN
PCLICITDOCUMENTOS           CODFORNEC   NUMBER(6,0)            Codigo do fornecedor            OPERACIONAL                        NaN
PCLICITDOCUMENTOS             CODPROD  NUMBER(10,0)               Codigo do produto            OPERACIONAL                        NaN
PCLICITDOCUMENTOS           CODEDITAL   NUMBER(9,0)                Codigo do edital            OPERACIONAL                        NaN
PCLICITDOCUMENTOS           PROTOCOLO VARCHAR2(200)          Protoloco do documento            OPERACIONAL                        NaN
PCLICITDOCUMENTOS            RETIRADA          DATE           Retirada do documento            OPERACIONAL                        NaN
PCLICITDOCUMENTOS             EMISSAO          DATE            Emissão do documento            OPERACIONAL                        NaN
PCLICITDOCUMENTOS            VALIDADE          DATE            Validade do documnto            OPERACIONAL                        NaN
PCLICITDOCUMENTOS              COPIAS   NUMBER(6,0)            Copias do documentos            OPERACIONAL                        NaN
PCLICITDOCUMENTOS          DIAS_AVISO   NUMBER(4,0)     Dias de aviso pro documento            OPERACIONAL                        NaN
PCLICITDOCUMENTOS          OBSERVACAO VARCHAR2(250)         Observação do documento            OPERACIONAL                        NaN
PCLICITDOCUMENTOS          DESATIVADO   VARCHAR2(1)        Desativação do documento            OPERACIONAL                        NaN
PCLICITDOCUMENTOS    DTULTDESATIVACAO          DATE      Data da ultima desativação            OPERACIONAL                        NaN
PCLICITDOCUMENTOS CODLICITGRUPOFORNEC   NUMBER(3,0) Codigo do grupo de fornecedores            OPERACIONAL                        NaN
PCLICITDOCUMENTOS         RESPONSAVEL   NUMBER(8,0)      Responsavel pelo documento            OPERACIONAL                        NaN
PCLICITDOCUMENTOS           CODPERFIL   NUMBER(6,0) Perfil do usuario pro documento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*