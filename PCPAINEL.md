# 📊 Tabela: PCPAINEL

### Estrutura de Colunas e Restrições

  Tabela        Coluna Tipo/Tamanho Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPAINEL CODIGO_PORTAL VARCHAR2(45)      Código Portal.    CHAVE PRIMÁRIA (PK)                   PCPORTAL
PCPAINEL CODIGO_PAINEL VARCHAR2(45)   Código do Painel.            OPERACIONAL                        NaN
PCPAINEL     MATRICULA  NUMBER(8,0)          Matricula.    CHAVE PRIMÁRIA (PK)                   PCPORTAL
PCPAINEL     ID_WIDGET       NUMBER          Id_widget.    CHAVE PRIMÁRIA (PK)                   PCWIDGET

---
*Documentação gerada automaticamente.*