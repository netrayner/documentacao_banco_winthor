# 📊 Tabela: PCBANDEIRASITEF

### Estrutura de Colunas e Restrições

         Tabela          Coluna  Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBANDEIRASITEF  CODIGOBANDEIRA   NUMBER(8,0)            Código da bandeira do TEF    CHAVE PRIMÁRIA (PK)                        NaN
PCBANDEIRASITEF        BANDEIRA  VARCHAR2(50)                     Nome da bandeira            OPERACIONAL                        NaN
PCBANDEIRASITEF    TIPOBANDEIRA  VARCHAR2(25) Tipo (VOUCHER, CREDITO, DEBITO, etc)    CHAVE PRIMÁRIA (PK)                        NaN
PCBANDEIRASITEF SUBTIPOBANDEIRA  VARCHAR2(25)                  Subtipo da bandeira            OPERACIONAL                        NaN
PCBANDEIRASITEF        DETALHES VARCHAR2(400)      Detalhes de uso e comportamento            OPERACIONAL                        NaN
PCBANDEIRASITEF           ATIVO   VARCHAR2(1)                Bandeira ativa ou não            OPERACIONAL                        NaN
PCBANDEIRASITEF         TIPOTEF  VARCHAR2(50)                      Tipo: S - SITEF            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*