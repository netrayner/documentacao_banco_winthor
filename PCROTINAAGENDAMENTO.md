# 📊 Tabela: PCROTINAAGENDAMENTO

### Estrutura de Colunas e Restrições

             Tabela             Coluna  Tipo/Tamanho                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCROTINAAGENDAMENTO          CODROTINA   NUMBER(6,0)                          Codigo da rotina de agendamento    CHAVE PRIMÁRIA (PK)                        NaN
PCROTINAAGENDAMENTO               PATH VARCHAR2(100)                 Caminho do executável que será utilizado            OPERACIONAL                        NaN
PCROTINAAGENDAMENTO     EXECUTAPORLOJA   VARCHAR2(1)  Responsável por indicar que  será organizado por filial            OPERACIONAL                        NaN
PCROTINAAGENDAMENTO EXECUTAPORTIMEZONE   VARCHAR2(1) Responsável por indicar que será organizado por timezone            OPERACIONAL                        NaN
PCROTINAAGENDAMENTO          CODMODULO   NUMBER(4,0)                        Código de identificação do módulo CHAVE ESTRANGEIRA (FK)                   PCMODULO

---
*Documentação gerada automaticamente.*