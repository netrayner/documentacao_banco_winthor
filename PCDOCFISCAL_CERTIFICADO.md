# 📊 Tabela: PCDOCFISCAL_CERTIFICADO

### Estrutura de Colunas e Restrições

                 Tabela      Coluna  Tipo/Tamanho                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDOCFISCAL_CERTIFICADO   CODFILIAL   VARCHAR2(2)  Código da Filial que o Certificado Assina CHAVE ESTRANGEIRA (FK)                   PCFILIAL
PCDOCFISCAL_CERTIFICADO CERTIFICADO VARCHAR2(500)                        Nome do Certificado            OPERACIONAL                        NaN
PCDOCFISCAL_CERTIFICADO       SENHA VARCHAR2(200)             Senha para abrir o Certificado            OPERACIONAL                        NaN
PCDOCFISCAL_CERTIFICADO     BROWSER   NUMBER(1,0)                       Fonte do Certificado            OPERACIONAL                        NaN
PCDOCFISCAL_CERTIFICADO      SERIAL VARCHAR2(100)                      Serial do Certificado            OPERACIONAL                        NaN
PCDOCFISCAL_CERTIFICADO    VALIDADE          DATE            Data de validade do Certificado            OPERACIONAL                        NaN
PCDOCFISCAL_CERTIFICADO        CNPJ  VARCHAR2(14) CNPJ para o qual o Certificado foi Emitido            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*