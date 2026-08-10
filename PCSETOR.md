# 📊 Tabela: PCSETOR

### Estrutura de Colunas e Restrições

 Tabela     Coluna Tipo/Tamanho                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSETOR   CODSETOR  NUMBER(6,0)                            Código do setor    CHAVE PRIMÁRIA (PK)                        NaN
PCSETOR  DESCRICAO VARCHAR2(30)                         Descrição do setor            OPERACIONAL                        NaN
PCSETOR USAMYFROTA  VARCHAR2(1) Indica se o setor será usado pelo  myfrota            OPERACIONAL                        NaN
PCSETOR DTULTALTER         DATE                   Data da última alteração            OPERACIONAL                        NaN
PCSETOR DTMXSALTER         DATE                                        NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*