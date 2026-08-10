# 📊 Tabela: PCCOTACAOMOEDAC

### Estrutura de Colunas e Restrições

         Tabela        Coluna Tipo/Tamanho          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOTACAOMOEDAC        CODIGO  NUMBER(6,0)                          NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCOTACAOMOEDAC         MOEDA VARCHAR2(40)                          NaN            OPERACIONAL                        NaN
PCCOTACAOMOEDAC          PAIS VARCHAR2(40)                          NaN            OPERACIONAL                        NaN
PCCOTACAOMOEDAC       SIMBOLO VARCHAR2(10)  Símbolo da moeda. Ex.: US$.            OPERACIONAL                        NaN
PCCOTACAOMOEDAC   CODSISCOMEX NUMBER(10,0)    Código SISCOMEX da Moeda.            OPERACIONAL                        NaN
PCCOTACAOMOEDAC       CODPAIS  NUMBER(6,0)               Código do Pais            OPERACIONAL                        NaN
PCCOTACAOMOEDAC    DTEXCLUSAO         DATE             Data da Exclusão            OPERACIONAL                        NaN
PCCOTACAOMOEDAC TIPOCONVERSAO  VARCHAR2(1)            Tipo de Conversão            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*