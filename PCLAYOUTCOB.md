# 📊 Tabela: PCLAYOUTCOB

### Estrutura de Colunas e Restrições

     Tabela                  Coluna  Tipo/Tamanho                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLAYOUTCOB                  CODIGO        NUMBER                                   Código layout de cobrança magnética    CHAVE PRIMÁRIA (PK)                        NaN
PCLAYOUTCOB               DESCRICAO VARCHAR2(100)                                Descrição layout de cobrança magnética            OPERACIONAL                        NaN
PCLAYOUTCOB                 REMESSA   VARCHAR2(1)                                                            É remessa?            OPERACIONAL                        NaN
PCLAYOUTCOB                PROCESSO        NUMBER                                                             Processo?            OPERACIONAL                        NaN
PCLAYOUTCOB                TAMLINHA        NUMBER                                                      Tamanho da linha            OPERACIONAL                        NaN
PCLAYOUTCOB             POSSUIERROS   VARCHAR2(1)                                                         Possui erros?            OPERACIONAL                        NaN
PCLAYOUTCOB POSSUIHEADERTRAILERLOTE   VARCHAR2(1)                                        Possui header, trailer e lote?            OPERACIONAL                        NaN
PCLAYOUTCOB         FORMATACAOTEXTO        NUMBER                     Formatação dos textos usada na geração do arquivo            OPERACIONAL                        NaN
PCLAYOUTCOB       FORMATACAOINTEIRO        NUMBER Formatação dos números sem casas decimais usada na geração do arquivo            OPERACIONAL                        NaN
PCLAYOUTCOB         FORMATACAOFLOAT        NUMBER       Formatação dos números com decimais usada na geração do arquivo            OPERACIONAL                        NaN
PCLAYOUTCOB          FORMATACAODATA        NUMBER                      Formatação das datas usada na geração do arquivo            OPERACIONAL                        NaN
PCLAYOUTCOB        GERARLINHABRANCO   VARCHAR2(1)                   Gerar última linha do arquivo de Remessa em branco.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*