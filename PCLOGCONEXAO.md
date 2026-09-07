# 📊 Tabela: PCLOGCONEXAO

### Estrutura de Colunas e Restrições

      Tabela    Coluna Tipo/Tamanho           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGCONEXAO   USUARIO VARCHAR2(80)             Usuário Conectado            OPERACIONAL                        NaN
PCLOGCONEXAO   MAQUINA VARCHAR2(80) Máquina que foi feita o login            OPERACIONAL                        NaN
PCLOGCONEXAO DTCONEXAO         DATE               Data da Conexão            OPERACIONAL                        NaN
PCLOGCONEXAO  PROGRAMA VARCHAR2(80)               Rotina Acessada            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*