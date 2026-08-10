# 📊 Tabela: PCCONTROLECONSINCO

### Estrutura de Colunas e Restrições

            Tabela           Coluna  Tipo/Tamanho                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONTROLECONSINCO               ID  NUMBER(20,0)                                     Código sequencial    CHAVE PRIMÁRIA (PK)     PCTIPOPROCESSOCONSINCO
PCCONTROLECONSINCO      CODPROCESSO  NUMBER(20,0)       ID do processo da tabela PCTIPOPROCESSOCONSINCO            OPERACIONAL                        NaN
PCCONTROLECONSINCO   ULTIMAEXECUCAO  TIMESTAMP(6)                            Horário da última execução            OPERACIONAL                        NaN
PCCONTROLECONSINCO             TIPO   VARCHAR2(1)                                  [S]Subida [D]Descida            OPERACIONAL                        NaN
PCCONTROLECONSINCO OBJETOREFERENCIA VARCHAR2(200)                       Objeto de banco a ser executado            OPERACIONAL                        NaN
PCCONTROLECONSINCO      PRECEDENCIA   NUMBER(3,0)                    Identificador de ordem de execução            OPERACIONAL                        NaN
PCCONTROLECONSINCO            ATIVO   VARCHAR2(1)                              Indicativo para execução            OPERACIONAL                        NaN
PCCONTROLECONSINCO        DTCRIACAO  TIMESTAMP(6)                                       Data da criação            OPERACIONAL                        NaN
PCCONTROLECONSINCO      DTALTERACAO  TIMESTAMP(6)                                     Data de alteração            OPERACIONAL                        NaN
PCCONTROLECONSINCO      PROCESSANDO   VARCHAR2(1) Indica que a função de sincronização está processando            OPERACIONAL                        NaN
PCCONTROLECONSINCO        DESCRICAO  VARCHAR2(60)                 Descrição do processo a ser executado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*