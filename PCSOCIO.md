# 📊 Tabela: PCSOCIO

### Estrutura de Colunas e Restrições

 Tabela        Coluna Tipo/Tamanho                                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSOCIO      CODSOCIO  NUMBER(5,0)                                                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCSOCIO    NOME_SOCIO VARCHAR2(50)                                                                  NaN            OPERACIONAL                        NaN
PCSOCIO  CNPJ_CPF_CEI VARCHAR2(15) Indica a inscrição do sócio.|Campo do tipo caracter, de tamanho 15.             OPERACIONAL                        NaN
PCSOCIO            RG VARCHAR2(20)                                                                  NaN            OPERACIONAL                        NaN
PCSOCIO      ENDERECO VARCHAR2(50)                                                                  NaN            OPERACIONAL                        NaN
PCSOCIO        BAIRRO VARCHAR2(30)                                                                  NaN            OPERACIONAL                        NaN
PCSOCIO     CODCIDADE  NUMBER(6,0)                                                                  NaN            OPERACIONAL                        NaN
PCSOCIO           CEP VARCHAR2(10)                                                                  NaN            OPERACIONAL                        NaN
PCSOCIO    TELEFONE01 VARCHAR2(13)                                                                  NaN            OPERACIONAL                        NaN
PCSOCIO    TELEFONE02 VARCHAR2(13)                                                                  NaN            OPERACIONAL                        NaN
PCSOCIO       CELULAR VARCHAR2(13)                                                                  NaN            OPERACIONAL                        NaN
PCSOCIO         EMAIL VARCHAR2(70)                                                                  NaN            OPERACIONAL                        NaN
PCSOCIO REPRESENTANTE      CHAR(1)                                                                  NaN            OPERACIONAL                        NaN
PCSOCIO         CARGO VARCHAR2(30)                                             Indica o cargo do sócio.            OPERACIONAL                        NaN
PCSOCIO TIPOINSCRICAO  VARCHAR2(1)                         Indica o tipo da inscrição CNPJ, CPF ou CEI.            OPERACIONAL                        NaN
PCSOCIO        FUNCAO  VARCHAR2(4)                                                     Função do sócio.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*