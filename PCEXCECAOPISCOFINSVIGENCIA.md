# 📊 Tabela: PCEXCECAOPISCOFINSVIGENCIA

### Estrutura de Colunas e Restrições

                    Tabela           Coluna Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEXCECAOPISCOFINSVIGENCIA       CODEXCECAO  NUMBER(8,0)                          Código Exceção    CHAVE PRIMÁRIA (PK)                        NaN
PCEXCECAOPISCOFINSVIGENCIA CODTRIBPISCOFINS  NUMBER(4,0)               Código Tribut. PIS/COFINS            OPERACIONAL                        NaN
PCEXCECAOPISCOFINSVIGENCIA         DTINICIO         DATE               Data inicial de vingência    CHAVE PRIMÁRIA (PK)                        NaN
PCEXCECAOPISCOFINSVIGENCIA          DTFINAL         DATE                 Data final de vingência    CHAVE PRIMÁRIA (PK)                        NaN
PCEXCECAOPISCOFINSVIGENCIA             TIPO  VARCHAR2(2)                                 Tipo ST            OPERACIONAL                        NaN
PCEXCECAOPISCOFINSVIGENCIA            VALOR VARCHAR2(10)               Valor Excessão PIS/COFINS            OPERACIONAL                        NaN
PCEXCECAOPISCOFINSVIGENCIA    CODEXCFIGTRIB  NUMBER(4,0) C?digo da Exceção da Figura Tributária.            OPERACIONAL                        NaN
PCEXCECAOPISCOFINSVIGENCIA            TIPO2 VARCHAR2(10)                            Segundo Tipo            OPERACIONAL                        NaN
PCEXCECAOPISCOFINSVIGENCIA           VALOR2 VARCHAR2(10)                           Segundo Valor            OPERACIONAL                        NaN
PCEXCECAOPISCOFINSVIGENCIA            TIPO3 VARCHAR2(10)                           Terceiro Tipo            OPERACIONAL                        NaN
PCEXCECAOPISCOFINSVIGENCIA           VALOR3 VARCHAR2(10)                          Terceiro Valor            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*