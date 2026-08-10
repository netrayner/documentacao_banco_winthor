# 📊 Tabela: PCEMAILUSUARIO

### Estrutura de Colunas e Restrições

        Tabela          Coluna  Tipo/Tamanho Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEMAILUSUARIO  CODIGO_USUARIO  NUMBER(10,0)      CODIGO_USUARIO    CHAVE PRIMÁRIA (PK)                        NaN
PCEMAILUSUARIO   CODIGO_ROTINA  NUMBER(10,0)       CODIGO_ROTINA    CHAVE PRIMÁRIA (PK)                        NaN
PCEMAILUSUARIO            NOME  VARCHAR2(35)                NOME            OPERACIONAL                        NaN
PCEMAILUSUARIO           EMAIL VARCHAR2(256)               EMAIL            OPERACIONAL                        NaN
PCEMAILUSUARIO           SENHA  VARCHAR2(35)               SENHA            OPERACIONAL                        NaN
PCEMAILUSUARIO CODIGO_SERVIDOR  NUMBER(10,0)     CODIGO_SERVIDOR CHAVE ESTRANGEIRA (FK)       PCINFORMACAOSERVIDOR

---
*Documentação gerada automaticamente.*