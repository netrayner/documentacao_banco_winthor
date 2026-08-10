# 📊 Tabela: PCMOVMOTOQUEIRO

### Estrutura de Colunas e Restrições

         Tabela            Coluna  Tipo/Tamanho                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVMOTOQUEIRO            NUMPED  NUMBER(10,0)                   Número do pedido    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVMOTOQUEIRO     CODMOTOQUEIRO  NUMBER(10,0)               Código do motoqueiro    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVMOTOQUEIRO        CODVEICULO  NUMBER(10,0)                  Código do veículo            OPERACIONAL                        NaN
PCMOVMOTOQUEIRO CODTRANSPORTADORA  NUMBER(10,0)                Cód. Transportadora    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVMOTOQUEIRO   CODBAIRROORIGEM  NUMBER(10,0)                      Bairro origem            OPERACIONAL                        NaN
PCMOVMOTOQUEIRO  CODBAIRRODESTINO  NUMBER(10,0)                     Bairro destino            OPERACIONAL                        NaN
PCMOVMOTOQUEIRO     VLTAXAENTREGA  NUMBER(18,6)           Valor da taxa de entrega            OPERACIONAL                        NaN
PCMOVMOTOQUEIRO           DTSAIDA          DATE        Data de saida do motoqueiro            OPERACIONAL                        NaN
PCMOVMOTOQUEIRO         KMINICIAL  NUMBER(18,6)               Kilometragem inicial            OPERACIONAL                        NaN
PCMOVMOTOQUEIRO    HISTORICOSAIDA VARCHAR2(300)                 Historico de saida            OPERACIONAL                        NaN
PCMOVMOTOQUEIRO         DTRETORNO          DATE                    Data de retorno            OPERACIONAL                        NaN
PCMOVMOTOQUEIRO           KMFINAL  NUMBER(18,6)                 Kilometragem final            OPERACIONAL                        NaN
PCMOVMOTOQUEIRO  HISTORICORETORNO VARCHAR2(300)               Historico de retorno            OPERACIONAL                        NaN
PCMOVMOTOQUEIRO         CODFILIAL   VARCHAR2(2)                   Filial do pedido            OPERACIONAL                        NaN
PCMOVMOTOQUEIRO  PERCPARTICIPACAO  NUMBER(18,6) % Participação da empresa no frete            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*