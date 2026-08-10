# 📊 Tabela: PCINTEGRAFRETE

### Estrutura de Colunas e Restrições

        Tabela         Coluna Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRAFRETE      CODFILIAL  VARCHAR2(2)                      CÓDIGO FILIAL.    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRAFRETE  SEQCONHECNOTA NUMBER(10,0) SEQÜÊNCIA DO CONHECIMENTO DE NOTA .            OPERACIONAL                        NaN
PCINTEGRAFRETE      MANIFESTO NUMBER(15,0)                CÓDIGO DO MANIFESTO.    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRAFRETE        NUMNOTA  NUMBER(8,0)              NUMERO DE NOTA FISCAL.    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRAFRETE      CODTRANSP NUMBER(10,0)              CÓDIGO TRANSPORTADORA.            OPERACIONAL                        NaN
PCINTEGRAFRETE     NOMETRANSP VARCHAR2(25)                NOME TRANSPORTADORA.            OPERACIONAL                        NaN
PCINTEGRAFRETE         CODCLI NUMBER(10,0)                     CÓDIGO CLIENTE.            OPERACIONAL                        NaN
PCINTEGRAFRETE      PESOTOTAL NUMBER(18,6)                         PESO TOTAL.            OPERACIONAL                        NaN
PCINTEGRAFRETE    VOLUMETOTAL NUMBER(18,6)                       VOLUME TOTAL.            OPERACIONAL                        NaN
PCINTEGRAFRETE        VLRNOTA NUMBER(18,6)                      VALOR DA NOTA.            OPERACIONAL                        NaN
PCINTEGRAFRETE        VLFRETE NUMBER(18,6)                     VALOR DO FRETE.            OPERACIONAL                        NaN
PCINTEGRAFRETE     VLIMPOSTOS NUMBER(18,6)                 VALOR DOS IMPOSTOS.            OPERACIONAL                        NaN
PCINTEGRAFRETE        AD_VLEM NUMBER(18,6)                    VALOR ADICIONAL.            OPERACIONAL                        NaN
PCINTEGRAFRETE      QT_VOLUME  NUMBER(4,0)               QUANTIDADE DE VOLUME.            OPERACIONAL                        NaN
PCINTEGRAFRETE       DTEMISAO         DATE                    DATA DE EMISSÃO.            OPERACIONAL                        NaN
PCINTEGRAFRETE    DTEMISAOMAN         DATE       DATA DE EMISSÃO DO MANIFESTO.            OPERACIONAL                        NaN
PCINTEGRAFRETE        PERCICM NUMBER(10,2)                    PERCENTUAL ICMS.            OPERACIONAL                        NaN
PCINTEGRAFRETE      VLPEDAGIO NUMBER(18,6)                   VALOR DO PEDAGIO.            OPERACIONAL                        NaN
PCINTEGRAFRETE     VLDESCARGA NUMBER(18,6)                  VALOR DA DESCARGA.            OPERACIONAL                        NaN
PCINTEGRAFRETE REM_NOMEFILIAL VARCHAR2(40)                  NOME DA REMETENTE.            OPERACIONAL                        NaN
PCINTEGRAFRETE   REM_ENDERECO VARCHAR2(40)              ENDEREÇO DA REMETENTE.            OPERACIONAL                        NaN
PCINTEGRAFRETE     REM_BAIRRO VARCHAR2(20)                BAIRRO DA REMETENTE.            OPERACIONAL                        NaN
PCINTEGRAFRETE     REM_CIDADE VARCHAR2(30)                CIDADE DA REMETENTE.            OPERACIONAL                        NaN
PCINTEGRAFRETE         REM_UF  VARCHAR2(2)                    UF DA REMETENTE.            OPERACIONAL                        NaN
PCINTEGRAFRETE        REM_CEP VARCHAR2(11)                   CEP DA REMETENTE.            OPERACIONAL                        NaN
PCINTEGRAFRETE         REM_IE VARCHAR2(15)    INSCRIÇÃO ESTADUAL DO REMETENTE.            OPERACIONAL                        NaN
PCINTEGRAFRETE        REM_CGC VARCHAR2(14)                   CGC DA REMETENTE.            OPERACIONAL                        NaN
PCINTEGRAFRETE EMI_NOMEFILIAL VARCHAR2(40)                    NOME DO EMISSOR.            OPERACIONAL                        NaN
PCINTEGRAFRETE   EMI_ENDERECO VARCHAR2(40)                ENDEREÇO DO EMISSOR.            OPERACIONAL                        NaN
PCINTEGRAFRETE     EMI_BAIRRO VARCHAR2(20)                  BAIRRO DO EMISSOR.            OPERACIONAL                        NaN
PCINTEGRAFRETE     EMI_CIDADE VARCHAR2(30)                  CIDADE DO EMISSOR.            OPERACIONAL                        NaN
PCINTEGRAFRETE         EMI_UF  VARCHAR2(2)                      UF DO EMISSOR.            OPERACIONAL                        NaN
PCINTEGRAFRETE        EMI_CEP VARCHAR2(11)                     CEP DO EMISSOR.            OPERACIONAL                        NaN
PCINTEGRAFRETE         EMI_IE VARCHAR2(15)      INSCRIÇÃO ESTADUAL DO EMISSOR.            OPERACIONAL                        NaN
PCINTEGRAFRETE        EMI_CGC VARCHAR2(14)                     CGC DO EMISSOR.            OPERACIONAL                        NaN
PCINTEGRAFRETE ENT_NOMEFILIAL VARCHAR2(40)                    NOME DA ENTREGA.            OPERACIONAL                        NaN
PCINTEGRAFRETE   ENT_ENDERECO VARCHAR2(40)                ENDEREÇO DA ENTREGA.            OPERACIONAL                        NaN
PCINTEGRAFRETE     ENT_BAIRRO VARCHAR2(20)                  BAIRRO DA ENTREGA.            OPERACIONAL                        NaN
PCINTEGRAFRETE     ENT_CIDADE VARCHAR2(30)                  CIDADE DA ENTREGA.            OPERACIONAL                        NaN
PCINTEGRAFRETE         ENT_UF  VARCHAR2(2)                      UF DA ENTREGA.            OPERACIONAL                        NaN
PCINTEGRAFRETE        ENT_CEP VARCHAR2(11)                     CEP DA ENTREGA.            OPERACIONAL                        NaN
PCINTEGRAFRETE         ENT_IE VARCHAR2(15)      INSCRIÇÃO ESTADUAL DA ENTREGA.            OPERACIONAL                        NaN
PCINTEGRAFRETE        ENT_CGC VARCHAR2(14)                     CGC DA ENTREGA.            OPERACIONAL                        NaN
PCINTEGRAFRETE         GERADO  VARCHAR2(1)                CONHECIMENTO GERADO.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*