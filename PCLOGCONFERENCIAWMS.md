# 📊 Tabela: PCLOGCONFERENCIAWMS

### Estrutura de Colunas e Restrições

             Tabela      Coluna Tipo/Tamanho                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGCONFERENCIAWMS        DATA         DATE                                         Data do LOG.            OPERACIONAL                        NaN
PCLOGCONFERENCIAWMS      NUMCAR  NUMBER(8,0)                              Número do Carregamento.            OPERACIONAL                        NaN
PCLOGCONFERENCIAWMS  NUMSEQCONF NUMBER(20,0)                            Número sequencial do LOG.            OPERACIONAL                        NaN
PCLOGCONFERENCIAWMS       NUMOS NUMBER(10,0) Número da ordem de serviço que está sendo conferida.            OPERACIONAL                        NaN
PCLOGCONFERENCIAWMS     CODPROD  NUMBER(6,0)          Código do produto que está sendo conferido.            OPERACIONAL                        NaN
PCLOGCONFERENCIAWMS          QT NUMBER(20,8)                                Quantidade conferida.            OPERACIONAL                        NaN
PCLOGCONFERENCIAWMS CODFUNCCONF  NUMBER(8,0)     Código do funcionário que conferiu a mercadoria.            OPERACIONAL                        NaN
PCLOGCONFERENCIAWMS   CODROTINA  NUMBER(6,0)     Número da rotina que gerou o registro na tabela.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*