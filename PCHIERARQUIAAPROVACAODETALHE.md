# 📊 Tabela: PCHIERARQUIAAPROVACAODETALHE

### Estrutura de Colunas e Restrições

                      Tabela               Coluna Tipo/Tamanho                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCHIERARQUIAAPROVACAODETALHE CODHIERARQUIADETALHE NUMBER(10,0)                                Código Chave Primária da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCHIERARQUIAAPROVACAODETALHE        CODHIERARQUIA NUMBER(10,0)                       Código Chave Extrangeira para Hierarquia CHAVE ESTRANGEIRA (FK)      PCHIERARQUIAAPROVACAO
PCHIERARQUIAAPROVACAODETALHE       CODSOLICITANTE NUMBER(10,0)                                          Código do Solicitante            OPERACIONAL                        NaN
PCHIERARQUIAAPROVACAODETALHE    CODIGOCENTROCUSTO VARCHAR2(40)                     Código Chave Extrangeira para Centro Custo CHAVE ESTRANGEIRA (FK)              PCCENTROCUSTO
PCHIERARQUIAAPROVACAODETALHE      TIPOSOLICITANTE  VARCHAR2(1) Tipo Solicitante (F=funcionário, M=Motorista, V=Vendedor(RCA))            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*