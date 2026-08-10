# 📊 Tabela: PCSUPPLIFILIAL

### Estrutura de Colunas e Restrições

        Tabela              Coluna  Tipo/Tamanho         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSUPPLIFILIAL       CODIGOEMPRESA   VARCHAR2(2)           Código da empresa            OPERACIONAL                        NaN
PCSUPPLIFILIAL        CODIGOFILIAL   VARCHAR2(4)     Código da filial D+Cred            OPERACIONAL                        NaN
PCSUPPLIFILIAL CODIGOFILIALWINTHOR   VARCHAR2(2) Código da filial do Winthor            OPERACIONAL                        NaN
PCSUPPLIFILIAL   CODIGOFUNCIONARIO  VARCHAR2(22)       Código do funcionário            OPERACIONAL                        NaN
PCSUPPLIFILIAL          CODIGOLOJA   VARCHAR2(4)              Código da loja            OPERACIONAL                        NaN
PCSUPPLIFILIAL       DIRETORIOSFTP VARCHAR2(100)           Diretório do SFTP            OPERACIONAL                        NaN
PCSUPPLIFILIAL                  ID  NUMBER(22,0)             Chave da tabela    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*