# 📊 Tabela: PCREGISTROINTEGRACOESWMSSAAS

### Estrutura de Colunas e Restrições

                      Tabela           Coluna  Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREGISTROINTEGRACOESWMSSAAS             DATA          DATE                        Data de integração            OPERACIONAL                        NaN
PCREGISTROINTEGRACOESWMSSAAS  NUMERODOCUMENTO  NUMBER(15,0)                       Numero do documento            OPERACIONAL                        NaN
PCREGISTROINTEGRACOESWMSSAAS             TIPO  VARCHAR2(40)                         Tipo de Documento            OPERACIONAL                        NaN
PCREGISTROINTEGRACOESWMSSAAS        CODFILIAL   VARCHAR2(2)               Código da filial no Winthor            OPERACIONAL                        NaN
PCREGISTROINTEGRACOESWMSSAAS CODFILIALWMSSAAS   VARCHAR2(2)      Código da filial destino no WMS Saas            OPERACIONAL                        NaN
PCREGISTROINTEGRACOESWMSSAAS              API VARCHAR2(300) Descrição da api utilizada nesse processo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*