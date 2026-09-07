# 📊 Tabela: PCCAMPOLGPD

### Estrutura de Colunas e Restrições

     Tabela        Coluna  Tipo/Tamanho                                                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCAMPOLGPD      CODCAMPO   NUMBER(8,0)                                                                           Identificador único    CHAVE PRIMÁRIA (PK)                        NaN
PCCAMPOLGPD     CODTABELA   NUMBER(8,0)                                                   Código que referência a tabela PCTABELALGPD CHAVE ESTRANGEIRA (FK)               PCTABELALGPD
PCCAMPOLGPD  CODGRUPODADO   NUMBER(8,0)                                                Código que referência a tabela PCGRUPODADOLGPD CHAVE ESTRANGEIRA (FK)            PCGRUPODADOLGPD
PCCAMPOLGPD     DESCRICAO VARCHAR2(200)                                                                   Descrição do label do campo            OPERACIONAL                        NaN
PCCAMPOLGPD JUSTIFICATIVA VARCHAR2(200)                                                       Justificativa porque o dado é utilizado            OPERACIONAL                        NaN
PCCAMPOLGPD         CAMPO  VARCHAR2(40)                                                              Nome do campo elegível para LGPD            OPERACIONAL                        NaN
PCCAMPOLGPD CLASSIFICACAO VARCHAR2(100) "Classificação da informação:  (Execução e contrato, Consentimento, Obrigação legal, Outros)"            OPERACIONAL                        NaN
PCCAMPOLGPD     ANONIMIZA   VARCHAR2(1)                                                             Identifica se anoniminiza o campo            OPERACIONAL                        NaN
PCCAMPOLGPD          HASH  VARCHAR2(32)                                                      Hash para garantir a fidelidade do dados            OPERACIONAL                        NaN
PCCAMPOLGPD     MATRICULA   NUMBER(8,0)                                          Código da matrícula do usuário que gravou o registro            OPERACIONAL                        NaN
PCCAMPOLGPD      DATAHORA          DATE                                                           Data e hora da gravação do registro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*