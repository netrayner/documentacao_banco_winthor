# 📊 Tabela: PCSPEDECFM410

### Estrutura de Colunas e Restrições

       Tabela              Coluna  Tipo/Tamanho                                                                                                                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSPEDECFM410                  ID   NUMBER(8,0)                                                                                                                       Identificador único do registro (PK)    CHAVE PRIMÁRIA (PK)                        NaN
PCSPEDECFM410           CODFILIAL   VARCHAR2(2)                                                                                                                                Cód da filial do lançamento            OPERACIONAL                        NaN
PCSPEDECFM410         TIPOPERIODO       CHAR(1)                                                                                                                T = período trimestral ou A = período anual            OPERACIONAL                        NaN
PCSPEDECFM410         PERIODOLANC   NUMBER(2,0)                                                                                                  1 a 4 para período trimestral e 1 a 12 para período anual            OPERACIONAL                        NaN
PCSPEDECFM410                 ANO   NUMBER(4,0)                                                                                                                                          Ano do lançamento            OPERACIONAL                        NaN
PCSPEDECFM410              IDM010   NUMBER(8,0)                                                                                                  ID da conta relacionada. Refere-se à tabela PCSPEDECFM010 CHAVE ESTRANGEIRA (FK)              PCSPEDECFM010
PCSPEDECFM410               VALOR  NUMBER(22,4)                                                                                                                                        Valor do lançamento            OPERACIONAL                        NaN
PCSPEDECFM410 INDICADORLANCAMENTO   VARCHAR2(2)                                 Pode ser: BC = Base de calculo negativa da CSLL (débito), CR = Crédito, DB = Débito ou PF = Prejuízo do Exercício (débito)            OPERACIONAL                        NaN
PCSPEDECFM410 IDM010CONTRAPARTIDA   NUMBER(8,0)                                                                                             ID da conta de contrapartida. Refere-se à tabela PCSPEDECFM010 CHAVE ESTRANGEIRA (FK)              PCSPEDECFM010
PCSPEDECFM410           HISTORICO VARCHAR2(200)                                                                                                                         Motivo ou finalidade do lançamento            OPERACIONAL                        NaN
PCSPEDECFM410   REALIZACAOVALORES       CHAR(1) Realizacao de valores cuja tributação tenha sido diferida. Utilizado nos casos de mudança de tributação para presumido e retorno para real. S=Sim ou N=Não            OPERACIONAL                        NaN
PCSPEDECFM410           DTCRIACAO          DATE                                                                                                              Data de criação do registro no banco de dados            OPERACIONAL                        NaN
PCSPEDECFM410          IDORIGINAL  VARCHAR2(32)                                                                                              ID da origem quando o lançamento é copiado do LALUR para LACS            OPERACIONAL                        NaN
PCSPEDECFM410         TIPOTRIBUTO       CHAR(1)                                                                                                                         I=Imposto de Renda Pessoa Jurídica            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*