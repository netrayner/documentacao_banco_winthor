# 📊 Tabela: PCLICITTIPODOCUMENTO

### Estrutura de Colunas e Restrições

              Tabela                 Coluna Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLICITTIPODOCUMENTO       CODTIPODOCUMENTO  NUMBER(6,0)            Codigo do tipo de documento    CHAVE PRIMÁRIA (PK)                        NaN
PCLICITTIPODOCUMENTO              DESCRICAO VARCHAR2(80)                 Descrição do documento            OPERACIONAL                        NaN
PCLICITTIPODOCUMENTO         TIPOREFERENCIA  VARCHAR2(1) Referencia do documento(Ex: E-Empresa)            OPERACIONAL                        NaN
PCLICITTIPODOCUMENTO   INCLUIRLISTAPRECOCOT  VARCHAR2(1)                         Inclusao lista            OPERACIONAL                        NaN
PCLICITTIPODOCUMENTO         USOHABILITACAO  VARCHAR2(1)                     Uso da Habilitação            OPERACIONAL                        NaN
PCLICITTIPODOCUMENTO            USOPROPOSTA  VARCHAR2(1)                        Uso da proposta            OPERACIONAL                        NaN
PCLICITTIPODOCUMENTO      USOCREDENCIAMENTO  VARCHAR2(1)                  Uso do credenciamento            OPERACIONAL                        NaN
PCLICITTIPODOCUMENTO         ORDEMIMPRESSAO  NUMBER(3,0)                     Ordem da impressão            OPERACIONAL                        NaN
PCLICITTIPODOCUMENTO    ORDEMIMPHABILITACAO  NUMBER(3,0)                   Ordem da habilitação            OPERACIONAL                        NaN
PCLICITTIPODOCUMENTO       ORDEMIMPPROPOSTA  NUMBER(3,0)                      Ordem da proposta            OPERACIONAL                        NaN
PCLICITTIPODOCUMENTO ORDEMIMPCREDENCIAMENTO  NUMBER(3,0)                Ordem do credenciamento            OPERACIONAL                        NaN
PCLICITTIPODOCUMENTO             USOTECNICO  VARCHAR2(1)                       Fins uso tecnico            OPERACIONAL                        NaN
PCLICITTIPODOCUMENTO        USOPOSLICITACAO  VARCHAR2(1)                     Uso após licitação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*