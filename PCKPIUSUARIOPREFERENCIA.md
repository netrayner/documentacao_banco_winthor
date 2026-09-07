# 📊 Tabela: PCKPIUSUARIOPREFERENCIA

### Estrutura de Colunas e Restrições

                 Tabela    Coluna Tipo/Tamanho                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCKPIUSUARIOPREFERENCIA MATRICULA  NUMBER(8,0)                                 Matricula do usuário            OPERACIONAL                        NaN
PCKPIUSUARIOPREFERENCIA     ORDEM  NUMBER(5,0) Ordem que o KPI será exibido no dashboard do usuário            OPERACIONAL                        NaN
PCKPIUSUARIOPREFERENCIA   EXIBIDO  VARCHAR2(1) Indicador de exibição do KPI no dashboard do usuário            OPERACIONAL                        NaN
PCKPIUSUARIOPREFERENCIA CODIGOKPI  NUMBER(5,0)                       Codigo de identificação do KPI            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*