# 📊 Tabela: PCNFDECLARARC

### Estrutura de Colunas e Restrições

       Tabela         Coluna Tipo/Tamanho                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCNFDECLARARC             IE  VARCHAR2(9)                                                 Inscrição estadual.            OPERACIONAL                        NaN
PCNFDECLARARC            MES  NUMBER(2,0)                              Mês referente a apresentação do danfe.            OPERACIONAL                        NaN
PCNFDECLARARC            ANO  NUMBER(4,0)                              Ano referente a apresentação do danfe.            OPERACIONAL                        NaN
PCNFDECLARARC       NUMORDEM  NUMBER(6,0)                                             Ordem da nota na lista.            OPERACIONAL                        NaN
PCNFDECLARARC          CHAVE VARCHAR2(44)                                                         Chave NF-e.            OPERACIONAL                        NaN
PCNFDECLARARC    CODREGISTRO  NUMBER(6,0)                                    Codigo único para cada registro.    CHAVE PRIMÁRIA (PK)                        NaN
PCNFDECLARARC DATAIMPORTACAO         DATE                                        Data da geração do registro.            OPERACIONAL                        NaN
PCNFDECLARARC      CODFILIAL  VARCHAR2(2)                                                   Código da filial.            OPERACIONAL                        NaN
PCNFDECLARARC         ORIGEM  VARCHAR2(1) Origem do registro, se veio do XML ou se foi incluído pelo usuário.            OPERACIONAL                        NaN
PCNFDECLARARC   DTIMPORTACAO         DATE                                       Data de inclusão do registro.            OPERACIONAL                        NaN
PCNFDECLARARC    RECONHECENF  VARCHAR2(1)                                    Reconhecimento da Nfe importada.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*