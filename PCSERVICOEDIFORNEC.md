# 📊 Tabela: PCSERVICOEDIFORNEC

### Estrutura de Colunas e Restrições

            Tabela         Coluna  Tipo/Tamanho          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSERVICOEDIFORNEC  CODSERVICOEDI   NUMBER(6,0)     Código do Serviço de EDI    CHAVE PRIMÁRIA (PK)                        NaN
PCSERVICOEDIFORNEC      CODFORNEC   NUMBER(6,0)         Código do Fornecedor    CHAVE PRIMÁRIA (PK)                        NaN
PCSERVICOEDIFORNEC CXPOSTALDESTIN  VARCHAR2(35) Caixa Postal do Destinatário            OPERACIONAL                        NaN
PCSERVICOEDIFORNEC      DIRETORIO VARCHAR2(200)                    Diretório            OPERACIONAL                        NaN
PCSERVICOEDIFORNEC  TIPOSUBDIRFIL   VARCHAR2(1) Tipo Sub-Diretório da Filial            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*