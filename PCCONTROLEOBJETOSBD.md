# 📊 Tabela: PCCONTROLEOBJETOSBD

### Estrutura de Colunas e Restrições

             Tabela         Coluna  Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONTROLEOBJETOSBD     NOMEOBJETO VARCHAR2(100)                    Nome do objeto no banco de dados            OPERACIONAL                        NaN
PCCONTROLEOBJETOSBD  EM_UTILIZACAO   VARCHAR2(1)  Flag que diz se o objeto esta em uso ou não (S, N)            OPERACIONAL                        NaN
PCCONTROLEOBJETOSBD           DATA          DATE                        Data de registro do controle            OPERACIONAL                        NaN
PCCONTROLEOBJETOSBD       PROGRAMA  VARCHAR2(60)     Programa que esta ou estava utilizando o objeto            OPERACIONAL                        NaN
PCCONTROLEOBJETOSBD        MAQUINA  VARCHAR2(60)      Maquina onde o programa estava sendo executado            OPERACIONAL                        NaN
PCCONTROLEOBJETOSBD       TERMINAL  VARCHAR2(60)     Terminal onde o programa estava sendo executado            OPERACIONAL                        NaN
PCCONTROLEOBJETOSBD         OSUSER  VARCHAR2(60)    Usuario da rede que estava utilizando o programa            OPERACIONAL                        NaN
PCCONTROLEOBJETOSBD USUARIOWINTHOR  VARCHAR2(60) Usuario do Winthor que estava utilizando o programa            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*