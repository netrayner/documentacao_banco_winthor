# 📊 Tabela: PCPLANOCONTALALUR

### Estrutura de Colunas e Restrições

           Tabela       Coluna  Tipo/Tamanho                                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPLANOCONTALALUR           ID   NUMBER(8,0)                                                    Identificador único do registro na tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCPLANOCONTALALUR       VERSAO   NUMBER(2,0)         Nº da versão do plano de contas. Anualmente, a Receita Federal lança uma nova versão            OPERACIONAL                        NaN
PCPLANOCONTALALUR     CODCONTA   VARCHAR2(7)                                           Código da conta do plano. Pode conter nºs e pontos            OPERACIONAL                        NaN
PCPLANOCONTALALUR    DESCRICAO VARCHAR2(100)                                                                  Descrição da conta do plano            OPERACIONAL                        NaN
PCPLANOCONTALALUR        DTINI          DATE                                                            Data inicial da validade da conta            OPERACIONAL                        NaN
PCPLANOCONTALALUR        DTFIM          DATE Data final da validade da conta. Se for vazia, a conta perderá a validade em uma nova versão            OPERACIONAL                        NaN
PCPLANOCONTALALUR        ORDEM   NUMBER(5,0)                                                               Ordem da conta dentro do plano            OPERACIONAL                        NaN
PCPLANOCONTALALUR         TIPO   VARCHAR2(3)    A conta pode ser do tipo R-Resumo, E-Editável, CA-Calculado ou CNA-Calculado não editável            OPERACIONAL                        NaN
PCPLANOCONTALALUR      FORMATO   VARCHAR2(3)                                                     Pode ser vazio ou NS-Nº decimal c/ sinal            OPERACIONAL                        NaN
PCPLANOCONTALALUR     LINHAECF   NUMBER(5,0)                                                            Nº da linha correspondente no ECF            OPERACIONAL                        NaN
PCPLANOCONTALALUR      FORMULA VARCHAR2(200)                                                                Pode ser vazio ou uma fórmula            OPERACIONAL                        NaN
PCPLANOCONTALALUR TIPOLANCSPED   VARCHAR2(3)               Info para o SPED. Pode ser R-Resumo, L-Lucro, A-Adição, E-Exclusão, P-Prejuízo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*