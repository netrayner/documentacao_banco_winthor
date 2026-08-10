# 📊 Tabela: PCORDEMAPURACAOCOMIS

### Estrutura de Colunas e Restrições

              Tabela     Coluna Tipo/Tamanho                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCORDEMAPURACAOCOMIS  CODFILIAL  VARCHAR2(2)                             Campo para armazenar o código da filial.     CHAVE PRIMÁRIA (PK)                        NaN
PCORDEMAPURACAOCOMIS   CODCOMIS  NUMBER(2,0)                   Campo para armazenar o código do tipo de comissão.     CHAVE PRIMÁRIA (PK)                        NaN
PCORDEMAPURACAOCOMIS  DESCRICAO VARCHAR2(40)                Campo para armazenar a descrição do tipo de comissão.             OPERACIONAL                        NaN
PCORDEMAPURACAOCOMIS      ORDEM  NUMBER(2,0) Campo para armazenar a ordem de apuração para cada tipo de comissão.             OPERACIONAL                        NaN
PCORDEMAPURACAOCOMIS DTMXSALTER         DATE                                                                   NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*