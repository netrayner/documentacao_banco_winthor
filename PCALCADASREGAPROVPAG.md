# 📊 Tabela: PCALCADASREGAPROVPAG

### Estrutura de Colunas e Restrições

              Tabela         Coluna Tipo/Tamanho                                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCALCADASREGAPROVPAG      CODFILIAL  VARCHAR2(2)                          Código da filial do lançamento e do item da alçada CHAVE ESTRANGEIRA (FK)         PCALCADASAPROVPAGI
PCALCADASREGAPROVPAG      CODALCADA NUMBER(10,0)        Código da alçada vinculada ao item da alçada que gerou a autorização CHAVE ESTRANGEIRA (FK)         PCALCADASAPROVPAGI
PCALCADASREGAPROVPAG  CODALCADAITEM NUMBER(10,0)                            Código do item da alçada que gerou a autorização CHAVE ESTRANGEIRA (FK)         PCALCADASAPROVPAGI
PCALCADASREGAPROVPAG         RECNUM NUMBER(10,0)                          Número do lançamento que utilizou o item da alçada            OPERACIONAL                        NaN
PCALCADASREGAPROVPAG          VALOR NUMBER(16,4)                                                         Valor do lançamento            OPERACIONAL                        NaN
PCALCADASREGAPROVPAG   VLLIMITELANC NUMBER(16,4)                        Valor limite definido no item da alçada do pagamento            OPERACIONAL                        NaN
PCALCADASREGAPROVPAG     VLSALDODIA NUMBER(16,4)     Saldo restante gerado a partir do uso do limite total do item de alçada            OPERACIONAL                        NaN
PCALCADASREGAPROVPAG     CODFUNCAUT NUMBER(10,0)                 Código do usuário que autorizou e utilizou o item da alcada            OPERACIONAL                        NaN
PCALCADASREGAPROVPAG          DTREG         DATE                   Data e hora do momento em que o lançamento foi autorizado            OPERACIONAL                        NaN
PCALCADASREGAPROVPAG       OPERACAO  VARCHAR2(1)        Operação de "A" para autorização ou "D" desautorização do lançamento            OPERACIONAL                        NaN
PCALCADASREGAPROVPAG DTALCADAORIGEM  VARCHAR2(2) Data do registro de autorização do lançamento no momento da desautorização.            OPERACIONAL                        NaN
PCALCADASREGAPROVPAG  CALCULARSALDO  VARCHAR2(1)                  Determina se o registro entrará ou não no calculo do saldo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*