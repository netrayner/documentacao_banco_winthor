# 📊 Tabela: PCVINCULOPALAVRAS

### Estrutura de Colunas e Restrições

           Tabela             Coluna Tipo/Tamanho                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVINCULOPALAVRAS        TIPOVINCULO VARCHAR2(20)                         TIPO DO VINCULO QUE FOI REALIZADO    CHAVE PRIMÁRIA (PK)                        NaN
PCVINCULOPALAVRAS      CODIGOVINCULO NUMBER(20,0) CODIGO QUE FOI CADASTRADO NO VINCULO DE ACORDO COM O TIPO    CHAVE PRIMÁRIA (PK)                        NaN
PCVINCULOPALAVRAS CODIGOPALAVRACHAVE NUMBER(20,0)                      CODIGO DO KEY WORD QUE FOI VINCULADO    CHAVE PRIMÁRIA (PK)                        NaN
PCVINCULOPALAVRAS         DTEXCLUSAO         DATE                                          Data de exclusão            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*