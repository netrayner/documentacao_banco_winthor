# 📊 Tabela: PCLOGTRANSFVIRTRET

### Estrutura de Colunas e Restrições

            Tabela        Coluna Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGTRANSFVIRTRET      DTTRANSF         DATE                        Data da transferência            OPERACIONAL                        NaN
PCLOGTRANSFVIRTRET NUMTRANSVENDA NUMBER(11,0)                          Número da transação            OPERACIONAL                        NaN
PCLOGTRANSFVIRTRET       CODPROD  NUMBER(6,0)                            Código do produto            OPERACIONAL                        NaN
PCLOGTRANSFVIRTRET        NUMSEQ NUMBER(20,0) Número da sequeência do prodtuo na transação            OPERACIONAL                        NaN
PCLOGTRANSFVIRTRET PRECOORIGINAL NUMBER(18,6)                               Preço original            OPERACIONAL                        NaN
PCLOGTRANSFVIRTRET   PSEMIMPOSTO NUMBER(18,6)                            Preço sem imposto            OPERACIONAL                        NaN
PCLOGTRANSFVIRTRET       PERCIPI NUMBER(18,6)                            Percentual de IPI            OPERACIONAL                        NaN
PCLOGTRANSFVIRTRET       BASEIPI NUMBER(18,6)                                  Base de IPI            OPERACIONAL                        NaN
PCLOGTRANSFVIRTRET         VLIPI NUMBER(18,6)                                 Valor do IPI            OPERACIONAL                        NaN
PCLOGTRANSFVIRTRET        BASEST NUMBER(18,6)                                   Base do ST            OPERACIONAL                        NaN
PCLOGTRANSFVIRTRET            ST NUMBER(18,6)                                  Valor do ST            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*