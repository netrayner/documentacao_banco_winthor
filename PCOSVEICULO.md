# 📊 Tabela: PCOSVEICULO

### Estrutura de Colunas e Restrições

     Tabela           Coluna   Tipo/Tamanho              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCOSVEICULO     CODOSVEICULO    NUMBER(6,0)                Código do veiculo            OPERACIONAL                        NaN
PCOSVEICULO            PLACA   VARCHAR2(10)       Numero da placa do veiculo            OPERACIONAL                        NaN
PCOSVEICULO      CODOSMODELO    NUMBER(6,0)      Código do modelo do veiculo            OPERACIONAL                        NaN
PCOSVEICULO              ANO    NUMBER(4,0)                   Ano do veiculo            OPERACIONAL                        NaN
PCOSVEICULO CODOSCOMBUSTIVEL    NUMBER(1,0) Código do combustivel do veiculo            OPERACIONAL                        NaN
PCOSVEICULO            MOTOR   VARCHAR2(50)    Descrição do motor do veiculo            OPERACIONAL                        NaN
PCOSVEICULO              OBS VARCHAR2(2000)           campo para observações            OPERACIONAL                        NaN
PCOSVEICULO       DTCADASTRO           DATE                 Data do cadastro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*