# 📊 Tabela: PCSNGPCCOMPRADOR

### Estrutura de Colunas e Restrições

          Tabela       Coluna  Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSNGPCCOMPRADOR     CPFCOMPR  VARCHAR2(14)                          CPF do Comprador    CHAVE PRIMÁRIA (PK)                        NaN
PCSNGPCCOMPRADOR    NOMECOMPR VARCHAR2(100)                            Nome Comprador            OPERACIONAL                        NaN
PCSNGPCCOMPRADOR CODTIPODOCUM   NUMBER(2,0)  Código do Tipo de Documento do Comprador            OPERACIONAL                        NaN
PCSNGPCCOMPRADOR TIPOORGAOEXP   VARCHAR2(8) Orgão Expedidor do Documento do Comprador            OPERACIONAL                        NaN
PCSNGPCCOMPRADOR     NUMDOCUM  VARCHAR2(30)          Número do Documento do Comprador            OPERACIONAL                        NaN
PCSNGPCCOMPRADOR      UFDOCUM   VARCHAR2(2)      UF Emissão do Documento do Comprador            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*