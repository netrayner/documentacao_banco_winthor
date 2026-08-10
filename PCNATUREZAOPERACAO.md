# 📊 Tabela: PCNATUREZAOPERACAO

### Estrutura de Colunas e Restrições

            Tabela          Coluna Tipo/Tamanho                                                                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCNATUREZAOPERACAO       CODFISCAL  NUMBER(8,0) CFOP - Código Fiscal de Operações e de Prestações das Entradas de Mercadorias e Bens e da Aquisição de Serviços    CHAVE PRIMÁRIA (PK)                        NaN
PCNATUREZAOPERACAO         CODOPER  VARCHAR2(2)                                                                      Código da Operação movimentação de estoque    CHAVE PRIMÁRIA (PK)                        NaN
PCNATUREZAOPERACAO       DESCRICAO VARCHAR2(60)                                                                              Nome da natureza da operação (NOP)            OPERACIONAL                        NaN
PCNATUREZAOPERACAO CODROTINAORIGEM  NUMBER(4,0)                                                                          Código da Rotina emissora do documento            OPERACIONAL                        NaN
PCNATUREZAOPERACAO      DTCADASTRO         DATE                                                                                                Data do Cadastro            OPERACIONAL                        NaN
PCNATUREZAOPERACAO      DTEXCLUSAO         DATE                                  DATA DE EXCLUSÃO DO LANÇAMENTO. UTILIZADA PARA IDENTIFICAR LANÇAMENTO INATIVOS            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*