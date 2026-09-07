# 📊 Tabela: PCLOGREMCNAB

### Estrutura de Colunas e Restrições

      Tabela      Coluna Tipo/Tamanho                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGREMCNAB      CODLOG NUMBER(10,0)                         Chave primária da tabela, numero sequencial    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGREMCNAB   CODFILIAL  VARCHAR2(2)                  Código da filial selecionada na geração do arquivo            OPERACIONAL                        NaN
PCLOGREMCNAB   DTGERACAO         DATE                             Data que o arquivo foi gerado na rotina            OPERACIONAL                        NaN
PCLOGREMCNAB NOMEARQUIVO VARCHAR2(80)                                 Nome do arquivo gerado pelo usuário            OPERACIONAL                        NaN
PCLOGREMCNAB   MATRICULA  NUMBER(8,0)                            Matricula do usuário que gerou o arquivo            OPERACIONAL                        NaN
PCLOGREMCNAB     USUARIO VARCHAR2(80)                                  Nome do usuário que gero o arquivo            OPERACIONAL                        NaN
PCLOGREMCNAB      ROTINA VARCHAR2(80)                                   Nome da rotina que gero o arquivo            OPERACIONAL                        NaN
PCLOGREMCNAB     MAQUINA VARCHAR2(80)                             Márquina que gerou o arquivo de remessa            OPERACIONAL                        NaN
PCLOGREMCNAB TIPOREMESSA VARCHAR2(20) Se o arquivo é de remessa ou de abatimento ou alteração de registro            OPERACIONAL                        NaN
PCLOGREMCNAB  CODBANCOCM  NUMBER(4,0)            Gravar o código do banco utilizado na geração da remessa            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*