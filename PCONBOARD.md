# 📊 Tabela: PCONBOARD

### Estrutura de Colunas e Restrições

   Tabela            Coluna Tipo/Tamanho                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCONBOARD         CODROTINA  NUMBER(6,0)                                                Código da Rotina            OPERACIONAL                        NaN
PCONBOARD    VERIFICARADMIN  VARCHAR2(1) Verificação se Onboard vai ser visualizado por qualquer usuário            OPERACIONAL                        NaN
PCONBOARD         IDONBOARD  NUMBER(6,0)                                               Código do Onboard    CHAVE PRIMÁRIA (PK)                        NaN
PCONBOARD ULTIMAATUALIZACAO         DATE                                     Data da Última Atualização             OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*