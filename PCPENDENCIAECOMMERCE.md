# 📊 Tabela: PCPENDENCIAECOMMERCE

### Estrutura de Colunas e Restrições

              Tabela                 Coluna  Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPENDENCIAECOMMERCE                     ID  NUMBER(10,0)              Identificador de registro    CHAVE PRIMÁRIA (PK)                        NaN
PCPENDENCIAECOMMERCE              DESCRICAO VARCHAR2(250)              Descrição da pendência            OPERACIONAL                        NaN
PCPENDENCIAECOMMERCE         DTHORAREGISTRO          DATE   Data e hora da inclusão do registro            OPERACIONAL                        NaN
PCPENDENCIAECOMMERCE         TIPOINTEGRACAO  VARCHAR2(50)                   Tipo de integração            OPERACIONAL                        NaN
PCPENDENCIAECOMMERCE               EXCLUIDO   NUMBER(1,0) Inform a se o registro está excluído            OPERACIONAL                        NaN
PCPENDENCIAECOMMERCE               FILIALID  NUMBER(10,0)            Código da filial ecommerce CHAVE ESTRANGEIRA (FK)          PCFILIALECOMMERCE
PCPENDENCIAECOMMERCE CATALOGOPENDECIACODIGO  NUMBER(10,0)    Código do catálogo de pendências CHAVE ESTRANGEIRA (FK)        PCCATALOGOPENDENCIA
PCPENDENCIAECOMMERCE              CODIGOERP  NUMBER(10,0)                         Código do ERP            OPERACIONAL                        NaN
PCPENDENCIAECOMMERCE           CODIGOPEDWEB  NUMBER(10,0)                  Código do pedido web            OPERACIONAL                        NaN
PCPENDENCIAECOMMERCE          FILIALWINTHOR   VARCHAR2(2)              Código da filial winthor            OPERACIONAL                        NaN
PCPENDENCIAECOMMERCE             CGCCLIENTE  VARCHAR2(32)            Cnpj do cliente que comprou            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*