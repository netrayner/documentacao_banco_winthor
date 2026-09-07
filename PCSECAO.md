# 📊 Tabela: PCSECAO

### Estrutura de Colunas e Restrições

 Tabela              Coluna  Tipo/Tamanho                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSECAO              CODSEC   NUMBER(6,0)                                                NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCSECAO           DESCRICAO  VARCHAR2(40)                                                NaN            OPERACIONAL                        NaN
PCSECAO             CODEPTO   NUMBER(6,0)                                                NaN            OPERACIONAL                        NaN
PCSECAO               QTMAX  NUMBER(10,3)                                                NaN            OPERACIONAL                        NaN
PCSECAO                TIPO   VARCHAR2(1)                                                NaN            OPERACIONAL                        NaN
PCSECAO        CODSECNESTLE   NUMBER(6,0)                                                NaN            OPERACIONAL                        NaN
PCSECAO               LINHA  VARCHAR2(20)                                   Linha do produto            OPERACIONAL                        NaN
PCSECAO          DTEXCLUSAO          DATE                              Data exclusão produto            OPERACIONAL                        NaN
PCSECAO IDINTEGRACAOCIASHOP VARCHAR2(250)          Referência da seção no E-commerce CiaShop            OPERACIONAL                        NaN
PCSECAO      ENVIAECOMMERCE   VARCHAR2(1) Identifica se o produto será enviado ao e-commerce            OPERACIONAL                        NaN
PCSECAO          DTULTALTER          DATE                           Data da ultima alteração            OPERACIONAL                        NaN
PCSECAO          DTCADASTRO          DATE                                   Data de cadastro            OPERACIONAL                        NaN
PCSECAO          DTMXSALTER          DATE                                                NaN            OPERACIONAL                        NaN
PCSECAO              STATUS   VARCHAR2(1)                                                NaN            OPERACIONAL                        NaN
PCSECAO           DTALTERC5  TIMESTAMP(6)                                     Data alteracao            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*