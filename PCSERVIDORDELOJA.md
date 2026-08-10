# 📊 Tabela: PCSERVIDORDELOJA

### Estrutura de Colunas e Restrições

          Tabela                    Coluna  Tipo/Tamanho                                                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSERVIDORDELOJA                 CODFILIAL   VARCHAR2(2)                                                                           Código da filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCSERVIDORDELOJA EXIBIRCAIXASMONITORAMENTO   VARCHAR2(1)                     Indica se exibe ou não os caixas da filial no monitoramentos de caixas.            OPERACIONAL                        NaN
PCSERVIDORDELOJA         PERCENTUALCRITICO   NUMBER(3,0) Percentual de registros não recebidos que indica que o caixa está em estado crítico ou não.            OPERACIONAL                        NaN
PCSERVIDORDELOJA            TIPODESERVIDOR   VARCHAR2(2)                                                    Indica o tipo de servidor para a filial.            OPERACIONAL                        NaN
PCSERVIDORDELOJA                  ENDERECO VARCHAR2(100)                                                         Endereço do banco de dados central.            OPERACIONAL                        NaN
PCSERVIDORDELOJA              USUARIOBANCO  VARCHAR2(40)                                                          Usuário do banco de dados central.            OPERACIONAL                        NaN
PCSERVIDORDELOJA                SENHABANCO  VARCHAR2(40)                                                            Senha do banco de dados central.            OPERACIONAL                        NaN
PCSERVIDORDELOJA             NOMEDOSERVICO  VARCHAR2(40)                                                  Nome do serviço do banco de dados central.            OPERACIONAL                        NaN
PCSERVIDORDELOJA    EXIBIRCAIXASBLOQUEADOS   VARCHAR2(1)                                    Indica se o sistema deve exibir caixas bloqueados (S/N).            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*