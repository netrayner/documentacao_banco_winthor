# 📊 Tabela: PCVLFRETEAUTONOMOPESOKM

### Estrutura de Colunas e Restrições

                 Tabela          Coluna Tipo/Tamanho Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVLFRETEAUTONOMOPESOKM    FAIXAINICIAL NUMBER(12,4)       Faixa Inicial            OPERACIONAL                        NaN
PCVLFRETEAUTONOMOPESOKM      FAIXAFINAL NUMBER(12,4)         Faixa Final            OPERACIONAL                        NaN
PCVLFRETEAUTONOMOPESOKM VALORREFERENCIA NUMBER(12,4)    Valor Referência            OPERACIONAL                        NaN
PCVLFRETEAUTONOMOPESOKM     CODFILIALNF  VARCHAR2(2)    Código da Filial CHAVE ESTRANGEIRA (FK)               PCTRIBOUTROS
PCVLFRETEAUTONOMOPESOKM       UFDESTINO  VARCHAR2(2)          UF Destino CHAVE ESTRANGEIRA (FK)               PCTRIBOUTROS

---
*Documentação gerada automaticamente.*