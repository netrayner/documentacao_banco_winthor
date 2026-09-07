# 📊 Tabela: PCINTEGRACOESLOGISTICAS

### Estrutura de Colunas e Restrições

                 Tabela    Coluna  Tipo/Tamanho                                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACOESLOGISTICAS    TABELA  VARCHAR2(50)                                         Nome da tabela no Winthor            OPERACIONAL                        NaN
PCINTEGRACOESLOGISTICAS        ID  NUMBER(10,0)                                           Identificador da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRACOESLOGISTICAS     CAMPO  VARCHAR2(50)                       Campo chave primária da tabela especificada            OPERACIONAL                        NaN
PCINTEGRACOESLOGISTICAS IDINTERNO VARCHAR2(100) ID Interno do Winhor para comparação e que equivale ao ID Externo            OPERACIONAL                        NaN
PCINTEGRACOESLOGISTICAS IDEXTERNO VARCHAR2(100) ID Externo para comparação e que equivale ao ID Interno do Winhor            OPERACIONAL                        NaN
PCINTEGRACOESLOGISTICAS  IDVIAGEM  NUMBER(10,0)                        Identificador da viagem do sistema externo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*