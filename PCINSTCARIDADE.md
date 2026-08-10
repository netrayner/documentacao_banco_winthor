# 📊 Tabela: PCINSTCARIDADE

### Estrutura de Colunas e Restrições

        Tabela           Coluna  Tipo/Tamanho                                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINSTCARIDADE CODINSTDOACAOTEF   NUMBER(6,0)                        Código da Instituição para doação via troco TEF    CHAVE PRIMÁRIA (PK)                        NaN
PCINSTCARIDADE        CODFORNEC   NUMBER(6,0)                           Código do Fornecedor vinculado a Instituição            OPERACIONAL                        NaN
PCINSTCARIDADE         CODCONTA  NUMBER(10,0)                   Código da conta gerencial para lançamento de valores            OPERACIONAL                        NaN
PCINSTCARIDADE             NOME VARCHAR2(100)                                        Nome da Instituição para doação            OPERACIONAL                        NaN
PCINSTCARIDADE              CGC  VARCHAR2(18)                                Numero do CPF ou do CNPJ da Instituição            OPERACIONAL                        NaN
PCINSTCARIDADE           TIPOFJ   VARCHAR2(1)                                 Tipo da Instituição Física ou Jurídica            OPERACIONAL                        NaN
PCINSTCARIDADE            ENDER VARCHAR2(150)                                                Endereço da Instituição            OPERACIONAL                        NaN
PCINSTCARIDADE           BAIRRO VARCHAR2(100)                                                  Bairro da Instituição            OPERACIONAL                        NaN
PCINSTCARIDADE        CODCIDADE   NUMBER(6,0)            Código da Cidade da Instituição que contém o Código do IBGE            OPERACIONAL                        NaN
PCINSTCARIDADE               IE  VARCHAR2(15)                                      Inscrição Estadual da Instituição            OPERACIONAL                        NaN
PCINSTCARIDADE         TELEFONE  VARCHAR2(20)                           Numero do Telefone de Contato da Instituição            OPERACIONAL                        NaN
PCINSTCARIDADE      DEBITARTAXA   VARCHAR2(1) Se a taxa administrativa do cartão será descontada do valor doado. S/N            OPERACIONAL                        NaN
PCINSTCARIDADE            ATIVO   VARCHAR2(1)      Situação ativa do cadastro da Instituição, S = Ativo, N = Inativo            OPERACIONAL                        NaN
PCINSTCARIDADE       DTCADASTRO          DATE                                        Data do Cadastro da Instituição            OPERACIONAL                        NaN
PCINSTCARIDADE       DTULTALTER          DATE                    Data da ultima alteração do cadastro da Instituição            OPERACIONAL                        NaN
PCINSTCARIDADE  CODFUNCULTALTER   NUMBER(8,0)                                 Código do funcionário ultima alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*