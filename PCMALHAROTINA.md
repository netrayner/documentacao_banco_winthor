# 📊 Tabela: PCMALHAROTINA

### Estrutura de Colunas e Restrições

       Tabela          Coluna Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMALHAROTINA CODMALHAROTINAS  NUMBER(6,0)                          Código de identificador    CHAVE PRIMÁRIA (PK)                        NaN
PCMALHAROTINA        CODMALHA  NUMBER(6,0)                 Código de identificação da malha CHAVE ESTRANGEIRA (FK)                    PCMALHA
PCMALHAROTINA       CODROTINA  NUMBER(6,0) Código de identificação da rotina do agendamento CHAVE ESTRANGEIRA (FK)        PCROTINAAGENDAMENTO
PCMALHAROTINA           PASSO  NUMBER(2,0)     Identificador da ordem da execução da rotina            OPERACIONAL                        NaN
PCMALHAROTINA           DELAY  NUMBER(4,0)           Tempo de espera para executar a rotina            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*