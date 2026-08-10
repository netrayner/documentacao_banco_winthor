# 📊 Tabela: PCLOGCOBMAG

### Estrutura de Colunas e Restrições

     Tabela           Coluna  Tipo/Tamanho                                                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGCOBMAG CODSUBOCORRENCIA   VARCHAR2(4)                                                                                                 NaN            OPERACIONAL                        NaN
PCLOGCOBMAG    CODOCORRENCIA   VARCHAR2(2)                                                                                                 NaN            OPERACIONAL                        NaN
PCLOGCOBMAG    NUMTRANSVENDA  NUMBER(10,0)                                                                                                 NaN            OPERACIONAL                        NaN
PCLOGCOBMAG             DATA          DATE                                                                                                 NaN            OPERACIONAL                        NaN
PCLOGCOBMAG          CODFUNC   NUMBER(8,0)                                                                                                 NaN            OPERACIONAL                        NaN
PCLOGCOBMAG        CODFILIAL   NUMBER(8,0)                                                                                                 NaN            OPERACIONAL                        NaN
PCLOGCOBMAG         CODBANCO   NUMBER(8,0)                                                                                                 NaN            OPERACIONAL                        NaN
PCLOGCOBMAG            PREST   VARCHAR2(2)                                                                                                 NaN            OPERACIONAL                        NaN
PCLOGCOBMAG         VLCUSTAS  NUMBER(16,3)                                                                                                 NaN            OPERACIONAL                        NaN
PCLOGCOBMAG       VLDESPESAS  NUMBER(16,3)                                                                                                 NaN            OPERACIONAL                        NaN
PCLOGCOBMAG      CODFILIALCM   VARCHAR2(2) Novo campo para código da filial, criado para substituir campo de filial já existente (CODFILIAL).             OPERACIONAL                        NaN
PCLOGCOBMAG        DTGERACAO          DATE                                                                     Data Geração Arquivo de Retorno            OPERACIONAL                        NaN
PCLOGCOBMAG      NOSSONUMBCO  VARCHAR2(30)                                                        Nosso Numero do Registro Processado na Baixa            OPERACIONAL                        NaN
PCLOGCOBMAG       ARQRETORNO VARCHAR2(300)                                                     Conteúdo do caminho e nome do arquivo de baixa.            OPERACIONAL                        NaN
PCLOGCOBMAG          USUARIO  VARCHAR2(50)                                                 Usuario do windows que processou a baixa do arquivo            OPERACIONAL                        NaN
PCLOGCOBMAG          MAQUINA  VARCHAR2(50)                                                    Nome da maquina que processou a baixa do arquivo            OPERACIONAL                        NaN
PCLOGCOBMAG       ROTINALANC   NUMBER(4,0)                                            Código da rotina onde foi processada a baixa do aqrquivo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*