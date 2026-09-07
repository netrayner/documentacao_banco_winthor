# 📊 Tabela: PCIMPRETIQCOLETOR

### Estrutura de Colunas e Restrições

           Tabela        Coluna Tipo/Tamanho      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCIMPRETIQCOLETOR   CODAUXILIAR NUMBER(16,0)     Código da Embalagem.            OPERACIONAL                        NaN
PCIMPRETIQCOLETOR       CODFUNC  NUMBER(8,0)   Código do funcionário. CHAVE ESTRANGEIRA (FK)                     PCEMPR
PCIMPRETIQCOLETOR QTEMISSAOETIQ  NUMBER(8,0) Quantidade de etiquetas.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*