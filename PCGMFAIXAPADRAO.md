# 📊 Tabela: PCGMFAIXAPADRAO

### Estrutura de Colunas e Restrições

         Tabela       Coluna  Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGMFAIXAPADRAO       CODIGO  NUMBER(10,0)              Código da faixa padrão    CHAVE PRIMÁRIA (PK)                        NaN
PCGMFAIXAPADRAO    DESCRICAO VARCHAR2(200)           Descrição da faixa padrão            OPERACIONAL                        NaN
PCGMFAIXAPADRAO    CODPERFIL  NUMBER(10,0)    Código do perfil da faixa padrão CHAVE ESTRANGEIRA (FK)                 PCGMPERFIL
PCGMFAIXAPADRAO CODINDICADOR  NUMBER(10,0) Código do indicador da faixa padrão CHAVE ESTRANGEIRA (FK)                 PCGMPERFIL
PCGMFAIXAPADRAO DATAEXCLUSAO          DATE                    Data da exclusão            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*