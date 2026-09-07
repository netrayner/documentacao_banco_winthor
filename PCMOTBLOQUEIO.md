# 📊 Tabela: PCMOTBLOQUEIO

### Estrutura de Colunas e Restrições

       Tabela    Coluna Tipo/Tamanho                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOTBLOQUEIO CODMOTIVO  NUMBER(6,0)                                             NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCMOTBLOQUEIO DESCRICAO VARCHAR2(60)                                             NaN            OPERACIONAL                        NaN
PCMOTBLOQUEIO      TIPO  NUMBER(2,0)                        Indica tipo de bloqueio.            OPERACIONAL                        NaN
PCMOTBLOQUEIO    ORIGEM  NUMBER(1,0) Indica a origem do bloqueio do pedido de venda.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*