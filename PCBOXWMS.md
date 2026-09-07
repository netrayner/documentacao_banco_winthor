# 📊 Tabela: PCBOXWMS

### Estrutura de Colunas e Restrições

  Tabela            Coluna  Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBOXWMS            CODBOX   NUMBER(4,0)                           Codigo do Box    CHAVE PRIMÁRIA (PK)                        NaN
PCBOXWMS         DESCRICAO VARCHAR2(100)                       Descricao do Box.            OPERACIONAL                        NaN
PCBOXWMS       CODENDERECO   NUMBER(8,0)                      Endereco de Stage.            OPERACIONAL                        NaN
PCBOXWMS         CODFILIAL   VARCHAR2(2) Codigo de filtro para filial disitintas            OPERACIONAL                        NaN
PCBOXWMS DIGITOVERIFICADOR   NUMBER(9,0)               Dígito verificador do box            OPERACIONAL                        NaN
PCBOXWMS        CODESTEIRA   NUMBER(6,0)         Código da esteira dentro do Box            OPERACIONAL                        NaN
PCBOXWMS          QTPALETE   NUMBER(6,0)                   Quantidade de paletes            OPERACIONAL                        NaN
PCBOXWMS              PESO  NUMBER(12,6)                      CAPACIDADE EM PESO            OPERACIONAL                        NaN
PCBOXWMS            VOLUME  NUMBER(12,6)                     CAPACIADE EM VOLUME            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*