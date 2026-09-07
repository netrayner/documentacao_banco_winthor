# 📊 Tabela: PCLOGREPOSICAOVAREJOMED

### Estrutura de Colunas e Restrições

                 Tabela           Coluna  Tipo/Tamanho      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGREPOSICAOVAREJOMED        CODFILIAL   VARCHAR2(2)  Código da Filial Origem    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGREPOSICAOVAREJOMED CODFILIALDESTINO   VARCHAR2(2) Código da Filial Destino    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGREPOSICAOVAREJOMED   DATAPROCAGENDA          DATE    Data de Processamento    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGREPOSICAOVAREJOMED       CODFUNCGER   NUMBER(8,0)  Matrícula da execução\t            OPERACIONAL                        NaN
PCLOGREPOSICAOVAREJOMED         MENSAGEM VARCHAR2(240)         Mensagem de Logx            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*