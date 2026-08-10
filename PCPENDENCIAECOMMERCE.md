# 📊 Tabela: PCPENDENCIAECOMMERCE

### Estrutura de Colunas e Restrições

              Tabela                 Coluna  Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPENDENCIAECOMMERCE                     ID  NUMBER(10,0)              Identificador de registro    CHAVE PRIMÁRIA (PK)                        NaN
PCPENDENCIAECOMMERCE              DESCRICAO VARCHAR2(250)              DescriÃ§Ã£o da pendÃªncia            OPERACIONAL                        NaN
PCPENDENCIAECOMMERCE         DTHORAREGISTRO          DATE   Data e hora da inclusÃ£o do registro            OPERACIONAL                        NaN
PCPENDENCIAECOMMERCE         TIPOINTEGRACAO  VARCHAR2(50)                   Tipo de integraÃ§Ã£o            OPERACIONAL                        NaN
PCPENDENCIAECOMMERCE               EXCLUIDO   NUMBER(1,0) Inform a se o registro estÃ¡ excluÃ­do            OPERACIONAL                        NaN
PCPENDENCIAECOMMERCE               FILIALID  NUMBER(10,0)            CÃ³digo da filial ecommerce CHAVE ESTRANGEIRA (FK)          PCFILIALECOMMERCE
PCPENDENCIAECOMMERCE CATALOGOPENDECIACODIGO  NUMBER(10,0)    CÃ³digo do catÃ¡logo de pendÃªncias CHAVE ESTRANGEIRA (FK)        PCCATALOGOPENDENCIA
PCPENDENCIAECOMMERCE              CODIGOERP  NUMBER(10,0)                         CÃ³digo do ERP            OPERACIONAL                        NaN
PCPENDENCIAECOMMERCE           CODIGOPEDWEB  NUMBER(10,0)                  CÃ³digo do pedido web            OPERACIONAL                        NaN
PCPENDENCIAECOMMERCE          FILIALWINTHOR   VARCHAR2(2)              CÃ³digo da filial winthor            OPERACIONAL                        NaN
PCPENDENCIAECOMMERCE             CGCCLIENTE  VARCHAR2(32)            Cnpj do cliente que comprou            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*