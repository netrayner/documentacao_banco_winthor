# 📊 Tabela: PCPARAMATUALIZACAOMENSAL

### Estrutura de Colunas e Restrições

                  Tabela                         Coluna Tipo/Tamanho                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPARAMATUALIZACAOMENSAL           INICMESCONSOLIDARANT  VARCHAR2(1) Inicializar Venda do Mês e Consolidar Mês Anterior            OPERACIONAL                        NaN
PCPARAMATUALIZACAOMENSAL      CONSOLIDARDADOSHISTORICOS  VARCHAR2(1)                   Consolidação de Dados Históricos            OPERACIONAL                        NaN
PCPARAMATUALIZACAOMENSAL      ATUALIZARBALANCETE12MESES  VARCHAR2(1)                       Atualizar Balancete 12 Meses            OPERACIONAL                        NaN
PCPARAMATUALIZACAOMENSAL          CONSOLIDARDADOSVENDAS  VARCHAR2(1)                         Consolidar dados de vendas            OPERACIONAL                        NaN
PCPARAMATUALIZACAOMENSAL           ATUALIZARABCCLIENTES  VARCHAR2(1)               Atualizar Classificação ABC Clientes            OPERACIONAL                        NaN
PCPARAMATUALIZACAOMENSAL           ATUALIZARABCPRODUTOS  VARCHAR2(1)               Atualizar Classificação ABC Produtos            OPERACIONAL                        NaN
PCPARAMATUALIZACAOMENSAL       ATUALIZARABCFORNECEDORES  VARCHAR2(1)           Atualizar Classificação ABC Fornecedores            OPERACIONAL                        NaN
PCPARAMATUALIZACAOMENSAL         CANCELARPEDIDOSCOMPRAS  VARCHAR2(1)              Cancelar Pedidos de Compras Pendentes            OPERACIONAL                        NaN
PCPARAMATUALIZACAOMENSAL         ATUALIZACASUBCLASSEABC  VARCHAR2(1)                           Atualizar Sub Classe ABC            OPERACIONAL                        NaN
PCPARAMATUALIZACAOMENSAL GERARPOSANALITICACONTASRECEBER  VARCHAR2(1)           Gerar Posição Anatítica Contas A Receber            OPERACIONAL                        NaN
PCPARAMATUALIZACAOMENSAL                ABCPRODUTOPERCA NUMBER(10,2)            Porcentagem A Classificação ABC Produto            OPERACIONAL                        NaN
PCPARAMATUALIZACAOMENSAL                ABCPRODUTOPERCB NUMBER(10,2)            Porcentagem B Classificação ABC Produto            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*