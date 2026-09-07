# 📊 Tabela: PCCLIDEPOSITOI

### Estrutura de Colunas e Restrições

        Tabela      Coluna Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCLIDEPOSITOI      CODCLI  NUMBER(6,0)                     Código do Cliente.            OPERACIONAL                        NaN
PCCLIDEPOSITOI    CODBANCO  NUMBER(4,0)                       Código do Banco.            OPERACIONAL                        NaN
PCCLIDEPOSITOI  NUMREMESSA NUMBER(10,0)   Numero Sequencial do Arquivo Gerado.            OPERACIONAL                        NaN
PCCLIDEPOSITOI   DTGERACAO         DATE            Data de Geração do Arquivo.            OPERACIONAL                        NaN
PCCLIDEPOSITOI     TIPOARQ  VARCHAR2(1)                Tipo do Arquivo Gerado.            OPERACIONAL                        NaN
PCCLIDEPOSITOI NOMEARQUIVO VARCHAR2(60)                Nome do Arquivo Gerado.            OPERACIONAL                        NaN
PCCLIDEPOSITOI   CODFILIAL  VARCHAR2(2)              Filial do Arquivo Gerado.            OPERACIONAL                        NaN
PCCLIDEPOSITOI  CODFUNCGER  NUMBER(8,0) Usuário do Sistema que Gero o Arquivo.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*