# 📊 Tabela: PCLOGBLOQUEIOPEDVENDA

### Estrutura de Colunas e Restrições

               Tabela         Coluna Tipo/Tamanho           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGBLOQUEIOPEDVENDA         NUMPED NUMBER(10,0)    Número de pedido de venda.    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGBLOQUEIOPEDVENDA           DATA         DATE   Data de inclusão do motivo.    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGBLOQUEIOPEDVENDA      CODMOTIVO  NUMBER(6,0) Código de motivo de bloqueio.    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGBLOQUEIOPEDVENDA CODMOTBLOQUEIO  NUMBER(8,0) Código do bloqueio comercial.            OPERACIONAL                        NaN
PCLOGBLOQUEIOPEDVENDA  MOTIVOPOSICAO VARCHAR2(60) Motivo do bloqueio do pedido.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*