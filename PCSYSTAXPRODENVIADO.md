# 📊 Tabela: PCSYSTAXPRODENVIADO

### Estrutura de Colunas e Restrições

             Tabela       Coluna  Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSYSTAXPRODENVIADO      CODPROD   NUMBER(6,0)           Código do produto do Winthor    CHAVE PRIMÁRIA (PK)                        NaN
PCSYSTAXPRODENVIADO ORIGMERCTRIB   VARCHAR2(1)        Origem da Mercadoria ou Serviço    CHAVE PRIMÁRIA (PK)                        NaN
PCSYSTAXPRODENVIADO         ERRO   VARCHAR2(1)             RETORNO DE ERRO DO SERVIÇO            OPERACIONAL                        NaN
PCSYSTAXPRODENVIADO      MESSAGE VARCHAR2(200) MENSAGEM RETORNADA PELO SERVICO SYSTAX            OPERACIONAL                        NaN
PCSYSTAXPRODENVIADO        EXTRA VARCHAR2(200)                            ERROR EXTRA            OPERACIONAL                        NaN
PCSYSTAXPRODENVIADO     DT_ENVIO          DATE    DATA DE ENVIO DOS PRODUTOS A SYSTAX            OPERACIONAL                        NaN
PCSYSTAXPRODENVIADO    DT_INSERT          DATE             DATA DE INSERÇÃO NA TABELA            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*