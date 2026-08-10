# 📊 Tabela: PCAPURACAOICMSDIEF

### Estrutura de Colunas e Restrições

            Tabela     Coluna Tipo/Tamanho                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAPURACAOICMSDIEF  CODFILIAL  VARCHAR2(2) Código da filial apuração da DIEF.    CHAVE PRIMÁRIA (PK)                        NaN
PCAPURACAOICMSDIEF        MES  NUMBER(2,0)           Mês de apuração da DIEF.    CHAVE PRIMÁRIA (PK)                        NaN
PCAPURACAOICMSDIEF        ANO  NUMBER(4,0)           Ano de apuração da DIEF.    CHAVE PRIMÁRIA (PK)                        NaN
PCAPURACAOICMSDIEF  NOMECAMPO VARCHAR2(20)       Nome do campo no formulário.    CHAVE PRIMÁRIA (PK)                        NaN
PCAPURACAOICMSDIEF VALORCAMPO VARCHAR2(80)         Valor do campo formulário.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*