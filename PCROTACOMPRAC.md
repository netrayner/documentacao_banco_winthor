# 📊 Tabela: PCROTACOMPRAC

### Estrutura de Colunas e Restrições

       Tabela           Coluna  Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCROTACOMPRAC          CODROTA  NUMBER(10,0)                      Código da rota    CHAVE PRIMÁRIA (PK)                        NaN
PCROTACOMPRAC        DESCRICAO VARCHAR2(255)                   Descrição da rota            OPERACIONAL                        NaN
PCROTACOMPRAC CODFILIALDESTINO   VARCHAR2(2) Código da filial de destino da rota            OPERACIONAL                        NaN
PCROTACOMPRAC       DTEXCLUSAO          DATE          Data da inativação da rota            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*