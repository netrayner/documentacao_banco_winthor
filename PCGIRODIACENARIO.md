# 📊 Tabela: PCGIRODIACENARIO

### Estrutura de Colunas e Restrições

          Tabela        Coluna Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGIRODIACENARIO        CODIGO NUMBER(10,0)                         Código do cenário    CHAVE PRIMÁRIA (PK)                        NaN
PCGIRODIACENARIO     CODFILIAL  VARCHAR2(2)                          Código da filial            OPERACIONAL                        NaN
PCGIRODIACENARIO         NIVEL VARCHAR2(33)     Nível ou tabela de origem do registro            OPERACIONAL                        NaN
PCGIRODIACENARIO     NIVELITEM NUMBER(10,0)                           Código do nível            OPERACIONAL                        NaN
PCGIRODIACENARIO     CODFIGURA  NUMBER(6,0)                  Código da figura de giro            OPERACIONAL                        NaN
PCGIRODIACENARIO    TIPOMEDIDA  VARCHAR2(1) Tipo da medida: Faturamento ou quantidade            OPERACIONAL                        NaN
PCGIRODIACENARIO       FORMULA NUMBER(10,0)                         Código da fórmula            OPERACIONAL                        NaN
PCGIRODIACENARIO    FREQUENCIA VARCHAR2(30)                      Frequência de compra            OPERACIONAL                        NaN
PCGIRODIACENARIO     CODFORNEC  NUMBER(6,0)                      Código do fornecedor            OPERACIONAL                        NaN
PCGIRODIACENARIO    DTCADASTRO         DATE                          Data de cadastro            OPERACIONAL                        NaN
PCGIRODIACENARIO CODUSUARIOCAD  NUMBER(8,0)           Código do usuário que cadastrou            OPERACIONAL                        NaN
PCGIRODIACENARIO   DTALTERACAO         DATE                         Data de alteração            OPERACIONAL                        NaN
PCGIRODIACENARIO CODUSUARIOALT  NUMBER(8,0)             Código do usuário que alterou            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*