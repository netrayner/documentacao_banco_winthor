# 📊 Tabela: PCLOGPCPARAMFILIAL

### Estrutura de Colunas e Restrições

            Tabela      Coluna   Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGPCPARAMFILIAL     DTALTER           DATE     Data da alteração do parametro.    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGPCPARAMFILIAL     CODFUNC    NUMBER(8,0) Código do funcionario da alteração.    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGPCPARAMFILIAL   NOMEPARAM   VARCHAR2(34)                  Nome do parametro.    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGPCPARAMFILIAL   CODFILIAL    VARCHAR2(2)                   Código da filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGPCPARAMFILIAL  VALORATUAL VARCHAR2(1000)            Valor pararametro atual.            OPERACIONAL                        NaN
PCLOGPCPARAMFILIAL VALORANTIGO VARCHAR2(1000)           Valor pararametro antigo.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*