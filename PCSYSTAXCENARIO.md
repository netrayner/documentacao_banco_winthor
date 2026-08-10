# 📊 Tabela: PCSYSTAXCENARIO

### Estrutura de Colunas e Restrições

         Tabela                Coluna  Tipo/Tamanho                                                                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSYSTAXCENARIO            ID_CENARIO   VARCHAR2(7)                                                                                                    Id do cenário    CHAVE PRIMÁRIA (PK)                        NaN
PCSYSTAXCENARIO  ID_CENARIO_PRINCIPAL   VARCHAR2(7)                                                                                         Id do cenário principal.            OPERACIONAL                        NaN
PCSYSTAXCENARIO               APELIDO  VARCHAR2(50)                                                                                         Identificação do cenário            OPERACIONAL                        NaN
PCSYSTAXCENARIO          DIAS_FUTUROS   VARCHAR2(3)                                                 Indica a quantidade de dias futuros a ser analisada a legislação            OPERACIONAL                        NaN
PCSYSTAXCENARIO        GRUPO_PRODUTOS  VARCHAR2(50)                                                            Nome dos grupos de produtos associados a esse cenário            OPERACIONAL                        NaN
PCSYSTAXCENARIO             UF_ORIGEM   VARCHAR2(2)                                                                              Sigla da UF de origem da mercadoria            OPERACIONAL                        NaN
PCSYSTAXCENARIO            UF_DESTINO   VARCHAR2(2)                                                                             Sigla da UF de destino da mercadoria            OPERACIONAL                        NaN
PCSYSTAXCENARIO                ORIGEM VARCHAR2(120)           Perfil do estabelecimento remetente da operação. Para verificar os códigos, veja a tabela ¿Remetente¿.            OPERACIONAL                        NaN
PCSYSTAXCENARIO            DESTINACAO VARCHAR2(120)          Perfil do estabelecimento remetente da operação. Para verificar os códigos, veja a tabela ¿Destinação¿.            OPERACIONAL                        NaN
PCSYSTAXCENARIO COD_NATUREZA_OPERACAO   VARCHAR2(3)                Código da natureza da operação. Para verificar os códigos, veja a tabela ¿Natureza de Operações¿.            OPERACIONAL                        NaN
PCSYSTAXCENARIO      MUNICIPIO_ORIGEM   VARCHAR2(7)  Código de Município de origem da operação. Deve ser utilizada a Tabela de código de Município mantida pelo IBGE            OPERACIONAL                        NaN
PCSYSTAXCENARIO     MUNICIPIO_DESTINO   VARCHAR2(7) Código de Município de destino da operação. Deve ser utilizada a Tabela de código de Município mantida pelo IBGE            OPERACIONAL                        NaN
PCSYSTAXCENARIO     CNAE_DESTINATARIO   VARCHAR2(7)                 Código de Classificação Nacional de Atividades Econômicas (CNAE) do estabelecimento destinatário            OPERACIONAL                        NaN
PCSYSTAXCENARIO               ENT_SAI  VARCHAR2(27)              Indicação do tipo da operação: 1- Entrada 2- Devolução de Entradas 3- Saídas 4- Devolução de Saídas            OPERACIONAL                        NaN
PCSYSTAXCENARIO            FINALIDADE   VARCHAR2(3)                                       Código que indica a finalidade do produto, qual a destinação desse produto            OPERACIONAL                        NaN
PCSYSTAXCENARIO             DT_INSERT          DATE                                                                           Data de inserção do registro na tabela            OPERACIONAL                        NaN
PCSYSTAXCENARIO             DT_UPDATE          DATE                                                                             Data de update do registro na tabela            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*