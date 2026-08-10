# 📊 Tabela: PCCONTADOR

### Estrutura de Colunas e Restrições

    Tabela                Coluna Tipo/Tamanho                                                                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONTADOR           CODCONTADOR  NUMBER(5,0)                                                                                                    NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTADOR         NOME_CONTADOR VARCHAR2(50)                                                                                                    NaN            OPERACIONAL                        NaN
PCCONTADOR                   CRC VARCHAR2(15)                                                                                                    NaN            OPERACIONAL                        NaN
PCCONTADOR                    RG VARCHAR2(20)                                                                                                    NaN            OPERACIONAL                        NaN
PCCONTADOR              ENDERECO VARCHAR2(50)                                                                                                    NaN            OPERACIONAL                        NaN
PCCONTADOR                BAIRRO VARCHAR2(30)                                                                                                    NaN            OPERACIONAL                        NaN
PCCONTADOR             CODCIDADE  NUMBER(6,0)                                                                                                    NaN            OPERACIONAL                        NaN
PCCONTADOR                   CEP VARCHAR2(10)                                                                                                    NaN            OPERACIONAL                        NaN
PCCONTADOR            TELEFONE01 VARCHAR2(13)                                                                                                    NaN            OPERACIONAL                        NaN
PCCONTADOR            TELEFONE02 VARCHAR2(13)                                                                                                    NaN            OPERACIONAL                        NaN
PCCONTADOR               CELULAR VARCHAR2(13)                                                                                                    NaN            OPERACIONAL                        NaN
PCCONTADOR                 EMAIL VARCHAR2(70)                                                                                                    NaN            OPERACIONAL                        NaN
PCCONTADOR         TIPOINSCRICAO  VARCHAR2(4)                                                                Indica o tipo de inscrição do contador.            OPERACIONAL                        NaN
PCCONTADOR          CNPJ_CPF_CEI VARCHAR2(15)                                                              Indica o numero da inscrição do contador.            OPERACIONAL                        NaN
PCCONTADOR          TIPOCONTADOR  VARCHAR2(1)                                                            Indica se e Contador ou Téc. Contabilidade.            OPERACIONAL                        NaN
PCCONTADOR         DTVALIDADECRC         DATE                                                                               Data de validade do CRC.            OPERACIONAL                        NaN
PCCONTADOR QUALIFICACAOASSINANTE  NUMBER(5,0) Qualificação do Assinante essa opção deverá apresentar a tabela de ¿Qualificação do Assinante¿ do sped            OPERACIONAL                        NaN
PCCONTADOR         REPRESENTANTE      CHAR(1)                                                                         Representante Legal da Empresa            OPERACIONAL                        NaN
PCCONTADOR          SEQUENCIACRC VARCHAR2(20)                                                                                       Sequencia do CRC            OPERACIONAL                        NaN
PCCONTADOR        DTVALIDADEDHPC         DATE                                                                                      Dt. Validade DHPC            OPERACIONAL                        NaN
PCCONTADOR                 UFCRC  VARCHAR2(2)                                                                             UF do orgão emissor do CRC            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*