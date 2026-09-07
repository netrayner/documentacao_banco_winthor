# 📊 Tabela: PCMEDICOPRESCRIT

### Estrutura de Colunas e Restrições

          Tabela            Coluna  Tipo/Tamanho          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMEDICOPRESCRIT CODMEDICOPRESCRIT   NUMBER(6,0) Código do Médico Prescritor.    CHAVE PRIMÁRIA (PK)                        NaN
PCMEDICOPRESCRIT              NOME  VARCHAR2(40)              Nome do Médico.            OPERACIONAL                        NaN
PCMEDICOPRESCRIT            NUMCRM  VARCHAR2(14)               Número do CRM.            OPERACIONAL                        NaN
PCMEDICOPRESCRIT          ENDERECO  VARCHAR2(70)                    Endereço.            OPERACIONAL                        NaN
PCMEDICOPRESCRIT       COMPLEMENTO  VARCHAR2(20)                 Complemento.            OPERACIONAL                        NaN
PCMEDICOPRESCRIT               CEP   VARCHAR2(9)                         CEP.            OPERACIONAL                        NaN
PCMEDICOPRESCRIT            CIDADE  VARCHAR2(30)                      Cidade.            OPERACIONAL                        NaN
PCMEDICOPRESCRIT                UF   VARCHAR2(2)                          UF.            OPERACIONAL                        NaN
PCMEDICOPRESCRIT          TELEFONE  VARCHAR2(20)                    Telefone.            OPERACIONAL                        NaN
PCMEDICOPRESCRIT               FAX  VARCHAR2(20)                         Fax.            OPERACIONAL                        NaN
PCMEDICOPRESCRIT           DATACAD          DATE               Data Cadastro.            OPERACIONAL                        NaN
PCMEDICOPRESCRIT             EMAIL VARCHAR2(100)                      E-mail.            OPERACIONAL                        NaN
PCMEDICOPRESCRIT               URL  VARCHAR2(80)                Endereço WEB.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*