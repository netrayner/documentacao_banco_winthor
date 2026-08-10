# 📊 Tabela: PCCOMISSAORCACLIPROD

### Estrutura de Colunas e Restrições

              Tabela      Coluna Tipo/Tamanho                                                                                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOMISSAORCACLIPROD      CODCLI  NUMBER(6,0)          Código do cliente a ser utilizado na aplicação da comissão. |Campo do tipo numérico, de tamanho 6, sem casas decimais, obrigatória.    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMISSAORCACLIPROD     CODUSUR  NUMBER(4,0)              Código do RCA a ser utilizado na aplicação da comissão. |Campo do tipo numérico, de tamanho 4, sem casas decimais, obrigatória.    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMISSAORCACLIPROD     CODPROD  NUMBER(6,0) Código do produto a ser utilizado para aplicação da comissão do RCA. |Campo do tipo numérico, de tamanho 6, sem casas decimais, obrigatória.    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMISSAORCACLIPROD DATAINICIAL         DATE                                                               Data inicial de vigência da comissão do RCA. |Campo do tipo data, obrigatória.    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMISSAORCACLIPROD   DATAFINAL         DATE                                                                 Data final de vigência da comissão do RCA. |Campo do tipo data, obrigatória.    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMISSAORCACLIPROD      PERCOM  NUMBER(6,2)                                         Valor do percentual da comissão do RCA. |Campo do tipo numérico, de tamanho 6, com 2 casas decimais.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*