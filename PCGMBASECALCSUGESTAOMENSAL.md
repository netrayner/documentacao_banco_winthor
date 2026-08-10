# 📊 Tabela: PCGMBASECALCSUGESTAOMENSAL

### Estrutura de Colunas e Restrições

                    Tabela         Coluna Tipo/Tamanho                                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGMBASECALCSUGESTAOMENSAL        CODMETA NUMBER(10,0)                                                                               Código da meta    CHAVE PRIMÁRIA (PK)                   PCGMMETA
PCGMBASECALCSUGESTAOMENSAL  CODCOMBINACAO NUMBER(10,0)                                                 Código da combinacao da parametrização atual    CHAVE PRIMÁRIA (PK)             PCGMCOMBINACAO
PCGMBASECALCSUGESTAOMENSAL           DATA         DATE                                                                                          NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCGMBASECALCSUGESTAOMENSAL VLSAZONALIDADE  NUMBER(8,2)                                                       Valor da taxa de sazonalidade aplicada            OPERACIONAL                        NaN
PCGMBASECALCSUGESTAOMENSAL     VLPROPOSTO NUMBER(12,2) Valor proposto calculado de acordo com o histórico, taxas e sazonalidade, sugerido para meta            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*