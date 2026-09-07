# 📊 Tabela: PCCONFIGCLASSECLIMEDATRASO

### Estrutura de Colunas e Restrições

                    Tabela       Coluna Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONFIGCLASSECLIMEDATRASO    CODCONFIG  NUMBER(2,0)                                         Código    CHAVE PRIMÁRIA (PK)                        NaN
PCCONFIGCLASSECLIMEDATRASO FAIXAINICIAL  NUMBER(6,0) Faixa inicial da configuração de classe atraso    CHAVE PRIMÁRIA (PK)                        NaN
PCCONFIGCLASSECLIMEDATRASO   FAIXAFINAL  NUMBER(6,0)   Faixa final da configuração de classe atraso    CHAVE PRIMÁRIA (PK)                        NaN
PCCONFIGCLASSECLIMEDATRASO    TIPOJUROS  VARCHAR2(1) Tipo de juros da configuração de classe atraso    CHAVE PRIMÁRIA (PK)                        NaN
PCCONFIGCLASSECLIMEDATRASO       PONTOS  NUMBER(6,0)     Pontuação da configuração de classe atraso            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*