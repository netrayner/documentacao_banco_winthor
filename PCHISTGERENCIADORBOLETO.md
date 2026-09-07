# 📊 Tabela: PCHISTGERENCIADORBOLETO

### Estrutura de Colunas e Restrições

                 Tabela           Coluna  Tipo/Tamanho            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCHISTGERENCIADORBOLETO             ACAO  VARCHAR2(15)                Ação do usuário            OPERACIONAL                        NaN
PCHISTGERENCIADORBOLETO         ENTIDADE  VARCHAR2(50)            Entidade modificada            OPERACIONAL                        NaN
PCHISTGERENCIADORBOLETO MATRICULAUSUARIO   NUMBER(8,0) Código da matricula do usuario            OPERACIONAL                        NaN
PCHISTGERENCIADORBOLETO           ANTIGO          CLOB                  Dados antigos            OPERACIONAL                        NaN
PCHISTGERENCIADORBOLETO             NOVO          CLOB                    Dados novos            OPERACIONAL                        NaN
PCHISTGERENCIADORBOLETO              OBS VARCHAR2(255)                    Observações            OPERACIONAL                        NaN
PCHISTGERENCIADORBOLETO             DATA          DATE                 Data do evento            OPERACIONAL                        NaN
PCHISTGERENCIADORBOLETO   CODIGOENTIDADE  VARCHAR2(15)      Identificação da entidade            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*