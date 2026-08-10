# 📊 Tabela: PCGIRODIAFIGURA

### Estrutura de Colunas e Restrições

         Tabela                        Coluna  Tipo/Tamanho                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGIRODIAFIGURA                        CODIGO   NUMBER(6,0)                                         Código da figura    CHAVE PRIMÁRIA (PK)                        NaN
PCGIRODIAFIGURA                     DESCRICAO VARCHAR2(250)                                      Descrição da figura            OPERACIONAL                        NaN
PCGIRODIAFIGURA                    CODPERIODO   NUMBER(6,0)                                        Código do período            OPERACIONAL                        NaN
PCGIRODIAFIGURA                          PICO  NUMBER(18,6)                                       Percentaul de pico            OPERACIONAL                        NaN
PCGIRODIAFIGURA                          VALE  NUMBER(18,6)                                       Percentual de vale            OPERACIONAL                        NaN
PCGIRODIAFIGURA              USATRANSFERENCIA   VARCHAR2(1)                            Usa registro de transferência            OPERACIONAL                        NaN
PCGIRODIAFIGURA                        USAKIT   VARCHAR2(1)                           Usa registro de kit / produção            OPERACIONAL                        NaN
PCGIRODIAFIGURA                      USAFALTA   VARCHAR2(1)                           Usa registro de falta na venda            OPERACIONAL                        NaN
PCGIRODIAFIGURA                   TIPOESTOQUE   VARCHAR2(1)                                          Tipo do estoque            OPERACIONAL                        NaN
PCGIRODIAFIGURA                    DTCADASTRO          DATE                                         Data de cadastro            OPERACIONAL                        NaN
PCGIRODIAFIGURA                 CODUSUARIOCAD   NUMBER(8,0)                          Código do usuário que cadastrou            OPERACIONAL                        NaN
PCGIRODIAFIGURA                   DTALTERACAO          DATE                                        Data de alteração            OPERACIONAL                        NaN
PCGIRODIAFIGURA                 CODUSUARIOALT   NUMBER(8,0)                            Código do usuário que alterou            OPERACIONAL                        NaN
PCGIRODIAFIGURA  USATRANSFERENCIAFILIALRETIRA   VARCHAR2(1)  Usa transferência de filial retira para calculo do giro            OPERACIONAL                        NaN
PCGIRODIAFIGURA USATRANSFERENCIAFILIALVIRTUAL   VARCHAR2(1) Usa transferência de filial virtual para calculo do giro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*