# 📊 Tabela: PCSUBCATEGORIA

### Estrutura de Colunas e Restrições

        Tabela              Coluna  Tipo/Tamanho                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSUBCATEGORIA              CODSEC   NUMBER(6,0)                                                NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCSUBCATEGORIA        CODCATEGORIA   NUMBER(6,0)                                                NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCSUBCATEGORIA     CODSUBCATEGORIA   NUMBER(6,0)                                                NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCSUBCATEGORIA        SUBCATEGORIA  VARCHAR2(40)                                                NaN            OPERACIONAL                        NaN
PCSUBCATEGORIA IDINTEGRACAOCIASHOP VARCHAR2(250)  Referência da sub-categoria no E-commerce CiaShop            OPERACIONAL                        NaN
PCSUBCATEGORIA      ENVIAECOMMERCE   VARCHAR2(1) Identifica se o produto será enviado ao e-commerce            OPERACIONAL                        NaN
PCSUBCATEGORIA          DTMXSALTER          DATE                                                NaN            OPERACIONAL                        NaN
PCSUBCATEGORIA              STATUS   VARCHAR2(1)                                                NaN            OPERACIONAL                        NaN
PCSUBCATEGORIA          DTULTALTER          DATE    Data da última alteração feita na subcategoria.            OPERACIONAL                        NaN
PCSUBCATEGORIA          DTCADASTRO          DATE                   Data do cadastro da subcategoria            OPERACIONAL                        NaN
PCSUBCATEGORIA           DTALTERC5  TIMESTAMP(6)                                     DATA ALTERACAO            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*