# 📊 Tabela: PCPARAMFILIALTRANSF

### Estrutura de Colunas e Restrições

             Tabela              Coluna  Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPARAMFILIALTRANSF  CODIGOFILIALORIGEM   VARCHAR2(2)  Código da Filial Origem Transferência    CHAVE PRIMÁRIA (PK)                        NaN
PCPARAMFILIALTRANSF CODIGOFILIALDESTINO   VARCHAR2(2) Código da Filial Destino Transferência    CHAVE PRIMÁRIA (PK)                        NaN
PCPARAMFILIALTRANSF        CONFIGURACAO VARCHAR2(100)                   Nome da Configuração    CHAVE PRIMÁRIA (PK)                        NaN
PCPARAMFILIALTRANSF               VALOR VARCHAR2(100)                  Valor da Configuração            OPERACIONAL                        NaN
PCPARAMFILIALTRANSF              CODIGO  NUMBER(22,0)                      Código Sequencial            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*