# 📊 Tabela: PCLOGCOMISSAO

### Estrutura de Colunas e Restrições

       Tabela                Coluna  Tipo/Tamanho              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGCOMISSAO                  DATA          DATE               Data do Fechamento            OPERACIONAL                        NaN
PCLOGCOMISSAO               CODFUNC   NUMBER(8,0)            Código do Funcionário            OPERACIONAL                        NaN
PCLOGCOMISSAO             CODROTINA   NUMBER(6,0)                 Código da Rotina            OPERACIONAL                        NaN
PCLOGCOMISSAO               PERIODO  VARCHAR2(30)            Período de fechamento            OPERACIONAL                        NaN
PCLOGCOMISSAO             CODSUPERV  VARCHAR2(30)             Código do Supervisor            OPERACIONAL                        NaN
PCLOGCOMISSAO                CODRCA  VARCHAR2(30)                    Código do RCA            OPERACIONAL                        NaN
PCLOGCOMISSAO           OBSERVACOES VARCHAR2(100)                      Observações            OPERACIONAL                        NaN
PCLOGCOMISSAO              PROGRAMA  VARCHAR2(64)            Descrição do Programa            OPERACIONAL                        NaN
PCLOGCOMISSAO CALCCOMISSAOITEMVENDA   VARCHAR2(1)     Comissão calculada nos itens            OPERACIONAL                        NaN
PCLOGCOMISSAO   CALCCOMISSAORATEADA   VARCHAR2(1) Comissão reateada RCA / Operador            OPERACIONAL                        NaN
PCLOGCOMISSAO            DATAINICIO          DATE    Início do Período de apuração            OPERACIONAL                        NaN
PCLOGCOMISSAO               DATAFIM          DATE     Final do Período de apuração            OPERACIONAL                        NaN
PCLOGCOMISSAO          VERSAOROTINA  VARCHAR2(30)                 Versão da Rotina            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*