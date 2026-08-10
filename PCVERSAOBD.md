# 📊 Tabela: PCVERSAOBD

### Estrutura de Colunas e Restrições

    Tabela          Coluna  Tipo/Tamanho                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVERSAOBD          ROTINA  VARCHAR2(50)                     Rotina que altera o BD    CHAVE PRIMÁRIA (PK)                        NaN
PCVERSAOBD           OPCAO   NUMBER(6,0)                            Opção da rotina    CHAVE PRIMÁRIA (PK)                        NaN
PCVERSAOBD          VERSAO  VARCHAR2(15)                     Versão atual da rotina            OPERACIONAL                        NaN
PCVERSAOBD       DESCRICAO VARCHAR2(255)     Descrição que será mostrada ao usuário            OPERACIONAL                        NaN
PCVERSAOBD   DTATUALIZACAO          DATE                                        NaN            OPERACIONAL                        NaN
PCVERSAOBD DTSINCRONIZACAO          DATE Data da ultima sincronização do CCW Agente            OPERACIONAL                        NaN
PCVERSAOBD   DTBUILDROTINA          DATE                                        NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*