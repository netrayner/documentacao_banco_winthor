# 📊 Tabela: PCPERSONALGPD

### Estrutura de Colunas e Restrições

       Tabela     Coluna Tipo/Tamanho                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPERSONALGPD CODPERSONA  NUMBER(8,0)                                            Identificador único    CHAVE PRIMÁRIA (PK)                        NaN
PCPERSONALGPD    PERSONA  NUMBER(8,0) Identificação do persona Ex: (Cliente, Motorista, Colaboardor)            OPERACIONAL                        NaN
PCPERSONALGPD  DESCRICAO VARCHAR2(40)                                           Descrição do persona            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*