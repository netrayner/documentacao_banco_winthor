# 📊 Tabela: PCMED_TEMP_ESTDESTINO

### Estrutura de Colunas e Restrições

               Tabela            Coluna Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMED_TEMP_ESTDESTINO       CODFILIAL_D  VARCHAR2(2)           Código Filial Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO         CODPROD_D  NUMBER(6,0)          Código Produto Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO       CODFILIAL_O  VARCHAR2(2)             Código Filia Origem            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO         CODPROD_O  NUMBER(6,0)           Código Produto Origem            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO    CODGRUPOLOJA_D  NUMBER(6,0)       Código Grupo Loja Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO          CODCLI_D  NUMBER(6,0)       Código do Cliente Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO        CODMARCA_D  NUMBER(8,0)      Código Marca Prod. Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO           MARCA_D VARCHAR2(40)             Marca Prod. Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO    CODCATEGORIA_D  NUMBER(6,0)    Cód. Categoria Prod. Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO          CODSEC_D  NUMBER(6,0)   Código da Seção Prod. Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO         CODEPTO_D  NUMBER(6,0)  Código do Depto. Prod. Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO       CODFORNEC_D  NUMBER(6,0) Código Fornecedor Prod. Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO       DESCRICAO_D VARCHAR2(40)    Descrição do Produto Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO       EMBALAGEM_D VARCHAR2(12)         Embalagem Prod. Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO         UNIDADE_D  VARCHAR2(2)     Unidade Venda Prod. Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO        QTUNITCX_D NUMBER(22,6)    Qtde. Unidades Caixa Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO        QTESTGER_D NUMBER(22,8)       Estoque Gerencial Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO        QTRESERV_D NUMBER(22,8)       Estoque Reservado Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO     QTBLOQUEADA_D NUMBER(22,8)       Estoque Bloqueado Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO       QTINDENIZ_D NUMBER(22,8)        Estoque Avariado Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO      ESTOQUEMIN_D NUMBER(22,8)          Estoque Minimo Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO      ESTOQUEMAX_D NUMBER(22,8)          Estoque Máximo Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO        QTPEDIDA_D NUMBER(22,6)          Qtde. Pendente Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO     CUSTOULTENT_D NUMBER(22,6)        Custo Ult. Entrada Dest.            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO   PERCARREDONDA_D NUMBER(10,2) Percentual Arredondamento Dest.            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO    TIPOSUGESTAO_D  VARCHAR2(1)        Tipo de Sugestão Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO          CLASSE_D  VARCHAR2(1)           Classe de Venda Dest.            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO             PMC_D NUMBER(22,6)                     PMC Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO          PVENDA_D NUMBER(22,6)             Preço Venda Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO       QTVENDMES_D NUMBER(16,3)         Qtde. Venda Mês Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO      QTVENDMES1_D NUMBER(16,3)       Qtde. Venda Mês 1 Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO      QTVENDMES2_D NUMBER(16,3)       Qtde. Venda Mês 2 Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO      QTVENDMES3_D NUMBER(16,3)       Qtde. Venda Mês 3 Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO      QTPENDENTE_D NUMBER(16,3)          Qtde. Pendente Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO          CODFAB_D VARCHAR2(30)          Código Fábrica Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO     CODAUXILIAR_D NUMBER(20,0)                     EAN Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO       QTGIRODIA_D NUMBER(16,3)              Giro Prod. Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO          ESTMIN_D NUMBER(16,3)       Est. Mínimo Prod. Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO    ESTOQUEIDEAL_D NUMBER(16,3)     Estoque Ideal Prod. Destino            OPERACIONAL                        NaN
PCMED_TEMP_ESTDESTINO CODFILIALRETIRA_O  VARCHAR2(2)     Código Filial Retira Origem            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*