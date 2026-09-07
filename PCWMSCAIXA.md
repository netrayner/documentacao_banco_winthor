# 📊 Tabela: PCWMSCAIXA

### Estrutura de Colunas e Restrições

    Tabela        Coluna  Tipo/Tamanho                                                                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCWMSCAIXA      CODCAIXA   NUMBER(8,0)                                                                                     Código da Caixa.            OPERACIONAL                        NaN
PCWMSCAIXA     DESCRICAO VARCHAR2(100)                                                                                  Descrição da Caixa.            OPERACIONAL                        NaN
PCWMSCAIXA        ALTURA   NUMBER(8,2)                                                                                     Altura da Caixa.            OPERACIONAL                        NaN
PCWMSCAIXA       LARGURA   NUMBER(8,2)                                                                                    Largura da Caixa.            OPERACIONAL                        NaN
PCWMSCAIXA   COMPRIMENTO   NUMBER(8,2)                                                                                Comprimento da Caixa.            OPERACIONAL                        NaN
PCWMSCAIXA        VOLUME  NUMBER(15,8)                                                                                    Volume da Caixa .            OPERACIONAL                        NaN
PCWMSCAIXA      SITUACAO   VARCHAR2(1)                                                                                   Situação da Caixa.            OPERACIONAL                        NaN
PCWMSCAIXA       TAMANHO   VARCHAR2(1)                                                Tamanho da caixa - P - Pequena ,M - Média, G - Grande            OPERACIONAL                        NaN
PCWMSCAIXA MATERIALCAIXA   VARCHAR2(2)                                                       Material da caixa: PA - PAPELÃO, PL - PLÁSTICA            OPERACIONAL                        NaN
PCWMSCAIXA    RETORNAVEL   VARCHAR2(1)                                                             Se caixa é retornável: S - Sim, N - Não.            OPERACIONAL                        NaN
PCWMSCAIXA        STATUS   VARCHAR2(1) D  - Disponível,  U - Utilizado, C - Em Conferencia, T - Em Trânsito, A - Avariado,  E - Extraviado.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*