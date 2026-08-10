# 📊 Tabela: PCINTEGRACAOCONTRATODIGITAL

### Estrutura de Colunas e Restrições

                     Tabela        Coluna  Tipo/Tamanho                                                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOCONTRATODIGITAL            ID  NUMBER(20,0)                                                                      Chave primária da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRACAOCONTRATODIGITAL   INFORMACOES          CLOB Informações referentes ao contrato, preferencialmente criptografadas para evitar modificações            OPERACIONAL                        NaN
PCINTEGRACAOCONTRATODIGITAL   DATACRIACAO          DATE                                                          Data de criação do registro no banco            OPERACIONAL                        NaN
PCINTEGRACAOCONTRATODIGITAL      CONTEUDO          BLOB                                                                          Conteúdo do contrato            OPERACIONAL                        NaN
PCINTEGRACAOCONTRATODIGITAL       PRODUTO VARCHAR2(100)                                                               Aplicação referente ao contrato            OPERACIONAL                        NaN
PCINTEGRACAOCONTRATODIGITAL        VERSAO  VARCHAR2(30)                                                                            Versão do contrato            OPERACIONAL                        NaN
PCINTEGRACAOCONTRATODIGITAL        ACEITE VARCHAR2(100)                                           Aceite do contrato, preferencialmente criptografado            OPERACIONAL                        NaN
PCINTEGRACAOCONTRATODIGITAL    DATAACEITE VARCHAR2(100)                                   Data do aceite do contrato, preferencialmente criptografado            OPERACIONAL                        NaN
PCINTEGRACAOCONTRATODIGITAL USUARIOACEITE VARCHAR2(100)       Matricula do usuário do WinThor que aceitou o contrato, preferencialmente criptografado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*