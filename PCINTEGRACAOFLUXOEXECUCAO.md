# 📊 Tabela: PCINTEGRACAOFLUXOEXECUCAO

### Estrutura de Colunas e Restrições

                   Tabela                   Coluna Tipo/Tamanho                                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOFLUXOEXECUCAO            ORDEMEXECUCAO  NUMBER(5,0)                                          Armazena a ordem para execução            OPERACIONAL                        NaN
PCINTEGRACAOFLUXOEXECUCAO            IDROTASERVICO NUMBER(10,0)          Chave estrangeira com referência para a tabela de rota serviço CHAVE ESTRANGEIRA (FK)    PCINTEGRACAOROTASERVICO
PCINTEGRACAOFLUXOEXECUCAO IDINTEGRACAOCLASSEMETODO NUMBER(10,0)                                          Armazena o ID da classe/metodo CHAVE ESTRANGEIRA (FK)   PCINTEGRACAOCLASSEMETODO
PCINTEGRACAOFLUXOEXECUCAO                  IDFLUXO  NUMBER(5,0)                                                  Armazena o id do fluxo            OPERACIONAL                        NaN
PCINTEGRACAOFLUXOEXECUCAO                    ATIVO  VARCHAR2(1)                                              Armazena o status do fluxo            OPERACIONAL                        NaN
PCINTEGRACAOFLUXOEXECUCAO             IDDEPENDENTE NUMBER(10,0)  Armazena o ID dependente para vincular a rota de envio a rota de busca            OPERACIONAL                        NaN
PCINTEGRACAOFLUXOEXECUCAO               DTULTALTER         DATE                                     Armazena a data de última alteração            OPERACIONAL                        NaN
PCINTEGRACAOFLUXOEXECUCAO              CODEMPALTER VARCHAR2(40)                                         Armazena o código emp alteração            OPERACIONAL                        NaN
PCINTEGRACAOFLUXOEXECUCAO                DESCRICAO VARCHAR2(80)                                           Armazena a descrição do fluxo            OPERACIONAL                        NaN
PCINTEGRACAOFLUXOEXECUCAO                       ID NUMBER(10,0)                                                Chave primária da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRACAOFLUXOEXECUCAO                   EVENTO  VARCHAR2(1)                  Indica se o fluxo será executado por um evento ou não;            OPERACIONAL                        NaN
PCINTEGRACAOFLUXOEXECUCAO        INTERVALOSEGUNDOS NUMBER(10,0)                    Intervalo de Tempo (em segundos) entre as Execuções.            OPERACIONAL                        NaN
PCINTEGRACAOFLUXOEXECUCAO              EXPURGODIAS  NUMBER(3,0) Quantidade de dias minimo para execucao do Expurgo Individual por Fluxo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*