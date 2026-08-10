# 📊 Tabela: PCMARCA

### Estrutura de Colunas e Restrições

 Tabela             Coluna  Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMARCA           CODMARCA   NUMBER(8,0)                   Indica o código da marca.    CHAVE PRIMÁRIA (PK)                        NaN
PCMARCA              MARCA  VARCHAR2(40)                Indica o descrição da marca.            OPERACIONAL                        NaN
PCMARCA              ATIVO   VARCHAR2(1)    Indica se a marca esta ativa ou inativa.            OPERACIONAL                        NaN
PCMARCA         CODADWORDS VARCHAR2(200)                           Código do AdWords            OPERACIONAL                        NaN
PCMARCA DESCRICAOECOMMERCE VARCHAR2(400) Descrição da marca apresentado no ecommerce            OPERACIONAL                        NaN
PCMARCA     CODCAMPLOMADEE VARCHAR2(200)                     Código campanha Lomadee            OPERACIONAL                        NaN
PCMARCA             TITULO VARCHAR2(200)    Titulo da marca apresentado no ecommerce            OPERACIONAL                        NaN
PCMARCA         DTULTALTER          DATE       Data da ultima alteração do registro.            OPERACIONAL                        NaN
PCMARCA         DTCADASTRO          DATE                            Data de cadastro            OPERACIONAL                        NaN
PCMARCA       CODCOMPRADOR   NUMBER(8,0)                         Código do comprador            OPERACIONAL                        NaN
PCMARCA         DTMXSALTER          DATE                                         NaN            OPERACIONAL                        NaN
PCMARCA          DTALTERC5  TIMESTAMP(6)                              DATA ALTERACAO            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*