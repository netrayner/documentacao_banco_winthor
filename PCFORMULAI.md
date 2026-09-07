# 📊 Tabela: PCFORMULAI

### Estrutura de Colunas e Restrições

    Tabela      Coluna Tipo/Tamanho                                                                                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFORMULAI  CODFORMULA NUMBER(10,0)                             Campo para identificar a fórmula a ser utilizada. |Campo do tipo numérico, de tamanho 10, sem casas decimais.    CHAVE PRIMÁRIA (PK)                        NaN
PCFORMULAI   CODROTINA  NUMBER(6,0)                          Campo para identificar qual rotina utiliza a fórmula. |Campo do tipo numérico, de tamanho 6, sem casas decimais.    CHAVE PRIMÁRIA (PK)                        NaN
PCFORMULAI CODCONTROLE  NUMBER(6,0) Campo para identificar qual controle, pertencente a rotina, utiliza a fórmula. |Campo do tipo numérico, de tamanho 6, sem casas decimais.    CHAVE PRIMÁRIA (PK)                        NaN
PCFORMULAI    SITUACAO  VARCHAR2(1)                                          Indica se o registro está "A - Ativo" ou "I - Inativo".  |Campo do tipo caracter, de tamanho 32.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*