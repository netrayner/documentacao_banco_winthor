# 📊 Tabela: PCTIPOVERBA

### Estrutura de Colunas e Restrições

     Tabela        Coluna Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTIPOVERBA        CODIGO NUMBER(10,0)   Indica o cCódigo do tipo da conta.    CHAVE PRIMÁRIA (PK)                        NaN
PCTIPOVERBA     DESCRICAO VARCHAR2(60) Indica a descrição do tipo da verba.            OPERACIONAL                        NaN
PCTIPOVERBA      CODCONTA NUMBER(10,0)  Indica o código da conta gerencial.            OPERACIONAL                        NaN
PCTIPOVERBA   EMERCADORIA  VARCHAR2(1)            Indica o tipo mercadoria.            OPERACIONAL                        NaN
PCTIPOVERBA     EDINHEIRO  VARCHAR2(1)              Indica o tipo dinheiro.            OPERACIONAL                        NaN
PCTIPOVERBA     EDESCONTO  VARCHAR2(1)              Indica o tipo desconto.            OPERACIONAL                        NaN
PCTIPOVERBA     ECONTRATO  VARCHAR2(1)              Indica o tipo contrato.            OPERACIONAL                        NaN
PCTIPOVERBA EREBAIXACUSTO  VARCHAR2(1)        Indica se e rebaixa de custo.            OPERACIONAL                        NaN
PCTIPOVERBA         ATIVO  VARCHAR2(1)                Indica se esta ativo.            OPERACIONAL                        NaN
PCTIPOVERBA    DTEXCLUSAO         DATE           Indica a data de exclusão.            OPERACIONAL                        NaN
PCTIPOVERBA     EAPURACAO  VARCHAR2(1)  Indica se a verba utiliza apuração.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*