# 📊 Tabela: PCLOGECOMMERCE

### Estrutura de Colunas e Restrições

        Tabela          Coluna Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGECOMMERCE              ID NUMBER(10,0)         Identificador de registro    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGECOMMERCE            DATA         DATE     Data de inclusão do registro            OPERACIONAL                        NaN
PCLOGECOMMERCE            ACAO VARCHAR2(50)                    Ações do log            OPERACIONAL                        NaN
PCLOGECOMMERCE  TIPOINTEGRACAO VARCHAR2(50)              Tipo de integração            OPERACIONAL                        NaN
PCLOGECOMMERCE         TIPOLOG VARCHAR2(50)                       Tipo de log            OPERACIONAL                        NaN
PCLOGECOMMERCE    CODIGOWITHOR NUMBER(10,0)                Código do winthor            OPERACIONAL                        NaN
PCLOGECOMMERCE CODIGOECOMMERCE NUMBER(10,0)              Código do ecommerce            OPERACIONAL                        NaN
PCLOGECOMMERCE        FILIALID NUMBER(10,0) Identificador da filial ecommerce CHAVE ESTRANGEIRA (FK)          PCFILIALECOMMERCE
PCLOGECOMMERCE         DETALHE         CLOB                   Detalhes do log            OPERACIONAL                        NaN
PCLOGECOMMERCE       MENSSAGEM         CLOB                   Mensagem do log            OPERACIONAL                        NaN
PCLOGECOMMERCE   FILIALWINTHOR NUMBER(10,0)   Identificador da filial winthor            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*