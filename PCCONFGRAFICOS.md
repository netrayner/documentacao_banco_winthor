# 📊 Tabela: PCCONFGRAFICOS

### Estrutura de Colunas e Restrições

        Tabela    Coluna  Tipo/Tamanho   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONFGRAFICOS    CODIGO   NUMBER(9,0)     Código do grafico            OPERACIONAL                        NaN
PCCONFGRAFICOS DESCRICAO VARCHAR2(100)  Descrição do grafico            OPERACIONAL                        NaN
PCCONFGRAFICOS CABECALHO VARCHAR2(100) Cabeçalho para rotina            OPERACIONAL                        NaN
PCCONFGRAFICOS    EIXO_X VARCHAR2(100)       campo de eixo x            OPERACIONAL                        NaN
PCCONFGRAFICOS    EIXO_Y VARCHAR2(100)       campo de eixo y            OPERACIONAL                        NaN
PCCONFGRAFICOS USER_CONF   NUMBER(9,0)               usuario            OPERACIONAL                        NaN
PCCONFGRAFICOS      DATA          DATE        data alteração            OPERACIONAL                        NaN
PCCONFGRAFICOS     ATIVO   VARCHAR2(1)                status            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*