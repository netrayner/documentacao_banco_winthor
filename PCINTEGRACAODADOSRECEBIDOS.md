# 📊 Tabela: PCINTEGRACAODADOSRECEBIDOS

### Estrutura de Colunas e Restrições

                    Tabela         Coluna Tipo/Tamanho                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAODADOSRECEBIDOS             ID NUMBER(10,0)                            Chave primária da tabela.    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRACAODADOSRECEBIDOS  IDROTASERVICO NUMBER(10,0) Chave extrangeira referente a tabela de rota serviço CHAVE ESTRANGEIRA (FK)    PCINTEGRACAOROTASERVICO
PCINTEGRACAODADOSRECEBIDOS DADOSRECEBIDOS         CLOB            Armazera os dados recebidos da requisição            OPERACIONAL                        NaN
PCINTEGRACAODADOSRECEBIDOS    DATACRIACAO         DATE                          Armazeda a data de criação             OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*