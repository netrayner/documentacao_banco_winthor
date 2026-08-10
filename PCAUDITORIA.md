# 📊 Tabela: PCAUDITORIA

### Estrutura de Colunas e Restrições

     Tabela            Coluna Tipo/Tamanho                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAUDITORIA      NUMAUDITORIA  NUMBER(8,0)                Indica o número auditoria por veículo.    CHAVE PRIMÁRIA (PK)                        NaN
PCAUDITORIA        DTCADASTRO         DATE                           Indiaca a data de cadastro.            OPERACIONAL                        NaN
PCAUDITORIA      DTFINALIZADA         DATE                         Indica a data de finalização.            OPERACIONAL                        NaN
PCAUDITORIA        CODVEICULO  NUMBER(4,0)                           Indica o código do veículo.            OPERACIONAL                        NaN
PCAUDITORIA CODFUNCFINALIZADA  NUMBER(8,0) Indica o código usuário responsável pela finalização.            OPERACIONAL                        NaN
PCAUDITORIA       DIVERGENCIA  VARCHAR2(1)            Indica data de finalizada com divergência.            OPERACIONAL                        NaN
PCAUDITORIA            QTCONF NUMBER(18,4)                              Produtos com Divergencia            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*