# 📊 Tabela: PCMENSAGENSBOLEPIX

### Estrutura de Colunas e Restrições

            Tabela             Coluna Tipo/Tamanho                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMENSAGENSBOLEPIX             CODIGO NUMBER(10,0)                                           Chave primária    CHAVE PRIMÁRIA (PK)                        NaN
PCMENSAGENSBOLEPIX          DESCRICAO VARCHAR2(50)                                    Descrição da mensagem            OPERACIONAL                        NaN
PCMENSAGENSBOLEPIX           MENSAGEM VARCHAR2(50)                                         Mensagem bolepix            OPERACIONAL                        NaN
PCMENSAGENSBOLEPIX VARIAVEL_VINCULADA NUMBER(10,0)                Campo código da tabela PCVARIAVEISBOLEPIX CHAVE ESTRANGEIRA (FK)         PCVARIAVEISBOLEPIX
PCMENSAGENSBOLEPIX             STATUS  VARCHAR2(1) Status da mensagem, sendo A para ativa e I para inativa.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*