# 📊 Tabela: PCLIBPERFIL

### Estrutura de Colunas e Restrições

     Tabela      Coluna Tipo/Tamanho                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLIBPERFIL   CODPERFIL  NUMBER(8,0)                           Código do Perfil    CHAVE PRIMÁRIA (PK)                        NaN
PCLIBPERFIL   CODTABELA  NUMBER(4,0)                           Código da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCLIBPERFIL     CODIGOA VARCHAR2(40)                Código do tipo alfanumérico    CHAVE PRIMÁRIA (PK)                        NaN
PCLIBPERFIL     CODIGON NUMBER(10,0)                    Código do tipo numérico    CHAVE PRIMÁRIA (PK)                        NaN
PCLIBPERFIL CODFUNC_LIB  NUMBER(8,0) Código do usuário que realizou a liberação            OPERACIONAL                        NaN
PCLIBPERFIL    DATA_LIB         DATE                Data da liberação do acesso            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*