# 📊 Tabela: PCCATRACACONFIG

### Estrutura de Colunas e Restrições

         Tabela           Coluna  Tipo/Tamanho                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCATRACACONFIG           MODELO  VARCHAR2(30)                                       Modelo de catraca            OPERACIONAL                        NaN
PCCATRACACONFIG        CODFILIAL   VARCHAR2(2)                                        Código da filial            OPERACIONAL                        NaN
PCCATRACACONFIG        DIRETORIO VARCHAR2(300) Diretório onde será gravando os arquivos de comunicação            OPERACIONAL                        NaN
PCCATRACACONFIG               IP VARCHAR2(150)             Endereço IP de comunicação com o webservice            OPERACIONAL                        NaN
PCCATRACACONFIG            PORTA   NUMBER(6,0)                        Porta do endereço de comunicação            OPERACIONAL                        NaN
PCCATRACACONFIG       OBSERVACAO VARCHAR2(300)                              Observação sobre a catraca            OPERACIONAL                        NaN
PCCATRACACONFIG            ATIVO   VARCHAR2(1)                                           Catraca ativa            OPERACIONAL                        NaN
PCCATRACACONFIG       DTCADASTRO          DATE                                        Data de cadastro            OPERACIONAL                        NaN
PCCATRACACONFIG    CODUSUARIOINC   NUMBER(8,0)                            Código do usuário de incluiu            OPERACIONAL                        NaN
PCCATRACACONFIG      DTALTERACAO          DATE                                       Data de alteração            OPERACIONAL                        NaN
PCCATRACACONFIG    CODUSUARIOALT   NUMBER(8,0)                           Código do usuário que alterou            OPERACIONAL                        NaN
PCCATRACACONFIG       CODCATRACA   NUMBER(6,0)                           Código do cadastro da catraca    CHAVE PRIMÁRIA (PK)                        NaN
PCCATRACACONFIG RETIRARESPACOXML   VARCHAR2(1)                    Retirar espaço no arquivo XML gerado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*