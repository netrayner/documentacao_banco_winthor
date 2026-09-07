# 📊 Tabela: PCINTEGRACAOEVENTORECEBIDO

### Estrutura de Colunas e Restrições

                    Tabela            Coluna  Tipo/Tamanho                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOEVENTORECEBIDO            ORIGEM  VARCHAR2(50)                                                Origem do evento.            OPERACIONAL                        NaN
PCINTEGRACAOEVENTORECEBIDO      CODIGOORIGEM VARCHAR2(100)                               Código de identificação da origem.            OPERACIONAL                        NaN
PCINTEGRACAOEVENTORECEBIDO        OBSERVACAO          CLOB                                  Observação referente ao evento.            OPERACIONAL                        NaN
PCINTEGRACAOEVENTORECEBIDO             TOKEN          CLOB                               Token que identifica a requisição.            OPERACIONAL                        NaN
PCINTEGRACAOEVENTORECEBIDO        DTCADASTRO          DATE                                      Data de cadastro do evento.            OPERACIONAL                        NaN
PCINTEGRACAOEVENTORECEBIDO        DTULTALTER          DATE                                     Data de alteração do evento.            OPERACIONAL                        NaN
PCINTEGRACAOEVENTORECEBIDO    CODIGOPROCESSO  NUMBER(10,0)                              Códgo de identificação do processo.            OPERACIONAL                        NaN
PCINTEGRACAOEVENTORECEBIDO DESCRICAOPROCESSO VARCHAR2(200)                                           Descrição do processo.            OPERACIONAL                        NaN
PCINTEGRACAOEVENTORECEBIDO        PROCESSADO   VARCHAR2(1) Identifica se o registro já foi processado por alguma aplicação;            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*