# 📊 Tabela: PCTIPOCONTROLEVENDA

### Estrutura de Colunas e Restrições

             Tabela               Coluna Tipo/Tamanho                                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTIPOCONTROLEVENDA CODTIPOCONTROLEVENDA  NUMBER(3,0)                                                                 Código    CHAVE PRIMÁRIA (PK)                        NaN
PCTIPOCONTROLEVENDA            DESCRICAO VARCHAR2(30)                                                              Descrição            OPERACIONAL                        NaN
PCTIPOCONTROLEVENDA        CRITICANUMDOC  VARCHAR2(1)                                          Critica o Número do Documento            OPERACIONAL                        NaN
PCTIPOCONTROLEVENDA    CRITICADTVALIDADE  VARCHAR2(1)                                             Critica a Data de Validade            OPERACIONAL                        NaN
PCTIPOCONTROLEVENDA        TIPOVALIDACAO  VARCHAR2(1) Tipo de Validação (1 - Recusar Item; 2 - Gravar Pedido como Bloqueado)            OPERACIONAL                        NaN
PCTIPOCONTROLEVENDA      DEDUZDEVOLUCOES  VARCHAR2(1)                                               Deduz Devolução de Itens            OPERACIONAL                        NaN
PCTIPOCONTROLEVENDA        PESOLIMITEMES NUMBER(16,3)                                        Peso limite autorizado por mês.            OPERACIONAL                        NaN
PCTIPOCONTROLEVENDA UTILIZAPESOLIMITEMES  VARCHAR2(1)                                Utiliza Peso limite autorizado por mês.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*