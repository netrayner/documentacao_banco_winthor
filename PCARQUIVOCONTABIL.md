# 📊 Tabela: PCARQUIVOCONTABIL

### Estrutura de Colunas e Restrições

           Tabela           Coluna  Tipo/Tamanho                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCARQUIVOCONTABIL       CODARQCONT  NUMBER(10,0)                      Indica código de controle do arquivo.    CHAVE PRIMÁRIA (PK)                        NaN
PCARQUIVOCONTABIL        CODFILIAL   VARCHAR2(2)                                            Cód. Da filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCARQUIVOCONTABIL        DTGERACAO          DATE                                Data da geracao do arquivo.            OPERACIONAL                        NaN
PCARQUIVOCONTABIL           PERINI          DATE Periodo inicial que foi escolhido para geração do arquivo.            OPERACIONAL                        NaN
PCARQUIVOCONTABIL           PERFIM          DATE   Periodo final que foi escolhido para geração do arquivo.            OPERACIONAL                        NaN
PCARQUIVOCONTABIL         REGISTRO          CLOB                                            Arquivo gerado.            OPERACIONAL                        NaN
PCARQUIVOCONTABIL          TIPOARQ   VARCHAR2(1)                                           Tipo do Arquivo.            OPERACIONAL                        NaN
PCARQUIVOCONTABIL           ROTINA  VARCHAR2(40)                Rotina do Winthor que foi gerado o arquivo.            OPERACIONAL                        NaN
PCARQUIVOCONTABIL           VERSAO  VARCHAR2(20)               Qual a versão da rotina que gerou o arquivo.            OPERACIONAL                        NaN
PCARQUIVOCONTABIL        DESCRICAO VARCHAR2(300)                                    Nome do arquivo gerado.            OPERACIONAL                        NaN
PCARQUIVOCONTABIL      HORAGERACAO  VARCHAR2(10)                       Horário em que foi gerado o arquivo.            OPERACIONAL                        NaN
PCARQUIVOCONTABIL TIPOESCRITURACAO   VARCHAR2(1)            Indica qual a forma de escrituração foi gerada.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*