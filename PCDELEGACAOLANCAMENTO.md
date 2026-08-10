# 📊 Tabela: PCDELEGACAOLANCAMENTO

### Estrutura de Colunas e Restrições

               Tabela                 Coluna Tipo/Tamanho                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDELEGACAOLANCAMENTO CODDELEGACAOLANCAMENTO NUMBER(10,0)                            Código Chave Primária do Lançamento    CHAVE PRIMÁRIA (PK)                        NaN
PCDELEGACAOLANCAMENTO           CODDELEGACAO NUMBER(10,0)                        Código Chave Extrangeira para Delegação CHAVE ESTRANGEIRA (FK)       PCDELEGACAOATIVIDADE
PCDELEGACAOLANCAMENTO    TIPOFUNCSOLICITANTE  VARCHAR2(1) Tipo Solicitante (F=funcionário, M=Motorista, V=Vendedor(RCA))            OPERACIONAL                        NaN
PCDELEGACAOLANCAMENTO         CODSOLICITANTE  NUMBER(8,0)                                          Código do Solicitante            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*