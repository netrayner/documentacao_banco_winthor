# 📊 Tabela: PCDADOSXML

### Estrutura de Colunas e Restrições

    Tabela       Coluna  Tipo/Tamanho                                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDADOSXML NUMTRANSITEM  NUMBER(18,0)                                            Sequencial da coluna conforme pcmov e pcmovcomple    CHAVE PRIMÁRIA (PK)                        NaN
PCDADOSXML        VPROD  NUMBER(22,6)                                                   Valor Total Bruto dos Produtos ou Serviços            OPERACIONAL                        NaN
PCDADOSXML      VUNTRIB NUMBER(22,10)                                                                 Valor Unitário de tributação            OPERACIONAL                        NaN
PCDADOSXML        VDESC  NUMBER(22,6)                                                                            Valor do Desconto            OPERACIONAL                        NaN
PCDADOSXML          VBC  NUMBER(22,6)                                                                          Valor da BC do ICMS            OPERACIONAL                        NaN
PCDADOSXML        VICMS  NUMBER(22,6)                                                                                Valor do ICMS            OPERACIONAL                        NaN
PCDADOSXML        VBCST  NUMBER(22,6)                                                                       Valor da BC do ICMS ST            OPERACIONAL                        NaN
PCDADOSXML      VICMSST  NUMBER(22,6)                                                                             Valor do ICMS ST            OPERACIONAL                        NaN
PCDADOSXML     VICMSDIF  NUMBER(22,6)                                                                       Valor do ICMS diferido            OPERACIONAL                        NaN
PCDADOSXML         CEAN  VARCHAR2(14)            GTIN (Global Trade Item Number) do produto, antigo código EAN ou código de barras            OPERACIONAL                        NaN
PCDADOSXML     CEANTRIB  VARCHAR2(14) GTIN (Global Trade Item Number) da unidade tributável, antigo código EAN ou código de barras            OPERACIONAL                        NaN
PCDADOSXML       VOUTRO  NUMBER(22,6)                                                                   Outras despesas acessórias            OPERACIONAL                        NaN
PCDADOSXML   VICMSDESON  NUMBER(22,6)                                                                     Valor do ICMS desonerado            OPERACIONAL                        NaN
PCDADOSXML          VII  NUMBER(22,6)                                                                  Valor Imposto de Importação            OPERACIONAL                        NaN
PCDADOSXML       VFRETE  NUMBER(22,6)                                                                         Valor Total do Frete            OPERACIONAL                        NaN
PCDADOSXML         VSEG  NUMBER(22,6)                                                                       Valor Total do Seguro             OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*