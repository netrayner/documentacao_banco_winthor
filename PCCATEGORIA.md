# 📊 Tabela: PCCATEGORIA

### Estrutura de Colunas e Restrições

     Tabela              Coluna  Tipo/Tamanho                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCATEGORIA              CODSEC   NUMBER(6,0)                                                NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCATEGORIA        CODCATEGORIA   NUMBER(6,0)                                                NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCATEGORIA           CATEGORIA  VARCHAR2(40)                                                NaN            OPERACIONAL                        NaN
PCCATEGORIA IDINTEGRACAOCIASHOP VARCHAR2(250)      Referência da categoria no E-commerce CiaShop            OPERACIONAL                        NaN
PCCATEGORIA      ENVIAECOMMERCE   VARCHAR2(1) Identifica se o produto será enviado ao e-commerce            OPERACIONAL                        NaN
PCCATEGORIA          DTULTALTER          DATE                           Data da ultima alteração            OPERACIONAL                        NaN
PCCATEGORIA          DTCADASTRO          DATE                                   Data de cadastro            OPERACIONAL                        NaN
PCCATEGORIA          DTMXSALTER          DATE                                                NaN            OPERACIONAL                        NaN
PCCATEGORIA              STATUS   VARCHAR2(1)                                                NaN            OPERACIONAL                        NaN
PCCATEGORIA           DTALTERC5  TIMESTAMP(6)                                     Data alteracao            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*