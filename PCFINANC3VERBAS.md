# 📊 Tabela: PCFINANC3VERBAS

### Estrutura de Colunas e Restrições

         Tabela           Coluna Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFINANC3VERBAS   DATAREFERENCIA         DATE              Data de referencia dos dados (data)    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3VERBAS      DATAGERACAO         DATE            Data de geração dos dados (data/hora)            OPERACIONAL                        NaN
PCFINANC3VERBAS CODROTINAGERACAO  NUMBER(4,0)              Códido da rotina que gerou os dados    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3VERBAS        CODFILIAL  VARCHAR2(2)                       Código da filial do título    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3VERBAS         TIPODADO VARCHAR2(10)            Tipo de dado gerado como na PCFINANC2    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3VERBAS        CODFORNEC NUMBER(10,0)           Código do fornecedor vinculado a verba    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3VERBAS   CODFORNECPRINC NUMBER(10,0) Código do fornecedor principal vinculado a verba            OPERACIONAL                        NaN
PCFINANC3VERBAS        DTEMISSAO         DATE                  Data de emissão da verba (data)            OPERACIONAL                        NaN
PCFINANC3VERBAS           DTVENC         DATE               Data de vencimento da verba (data)            OPERACIONAL                        NaN
PCFINANC3VERBAS             TIPO  VARCHAR2(1)  Tipo do lançamento de verba (debito ou credito)            OPERACIONAL                        NaN
PCFINANC3VERBAS            VALOR NUMBER(24,8)                                   Valor da verba            OPERACIONAL                        NaN
PCFINANC3VERBAS         NUMVERBA NUMBER(10,0)                                  Número da verba    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3VERBAS        CODROTINA  NUMBER(6,0)              Código da rotina que lançou a verba            OPERACIONAL                        NaN
PCFINANC3VERBAS      NUMTRANSENT NUMBER(10,0)          Numero de transação de entrada da verba            OPERACIONAL                        NaN
PCFINANC3VERBAS    NUMTRANSCRFOR NUMBER(10,0)     Numero de transação de movimentação da verba    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*