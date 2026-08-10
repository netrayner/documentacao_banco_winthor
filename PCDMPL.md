# 📊 Tabela: PCDMPL

### Estrutura de Colunas e Restrições

Tabela              Coluna  Tipo/Tamanho                                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDMPL             CODDMPL  NUMBER(10,0)                                                            Código    CHAVE PRIMÁRIA (PK)                        NaN
PCDMPL           DESCRICAO VARCHAR2(100)                                                         Descrição            OPERACIONAL                        NaN
PCDMPL VALORNEGATIVOEXIBIR   VARCHAR2(1)                                             Exibir valor negativo            OPERACIONAL                        NaN
PCDMPL                DLPA   VARCHAR2(1)                                                  Estrutura é DLPA            OPERACIONAL                        NaN
PCDMPL                 ANO   NUMBER(4,0)                         Exibe o ano das configurações DMPL e DLPA            OPERACIONAL                        NaN
PCDMPL        DESCRICAOIMP VARCHAR2(100)                             Descrição para impressão da DMPL/DLPA            OPERACIONAL                        NaN
PCDMPL     NOTAEXPLICATIVA          CLOB                  Informações da nota explicativa do demonstrativo            OPERACIONAL                        NaN
PCDMPL     GERARAUTOMATICO   VARCHAR2(1) Indica se a estrutura de DMPL/DPLA será executada automáticamente            OPERACIONAL                        NaN
PCDMPL       CODPLANOCONTA   NUMBER(5,0)        Plano de conta utilizado para criar a estrutura automática            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*