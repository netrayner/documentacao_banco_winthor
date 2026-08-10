# 📊 Tabela: PCLOGINFOTPI

### Estrutura de Colunas e Restrições

      Tabela               Coluna  Tipo/Tamanho                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGINFOTPI   NUMTRANSPAGDIGITAL  VARCHAR2(50)                 Número identificador da transação    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGINFOTPI           DTCADASTRO          DATE                      Data do cadastro do registro            OPERACIONAL                        NaN
PCLOGINFOTPI        DTATUALIZACAO          DATE                     Data da alteração do registro            OPERACIONAL                        NaN
PCLOGINFOTPI DTINICARTEIRADIGITAL          DATE    Data do inicio da consulta da carteira digital            OPERACIONAL                        NaN
PCLOGINFOTPI DTFIMCARTEIRADIGITAL          DATE       Data do fim da consulta da carteira digital            OPERACIONAL                        NaN
PCLOGINFOTPI   DTINIGERACAOQRCODE          DATE  Data de inicio da geração dos dados de pagamento            OPERACIONAL                        NaN
PCLOGINFOTPI   DTFIMGERACAOQRCODE          DATE      Data do fim da geração do dados de pagamento            OPERACIONAL                        NaN
PCLOGINFOTPI DTINISTATUSPAGAMENTO          DATE Data do inicio da consulta do status de pagamento            OPERACIONAL                        NaN
PCLOGINFOTPI DTFIMSTATUSPAGAMENTO          DATE    Data do fim da consulta do status de pagamento            OPERACIONAL                        NaN
PCLOGINFOTPI            CODROTINA  NUMBER(22,0)                                  Código da rotina            OPERACIONAL                        NaN
PCLOGINFOTPI           OBSERVACAO VARCHAR2(500)                         Observações gerais do log            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*