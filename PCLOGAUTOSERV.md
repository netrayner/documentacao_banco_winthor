# 📊 Tabela: PCLOGAUTOSERV

### Estrutura de Colunas e Restrições

       Tabela        Coluna  Tipo/Tamanho        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGAUTOSERV     CODFILIAL   VARCHAR2(2)           Código da Filial            OPERACIONAL                        NaN
PCLOGAUTOSERV       CODFUNC   NUMBER(8,0)      Código do Funcionário            OPERACIONAL                        NaN
PCLOGAUTOSERV       DATALOG          DATE     Data de criação do Log            OPERACIONAL                        NaN
PCLOGAUTOSERV        COLUNA VARCHAR2(100)            Coluna Alterada            OPERACIONAL                        NaN
PCLOGAUTOSERV VALORALTERADO VARCHAR2(100)   Valor da Coluna alterado            OPERACIONAL                        NaN
PCLOGAUTOSERV VALORANTERIOR VARCHAR2(100) Valor anterior da Coluna              OPERACIONAL                        NaN
PCLOGAUTOSERV         CHAVE  VARCHAR2(25)         Chave do registro             OPERACIONAL                        NaN
PCLOGAUTOSERV     CODROTINA  VARCHAR2(40)             Nome da Rotina            OPERACIONAL                        NaN
PCLOGAUTOSERV        VERSAO  VARCHAR2(12)           Versão da Rotina            OPERACIONAL                        NaN
PCLOGAUTOSERV    NOMETABELA  VARCHAR2(40)             Nome da tabela            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*