# 📊 Tabela: PCINTEGRADORAFILIAL

### Estrutura de Colunas e Restrições

             Tabela              Coluna  Tipo/Tamanho                                                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRADORAFILIAL         INTEGRADORA   NUMBER(6,0)                                                             Código da Integradora    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRADORAFILIAL           CODFILIAL   VARCHAR2(2)                                                                  Código da Filial    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRADORAFILIAL IDENTIFICADORFILIAL  VARCHAR2(50)                                           Identificador Filial no Nome do Arquivo            OPERACIONAL                        NaN
PCINTEGRADORAFILIAL           DIRPEDIDO VARCHAR2(200)                                                 Diretório dos Arquivos de Pedidos            OPERACIONAL                        NaN
PCINTEGRADORAFILIAL          DIRRETORNO VARCHAR2(200)                               Diretório onde serão gerados os Arquivos de Retorno            OPERACIONAL                        NaN
PCINTEGRADORAFILIAL       DIRNOTAFISCAL VARCHAR2(200)                         Diretório onde serão gerados os Arquivos de Espelho de NF            OPERACIONAL                        NaN
PCINTEGRADORAFILIAL           DIRBACKUP VARCHAR2(200)        Diretório onde serão gerados os Arquivos de Pedidos importados com sucesso            OPERACIONAL                        NaN
PCINTEGRADORAFILIAL             DIRERRO VARCHAR2(200)                      Diretório onde serão gerados os Arquivos de Pedido com erros            OPERACIONAL                        NaN
PCINTEGRADORAFILIAL                HOST VARCHAR2(250)                                                                          Host FTP            OPERACIONAL                        NaN
PCINTEGRADORAFILIAL            USERNAME  VARCHAR2(20)                                                                       Usuário FTP            OPERACIONAL                        NaN
PCINTEGRADORAFILIAL            PASSWORD  VARCHAR2(20)                                                                         Senha FTP            OPERACIONAL                        NaN
PCINTEGRADORAFILIAL                PORT   NUMBER(4,0)                                                                         Porta FTP            OPERACIONAL                        NaN
PCINTEGRADORAFILIAL       DIRPEDIDO_FTP VARCHAR2(200)                                          Diretório dos Arquivos de Pedidos no FTP            OPERACIONAL                        NaN
PCINTEGRADORAFILIAL      DIRRETORNO_FTP VARCHAR2(200)                        Diretório onde serão gerados os Arquivos de Retorno no FTP            OPERACIONAL                        NaN
PCINTEGRADORAFILIAL   DIRNOTAFISCAL_FTP VARCHAR2(200)                  Diretório onde serão gerados os Arquivos de Espelho de NF no FTP            OPERACIONAL                        NaN
PCINTEGRADORAFILIAL       DIRBACKUP_FTP VARCHAR2(200) Diretório onde serão gerados os Arquivos de Pedidos importados com sucesso no FTP            OPERACIONAL                        NaN
PCINTEGRADORAFILIAL         DIRERRO_FTP VARCHAR2(200)               Diretório onde serão gerados os Arquivos de Pedido com erros no FTP            OPERACIONAL                        NaN
PCINTEGRADORAFILIAL        DIRDEVOLUCAO VARCHAR2(200)                                    Diretório de Geração dos Arquivos de Devolução            OPERACIONAL                        NaN
PCINTEGRADORAFILIAL        CODFILIALVAN  VARCHAR2(20)                                                           Código da Filial na VAN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*