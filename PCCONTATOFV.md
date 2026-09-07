# 📊 Tabela: PCCONTATOFV

### Estrutura de Colunas e Restrições

     Tabela        Coluna   Tipo/Tamanho                                                                                                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONTATOFV     IMPORTADO    NUMBER(1,0)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCCONTATOFV        CGCCLI   VARCHAR2(18)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCCONTATOFV   NOMECONTATO   VARCHAR2(40)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCCONTATOFV   TIPOCONTATO    VARCHAR2(1)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCCONTATOFV        CGCCPF   VARCHAR2(18)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCCONTATOFV  DTNASCIMENTO           DATE                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCCONTATOFV        HOBBIE   VARCHAR2(50)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCCONTATOFV          TIME   VARCHAR2(30)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCCONTATOFV   NOMECONJUGE   VARCHAR2(40)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCCONTATOFV DTNASCCONJUGE           DATE                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCCONTATOFV      ENDERECO   VARCHAR2(40)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCCONTATOFV        BAIRRO   VARCHAR2(30)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCCONTATOFV        CIDADE   VARCHAR2(30)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCCONTATOFV           CEP    VARCHAR2(9)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCCONTATOFV         CARGO   VARCHAR2(30)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCCONTATOFV      TELEFONE   VARCHAR2(18)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCCONTATOFV       CELULAR   VARCHAR2(18)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCCONTATOFV         EMAIL   VARCHAR2(50)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCCONTATOFV        ESTADO    VARCHAR2(2)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCCONTATOFV OBSERVACAO_PC VARCHAR2(4000)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCCONTATOFV    DTINCLUSAO           DATE                                                                                                               Grava Data e Hora da Última Importação.            OPERACIONAL                        NaN
PCCONTATOFV        CODCLI    NUMBER(6,0) Codigo do cliente que será usado em conjunto com o campo cnpj para identificar o cliente no caso de ter no cadastro mais de um cliente com mesmo cnpj            OPERACIONAL                        NaN
PCCONTATOFV   DTALTERACAO           DATE                                                                                                                         Data de Alteração no registro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*