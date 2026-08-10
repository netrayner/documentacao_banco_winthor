# 📊 Tabela: PCCONFIGFILIALECOMMERCE

### Estrutura de Colunas e Restrições

                 Tabela         Coluna  Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONFIGFILIALECOMMERCE             ID  NUMBER(10,0)            Identificador de registro    CHAVE PRIMÁRIA (PK)                        NaN
PCCONFIGFILIALECOMMERCE       FILIALID  NUMBER(10,0) Identificador da filial no ecommerce CHAVE ESTRANGEIRA (FK)          PCFILIALECOMMERCE
PCCONFIGFILIALECOMMERCE CONFIGURACAOID  NUMBER(10,0)       Indentificador da configuração            OPERACIONAL                        NaN
PCCONFIGFILIALECOMMERCE          VALOR VARCHAR2(250)                 Valores configurados            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*