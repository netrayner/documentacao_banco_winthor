# 📊 Tabela: PCEXCECAOPISCOFINS

### Estrutura de Colunas e Restrições

            Tabela           Coluna Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEXCECAOPISCOFINS       CODEXCECAO  NUMBER(8,0)                          Código Exceção    CHAVE PRIMÁRIA (PK)                        NaN
PCEXCECAOPISCOFINS CODTRIBPISCOFINS  NUMBER(4,0)               Código Tribut. PIS/COFINS            OPERACIONAL                        NaN
PCEXCECAOPISCOFINS             TIPO  VARCHAR2(2)                                 Tipo ST            OPERACIONAL                        NaN
PCEXCECAOPISCOFINS            VALOR VARCHAR2(10)               Valor Excessão PIS/COFINS            OPERACIONAL                        NaN
PCEXCECAOPISCOFINS    CODEXCFIGTRIB  NUMBER(4,0) Código da Exceção da Figura Tributária.            OPERACIONAL                        NaN
PCEXCECAOPISCOFINS            TIPO2 VARCHAR2(10)                            Segundo Tipo            OPERACIONAL                        NaN
PCEXCECAOPISCOFINS           VALOR2 VARCHAR2(10)                           Segundo Valor            OPERACIONAL                        NaN
PCEXCECAOPISCOFINS            TIPO3 VARCHAR2(10)                           Terceiro Tipo            OPERACIONAL                        NaN
PCEXCECAOPISCOFINS           VALOR3 VARCHAR2(10)                          Terceiro Valor            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*