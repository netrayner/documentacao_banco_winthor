# 📊 Tabela: PCTRIBNCMFILIAL

### Estrutura de Colunas e Restrições

         Tabela                   Coluna Tipo/Tamanho                                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTRIBNCMFILIAL                CODFILIAL  VARCHAR2(2)                                                     CODIGO FILIAL    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBNCMFILIAL                   CODNCM VARCHAR2(20)                                                        CODIGO NCM    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBNCMFILIAL            PERCENTFISICA  NUMBER(7,4)                                          PERCENTUAL PESSOA FISICA            OPERACIONAL                        NaN
PCTRIBNCMFILIAL          PERCENTJURIDICA  NUMBER(7,4)                                        PERCENTUAL PESSOA JURIDICA            OPERACIONAL                        NaN
PCTRIBNCMFILIAL   PERCENTFISICAIMPORTADO  NUMBER(7,4)                       % de Pessoa Física para produtos Importados            OPERACIONAL                        NaN
PCTRIBNCMFILIAL PERCENTJURIDICAIMPORTADO  NUMBER(7,4)                     % de Pessoa Juridica para produtos importados            OPERACIONAL                        NaN
PCTRIBNCMFILIAL       PERCFISICAMUNICNAC  NUMBER(7,4)    % tributos municipais de produtos nacionais para pessoa fisica            OPERACIONAL                        NaN
PCTRIBNCMFILIAL         PERCFISICAESTNAC  NUMBER(7,4)     % tributos estaduais de produtos nacionais para pessoa fisica            OPERACIONAL                        NaN
PCTRIBNCMFILIAL      PERCJURIDICMUNICNAC  NUMBER(7,4)  % tributos municipais de produtos nacionais para pessoa juridica            OPERACIONAL                        NaN
PCTRIBNCMFILIAL        PERCJURIDICESTNAC  NUMBER(7,4)   % tributos estaduais de produtos nacionais para pessoa juridica            OPERACIONAL                        NaN
PCTRIBNCMFILIAL       PERCFISICAMUNICIMP  NUMBER(7,4)   % tributos municipais de produtos importados para pessoa física            OPERACIONAL                        NaN
PCTRIBNCMFILIAL         PERCFISICAESTIMP  NUMBER(7,4)    % tributos estaduais de produtos importados para pessoa física            OPERACIONAL                        NaN
PCTRIBNCMFILIAL      PERCJURIDICMUNICIMP  NUMBER(7,4) % tributos municipais de produtos importados para pessoa juridica            OPERACIONAL                        NaN
PCTRIBNCMFILIAL        PERCJURIDICESTIMP  NUMBER(7,4) % tributos municipais de produtos importados para pessoa juridica            OPERACIONAL                        NaN
PCTRIBNCMFILIAL                    CODEX  NUMBER(2,0)                                 Indica o código da exceção do NCM            OPERACIONAL                        NaN
PCTRIBNCMFILIAL      DATAULTIMAALTERACAO         DATE                                        Data de Ultima Atualização            OPERACIONAL                        NaN
PCTRIBNCMFILIAL                DTALTERC5 TIMESTAMP(6)                                                 Data de alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*