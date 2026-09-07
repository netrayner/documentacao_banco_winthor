# 📊 Tabela: PCLOGGERACAOLIVROFISCAL

### Estrutura de Colunas e Restrições

                 Tabela      Coluna  Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGGERACAOLIVROFISCAL      CODLOG   NUMBER(8,0)                  Código do Log.    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGGERACAOLIVROFISCAL        TIPO   VARCHAR2(1)     Tipo de movimentação (E/S).            OPERACIONAL                        NaN
PCLOGGERACAOLIVROFISCAL   CODFILIAL   VARCHAR2(2)               Código da filial.            OPERACIONAL                        NaN
PCLOGGERACAOLIVROFISCAL    DTINICIO          DATE        Data inicial de geração.            OPERACIONAL                        NaN
PCLOGGERACAOLIVROFISCAL       DTFIM          DATE          Data final de geração.            OPERACIONAL                        NaN
PCLOGGERACAOLIVROFISCAL DATAGERACAO          DATE                Data da geração.            OPERACIONAL                        NaN
PCLOGGERACAOLIVROFISCAL    TERMINAL VARCHAR2(200)           Terminal de execução.            OPERACIONAL                        NaN
PCLOGGERACAOLIVROFISCAL  OS_USUARIO  VARCHAR2(30) Usuário do sistema operacional.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*