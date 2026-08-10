# 📊 Tabela: PCPARAMROTULOITEM

### Estrutura de Colunas e Restrições

           Tabela    Coluna  Tipo/Tamanho                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPARAMROTULOITEM        ID  VARCHAR2(40) Identificador do rótulo obtido da tabela PCPARAMROTULO.    CHAVE PRIMÁRIA (PK)              PCPARAMROTULO
PCPARAMROTULOITEM DESCRICAO VARCHAR2(255)      Descrição do valor do rótulo a apresentar na tela.    CHAVE PRIMÁRIA (PK)                        NaN
PCPARAMROTULOITEM     VALOR  VARCHAR2(15)       Valor do rótulo a gravar na tabela PCPARAMFILIAL.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*