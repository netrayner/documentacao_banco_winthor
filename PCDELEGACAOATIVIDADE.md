# 📊 Tabela: PCDELEGACAOATIVIDADE

### Estrutura de Colunas e Restrições

              Tabela                 Coluna Tipo/Tamanho                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDELEGACAOATIVIDADE           CODDELEGACAO NUMBER(10,0)                             Código Chave Primária da Delegação    CHAVE PRIMÁRIA (PK)                        NaN
PCDELEGACAOATIVIDADE              CODFILIAL  VARCHAR2(2)                                               Código da Filial CHAVE ESTRANGEIRA (FK)                   PCFILIAL
PCDELEGACAOATIVIDADE           TIPOOPERACAO  VARCHAR2(1)                Tipo Operação (A = Adiantamento, P = Prestação)            OPERACIONAL                        NaN
PCDELEGACAOATIVIDADE TIPOFUNCRESPLANCAMENTO  VARCHAR2(1) Tipo Funcionário (F=funcionário, M=Motorista, V=Vendedor(RCA))            OPERACIONAL                        NaN
PCDELEGACAOATIVIDADE      CODRESPLANCAMENTO  NUMBER(8,0)                          Código do Responsável pelo lançamento CHAVE ESTRANGEIRA (FK)                     PCEMPR

---
*Documentação gerada automaticamente.*