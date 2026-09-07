# 📊 Tabela: PCPRESTPAF

### Estrutura de Colunas e Restrições

    Tabela         Coluna  Tipo/Tamanho                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRESTPAF      DTEMISSAO          DATE                                               Data do pagamento    CHAVE PRIMÁRIA (PK)                        NaN
PCPRESTPAF      CODFILIAL   VARCHAR2(4)                                                Código da filial            OPERACIONAL                        NaN
PCPRESTPAF       NUMCAIXA   NUMBER(4,0)                                                 Número do caixa    CHAVE PRIMÁRIA (PK)                        NaN
PCPRESTPAF NUMCAIXAFISCAL   NUMBER(4,0)                                          Número do caixa fiscal            OPERACIONAL                        NaN
PCPRESTPAF  NUMSERIEEQUIP  VARCHAR2(30)                                          Número de série do ECF            OPERACIONAL                        NaN
PCPRESTPAF         CODCOB   VARCHAR2(4)                                              Código da cobrança    CHAVE PRIMÁRIA (PK)                        NaN
PCPRESTPAF          VALOR  NUMBER(12,2)                                              Valor do pagamento            OPERACIONAL                        NaN
PCPRESTPAF        TIPODOC   NUMBER(1,0) Tipo do documento do PAF (1 - ECF/ 2 - Comp Não Fiscal/ 3 - NF)    CHAVE PRIMÁRIA (PK)                        NaN
PCPRESTPAF         MD5PAF VARCHAR2(200)                               Assinatura MD5 do registro do PAF            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*