# 📊 Tabela: PCRESTRICAOAVANCADA

### Estrutura de Colunas e Restrições

             Tabela                Coluna  Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRESTRICAOAVANCADA                CODIGO  NUMBER(10,0)                 Código da Restrição Avançada    CHAVE PRIMÁRIA (PK)                        NaN
PCRESTRICAOAVANCADA             DESCRICAO  VARCHAR2(70)                           Descrição Resumida            OPERACIONAL                        NaN
PCRESTRICAOAVANCADA    DESCRICAODETALHADA VARCHAR2(300)                          Descrição Detalhada            OPERACIONAL                        NaN
PCRESTRICAOAVANCADA           DATAINICIAL          DATE                                 Data Inicial            OPERACIONAL                        NaN
PCRESTRICAOAVANCADA             DATAFINAL          DATE                                   Data Final            OPERACIONAL                        NaN
PCRESTRICAOAVANCADA         TIPORESTRICAO   VARCHAR2(1) Tipo de Restrição (Exclusividade, Proibição)            OPERACIONAL                        NaN
PCRESTRICAOAVANCADA       LIBERARCOMSENHA   VARCHAR2(1)                            Liberar com Senha            OPERACIONAL                        NaN
PCRESTRICAOAVANCADA         TIPOVALIDACAO   VARCHAR2(1)      Tipo de validação (Capa, Itens e Ambos)            OPERACIONAL                        NaN
PCRESTRICAOAVANCADA VIGENCIAINDETERMINADA   VARCHAR2(1)      Define se a vigência será indeterminada            OPERACIONAL                        NaN
PCRESTRICAOAVANCADA     CODFILTROAVANCADO  NUMBER(10,0)                    Código do filtro avançado CHAVE ESTRANGEIRA (FK)           PCFILTROAVANCADO

---
*Documentação gerada automaticamente.*