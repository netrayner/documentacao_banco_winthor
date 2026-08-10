# 📊 Tabela: PCLICENCAHASH

### Estrutura de Colunas e Restrições

       Tabela        Coluna Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLICENCAHASH       LICENCA VARCHAR2(32)        Hash da tabela PCLICENCA            OPERACIONAL                        NaN
PCLICENCAHASH       PRODUTO VARCHAR2(32) Hash da tabela PCLICENCAPRODUTO            OPERACIONAL                        NaN
PCLICENCAHASH LICENCAPERFIL VARCHAR2(32)  Hash da tabela PCLICENCAROTINA            OPERACIONAL                        NaN
PCLICENCAHASH       USUARIO VARCHAR2(32) Hash da tabela PCUSUARIOLICENCA            OPERACIONAL                        NaN
PCLICENCAHASH        SESSAO VARCHAR2(32)  Hash da tabela PCUSUARIOSESSAO            OPERACIONAL                        NaN
PCLICENCAHASH          HASH VARCHAR2(32)    Hash da tabela PCLICENCAHASH            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*