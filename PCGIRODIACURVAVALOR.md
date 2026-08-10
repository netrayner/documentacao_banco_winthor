# 📊 Tabela: PCGIRODIACURVAVALOR

### Estrutura de Colunas e Restrições

             Tabela           Coluna Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGIRODIACURVAVALOR        CODFILIAL  VARCHAR2(2)                          Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCGIRODIACURVAVALOR       TIPOMEDIDA  VARCHAR2(1) Tipo da medida: Faturamento ou Quantidade    CHAVE PRIMÁRIA (PK)                        NaN
PCGIRODIACURVAVALOR            CHAVE VARCHAR2(30)                           Código da chave    CHAVE PRIMÁRIA (PK)                        NaN
PCGIRODIACURVAVALOR       CHAVECURVA VARCHAR2(30)                    Código da chave: Curva            OPERACIONAL                        NaN
PCGIRODIACURVAVALOR    CHAVESUBCURVA VARCHAR2(30)                 Código da chave: SubCurva            OPERACIONAL                        NaN
PCGIRODIACURVAVALOR  CHAVEFREQUENCIA VARCHAR2(30)               Código da chave: Frequência            OPERACIONAL                        NaN
PCGIRODIACURVAVALOR            VALOR NUMBER(18,6)                     Valor da configuração            OPERACIONAL                        NaN
PCGIRODIACURVAVALOR DIASANALISECURVA  NUMBER(4,0)                  Dias de análise da curva            OPERACIONAL                        NaN
PCGIRODIACURVAVALOR   DTCONSOLIDACAO         DATE                      Data da consolidação            OPERACIONAL                        NaN
PCGIRODIACURVAVALOR       DTCADASTRO         DATE                          Data de cadastro            OPERACIONAL                        NaN
PCGIRODIACURVAVALOR    CODUSUARIOCAD  NUMBER(8,0)           Código do usuário que cadastrou            OPERACIONAL                        NaN
PCGIRODIACURVAVALOR      DTALTERACAO         DATE                         Data de alteração            OPERACIONAL                        NaN
PCGIRODIACURVAVALOR    CODUSUARIOALT  NUMBER(8,0)             Código do usuário que alterou            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*