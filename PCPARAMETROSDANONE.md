# 📊 Tabela: PCPARAMETROSDANONE

### Estrutura de Colunas e Restrições

            Tabela                   Coluna Tipo/Tamanho                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPARAMETROSDANONE     ESTOQUE_DE_SEGURANCA  NUMBER(6,2)                               Estoque de Segurança em %.            OPERACIONAL                        NaN
PCPARAMETROSDANONE  QTDE_COLETAS_REALIZADAS  NUMBER(8,2)                   Referência em Qtd. Coletas Realizadas.            OPERACIONAL                        NaN
PCPARAMETROSDANONE VENDA_SEM_COLETA_ESTOQUE  VARCHAR2(1)              Permitir Venda sem Coleta de Estoque (S/N).            OPERACIONAL                        NaN
PCPARAMETROSDANONE               TIPO_TROCA  VARCHAR2(2)                                   Tipo de Troca (A,T,N).            OPERACIONAL                        NaN
PCPARAMETROSDANONE      VERIFICAQTCALCULADA  VARCHAR2(1) A quantidade calculada será sempre assumida na sugestão.            OPERACIONAL                        NaN
PCPARAMETROSDANONE        PERCSEGSEMESTOQUE  NUMBER(6,2)                      Percentual do estoque de segurança.            OPERACIONAL                        NaN
PCPARAMETROSDANONE          DIASLEITURAGIRO  NUMBER(6,0)         Número dias para desconsiderar os giros zerados.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*