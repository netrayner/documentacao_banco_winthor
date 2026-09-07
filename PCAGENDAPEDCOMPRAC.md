# 📊 Tabela: PCAGENDAPEDCOMPRAC

### Estrutura de Colunas e Restrições

            Tabela        Coluna Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAGENDAPEDCOMPRAC     CODFILIAL  VARCHAR2(2)                    Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDAPEDCOMPRAC            ID NUMBER(10,0) Número Identificação do Agendamento            OPERACIONAL                        NaN
PCAGENDAPEDCOMPRAC          DATA         DATE                 Data do agendamento    CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDAPEDCOMPRAC       HORAINI  VARCHAR2(5)          Hora inicio do agendamento    CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDAPEDCOMPRAC       HORAFIM  VARCHAR2(5)             Hora fim do agendamento    CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDAPEDCOMPRAC    CODUSURCAD  NUMBER(8,0)          Código do usuário cadastro            OPERACIONAL                        NaN
PCAGENDAPEDCOMPRAC       DATACAD         DATE                    Data do cadastro            OPERACIONAL                        NaN
PCAGENDAPEDCOMPRAC CODUSURULTALT  NUMBER(8,0)         Código do usuário alteração            OPERACIONAL                        NaN
PCAGENDAPEDCOMPRAC    DATAULTALT         DATE                   Data da alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*