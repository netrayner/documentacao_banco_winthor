# 📊 Tabela: PCLOGTAE

### Estrutura de Colunas e Restrições

  Tabela       Coluna  Tipo/Tamanho                                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGTAE    CODLOGTAE   NUMBER(8,0)                                               Identificador da tabela,    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGTAE      CODFUNC   NUMBER(8,0)      Código do funcionário que solicitou a requisição com a API do TAE CHAVE ESTRANGEIRA (FK)                     PCEMPR
PCLOGTAE     NUMVERBA   NUMBER(6,0) Número da verba do contrato que estava em requisição com a API do TAE. CHAVE ESTRANGEIRA (FK)                    PCVERBA
PCLOGTAE DATAINCLUSAO          DATE                                Data da inclusão do registro na tabela.            OPERACIONAL                        NaN
PCLOGTAE     ENDPOINT VARCHAR2(100)                           End-point da API do TAE que foi requisitada.            OPERACIONAL                        NaN
PCLOGTAE          LOG          CLOB     Informações complementares do retorno da requisição da API do TAE.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*