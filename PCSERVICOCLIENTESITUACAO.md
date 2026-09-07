# 📊 Tabela: PCSERVICOCLIENTESITUACAO

### Estrutura de Colunas e Restrições

                  Tabela                       Coluna  Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSERVICOCLIENTESITUACAO                        FONTE VARCHAR2(255)                   Fonte de origem deste endereço            OPERACIONAL                        NaN
PCSERVICOCLIENTESITUACAO                       STATUS VARCHAR2(255)                               Situação cadastral            OPERACIONAL                        NaN
PCSERVICOCLIENTESITUACAO                   CODCLIENTE  NUMBER(10,0)                  Codigo identificador do cliente CHAVE ESTRANGEIRA (FK)           PCSERVICOCLIENTE
PCSERVICOCLIENTESITUACAO                 DATAREGISTRO          DATE                                 Data do registro            OPERACIONAL                        NaN
PCSERVICOCLIENTESITUACAO             DATAENCERRAMENTO          DATE                 Data do enceramento de atividade            OPERACIONAL                        NaN
PCSERVICOCLIENTESITUACAO            STATUSNORMALIZADO  VARCHAR2(50)                   Situação cadastral normalizada            OPERACIONAL                        NaN
PCSERVICOCLIENTESITUACAO           DATAULTIMACONSULTA          DATE  Data da ultima consulta da empresa no cadastral            OPERACIONAL                        NaN
PCSERVICOCLIENTESITUACAO        INFORMACOESADICIONAIS          CLOB                           Informações adicionais            OPERACIONAL                        NaN
PCSERVICOCLIENTESITUACAO            INSCRICAOESTADUAL  VARCHAR2(50)                               Inscrição estadual            OPERACIONAL                        NaN
PCSERVICOCLIENTESITUACAO        DATAALTERACAOCADASTRO          DATE Data da ultima alteração da empresa no cadastral            OPERACIONAL                        NaN
PCSERVICOCLIENTESITUACAO                  CODSITUACAO  NUMBER(10,0)              Código de identificação do endereço    CHAVE PRIMÁRIA (PK)                        NaN
PCSERVICOCLIENTESITUACAO RESPONSAVELALTERACAOCADASTRO VARCHAR2(255)   Nome do responsavel pela alteração do cadastro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*