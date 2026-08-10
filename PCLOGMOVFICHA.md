# 📊 Tabela: PCLOGMOVFICHA

### Estrutura de Colunas e Restrições

       Tabela         Coluna Tipo/Tamanho                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGMOVFICHA        CODUSUR  NUMBER(8,0) Código do atendente (ou garçom) que auxiliou o cliente da mesa.            OPERACIONAL                        NaN
PCLOGMOVFICHA      MATRICULA  NUMBER(8,0)                          Matrícula do usuário logado na rotina.            OPERACIONAL                        NaN
PCLOGMOVFICHA       NUMFICHA NUMBER(10,0)                                                 Número da mesa.            OPERACIONAL                        NaN
PCLOGMOVFICHA     DTABERTURA         DATE                                Data e hora da abertura da mesa.            OPERACIONAL                        NaN
PCLOGMOVFICHA     DTGRAVACAO         DATE                                Data e hora da gravação da mesa.            OPERACIONAL                        NaN
PCLOGMOVFICHA DTCANCELAMENTO         DATE                  Data e hora do cancelamento da edição da mesa.            OPERACIONAL                        NaN
PCLOGMOVFICHA      CODFILIAL  VARCHAR2(3)                         Código da filial a qual é gerado o log.            OPERACIONAL                        NaN
PCLOGMOVFICHA        NUMORCA NUMBER(10,0)                                             Número de Orçamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*