# 📊 Tabela: PCPORTOS

### Estrutura de Colunas e Restrições

  Tabela              Coluna  Tipo/Tamanho                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPORTOS            CODPORTO  NUMBER(10,0)                                           Código do Porto.    CHAVE PRIMÁRIA (PK)                        NaN
PCPORTOS           DESCRICAO  VARCHAR2(40)                                        Descrição do Porto.            OPERACIONAL                        NaN
PCPORTOS               SIGLA   VARCHAR2(5)                                            Sigla do Porto.            OPERACIONAL                        NaN
PCPORTOS         CODSISCOMEX  NUMBER(10,0)                                  Código SISCOMEX do Porto.            OPERACIONAL                        NaN
PCPORTOS            ENDERECO  VARCHAR2(40)                                         Endereço do Porto.            OPERACIONAL                        NaN
PCPORTOS           CODCIDADE  NUMBER(10,0)                                           Cidade do Porto.            OPERACIONAL                        NaN
PCPORTOS                  UF   VARCHAR2(2)                                           Estado do Porto.            OPERACIONAL                        NaN
PCPORTOS                 CEP   NUMBER(8,0)                                              CEP do Porto.            OPERACIONAL                        NaN
PCPORTOS             CODPAIS  NUMBER(10,0)                                             País do Porto.            OPERACIONAL                        NaN
PCPORTOS            TELEFONE  NUMBER(10,0)                                         Telefone do Porto.            OPERACIONAL                        NaN
PCPORTOS                 FAX  NUMBER(10,0)                                              Fax do Porto.            OPERACIONAL                        NaN
PCPORTOS               EMAIL VARCHAR2(100)                                            Email do Porto.            OPERACIONAL                        NaN
PCPORTOS             CONTATO  VARCHAR2(40)                                          Contato do Porto.            OPERACIONAL                        NaN
PCPORTOS        UNRECFEDNOME  VARCHAR2(40)               Nome da Unidade da Receita Federal do Porto.            OPERACIONAL                        NaN
PCPORTOS       UNRECFEDSIGLA   VARCHAR2(5)              Sigla da Unidade da Receita Federal do Porto.            OPERACIONAL                        NaN
PCPORTOS UNRECFEDCODSISCOMEX  NUMBER(10,0)    Código SISCOMEX da Unidade da Receita Federal do Porto.            OPERACIONAL                        NaN
PCPORTOS           CODFORNEC   NUMBER(6,0) Código do fornecedor responsável pelo armazém alfandegário            OPERACIONAL                        NaN
PCPORTOS         RAZAOSOCIAL  VARCHAR2(60)                                              Razão Social.            OPERACIONAL                        NaN
PCPORTOS                  IE  VARCHAR2(14)                                        Inscrição Estadual.            OPERACIONAL                        NaN
PCPORTOS            CNPJ_CPF  VARCHAR2(14)                                               Cnpj ou CPF.            OPERACIONAL                        NaN
PCPORTOS              NUMERO  VARCHAR2(60)                                           Número do Porto.            OPERACIONAL                        NaN
PCPORTOS         COMPLEMENTO  VARCHAR2(60)                                      Complemento do Porto.            OPERACIONAL                        NaN
PCPORTOS              BAIRRO  VARCHAR2(60)                                           Bairro do Porto.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*