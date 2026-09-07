# 📊 Tabela: PCPREREQMATCONSUMOC

### Estrutura de Colunas e Restrições

             Tabela              Coluna Tipo/Tamanho                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPREREQMATCONSUMOC    NUMPREREQUISICAO  NUMBER(8,0)                                   Numero da requisicao    CHAVE PRIMÁRIA (PK)                        NaN
PCPREREQMATCONSUMOC           CODFILIAL  VARCHAR2(2)                               Filial da pré-requisição            OPERACIONAL                        NaN
PCPREREQMATCONSUMOC                DATA         DATE                                 Data da pré-requisição            OPERACIONAL                        NaN
PCPREREQMATCONSUMOC          CODFUNCREQ  NUMBER(8,0)                               Funcionário requisitante            OPERACIONAL                        NaN
PCPREREQMATCONSUMOC              MOTIVO VARCHAR2(60)                               Motivo da pré-requisição            OPERACIONAL                        NaN
PCPREREQMATCONSUMOC            SITUACAO  VARCHAR2(1)                             Situação da pré-requisição            OPERACIONAL                        NaN
PCPREREQMATCONSUMOC       NUMTRANSVENDA NUMBER(10,0)                          Número da transação de venda.            OPERACIONAL                        NaN
PCPREREQMATCONSUMOC IDINTEGRACAOMYFROTA          RAW                  Identifica a integração com My Frota.            OPERACIONAL                        NaN
PCPREREQMATCONSUMOC        PRERECORIGEM VARCHAR2(10)                                 Prerequisito original.            OPERACIONAL                        NaN
PCPREREQMATCONSUMOC         IDSOFITVIEW VARCHAR2(10) Indica o código da requisição de material na SofitView            OPERACIONAL                        NaN
PCPREREQMATCONSUMOC     STATUSAPROVACAO  VARCHAR2(2)                               Status da Pré-Requisição            OPERACIONAL                        NaN
PCPREREQMATCONSUMOC   RESPONSAVELSTATUS  NUMBER(8,0)                              Responável pela Aprovação            OPERACIONAL                        NaN
PCPREREQMATCONSUMOC          DATASTATUS         DATE           Data/ hora (SYSDATE) na gravação do servidor            OPERACIONAL                        NaN
PCPREREQMATCONSUMOC DTULTALTERSOFITVIEW         DATE                                      Data de alteração            OPERACIONAL                        NaN
PCPREREQMATCONSUMOC DTEXCLUSAOSOFITVIEW         DATE                                       Data de exclusão            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*