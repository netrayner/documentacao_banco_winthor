# 📊 Tabela: PCEXTRATOBANCARIO

### Estrutura de Colunas e Restrições

           Tabela              Coluna  Tipo/Tamanho                                                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEXTRATOBANCARIO        IDLANCAMENTO  NUMBER(20,0)                                                    Chave Primária identifica o registro    CHAVE PRIMÁRIA (PK)                        NaN
PCEXTRATOBANCARIO      DATAINTEGRACAO          DATE                                                         Data que buscou os dados na API            OPERACIONAL                        NaN
PCEXTRATOBANCARIO          CONCILIADO   VARCHAR2(1)                                                                           Já Conciliado            OPERACIONAL                        NaN
PCEXTRATOBANCARIO            CODBANCO   NUMBER(4,0)                                                  Código do banco utilizado para conexão            OPERACIONAL                        NaN
PCEXTRATOBANCARIO      DATALANCAMENTO          DATE                                                                         Data Lançamento            OPERACIONAL                        NaN
PCEXTRATOBANCARIO     NUMERODOCUMENTO  NUMBER(20,0)                                                                        Número Documento            OPERACIONAL                        NaN
PCEXTRATOBANCARIO     VALORLANCAMENTO  NUMBER(16,2)                                                                        Valor Lançamento            OPERACIONAL                        NaN
PCEXTRATOBANCARIO     SINALLANCAMENTO   VARCHAR2(1)                                                                        Sinal Lançamento            OPERACIONAL                        NaN
PCEXTRATOBANCARIO    CODIGOLANCAMENTO  NUMBER(20,0)                                                                       Código Lançamento            OPERACIONAL                        NaN
PCEXTRATOBANCARIO           HISTORICO VARCHAR2(500)                                                                Segunda Linha Lançamento            OPERACIONAL                        NaN
PCEXTRATOBANCARIO DESCRITIVOABREVIADO VARCHAR2(100)                                                         Descritivo Lançamento Abreviado            OPERACIONAL                        NaN
PCEXTRATOBANCARIO  DESCRITIVOCOMPLETO VARCHAR2(500)                                                          Descritivo Lançamento Completo            OPERACIONAL                        NaN
PCEXTRATOBANCARIO            NUMTRANS  NUMBER(10,0)                                             Número de Transação da tabela de lançamento            OPERACIONAL                        NaN
PCEXTRATOBANCARIO    IDLANCAMENTOGUID  VARCHAR2(50)           Id do lançamento em formato GUID, gerado pela integração bancária com o Itaú.            OPERACIONAL                        NaN
PCEXTRATOBANCARIO            OPERACAO   VARCHAR2(1)     Operação retornada na integração com o Itaú, sendo C para Crédito ou D para Débito.            OPERACIONAL                        NaN
PCEXTRATOBANCARIO       CORRELATIONID  VARCHAR2(50) UUID gerado e enviado ao banco para agrupar itens retornados em pesquisa a API do Itaú.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*