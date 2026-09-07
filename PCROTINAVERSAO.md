# 📊 Tabela: PCROTINAVERSAO

### Estrutura de Colunas e Restrições

        Tabela           Coluna Tipo/Tamanho                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCROTINAVERSAO        CODROTINA  NUMBER(4,0)                                     Apresenta codigo da rotina            OPERACIONAL                        NaN
PCROTINAVERSAO PERMITECONTINUAR  VARCHAR2(1) Apresenta se e permitido continuar mesmo estando desatualizada            OPERACIONAL                        NaN
PCROTINAVERSAO    VERSAOCLIENTE  NUMBER(8,0)                        Apresenta a versão da rotina do cliente            OPERACIONAL                        NaN
PCROTINAVERSAO      MENORVERSAO  NUMBER(8,0)                Apresenta a menor versao que deve ser executada            OPERACIONAL                        NaN
PCROTINAVERSAO             DATA         DATE                                  Apresnta a data de lancamento            OPERACIONAL                        NaN
PCROTINAVERSAO    CODROTINALANC  NUMBER(4,0)             Apresenta o codigo da rotina da ultima atualização            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*