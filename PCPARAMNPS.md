# 📊 Tabela: PCPARAMNPS

### Estrutura de Colunas e Restrições

    Tabela                 Coluna   Tipo/Tamanho                                                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPARAMNPS                URLBASE  VARCHAR2(100)                                                                   Url base da API do NPS            OPERACIONAL                        NaN
PCPARAMNPS     CHAVE_AUTENTICACAO  VARCHAR2(255)                                                       Hash de autenticação da API do NPS            OPERACIONAL                        NaN
PCPARAMNPS                  ATIVO    VARCHAR2(1)                                              Indica se está com integração com NPS ativo            OPERACIONAL                        NaN
PCPARAMNPS              DATA_ERRO           DATE               Data do último erro retornado pela API. Qualquer retorno diferente de 0200            OPERACIONAL                        NaN
PCPARAMNPS      TEMPO_INATIVIDADE    NUMBER(5,0) Tempo, em horas, que a integração ficará inoperante a partir da data/hora do último erro            OPERACIONAL                        NaN
PCPARAMNPS               LOG_ERRO VARCHAR2(2000)            Campo responsável por gravar o log de erro para verificação da causa do erro.            OPERACIONAL                        NaN
PCPARAMNPS                   NOME   VARCHAR2(30)                                                                        Nome do parâmetro            OPERACIONAL                        NaN
PCPARAMNPS TEMPOPROXIMAREQUISICAO    NUMBER(5,0)                                           Tempo em horas para fazer a próxima requisição            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*