# 📊 Tabela: PCTIPOBONIFIC

### Estrutura de Colunas e Restrições

       Tabela         Coluna Tipo/Tamanho                                                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTIPOBONIFIC         CODBNF  NUMBER(6,0)                                                    Código do tipo de bonificação.    CHAVE PRIMÁRIA (PK)                        NaN
PCTIPOBONIFIC      DESCRICAO VARCHAR2(60)                                                 Descrição do tipo de bonificação.            OPERACIONAL                        NaN
PCTIPOBONIFIC MOVIMENTACCRCA  VARCHAR2(1)                                                   MOVIMENTA CONTA CORRENTE DO RCA            OPERACIONAL                        NaN
PCTIPOBONIFIC    BONIFPADRAO  VARCHAR2(1)                   VERIFICA SE A BONIFICAÇÃO CORRENTE É A PADRÃO DENTRE AS DEMAIS.            OPERACIONAL                        NaN
PCTIPOBONIFIC     CALCULAIPI  VARCHAR2(1)                                                                               NaN            OPERACIONAL                        NaN
PCTIPOBONIFIC       CODCONTA NUMBER(10,0) Conta gerencial que deve ser lançado a bonificação ao faturar o pedido bonificado            OPERACIONAL                        NaN
PCTIPOBONIFIC     DTMXSALTER         DATE                                                                               NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*