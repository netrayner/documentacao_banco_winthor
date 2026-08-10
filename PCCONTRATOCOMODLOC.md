# 📊 Tabela: PCCONTRATOCOMODLOC

### Estrutura de Colunas e Restrições

            Tabela            Coluna  Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONTRATOCOMODLOC       NUMCONTRATO   NUMBER(8,0)              Indica o número do contrato.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTRATOCOMODLOC        DTCADASTRO          DATE    Indica a data de cadastro do contrato.            OPERACIONAL                        NaN
PCCONTRATOCOMODLOC            CODCLI   NUMBER(6,0)               Indica o código do cliente.            OPERACIONAL                        NaN
PCCONTRATOCOMODLOC         CODFILIAL   VARCHAR2(2)                Indica o código da filial.            OPERACIONAL                        NaN
PCCONTRATOCOMODLOC     DTVIGENCIAINI          DATE        Indica a data inicial de vigência.            OPERACIONAL                        NaN
PCCONTRATOCOMODLOC     DTVIGENCIAFIN          DATE          Indica a data final de vigência.            OPERACIONAL                        NaN
PCCONTRATOCOMODLOC              TIPO   NUMBER(3,0)                Indica o tipo do contrato.            OPERACIONAL                        NaN
PCCONTRATOCOMODLOC               OBS VARCHAR2(300)          Infica a observação do contrato.            OPERACIONAL                        NaN
PCCONTRATOCOMODLOC DTVIGENCIAFINORIG          DATE Indica a data final de vigência original.            OPERACIONAL                        NaN
PCCONTRATOCOMODLOC            STATUS   VARCHAR2(1)           Status do Contrato de Comodato.            OPERACIONAL                        NaN
PCCONTRATOCOMODLOC           CODUSUR   NUMBER(4,0)                 Código do RCA do Contrato            OPERACIONAL                        NaN
PCCONTRATOCOMODLOC            CODRCA   NUMBER(8,0)                 Código do RCA do Contrato            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*