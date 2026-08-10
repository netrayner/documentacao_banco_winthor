# 📊 Tabela: PCPRECO

### Estrutura de Colunas e Restrições

 Tabela                 Coluna Tipo/Tamanho                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRECO                CODPROD  NUMBER(6,0)                                             NaN            OPERACIONAL                        NaN
PCPRECO              DATAALTER         DATE                                             NaN            OPERACIONAL                        NaN
PCPRECO              CUSTOREAL NUMBER(18,6)                                             NaN            OPERACIONAL                        NaN
PCPRECO              PVENDAANT NUMBER(18,6)                                             NaN            OPERACIONAL                        NaN
PCPRECO                 PVENDA NUMBER(18,6)                                             NaN            OPERACIONAL                        NaN
PCPRECO                 ROTINA VARCHAR2(40)                                             NaN            OPERACIONAL                        NaN
PCPRECO          PERDESCMAXANT NUMBER(10,2)                                             NaN            OPERACIONAL                        NaN
PCPRECO             PERDESCMAX NUMBER(10,2)                                             NaN            OPERACIONAL                        NaN
PCPRECO                POFERTA NUMBER(10,2)                                             NaN            OPERACIONAL                        NaN
PCPRECO             POFERTAANT NUMBER(10,2)                                             NaN            OPERACIONAL                        NaN
PCPRECO              NUMREGIAO  NUMBER(4,0)                                             NaN            OPERACIONAL                        NaN
PCPRECO              MATRICULA  NUMBER(8,0)                                             NaN            OPERACIONAL                        NaN
PCPRECO               CUSTOFIN NUMBER(18,6)                                             NaN            OPERACIONAL                        NaN
PCPRECO        PERDESCAUTORANT  NUMBER(6,3)                                             NaN            OPERACIONAL                        NaN
PCPRECO           PERDESCAUTOR  NUMBER(6,3)                                             NaN            OPERACIONAL                        NaN
PCPRECO         QTDESCAUTORANT  NUMBER(6,0)                                             NaN            OPERACIONAL                        NaN
PCPRECO            QTDESCAUTOR  NUMBER(6,0)                                             NaN            OPERACIONAL                        NaN
PCPRECO            CODAUXILIAR NUMBER(16,0)                                             NaN            OPERACIONAL                        NaN
PCPRECO              CODFILIAL  VARCHAR2(2)                                             NaN            OPERACIONAL                        NaN
PCPRECO                    OBS VARCHAR2(80)   Motivo da Precificação abaixo da Margem Atual            OPERACIONAL                        NaN
PCPRECO         MARGEMIDEALANT NUMBER(12,6)                Valor da Margem Ideal Anterior.             OPERACIONAL                        NaN
PCPRECO       MARGEMIDEALATUAL NUMBER(12,6)                   Valor da Margem Ideal Atual.             OPERACIONAL                        NaN
PCPRECO      QTMINATACANTERIOR NUMBER(22,8)         Quantidade mínima de atacado anterior.             OPERACIONAL                        NaN
PCPRECO                PTABELA NUMBER(18,6)      Simulação do preço futuro de venda/atual.             OPERACIONAL                        NaN
PCPRECO             PTABELAANT NUMBER(18,6)   Simulação do preço futuro de venda/anterior.             OPERACIONAL                        NaN
PCPRECO     MARGEMIDEALATACANT NUMBER(18,6)                  Gravar margem Ideal Anterior.             OPERACIONAL                        NaN
PCPRECO   MARGEMIDEALATUALATAC NUMBER(18,6)                           Gravar margem Ideal.             OPERACIONAL                        NaN
PCPRECO             PVENDAATAC NUMBER(12,3)           Indica o preço de venda por atacado.             OPERACIONAL                        NaN
PCPRECO            POFERTAATAC NUMBER(12,2)          Indica o preço de oferta por atacado.             OPERACIONAL                        NaN
PCPRECO         POFERTAATACANT NUMBER(12,2) Indica o preço de oferta por atacado anterior.             OPERACIONAL                        NaN
PCPRECO          PVENDAATACANT NUMBER(12,3)    Indica preço da venda por atacado anterior.             OPERACIONAL                        NaN
PCPRECO            DTOFERTAINI         DATE               Indica a data de oferta inicial.             OPERACIONAL                        NaN
PCPRECO            DTOFERTAFIM         DATE                 Indica a data de oferta final.             OPERACIONAL                        NaN
PCPRECO        DTOFERTAATACINI         DATE       Indica a data de oferta atacado inicial.             OPERACIONAL                        NaN
PCPRECO        DTOFERTAATACFIM         DATE         Indica a data de oferta atacado final.             OPERACIONAL                        NaN
PCPRECO         QTMINATACATUAL NUMBER(22,8)            Quantidade mínima de atacado atual.             OPERACIONAL                        NaN
PCPRECO    PERDESCMAXTABBALCAO NUMBER(10,2)                        % desconto futuro balcão            OPERACIONAL                        NaN
PCPRECO PERDESCMAXTABBALCAOANT NUMBER(10,2)               % desconto futuro balcão anterior            OPERACIONAL                        NaN
PCPRECO           MOTIVOOFERTA VARCHAR2(60)                                Motivo da oferta            OPERACIONAL                        NaN
PCPRECO               PROGRAMA VARCHAR2(40)             Programa responsavel pela alteração            OPERACIONAL                        NaN
PCPRECO            USUARIOREDE VARCHAR2(40)                           Grava usuário da rede            OPERACIONAL                        NaN
PCPRECO                MAQUINA VARCHAR2(40)                                 Nome da máquina            OPERACIONAL                        NaN
PCPRECO                PVENDA1 NUMBER(18,6)                                   Preço venda 1            OPERACIONAL                        NaN
PCPRECO                PVENDA2 NUMBER(18,6)                                   Preço venda 2            OPERACIONAL                        NaN
PCPRECO                PVENDA3 NUMBER(18,6)                                   Preço venda 3            OPERACIONAL                        NaN
PCPRECO                PVENDA4 NUMBER(18,6)                                   Preço venda 4            OPERACIONAL                        NaN
PCPRECO                PVENDA5 NUMBER(18,6)                                   Preço venda 5            OPERACIONAL                        NaN
PCPRECO                PVENDA6 NUMBER(18,6)                                   Preço venda 6            OPERACIONAL                        NaN
PCPRECO                PVENDA7 NUMBER(18,6)                                   Preço venda 7            OPERACIONAL                        NaN
PCPRECO             PVENDA1ANT NUMBER(18,6)                          Preço venda anterior 1            OPERACIONAL                        NaN
PCPRECO             PVENDA2ANT NUMBER(18,6)                          Preço venda anterior 2            OPERACIONAL                        NaN
PCPRECO             PVENDA3ANT NUMBER(18,6)                          Preço venda anterior 3            OPERACIONAL                        NaN
PCPRECO             PVENDA4ANT NUMBER(18,6)                          Preço venda anterior 4            OPERACIONAL                        NaN
PCPRECO             PVENDA5ANT NUMBER(18,6)                          Preço venda anterior 5            OPERACIONAL                        NaN
PCPRECO             PVENDA6ANT NUMBER(18,6)                          Preço venda anterior 6            OPERACIONAL                        NaN
PCPRECO             PVENDA7ANT NUMBER(18,6)                          Preço venda anterior 7            OPERACIONAL                        NaN
PCPRECO            PTABELA1ANT NUMBER(18,6)                         Preço tabela anterior 1            OPERACIONAL                        NaN
PCPRECO            PTABELA2ANT NUMBER(18,6)                         Preço tabela anterior 2            OPERACIONAL                        NaN
PCPRECO            PTABELA3ANT NUMBER(18,6)                         Preço tabela anterior 3            OPERACIONAL                        NaN
PCPRECO            PTABELA4ANT NUMBER(18,6)                         Preço tabela anterior 4            OPERACIONAL                        NaN
PCPRECO            PTABELA5ANT NUMBER(18,6)                         Preço tabela anterior 5            OPERACIONAL                        NaN
PCPRECO            PTABELA6ANT NUMBER(18,6)                         Preço tabela anterior 6            OPERACIONAL                        NaN
PCPRECO            PTABELA7ANT NUMBER(18,6)                         Preço tabela anterior 7            OPERACIONAL                        NaN
PCPRECO               PTABELA1 NUMBER(18,6)                                  Preço tabela 1            OPERACIONAL                        NaN
PCPRECO               PTABELA2 NUMBER(18,6)                                  Preço tabela 2            OPERACIONAL                        NaN
PCPRECO               PTABELA3 NUMBER(18,6)                                  Preço tabela 3            OPERACIONAL                        NaN
PCPRECO               PTABELA4 NUMBER(18,6)                                  Preço tabela 4            OPERACIONAL                        NaN
PCPRECO               PTABELA5 NUMBER(18,6)                                  Preço tabela 5            OPERACIONAL                        NaN
PCPRECO               PTABELA6 NUMBER(18,6)                                  Preço tabela 6            OPERACIONAL                        NaN
PCPRECO               PTABELA7 NUMBER(18,6)                                  Preço tabela 7            OPERACIONAL                        NaN
PCPRECO        PERDESCMAXIDEAL NUMBER(10,2)                   % DESCONTO MAXIMO IDEAL VENDA            OPERACIONAL                        NaN
PCPRECO     PERDESCMAXIDEALANT NUMBER(10,2)          % DESCONTO MAXIMO IDEAL VENDA ANTERIOR            OPERACIONAL                        NaN
PCPRECO       PERCCOMGARANTIDA NUMBER(10,2)                            % COMISSAO GARANTIDA            OPERACIONAL                        NaN
PCPRECO    PERCCOMGARANTIDAANT NUMBER(10,2)                   % COMISSAO GARANTIDA ANTERIOR            OPERACIONAL                        NaN
PCPRECO       PERDESCMAXAVISTA NUMBER(10,2)                  % DESCONTO MÁXIMO VENDA AVISTA            OPERACIONAL                        NaN
PCPRECO    PERDESCMAXAVISTAANT NUMBER(10,2)         % DESCONTO MÁXIMO VENDA AVISTA ANTERIOR            OPERACIONAL                        NaN
PCPRECO     PERDESCMAXPOSSIVEL NUMBER(10,2)                      % DESCONTO MÁXIMO POSSÍVEL            OPERACIONAL                        NaN
PCPRECO  PERDESCMAXPOSSIVELANT NUMBER(10,2)             % DESCONTO MÁXIMO POSSÍVEL ANTERIOR            OPERACIONAL                        NaN
PCPRECO            PTABELAATAC NUMBER(18,6)                            Preço futuro atacado            OPERACIONAL                        NaN
PCPRECO         PTABELAATACANT NUMBER(18,6)                   Preço futuro atacado anterior            OPERACIONAL                        NaN
PCPRECO              PVENDAWEB NUMBER(18,6)                                 Preço venda web            OPERACIONAL                        NaN
PCPRECO           PVENDAWEBANT NUMBER(18,6)                        Preço venda web anterior            OPERACIONAL                        NaN
PCPRECO             PTABELAWEB NUMBER(18,6)                                Preço futuro web            OPERACIONAL                        NaN
PCPRECO          PTABELAWEBANT NUMBER(18,6)                       Preço futuro web anterior            OPERACIONAL                        NaN
PCPRECO             POFERTAWEB NUMBER(18,6)                                Preço oferta web            OPERACIONAL                        NaN
PCPRECO          POFERTAWEBANT NUMBER(18,6)                       Preço oferta web anterior            OPERACIONAL                        NaN
PCPRECO         DTOFERTAWEBINI         DATE                          Data inicio oferta web            OPERACIONAL                        NaN
PCPRECO         DTOFERTAWEBFIM         DATE                             Data fim oferta web            OPERACIONAL                        NaN
PCPRECO             PERDESCFOB  NUMBER(5,2)            Percentual de desconto do frete fob.            OPERACIONAL                        NaN
PCPRECO          PERDESCFOBANT  NUMBER(5,2)   Percentual de desconto do frete fob anterior.            OPERACIONAL                        NaN
PCPRECO          CUSTOPRECIFIC NUMBER(18,6)                Custo utilizado na precificação.            OPERACIONAL                        NaN
PCPRECO       CUSTOPRECIFICTAB NUMBER(18,6)            Custo utilizado na precificação tab.            OPERACIONAL                        NaN
PCPRECO       CUSTOPRECIFICANT NUMBER(18,6)       Custo utilizado na precificação anterior.            OPERACIONAL                        NaN
PCPRECO    CUSTOPRECIFICTABANT NUMBER(18,6)   Custo utilizado na precificação tab anterior.            OPERACIONAL                        NaN
PCPRECO            VLULTENTMES NUMBER(18,6)                Média do valor da última entrada            OPERACIONAL                        NaN
PCPRECO               DTCANCEL         DATE                      Data de exclusão da oferta            OPERACIONAL                        NaN
PCPRECO              CODOFERTA  NUMBER(5,0)                                Número da oferta            OPERACIONAL                        NaN
PCPRECO        PRECOMINITABANT NUMBER(18,6)                 Preço mínimo de tabela anterior            OPERACIONAL                        NaN
PCPRECO      PRECOMINITABATUAL NUMBER(18,6)                    Preço mínimo de tabela atual            OPERACIONAL                        NaN
PCPRECO     JUSTIFICATIVAPRECO VARCHAR2(50)             JUSTIFICATIVA DE ALTERACAO DE PRECO            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*