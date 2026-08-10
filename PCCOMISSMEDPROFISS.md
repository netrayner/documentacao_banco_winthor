# 📊 Tabela: PCCOMISSMEDPROFISS

### Estrutura de Colunas e Restrições

            Tabela          Coluna Tipo/Tamanho                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOMISSMEDPROFISS       CODFILIAL  VARCHAR2(2)                                     Código da Filial    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMISSMEDPROFISS      TIPOCOMISS  VARCHAR2(1)              Tpo de Comissão [F-Fornecedor; M-Marca]    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMISSMEDPROFISS       CODCOMISS  NUMBER(9,0) Código da Comissão para o Tipo de Comissão informado    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMISSMEDPROFISS       PERCOMISS  NUMBER(8,4)                               Percentual de Comissão            OPERACIONAL                        NaN
PCCOMISSMEDPROFISS CODFUNCCADASTRO  NUMBER(8,0)                                 Funcionário cadastro            OPERACIONAL                        NaN
PCCOMISSMEDPROFISS      DTCADASTRO         DATE                                        Data Cadastro            OPERACIONAL                        NaN
PCCOMISSMEDPROFISS   CODFUNCULTALT  NUMBER(8,0)                         Funcionário última alteração            OPERACIONAL                        NaN
PCCOMISSMEDPROFISS        DTULTALT         DATE                                  Data últ. Alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*