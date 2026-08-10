# 📊 Tabela: PCMALHAAGENDAMENTOROT

### Estrutura de Colunas e Restrições

               Tabela              Coluna Tipo/Tamanho                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMALHAAGENDAMENTOROT    CODMLHAGENROTINA  NUMBER(6,0) Código de identificação da rotina agendada            OPERACIONAL                        NaN
PCMALHAAGENDAMENTOROT CODMALHAAGENDAMENTO  NUMBER(6,0)     Código de identificação do agendamento            OPERACIONAL                        NaN
PCMALHAAGENDAMENTOROT     CODMALHAROTINAS  NUMBER(6,0) Código de identificação da rotina na malha            OPERACIONAL                        NaN
PCMALHAAGENDAMENTOROT            TIMEZONE TIMESTAMP(6)        Timezone  que é executada na rotina            OPERACIONAL                        NaN
PCMALHAAGENDAMENTOROT           CODFILIAL  VARCHAR2(2)                           Código da filial            OPERACIONAL                        NaN
PCMALHAAGENDAMENTOROT DATAHORAAGENDAMENTO TIMESTAMP(6) Hora prevista para ser iniciada a execução            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*