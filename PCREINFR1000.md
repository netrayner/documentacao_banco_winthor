# 📊 Tabela: PCREINFR1000

### Estrutura de Colunas e Restrições

      Tabela             Coluna  Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREINFR1000                 ID   NUMBER(8,0)                                       Identificador    CHAVE PRIMÁRIA (PK)                        NaN
PCREINFR1000            GRUPOID   NUMBER(8,0)                        Identificador grupo empresas            OPERACIONAL                        NaN
PCREINFR1000        CLASSIFTRIB       CHAR(2)                            Classificação tributaria            OPERACIONAL                        NaN
PCREINFR1000    SITUACAOEMPRESA       CHAR(1)                                 Situação da empresa            OPERACIONAL                        NaN
PCREINFR1000     ENTEFEDERATIVO       CHAR(1)                                     Ente federativo            OPERACIONAL                        NaN
PCREINFR1000            CNPJEFR      CHAR(18)                CNPJ do Ente Federativo responsáveil            OPERACIONAL                        NaN
PCREINFR1000         ENTREGAECD       CHAR(1)                                Empresa enterega ECD            OPERACIONAL                        NaN
PCREINFR1000     INDICATIVOCPRB       CHAR(1)           Indicativo desoneração da folha pelo CPRB            OPERACIONAL                        NaN
PCREINFR1000 ACORDOISENCAOMULTA       CHAR(1)          Acordo internacional para isenção de multa            OPERACIONAL                        NaN
PCREINFR1000    NOMERESPCONTRIB VARCHAR2(100)               Nome do responsavel pelo contribuinte            OPERACIONAL                        NaN
PCREINFR1000     CPFRESPCONTRIB      CHAR(14)                CPF do responsavel pelo contribuinte            OPERACIONAL                        NaN
PCREINFR1000    TELRESPOCONTRIB  VARCHAR2(15)           Telefone do responsavel pelo contribuinte            OPERACIONAL                        NaN
PCREINFR1000     CELRESPCONTRIB  VARCHAR2(15)            Celular do responsavel pelo contribuinte            OPERACIONAL                        NaN
PCREINFR1000   EMAILRESPCONTRIB  VARCHAR2(50)              Email do responsavel pelo contribuinte            OPERACIONAL                        NaN
PCREINFR1000  RAZAOSOCIALDESENV VARCHAR2(100)          Razão social da empresa de desenvolvimento            OPERACIONAL                        NaN
PCREINFR1000         CNPJDESENV      CHAR(18)                  CNPJ da empresa de desenvolvimento            OPERACIONAL                        NaN
PCREINFR1000      CONTATODESENV  VARCHAR2(50)               Contato da empresa de desenvolvimento            OPERACIONAL                        NaN
PCREINFR1000   TELCONTATODESENV  VARCHAR2(15)              Telefone da empresa de desenvolvimento            OPERACIONAL                        NaN
PCREINFR1000 EMAILCONTATODESENV  VARCHAR2(50)                 Email da empresa de desenvolvimento            OPERACIONAL                        NaN
PCREINFR1000           INIVALID   VARCHAR2(7)                                  Inicio da validade            OPERACIONAL                        NaN
PCREINFR1000           FIMVALID   VARCHAR2(7)                                   Final da validade            OPERACIONAL                        NaN
PCREINFR1000      DTTRANSMISSAO          DATE                                 Data de transmissão            OPERACIONAL                        NaN
PCREINFR1000    TIPOTRANSMISSAO  VARCHAR2(50)                                 Tipo da transmissão            OPERACIONAL                        NaN
PCREINFR1000    CODFUNCULTALTER   NUMBER(8,0)              Código do funcionario ultima alteração            OPERACIONAL                        NaN
PCREINFR1000         DTULTALTER          DATE                            Data da ultima alteração            OPERACIONAL                        NaN
PCREINFR1000             ID_XML VARCHAR2(100)                                  Id do XML de envio            OPERACIONAL                        NaN
PCREINFR1000 ENVIADO_ASSINCRONO   VARCHAR2(1) Campo de controle para transmissão modo assíncrono.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*