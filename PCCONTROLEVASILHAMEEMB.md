# 📊 Tabela: PCCONTROLEVASILHAMEEMB

### Estrutura de Colunas e Restrições

                Tabela         Coluna Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONTROLEVASILHAMEEMB    CODCONTROLE NUMBER(10,0)            Código controle vasilhame            OPERACIONAL                        NaN
PCCONTROLEVASILHAMEEMB      CODFILIAL  VARCHAR2(2)                     Código da filial            OPERACIONAL                        NaN
PCCONTROLEVASILHAMEEMB   CODVASILHAME  NUMBER(6,0)                  Código do vasilhame            OPERACIONAL                        NaN
PCCONTROLEVASILHAMEEMB    CODAUXILIAR NUMBER(20,0)        Codigo da embalagem vinculada            OPERACIONAL                        NaN
PCCONTROLEVASILHAMEEMB      QTENTRADA NUMBER(22,8)     Quantidade recebida de vasilhame            OPERACIONAL                        NaN
PCCONTROLEVASILHAMEEMB        QTSAIDA NUMBER(22,8)        Quantidade saida de vasilhame            OPERACIONAL                        NaN
PCCONTROLEVASILHAMEEMB        VENDIDO  VARCHAR2(1)                Vasilhame foi vendido            OPERACIONAL                        NaN
PCCONTROLEVASILHAMEEMB      MATRICULA  NUMBER(8,0)     Matricula do usuario que recebeu            OPERACIONAL                        NaN
PCCONTROLEVASILHAMEEMB      DTENTRADA         DATE         Data de entrada do vasilhame            OPERACIONAL                        NaN
PCCONTROLEVASILHAMEEMB      QTESTORNO NUMBER(22,8)    Quantidade de vasilhame estornado            OPERACIONAL                        NaN
PCCONTROLEVASILHAMEEMB CODFUNCESTORNO  NUMBER(8,0)   Funcionario que realizou o estorno            OPERACIONAL                        NaN
PCCONTROLEVASILHAMEEMB      DTESTORNO         DATE Data e hora da realização do estorno            OPERACIONAL                        NaN
PCCONTROLEVASILHAMEEMB MAQUINAENTRADA VARCHAR2(30)  Nome maquina que realizou o entrada            OPERACIONAL                        NaN
PCCONTROLEVASILHAMEEMB MAQUINAESTORNO VARCHAR2(30)  Nome maquina que realizou o estorno            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*