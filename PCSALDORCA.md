# 📊 Tabela: PCSALDORCA

### Estrutura de Colunas e Restrições

    Tabela            Coluna Tipo/Tamanho                                                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSALDORCA           CODUSUR  NUMBER(6,0)                             Código do RCA. |Campo do tipo numérico, de tamanho 6, sem casas decimais.    CHAVE PRIMÁRIA (PK)                        NaN
PCSALDORCA           VLSALDO NUMBER(12,6)                  Valor do saldo atual do RCA. |Campo do tipo numérico, de tamanho 12, com 6 decimais.            OPERACIONAL                        NaN
PCSALDORCA        VLSALDOANT NUMBER(12,6) Valor do saldo anterior a última atualização. |Campo do tipo numérico, de tamanho 12, com 6 decimais.            OPERACIONAL                        NaN
PCSALDORCA   SALDORESERVAANT NUMBER(18,6)                                                                Valor do saldo reserva do RCA anterior            OPERACIONAL                        NaN
PCSALDORCA SALDORESERVAATUAL NUMBER(18,6)                                                                   Valor do saldo reserva do RCA atual            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*