# 📊 Tabela: PCESTANALITICOVENDA

### Estrutura de Colunas e Restrições

             Tabela           Coluna Tipo/Tamanho                                                                                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCESTANALITICOVENDA CODFILIALESTOQUE  VARCHAR2(2)                                                                                          O código da filial onde o estoque foi/será reservado.            OPERACIONAL                        NaN
PCESTANALITICOVENDA           NUMPED NUMBER(10,0)                                                                                                           O número do pedido usado na reserva.    CHAVE PRIMÁRIA (PK)                        NaN
PCESTANALITICOVENDA           NUMSEQ NUMBER(20,0)                                                                                                         A posição do pedido durante a reserva.    CHAVE PRIMÁRIA (PK)                        NaN
PCESTANALITICOVENDA            NUMOS NUMBER(10,0)                                                                                                 O número da Ordem de serviço usada na reserva.    CHAVE PRIMÁRIA (PK)                        NaN
PCESTANALITICOVENDA   NUMTRANSAVULSA NUMBER(10,0)                                                                             O número da transação de Ordem de serviço avulsa usada na reserva.    CHAVE PRIMÁRIA (PK)                        NaN
PCESTANALITICOVENDA       POSICAOPED  VARCHAR2(2) A posição em que o estoque se encontra. Existe apenas duas posições para o estoque duratne a venda "R - Para reservado" e "P - Para pendente".            OPERACIONAL                        NaN
PCESTANALITICOVENDA       POSICAOEST  VARCHAR2(2)                                                                                                                               Data da reserva.            OPERACIONAL                        NaN
PCESTANALITICOVENDA             DATA         DATE                                                                                                            Código do produto usado na reserva.            OPERACIONAL                        NaN
PCESTANALITICOVENDA          CODPROD  NUMBER(6,0)                                                                                                                          Quantidade reservada.    CHAVE PRIMÁRIA (PK)                        NaN
PCESTANALITICOVENDA               QT NUMBER(20,6)                                                                                                         Número de sequencia do item no pedido.            OPERACIONAL                        NaN
PCESTANALITICOVENDA     ROTINAULTALT VARCHAR2(80)                                                                                                 Rotina que fez a ultima alteração do registro.            OPERACIONAL                        NaN
PCESTANALITICOVENDA       ROTINALANC VARCHAR2(80)                                                                                                                 Rotina que lançou o resgistro.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*