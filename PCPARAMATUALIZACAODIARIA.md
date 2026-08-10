# 📊 Tabela: PCPARAMATUALIZACAODIARIA

### Estrutura de Colunas e Restrições

                  Tabela                        Coluna Tipo/Tamanho                                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPARAMATUALIZACAODIARIA         BLOQUEARPRODFORALINHA  VARCHAR2(1)                             Excluir produto FL sem estoque (Preecher DTEXCLUSAO)            OPERACIONAL                        NaN
PCPARAMATUALIZACAODIARIA        ZERAACUMULADORVENDADIA  VARCHAR2(1)                                                  Zerar acumuladores Venda do Dia            OPERACIONAL                        NaN
PCPARAMATUALIZACAODIARIA   ARMAZENAACUMULADORESCXBANCO  VARCHAR2(1)                                                     Armazenar Saldos Caixa Banco            OPERACIONAL                        NaN
PCPARAMATUALIZACAODIARIA          ARMAZENASALDOESTOQUE  VARCHAR2(1)                                                         Armanenar Saldos Estoque            OPERACIONAL                        NaN
PCPARAMATUALIZACAODIARIA      ARMAZENASALDOESTOQUELOTE  VARCHAR2(1)                                                 Armazenar Saldos Estoque de Lote            OPERACIONAL                        NaN
PCPARAMATUALIZACAODIARIA        CONSOLIDADADOSPLANOVOO  VARCHAR2(1)                                                            Consolidação de Dados            OPERACIONAL                        NaN
PCPARAMATUALIZACAODIARIA     ATUALIZASALDOSFINANCEIROS  VARCHAR2(1)                                               Atualização dos Saldos Financeiros            OPERACIONAL                        NaN
PCPARAMATUALIZACAODIARIA    BLOQUEIADESBLOQUEIACLIENTE  VARCHAR2(1)                                    Bloqueia/Desbloqueia Clientes Automaticamente            OPERACIONAL                        NaN
PCPARAMATUALIZACAODIARIA        BLOQUEIACLIENTEINATIVO  VARCHAR2(1)                                     Bloqueia Clientes Inativos a mais de %s Dias            OPERACIONAL                        NaN
PCPARAMATUALIZACAODIARIA   RECALCPERCVENDAPESSOAFISICA  VARCHAR2(1)                                          Recálculo do % Venda para Pessoa Física            OPERACIONAL                        NaN
PCPARAMATUALIZACAODIARIA      ATUALIZARDTPROXIMAVISITA  VARCHAR2(1)                       Atualização de Dt. Prox. Visita (Roteirização de Clientes)            OPERACIONAL                        NaN
PCPARAMATUALIZACAODIARIA            GERARLIVROSFISCAIS  VARCHAR2(1)                                                               Geração dos Livros            OPERACIONAL                        NaN
PCPARAMATUALIZACAODIARIA    BLOQUEIACLIENTECHEQUEDEVOL  VARCHAR2(1)         Bloqueia Clientes com mais de %s Cheques Devolvidos nos últimos %s  Dias            OPERACIONAL                        NaN
PCPARAMATUALIZACAODIARIA  BLOQUEIACLIENTENOVOCHEQUEDEV  VARCHAR2(1) Bloqueia Clientes Cadastrados nos últimos %s Dias que tiveram Cheques Devolvidos            OPERACIONAL                        NaN
PCPARAMATUALIZACAODIARIA        BLOQUEIALOTEVENCIMENTO  VARCHAR2(1)                     Bloquear LOTES de acordo com XXX dias para o fim da validade            OPERACIONAL                        NaN
PCPARAMATUALIZACAODIARIA      EXCLUIRORCAMENTOEXPIRADO  VARCHAR2(1)                                            Excluir Orçamentos com Prazo Expirado            OPERACIONAL                        NaN
PCPARAMATUALIZACAODIARIA   BLOQUEIAFORNECVERBAVENCIADA  VARCHAR2(1)          Bloqueia/desbloqueia Fornecedores com Verbas Vencidas a mais de %s Dias            OPERACIONAL                        NaN
PCPARAMATUALIZACAODIARIA          ATUALIZADEVOLUCAOMES  VARCHAR2(1)                                            Atualizar Quantidade Devolvida no Mês            OPERACIONAL                        NaN
PCPARAMATUALIZACAODIARIA     RECALCQTRESERVQTPENDVENDA  VARCHAR2(1)                                 Recálculo da Qtde. Pendente e da Qtde. Reservada            OPERACIONAL                        NaN
PCPARAMATUALIZACAODIARIA        TITULOSAGENTECOBRANCAO  VARCHAR2(1)                            Direcionar Títulos Vencidos entre Agentes de Cobrança            OPERACIONAL                        NaN
PCPARAMATUALIZACAODIARIA        BLOQUEARCLIENTEINATIVO  VARCHAR2(1)    Zera limites e altera cobrança para D para cliente inativos a mais de %s Dias            OPERACIONAL                        NaN
PCPARAMATUALIZACAODIARIA      ATUALIZARAGENDAFORNCEDOR  VARCHAR2(1)                                                                Agenda Fornecedor            OPERACIONAL                        NaN
PCPARAMATUALIZACAODIARIA RECALCULARCONTASPAGARPREVISTO  VARCHAR2(1)                                                Recálculo Contas a Pagar Previsto            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*