# 📊 Tabela: PCPARAMATUALIZACAOEVENTUAL

### Estrutura de Colunas e Restrições

                    Tabela                   Coluna Tipo/Tamanho                                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPARAMATUALIZACAOEVENTUAL       ATUALIZAPRECOVENDA  VARCHAR2(1)                                         Atualização Preço de Venda            OPERACIONAL                        NaN
PCPARAMATUALIZACAOEVENTUAL   ATUALIZAPRECOQTMINATAC  VARCHAR2(1)                               Atualização Preços Qt.Minima Atacado            OPERACIONAL                        NaN
PCPARAMATUALIZACAOEVENTUAL    ATUALIZACUSTOSTULTENT  VARCHAR2(1)                                  Atualizar Custos ST. Últ. Entrada            OPERACIONAL                        NaN
PCPARAMATUALIZACAOEVENTUAL ATUALIZATABSITTRIBUTARIA  VARCHAR2(1)                             Atualização Tabela Situação Tributária            OPERACIONAL                        NaN
PCPARAMATUALIZACAOEVENTUAL      LIBERAENTBLOQUEADAS  VARCHAR2(1)                                     Liberar as Entradas Bloqueadas            OPERACIONAL                        NaN
PCPARAMATUALIZACAOEVENTUAL     DESBLOQTODOSPRODUTOS  VARCHAR2(1)                                         Desbloquear todos produtos            OPERACIONAL                        NaN
PCPARAMATUALIZACAOEVENTUAL         DESBENTBLOQVENDA  VARCHAR2(1)                            Desbloquear entradas bloqueadas p/venda            OPERACIONAL                        NaN
PCPARAMATUALIZACAOEVENTUAL      ATUALIZACUSTOFINANC  VARCHAR2(1)                                         Atualizar Custo Financeiro            OPERACIONAL                        NaN
PCPARAMATUALIZACAOEVENTUAL           CALCULAGIRODIA  VARCHAR2(1)                                                  Calcular Giro Dia            OPERACIONAL                        NaN
PCPARAMATUALIZACAOEVENTUAL         INICIALIZASEMANA  VARCHAR2(1)                  Inicialização do Giro Semanal (Zera semana atual)            OPERACIONAL                        NaN
PCPARAMATUALIZACAOEVENTUAL    ATUALIZARSUBCLASSEABC  VARCHAR2(1)                   Atualizar Sub-Classe ABC dos produtos por filial            OPERACIONAL                        NaN
PCPARAMATUALIZACAOEVENTUAL       CALCULODIASESTOQUE  VARCHAR2(1) Indica o cálculo de dias sobre o estoque (Gerencial ou Disponível)            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*