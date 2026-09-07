# 📊 Tabela: PCCARTACORRECAOI

### Estrutura de Colunas e Restrições

          Tabela                Coluna   Tipo/Tamanho            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCARTACORRECAOI      NUMCARTACORRECAO   NUMBER(10,0)                            NaN            OPERACIONAL                        NaN
PCCARTACORRECAOI        IDITEMCORRECAO    NUMBER(3,0)                            NaN            OPERACIONAL                        NaN
PCCARTACORRECAOI DESCRICAOITEMCORRECAO  VARCHAR2(100)                            NaN            OPERACIONAL                        NaN
PCCARTACORRECAOI     DESCRICAOCORRECAO VARCHAR2(1000)                            NaN            OPERACIONAL                        NaN
PCCARTACORRECAOI         GRUPOALTERADO   VARCHAR2(20) Grupo de informações alteradas            OPERACIONAL                        NaN
PCCARTACORRECAOI         CAMPOALTERADO   VARCHAR2(20)      Nome do campo modificado.            OPERACIONAL                        NaN
PCCARTACORRECAOI         VALORALTERADO VARCHAR2(1500)             Valor da alteração            OPERACIONAL                        NaN
PCCARTACORRECAOI       NUMITEMALTERADO    VARCHAR2(2)       Indice do item alterado.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*