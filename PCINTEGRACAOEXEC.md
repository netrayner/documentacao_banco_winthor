# 📊 Tabela: PCINTEGRACAOEXEC

### Estrutura de Colunas e Restrições

          Tabela     Coluna  Tipo/Tamanho              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOEXEC   DATAACAO  TIMESTAMP(6) Data em que a ação foi executada            OPERACIONAL                        NaN
PCINTEGRACAOEXEC INTEGRACAO VARCHAR2(255)   Integração que realizou a ação            OPERACIONAL                        NaN
PCINTEGRACAOEXEC     VERSAO  VARCHAR2(80)             Versão da Integração            OPERACIONAL                        NaN
PCINTEGRACAOEXEC  DESCRICAO VARCHAR2(255)  Descrição da operação realizada            OPERACIONAL                        NaN
PCINTEGRACAOEXEC     STATUS  VARCHAR2(20)   Status de execução da operação            OPERACIONAL                        NaN
PCINTEGRACAOEXEC    PAYLOAD          CLOB            Payload da Integração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*