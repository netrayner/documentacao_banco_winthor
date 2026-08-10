# 📊 Tabela: PCACESSOCOLETOR

### Estrutura de Colunas e Restrições

         Tabela       Coluna Tipo/Tamanho            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCACESSOCOLETOR    CODROTINA NUMBER(10,0)    Código da rotina do coletor            OPERACIONAL                        NaN
PCACESSOCOLETOR CODPERMISSAO NUMBER(10,0)  Código da permissão da rotina            OPERACIONAL                        NaN
PCACESSOCOLETOR   CODUSUARIO  NUMBER(8,0)              Código do usuário CHAVE ESTRANGEIRA (FK)                     PCEMPR
PCACESSOCOLETOR       ACESSO  VARCHAR2(1) Se o usuário tem acesso ou não            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*