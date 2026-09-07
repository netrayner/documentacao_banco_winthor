# 📊 Tabela: PCLOGAPIASD

### Estrutura de Colunas e Restrições

     Tabela            Coluna   Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGAPIASD              DATA           DATE                                      Data do log            OPERACIONAL                        NaN
PCLOGAPIASD            VERSAO  VARCHAR2(100)                                    Versão da API            OPERACIONAL                        NaN
PCLOGAPIASD          ARTEFATO  VARCHAR2(400)                                 Nome do Artefato            OPERACIONAL                        NaN
PCLOGAPIASD            METODO  VARCHAR2(200)                                 Método executado            OPERACIONAL                        NaN
PCLOGAPIASD    PARAMETROS_URL VARCHAR2(1000)                    Parâmetros recebidos pela URL            OPERACIONAL                        NaN
PCLOGAPIASD  PARAMETROS_CORPO VARCHAR2(1000)                    Parâmetros recebidos no Corpo            OPERACIONAL                        NaN
PCLOGAPIASD          SITUACAO  VARCHAR2(100)                        Situação de processamento            OPERACIONAL                        NaN
PCLOGAPIASD         DESCRICAO VARCHAR2(1000)                                        Descrição            OPERACIONAL                        NaN
PCLOGAPIASD           TIPOLOG    VARCHAR2(1)                               Tipo de Log (I, E)            OPERACIONAL                        NaN
PCLOGAPIASD TIPOIDENTIFICADOR  VARCHAR2(100) Tipo de identifcação. Ex: PCNFSAID.NUMTRANSVENDA            OPERACIONAL                        NaN
PCLOGAPIASD     IDENTIFICADOR   NUMBER(22,0)             Número do Identificador. Ex: 1000000            OPERACIONAL                        NaN
PCLOGAPIASD         SEQUENCIA   NUMBER(22,0)                                Número Sequencial            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*