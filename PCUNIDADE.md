# 📊 Tabela: PCUNIDADE

### Estrutura de Colunas e Restrições

   Tabela     Coluna Tipo/Tamanho                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCUNIDADE    UNIDADE  VARCHAR2(6) Indica a sigla da unidade.|Campo do tipo caracter, de tamanho 2, obrigatório.     CHAVE PRIMÁRIA (PK)                        NaN
PCUNIDADE  DESCRICAO VARCHAR2(60)         Indica a descrição da unidade.|Campo do tipo caracter, de tamanho 60.             OPERACIONAL                        NaN
PCUNIDADE UNIDADECTE  VARCHAR2(2)                                                                 Unidade do CTE            OPERACIONAL                        NaN
PCUNIDADE DTEXCLUSAO         DATE                                                          Data exclusão produto            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*