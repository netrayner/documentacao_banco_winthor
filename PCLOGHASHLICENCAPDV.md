# 📊 Tabela: PCLOGHASHLICENCAPDV

### Estrutura de Colunas e Restrições

             Tabela         Coluna Tipo/Tamanho                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGHASHLICENCAPDV        MAQUINA VARCHAR2(64)               Máquina que está alterando            OPERACIONAL                        NaN
PCLOGHASHLICENCAPDV           DATA         DATE                         Data da gravação            OPERACIONAL                        NaN
PCLOGHASHLICENCAPDV       NUMCAIXA  NUMBER(4,0)                          Número do caixa            OPERACIONAL                        NaN
PCLOGHASHLICENCAPDV       PROGRAMA VARCHAR2(64)             Aplicação que está alterando            OPERACIONAL                        NaN
PCLOGHASHLICENCAPDV         OSUSER VARCHAR2(64)                            Usuário do SO            OPERACIONAL                        NaN
PCLOGHASHLICENCAPDV      QTLICENCA  NUMBER(3,0)                   Quantidade de licenças            OPERACIONAL                        NaN
PCLOGHASHLICENCAPDV QTLICENCAEMUSO  NUMBER(3,0) Quantidade de licenças em uso no momento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*