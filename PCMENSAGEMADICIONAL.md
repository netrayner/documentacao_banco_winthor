# 📊 Tabela: PCMENSAGEMADICIONAL

### Estrutura de Colunas e Restrições

             Tabela        Coluna  Tipo/Tamanho                                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMENSAGEMADICIONAL   CODMENSAGEM   NUMBER(6,0)                                                                   Código da mensagem.    CHAVE PRIMÁRIA (PK)                        NaN
PCMENSAGEMADICIONAL     DESCRICAO VARCHAR2(180)                                                               Descricao da mensagem.             OPERACIONAL                        NaN
PCMENSAGEMADICIONAL     MOVIMENTO   VARCHAR2(3) E = Entrada/ S = Saida/ C = CTe/ M = MDFe/ EF = Entrada obsFisco/ SF = Saida obsFisco            OPERACIONAL                        NaN
PCMENSAGEMADICIONAL           SQL          CLOB                                                             Contém o SQL do usuário.             OPERACIONAL                        NaN
PCMENSAGEMADICIONAL MENSAGEMATIVA   VARCHAR2(1)                                                Define se a mensagem esta ativa ou não            OPERACIONAL                        NaN
PCMENSAGEMADICIONAL   OBRIGATORIA   VARCHAR2(1)    Identifica mensagens obrigatórias no xml, estas não são desativadas pelo DocFiscal            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*