# 📊 Tabela: PCROTASASSOCIADABOX

### Estrutura de Colunas e Restrições

             Tabela            Coluna Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCROTASASSOCIADABOX     CODASSOCIACAO  NUMBER(6,0)            Código da Associação    CHAVE PRIMÁRIA (PK)                        NaN
PCROTASASSOCIADABOX         CODFILIAL  VARCHAR2(5)                Código da Filial            OPERACIONAL                        NaN
PCROTASASSOCIADABOX            CODBOX  NUMBER(6,0)         Código do Box Associado            OPERACIONAL                        NaN
PCROTASASSOCIADABOX           CODROTA  NUMBER(6,0)        Código da Rota Associada            OPERACIONAL                        NaN
PCROTASASSOCIADABOX      DTASSOCIACAO         DATE              Data da Associação            OPERACIONAL                        NaN
PCROTASASSOCIADABOX       DTALTERACAO         DATE Data de Alteração da Associação            OPERACIONAL                        NaN
PCROTASASSOCIADABOX USUARIO_ALTERACAO  NUMBER(6,0)  Usuário que realizou alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*