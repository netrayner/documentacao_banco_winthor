# 📊 Tabela: PCCONFIGFATURAMENTOPADRAO

### Estrutura de Colunas e Restrições

                   Tabela     Coluna Tipo/Tamanho                                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONFIGFATURAMENTOPADRAO  CODFILIAL  VARCHAR2(2)                                                         CODIGO DA FILIAL            OPERACIONAL                        NaN
PCCONFIGFATURAMENTOPADRAO CODUSUARIO NUMBER(38,0)      Código do usuário com permissão a realizar o faturamento automático            OPERACIONAL                        NaN
PCCONFIGFATURAMENTOPADRAO  QTDMAXFAT  NUMBER(3,0) Definir em dias o prazo para considerar vendas no faturamento automatico            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*