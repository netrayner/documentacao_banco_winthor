# 📊 Tabela: PCSPEDECFM310

### Estrutura de Colunas e Restrições

       Tabela                Coluna Tipo/Tamanho                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSPEDECFM310                    ID  NUMBER(8,0)          Identificador único do registro (PK)    CHAVE PRIMÁRIA (PK)                        NaN
PCSPEDECFM310          IDLANCAMENTO       NUMBER              ID da tabela PCSPEDECFLANCAMENTO CHAVE ESTRANGEIRA (FK)        PCSPEDECFLANCAMENTO
PCSPEDECFM310         CODPLANOCONTA  NUMBER(5,0)                     Código do plano de contas CHAVE ESTRANGEIRA (FK)                 PCMODELOPC
PCSPEDECFM310        CODREDUZIDO_PC VARCHAR2(12)                   Código da conta relacionada CHAVE ESTRANGEIRA (FK)                 PCMODELOPC
PCSPEDECFM310            SALDOFINAL NUMBER(22,4)                         Saldo final calculado            OPERACIONAL                        NaN
PCSPEDECFM310          SALDOFINALDC      CHAR(1)                    Sinal (D/C) do saldo final            OPERACIONAL                        NaN
PCSPEDECFM310        SALDOUTILIZADO NUMBER(22,4)                     Saldo utilizado calculado            OPERACIONAL                        NaN
PCSPEDECFM310      SALDOUTILIZADODC      CHAR(1)                Sinal (D/C) do saldo utilizado            OPERACIONAL                        NaN
PCSPEDECFM310   SALDORELACIONAMENTO NUMBER(22,4)             Saldo do relacionamento calculado            OPERACIONAL                        NaN
PCSPEDECFM310 SALDORELACIONAMENTODC      CHAR(1)        Sinal (D/C) do saldo do relacionamento            OPERACIONAL                        NaN
PCSPEDECFM310                 LALUR      CHAR(1)                         S = LALUR ou N = LACS            OPERACIONAL                        NaN
PCSPEDECFM310             DTCRIACAO         DATE Data de criação do registro no banco de dados            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*