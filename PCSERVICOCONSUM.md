# 📊 Tabela: PCSERVICOCONSUM

### Estrutura de Colunas e Restrições

         Tabela                Coluna  Tipo/Tamanho   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSERVICOCONSUM                 NUMOS   NUMBER(6,0)           Número O.S.            OPERACIONAL                        NaN
PCSERVICOCONSUM                CLIENT  VARCHAR2(40)              Cliente.            OPERACIONAL                        NaN
PCSERVICOCONSUM                CGCENT  VARCHAR2(18)          CGC Cliente.            OPERACIONAL                        NaN
PCSERVICOCONSUM              ENDERENT  VARCHAR2(40)  Endereço de entrega.            OPERACIONAL                        NaN
PCSERVICOCONSUM             BAIRROENT  VARCHAR2(40)    Bairro de entrega.            OPERACIONAL                        NaN
PCSERVICOCONSUM                TELENT  VARCHAR2(13)  Telefone de entrega.            OPERACIONAL                        NaN
PCSERVICOCONSUM              MUNICENT  VARCHAR2(15) Município de entrega.            OPERACIONAL                        NaN
PCSERVICOCONSUM                ESTENT   VARCHAR2(2)    Estado de entrega.            OPERACIONAL                        NaN
PCSERVICOCONSUM                CEPENT   VARCHAR2(9)       Cep de entrega.            OPERACIONAL                        NaN
PCSERVICOCONSUM                 IEENT  VARCHAR2(15)   Inscrição estadual.            OPERACIONAL                        NaN
PCSERVICOCONSUM                CTLFAX  VARCHAR2(15)                  Fax.            OPERACIONAL                        NaN
PCSERVICOCONSUM              CTLEMAIL VARCHAR2(100)               E-Mail.            OPERACIONAL                        NaN
PCSERVICOCONSUM                   OBS VARCHAR2(100)           Observação.            OPERACIONAL                        NaN
PCSERVICOCONSUM           NOMECONTATO  VARCHAR2(40)         Nome contato.            OPERACIONAL                        NaN
PCSERVICOCONSUM       TELEFONECONTATO  VARCHAR2(13)  Telefone de contato.            OPERACIONAL                        NaN
PCSERVICOCONSUM            OBSCONTATO  VARCHAR2(75)   Observação contato.            OPERACIONAL                        NaN
PCSERVICOCONSUM             CODCIDADE   NUMBER(6,0)     Código da cidade.            OPERACIONAL                        NaN
PCSERVICOCONSUM   DTEXPORTACAOSERVINT          DATE   Data de exportação.            OPERACIONAL                        NaN
PCSERVICOCONSUM      EXPORTADOSERVINT   VARCHAR2(1)                   NaN            OPERACIONAL                        NaN
PCSERVICOCONSUM    IMPORTADOSERVPRINC   VARCHAR2(1)                   NaN            OPERACIONAL                        NaN
PCSERVICOCONSUM DTIMPORTACAOSERVPRINC          DATE                   NaN            OPERACIONAL                        NaN
PCSERVICOCONSUM                 EMAIL VARCHAR2(100)               E-Mail.            OPERACIONAL                        NaN
PCSERVICOCONSUM                LBLFAX  VARCHAR2(15)                  Fax.            OPERACIONAL                        NaN
PCSERVICOCONSUM              LBLEMAIL VARCHAR2(100)               E-Mail.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*