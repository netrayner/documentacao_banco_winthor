# 📊 Tabela: PCECOMMERCEUNILEVERCLIENTE

### Estrutura de Colunas e Restrições

                    Tabela     Coluna Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCECOMMERCEUNILEVERCLIENTE  CODFILIAL  VARCHAR2(2) Código da filial que recebeu o cliente    CHAVE PRIMÁRIA (PK)                   PCFILIAL
PCECOMMERCEUNILEVERCLIENTE     CODCLI  NUMBER(6,0)                      Código do cliente    CHAVE PRIMÁRIA (PK)                   PCCLIENT
PCECOMMERCEUNILEVERCLIENTE DTINCLUSAO         DATE                       Data de cadastro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*