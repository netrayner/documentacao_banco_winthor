# 📊 Tabela: PCWMSVINCULOCAIXA

### Estrutura de Colunas e Restrições

           Tabela           Coluna Tipo/Tamanho                                                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCWMSVINCULOCAIXA        CODFILIAL  VARCHAR2(2)                                              Codigo da Filial que esta sendo feita a conferencia            OPERACIONAL                        NaN
PCWMSVINCULOCAIXA         CODCAIXA  NUMBER(8,0)                                                            Codigo da caixa que vai ser vinculada            OPERACIONAL                        NaN
PCWMSVINCULOCAIXA            NUMOS NUMBER(10,0)                                                               Numero da OS que vai ser vinculada            OPERACIONAL                        NaN
PCWMSVINCULOCAIXA      NUMTRANSWMS NUMBER(10,0)                                                                    Indica o numero transacao WMS            OPERACIONAL                        NaN
PCWMSVINCULOCAIXA           NUMPED NUMBER(10,0)                                                                        Indica o numero do pedido            OPERACIONAL                        NaN
PCWMSVINCULOCAIXA           NUMCAR  NUMBER(8,0)                                                                  Indica o numero do carregamento            OPERACIONAL                        NaN
PCWMSVINCULOCAIXA      DATAVINCULO TIMESTAMP(3)                                                                      Data da associacao da caixa            OPERACIONAL                        NaN
PCWMSVINCULOCAIXA        DTESTORNO TIMESTAMP(6)                                                                                  Data do estorno            OPERACIONAL                        NaN
PCWMSVINCULOCAIXA        MATRICULA  NUMBER(8,0)                                                                          Matricula do conferente            OPERACIONAL                        NaN
PCWMSVINCULOCAIXA          USUARIO VARCHAR2(80)                                                           Usuario que esta fazendo a conferencia            OPERACIONAL                        NaN
PCWMSVINCULOCAIXA        CODROTINA NUMBER(10,0)                                          Codigo da rotina que esta sendo realizada a conferencia            OPERACIONAL                        NaN
PCWMSVINCULOCAIXA       DTEMBARQUE TIMESTAMP(6)                                                                                 Data do embarque            OPERACIONAL                        NaN
PCWMSVINCULOCAIXA        EMBARCADO  VARCHAR2(1)                                                                Se a caixa foi embarca Sim ou Nao            OPERACIONAL                        NaN
PCWMSVINCULOCAIXA        RETORNADO  VARCHAR2(1) Se a caixa foi retornada Sim ou Nao indicando que a caixa foi devolvida no retorno do motorista.            OPERACIONAL                        NaN
PCWMSVINCULOCAIXA MATRICULARETORNO  NUMBER(8,0)                                            Matrícula do usuário que realizou o retorno da caixa.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*