# 📊 Tabela: PCLOGENVIOEMAIL

### Estrutura de Colunas e Restrições

         Tabela            Coluna   Tipo/Tamanho                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGENVIOEMAIL      NUMTRANSACAO   NUMBER(10,0)                     Número da transação da nota fiscal            OPERACIONAL                        NaN
PCLOGENVIOEMAIL         MOVIMENTO    VARCHAR2(1)             Tipo do movimento (E = Entrada/ S = Saida)            OPERACIONAL                        NaN
PCLOGENVIOEMAIL       LISTAEMAILS VARCHAR2(3500)        Lista de emails informados, no momento do envio            OPERACIONAL                        NaN
PCLOGENVIOEMAIL CODUSUARIOWINTHOR   NUMBER(10,0)       Código do usuário do Winthor que efetuou o envio            OPERACIONAL                        NaN
PCLOGENVIOEMAIL         DATAENVIO           DATE                           Data de envio do(s) email(s)            OPERACIONAL                        NaN
PCLOGENVIOEMAIL          TERMINAL  VARCHAR2(100)             Terminal de onde foi enviado o(s) email(s)            OPERACIONAL                        NaN
PCLOGENVIOEMAIL           MAQUINA  VARCHAR2(100)              Maquina de onde foi enviado o(s) email(s)            OPERACIONAL                        NaN
PCLOGENVIOEMAIL          PROGRAMA  VARCHAR2(100)                      Programa que enviou o(s) email(s)            OPERACIONAL                        NaN
PCLOGENVIOEMAIL            OSUSER  VARCHAR2(100) Usuário do sistema operacinal que enviou o(s) email(s)            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*