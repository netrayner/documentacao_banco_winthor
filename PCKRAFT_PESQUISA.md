# 📊 Tabela: PCKRAFT_PESQUISA

### Estrutura de Colunas e Restrições

          Tabela           Coluna Tipo/Tamanho                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCKRAFT_PESQUISA           CODCLI  NUMBER(6,0)                    Código do cliente.    CHAVE PRIMÁRIA (PK)                        NaN
PCKRAFT_PESQUISA             DATA         DATE          Data de geração do registro.    CHAVE PRIMÁRIA (PK)                        NaN
PCKRAFT_PESQUISA          MODELEZ  VARCHAR2(1)                       Possui modelez.            OPERACIONAL                        NaN
PCKRAFT_PESQUISA MODELEZMEIOMETRO  VARCHAR2(1) Possui modelez a 1,5 metro do balcão.            OPERACIONAL                        NaN
PCKRAFT_PESQUISA   MIXOBRIGATORIO  VARCHAR2(1)               Possui mix obrigatorio.            OPERACIONAL                        NaN
PCKRAFT_PESQUISA         PROMOCAO  VARCHAR2(1)                      Possui promoção.            OPERACIONAL                        NaN
PCKRAFT_PESQUISA      OBSPROMOCAO VARCHAR2(40)          Observação sobre a promoção.            OPERACIONAL                        NaN
PCKRAFT_PESQUISA       PLANOGRAMA  VARCHAR2(1)                    Possui planograma.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*