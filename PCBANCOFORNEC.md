# 📊 Tabela: PCBANCOFORNEC

### Estrutura de Colunas e Restrições

       Tabela        Coluna  Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBANCOFORNEC     CODFORNEC   NUMBER(6,0)                  Código do Fornecedor.    CHAVE PRIMÁRIA (PK)                        NaN
PCBANCOFORNEC          IBAN  VARCHAR2(20)          Identificação do código iBan.    CHAVE PRIMÁRIA (PK)                        NaN
PCBANCOFORNEC         BANCO  VARCHAR2(10)                Identificação do Banco.            OPERACIONAL                        NaN
PCBANCOFORNEC       AGENCIA  VARCHAR2(10)              Identificação da Agência.            OPERACIONAL                        NaN
PCBANCOFORNEC CONTACORRENTE  VARCHAR2(20)          Identificação conta corrente.            OPERACIONAL                        NaN
PCBANCOFORNEC         SWIFT  VARCHAR2(20)   Código Swift emitido pelo banqueiro.            OPERACIONAL                        NaN
PCBANCOFORNEC      ENDERECO VARCHAR2(200) Endereço completo da agência bancária.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*