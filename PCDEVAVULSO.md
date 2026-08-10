# 📊 Tabela: PCDEVAVULSO

### Estrutura de Colunas e Restrições

     Tabela          Coluna  Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDEVAVULSO   NUMTRANSVENDA  NUMBER(10,0)       Indica o número da transação de saída.            OPERACIONAL                        NaN
PCDEVAVULSO     NUMTRANSENT  NUMBER(10,0)     Indica o número da transação de entrada.            OPERACIONAL                        NaN
PCDEVAVULSO         NUMNOTA  NUMBER(10,0)              Indica o número da nota fiscal.            OPERACIONAL                        NaN
PCDEVAVULSO           SERIE   VARCHAR2(3)               Indica a serie da nota fiscal.            OPERACIONAL                        NaN
PCDEVAVULSO       DTEMISSAO          DATE     Indica a data de emissão da nota fiscal.            OPERACIONAL                        NaN
PCDEVAVULSO        CHAVENFE  VARCHAR2(45)          Chave NFe da nota fiscal de entrada            OPERACIONAL                        NaN
PCDEVAVULSO          MODELO   VARCHAR2(2)                      Modelo da NF de entrada            OPERACIONAL                        NaN
PCDEVAVULSO         CODPAIS   NUMBER(6,0)              Código de identificação do país            OPERACIONAL                        NaN
PCDEVAVULSO   CNPJCPFFORNEC  VARCHAR2(18)                       CNPJ ou CPF fornecedor            OPERACIONAL                        NaN
PCDEVAVULSO    INSCESTADUAL  VARCHAR2(14)             Inscrição Estadual do fornecedor            OPERACIONAL                        NaN
PCDEVAVULSO          CODMUN   VARCHAR2(7)   Código do município conforme a tabela IBGE            OPERACIONAL                        NaN
PCDEVAVULSO     INSCSUFRAMA   VARCHAR2(9) Número de inscrição do fornecedor na SUFRAMA            OPERACIONAL                        NaN
PCDEVAVULSO  ENDERECOFORNEC  VARCHAR2(60)              Logradouro e endereço do imóvel            OPERACIONAL                        NaN
PCDEVAVULSO NUMIMOVELFORNEC  VARCHAR2(10)                             Número do imóvel            OPERACIONAL                        NaN
PCDEVAVULSO  COMPLENDFORNEC  VARCHAR2(60)             Dados complementares do endereço            OPERACIONAL                        NaN
PCDEVAVULSO    BAIRROFORNEC  VARCHAR2(60)          Bairro em que o imóvel está situado            OPERACIONAL                        NaN
PCDEVAVULSO      NOMEFORNEC VARCHAR2(100)    Nome pessoal ou empresarial do fornecedor            OPERACIONAL                        NaN
PCDEVAVULSO       CODFORNEC   VARCHAR2(6)        Código de identificação do fornecedor            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*