# 📊 Tabela: PCCARREGFV

### Estrutura de Colunas e Restrições

    Tabela        Coluna   Tipo/Tamanho              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCARREGFV       CODUSUR    NUMBER(4,0)                    Código do RCA            OPERACIONAL                        NaN
PCCARREGFV   NUMCARMANIF    NUMBER(8,0) Número do carregamento manifesto            OPERACIONAL                        NaN
PCCARREGFV     IMPORTADO    NUMBER(1,0)               Status do registro            OPERACIONAL                        NaN
PCCARREGFV OBSERVACAO_PC VARCHAR2(4000)               Observações gerais            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*