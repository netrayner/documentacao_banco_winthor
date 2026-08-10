# 📊 Tabela: PCSUGALTCOMISSAOC

### Estrutura de Colunas e Restrições

           Tabela        Coluna Tipo/Tamanho                                                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSUGALTCOMISSAOC  CODALTERACAO NUMBER(10,0)                                                    Indica o código da alteração de sugestão gerada.    CHAVE PRIMÁRIA (PK)                        NaN
PCSUGALTCOMISSAOC     CODFILIAL  VARCHAR2(2)                               Indica o código da filial para a sugestão de alteração para comissão.            OPERACIONAL                        NaN
PCSUGALTCOMISSAOC NUMTRANSVENDA NUMBER(10,0)        Indica o número da transação de venda da nota fiscal da sugestão de alteração para comissão.            OPERACIONAL                        NaN
PCSUGALTCOMISSAOC       CODUSUR  NUMBER(4,0)                       Indica o código do RCA da nota fiscal da sugestão de alteração para comissão.            OPERACIONAL                        NaN
PCSUGALTCOMISSAOC  CODMOTORISTA  NUMBER(8,0) Indica o código do motorista do carregamento da nota fiscal da sugestão de alteração para comissão.            OPERACIONAL                        NaN
PCSUGALTCOMISSAOC     VLTOTALNF NUMBER(18,6)                         Indica o valor total da nota fiscal da sugestão de alteração para comissão.            OPERACIONAL                        NaN
PCSUGALTCOMISSAOC     PERCLUCRO  NUMBER(8,4)                 Indica o percentual de lucro da nota fiscal da sugestão de alteração para comissão.            OPERACIONAL                        NaN
PCSUGALTCOMISSAOC   VALORDIFMOT NUMBER(18,6)                Indica o valor da diferença após a alteração do percentual de comissão do motorista.            OPERACIONAL                        NaN
PCSUGALTCOMISSAOC   VALORDIFRCA NUMBER(18,6)                    Indica o valor da diferença após a alteração do percentual de comissão para RCA.            OPERACIONAL                        NaN
PCSUGALTCOMISSAOC      SITUACAO  VARCHAR2(1)          Indica a situação da sugestão valores possíveis [P] Pendente, [R] Rejeitada e [A] Aprovada            OPERACIONAL                        NaN
PCSUGALTCOMISSAOC       DTFECHA         DATE                                                            Indica a data de fechamento da sugestão.            OPERACIONAL                        NaN
PCSUGALTCOMISSAOC          DATA         DATE                                                               Indica a data de geração da sugestão.            OPERACIONAL                        NaN
PCSUGALTCOMISSAOC  CODFUNCFECHA  NUMBER(8,0)                       Indica o código do usuário responsável por realizar o fechamento da sugestão.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*