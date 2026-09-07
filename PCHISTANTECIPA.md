# 📊 Tabela: PCHISTANTECIPA

### Estrutura de Colunas e Restrições

        Tabela           Coluna  Tipo/Tamanho                                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCHISTANTECIPA             ACAO  VARCHAR2(15)                                      Ação executada: Inserção ou Alteração            OPERACIONAL                        NaN
PCHISTANTECIPA           TABELA  VARCHAR2(30)                       Tabela aonde o registro vai ser alterado ou inserido            OPERACIONAL                        NaN
PCHISTANTECIPA MATRICULAUSUARIO   NUMBER(4,0)                                         Mátricula do usuário logado na WTA            OPERACIONAL                        NaN
PCHISTANTECIPA           ANTIGO          CLOB                    Informações dos campos anteriores a alteração dos dados            OPERACIONAL                        NaN
PCHISTANTECIPA             NOVO          CLOB       Informações dos campos posteriores a alteração ou inserção dos dados            OPERACIONAL                        NaN
PCHISTANTECIPA          DTALTER  TIMESTAMP(6)                                                Data da alteração dos dados            OPERACIONAL                        NaN
PCHISTANTECIPA            PREST   VARCHAR2(2)          Número da prestação do título que esta sendo alterado ou inserido            OPERACIONAL                        NaN
PCHISTANTECIPA        HISTORICO VARCHAR2(100)               Histórico com as informações resumidas da operação realizada            OPERACIONAL                        NaN
PCHISTANTECIPA    NUMTRANSVENDA  NUMBER(10,0) Número da transação de saída do título que esta sendo alterado ou inserido            OPERACIONAL                        NaN
PCHISTANTECIPA         OPERACAO   NUMBER(2,0)                            Código de operação da API do antecipa realizada            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*