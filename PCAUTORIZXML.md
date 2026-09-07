# 📊 Tabela: PCAUTORIZXML

### Estrutura de Colunas e Restrições

      Tabela              Coluna Tipo/Tamanho                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAUTORIZXML                TIPO  VARCHAR2(1) Define se o cadastro é um Cliente 'C' ou Fornecedor 'F'     CHAVE PRIMÁRIA (PK)                        NaN
PCAUTORIZXML              CODIGO  NUMBER(6,0)     Código do Fornecedor ou cliente de acordo com o TIPO    CHAVE PRIMÁRIA (PK)                        NaN
PCAUTORIZXML           CODFILIAL  VARCHAR2(2)                                         Código da Filial    CHAVE PRIMÁRIA (PK)                        NaN
PCAUTORIZXML          TIPOPESSOA  VARCHAR2(1)                        Tipo de pessoa Física ou Jurídica            OPERACIONAL                        NaN
PCAUTORIZXML                 CGC VARCHAR2(18)                CGC ou CPF de acordo com o TIPO de pessoa    CHAVE PRIMÁRIA (PK)                        NaN
PCAUTORIZXML         RAZAOSOCIAL VARCHAR2(60)                                             Razão Social            OPERACIONAL                        NaN
PCAUTORIZXML           DESCRICAO VARCHAR2(60)                                                Descrição            OPERACIONAL                        NaN
PCAUTORIZXML  CODFORNECPRODVENDA  NUMBER(6,0)                      Cód. Fornecedor do produto na venda            OPERACIONAL                        NaN
PCAUTORIZXML CODFORNECAUTORIZADO  NUMBER(6,0)       Cód. Fornecedor autorizado a fazer download do xml            OPERACIONAL                        NaN
PCAUTORIZXML      CGCAUTORIZAXML VARCHAR2(14)                      CNPJ/CPF do autorizado a baixar XML            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*