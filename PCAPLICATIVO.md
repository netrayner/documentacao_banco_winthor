# 📊 Tabela: PCAPLICATIVO

### Estrutura de Colunas e Restrições

      Tabela         Coluna  Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAPLICATIVO           DATA          DATE              Data de inclusão do agente            OPERACIONAL                        NaN
PCAPLICATIVO      DESCRICAO VARCHAR2(100)                     Descrição do agente            OPERACIONAL                        NaN
PCAPLICATIVO         VERSAO   NUMBER(4,0)                        Versão do agente            OPERACIONAL                        NaN
PCAPLICATIVO     APLICATIVO          BLOB      Agente em forma de arquivo binário            OPERACIONAL                        NaN
PCAPLICATIVO        CODHASH  VARCHAR2(32)                          Hash calculado            OPERACIONAL                        NaN
PCAPLICATIVO     HASHCODIGO  VARCHAR2(50)                        Campo HashCodigo            OPERACIONAL                        NaN
PCAPLICATIVO EXECUTARVIADLL   VARCHAR2(1) Se o aplicativo será executado pela DLL            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*