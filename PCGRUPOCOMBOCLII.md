# 📊 Tabela: PCGRUPOCOMBOCLII

### Estrutura de Colunas e Restrições

          Tabela            Coluna Tipo/Tamanho                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGRUPOCOMBOCLII            CODIGO NUMBER(10,0)                                         Codigo sequencial    CHAVE PRIMÁRIA (PK)                        NaN
PCGRUPOCOMBOCLII CODGRUPOCOMBOCLIC NUMBER(10,0)                           Código do cabeçalho da campanha            OPERACIONAL                        NaN
PCGRUPOCOMBOCLII    CODIGOCAMPANHA NUMBER(10,0)                                        Código da campanha            OPERACIONAL                        NaN
PCGRUPOCOMBOCLII           PERDESC NUMBER(18,6)                   %Desconto a ser concedido pela campanha            OPERACIONAL                        NaN
PCGRUPOCOMBOCLII                QT NUMBER(18,6) Quantidade a ser vendida do combo para validar a campanha            OPERACIONAL                        NaN
PCGRUPOCOMBOCLII        DTMXSALTER         DATE                                                       NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*