# 📊 Tabela: PCENDERECOENTREGAPEDIDO

### Estrutura de Colunas e Restrições

                 Tabela      Coluna Tipo/Tamanho                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCENDERECOENTREGAPEDIDO      NUMPED NUMBER(10,0) Um número único para identificar o pedido.    CHAVE PRIMÁRIA (PK)                        NaN
PCENDERECOENTREGAPEDIDO    ENDERECO VARCHAR2(40)          Descrição do endereço de entrega.            OPERACIONAL                        NaN
PCENDERECOENTREGAPEDIDO      NUMERO  VARCHAR2(6)             Número do endereço de entrega.            OPERACIONAL                        NaN
PCENDERECOENTREGAPEDIDO COMPLEMENTO VARCHAR2(80)        Complemento do endereço de entrega.            OPERACIONAL                        NaN
PCENDERECOENTREGAPEDIDO      BAIRRO VARCHAR2(40)             Bairro do endereço de entrega.            OPERACIONAL                        NaN
PCENDERECOENTREGAPEDIDO   MUNICIPIO VARCHAR2(15)          Municipio do endereço de entrega.            OPERACIONAL                        NaN
PCENDERECOENTREGAPEDIDO      ESTADO  VARCHAR2(2)             Estado do endereço de entrega.            OPERACIONAL                        NaN
PCENDERECOENTREGAPEDIDO         CEP  VARCHAR2(9)                Cep do endereço de entrega.            OPERACIONAL                        NaN
PCENDERECOENTREGAPEDIDO    TELEFONE VARCHAR2(13)              Telefone no local de entrega.            OPERACIONAL                        NaN
PCENDERECOENTREGAPEDIDO         FAX VARCHAR2(15)                   Fax no local de entrega.            OPERACIONAL                        NaN
PCENDERECOENTREGAPEDIDO   CODCIDADE  NUMBER(6,0)               Número da cidade de entrega.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*