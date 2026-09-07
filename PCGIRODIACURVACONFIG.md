# 📊 Tabela: PCGIRODIACURVACONFIG

### Estrutura de Colunas e Restrições

              Tabela        Coluna Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGIRODIACURVACONFIG     CODFILIAL  VARCHAR2(2)                               Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCGIRODIACURVACONFIG    TIPOMEDIDA  VARCHAR2(1)      Tipo da medida: Faturamento ou Quantidade    CHAVE PRIMÁRIA (PK)                        NaN
PCGIRODIACURVACONFIG    TIPOTABELA VARCHAR2(50) Tipo da tabela: Curva, sub-curva ou frequência    CHAVE PRIMÁRIA (PK)                        NaN
PCGIRODIACURVACONFIG         CHAVE VARCHAR2(30)    Chave do registro conforme o tipo da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCGIRODIACURVACONFIG       UTILIZA  VARCHAR2(1)                 Utiliza ou não na configuração            OPERACIONAL                        NaN
PCGIRODIACURVACONFIG    DTCADASTRO         DATE                               Data de cadastro            OPERACIONAL                        NaN
PCGIRODIACURVACONFIG CODUSUARIOCAD  NUMBER(8,0)                Código do usuário que cadastrou            OPERACIONAL                        NaN
PCGIRODIACURVACONFIG   DTALTERACAO         DATE                              Data de alteração            OPERACIONAL                        NaN
PCGIRODIACURVACONFIG CODUSUARIOALT  NUMBER(8,0)                  Código do usuário que alterou            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*