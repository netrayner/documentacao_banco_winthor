# 📊 Tabela: PCMOTIVONAOATENDLAYOUT

### Estrutura de Colunas e Restrições

                Tabela            Coluna Tipo/Tamanho                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOTIVONAOATENDLAYOUT            LAYOUT  NUMBER(2,0)                                       Código do Layout    CHAVE PRIMÁRIA (PK)                        NaN
PCMOTIVONAOATENDLAYOUT CODMOTIVONAOATEND  NUMBER(3,0)                    Código do Motivo de Não Atendimento    CHAVE PRIMÁRIA (PK)                        NaN
PCMOTIVONAOATENDLAYOUT           TIPOREG  VARCHAR2(1) Tipo de Registro (C - Cabeçalho; I - Itens; A - Ambos)    CHAVE PRIMÁRIA (PK)                        NaN
PCMOTIVONAOATENDLAYOUT   CODMOTIVOLAYOUT VARCHAR2(10)              Código do Motivo no Layout correspondente            OPERACIONAL                        NaN
PCMOTIVONAOATENDLAYOUT  DESCMOTIVOLAYOUT VARCHAR2(60)           Descrição do Motivo no Layout correspondente            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*