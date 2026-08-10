# 📊 Tabela: PCINTEGRACAOWTAC

### Estrutura de Colunas e Restrições

          Tabela            Coluna Tipo/Tamanho                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOWTAC                ID       NUMBER                                 Código integração            OPERACIONAL                        NaN
PCINTEGRACAOWTAC           SERVICO VARCHAR2(80)                      Serviço Integraçaõ utilizado            OPERACIONAL                        NaN
PCINTEGRACAOWTAC            VERSAO VARCHAR2(80)                                 Versão Integração            OPERACIONAL                        NaN
PCINTEGRACAOWTAC        CODIGOFILA VARCHAR2(80)                            Codigo Fila integracao            OPERACIONAL                        NaN
PCINTEGRACAOWTAC CODIGORETORNOFILA VARCHAR2(80)                    Codigo Retorno Fila Integração            OPERACIONAL                        NaN
PCINTEGRACAOWTAC            STATUS       NUMBER                                 Status Integração            OPERACIONAL                        NaN
PCINTEGRACAOWTAC              NOME VARCHAR2(80)                                   Nome Integração            OPERACIONAL                        NaN
PCINTEGRACAOWTAC             ATIVO  VARCHAR2(1) Campo referente se a integração está ativa ou não            OPERACIONAL                        NaN
PCINTEGRACAOWTAC  CODIGOINTEGRACAO  NUMBER(4,0)            Identificação do código da integração             OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*