# 📊 Tabela: PCPRESTOBS

### Estrutura de Colunas e Restrições

    Tabela        Coluna   Tipo/Tamanho                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRESTOBS NUMTRANSVENDA   NUMBER(10,0)         Número da transação de venda.    CHAVE PRIMÁRIA (PK)                        NaN
PCPRESTOBS         PREST    VARCHAR2(2)                    Parcela do título.    CHAVE PRIMÁRIA (PK)                        NaN
PCPRESTOBS     PENDENCIA    VARCHAR2(1)                 Título tem pendência?            OPERACIONAL                        NaN
PCPRESTOBS     OBSACERTO VARCHAR2(2000)                Observações de acerto.            OPERACIONAL                        NaN
PCPRESTOBS     OBSGERAIS VARCHAR2(2000) Observações Cadastradas pelo Usuário.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*