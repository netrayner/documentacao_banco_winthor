# 📊 Tabela: PCTAEAUTENTICADOR

### Estrutura de Colunas e Restrições

           Tabela          Coluna  Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTAEAUTENTICADOR CODAUTENTICADOR   NUMBER(6,0)                                       ID da tabela.    CHAVE PRIMÁRIA (PK)                        NaN
PCTAEAUTENTICADOR         USUARIO VARCHAR2(100)          Usuário para a autenticação na API do TAE.            OPERACIONAL                        NaN
PCTAEAUTENTICADOR           SENHA VARCHAR2(100)            Senha para a autenticação na API do TAE.            OPERACIONAL                        NaN
PCTAEAUTENTICADOR       CODFILIAL   VARCHAR2(2) Código da filial que a autenticação está vinculado. CHAVE ESTRANGEIRA (FK)                   PCFILIAL
PCTAEAUTENTICADOR        CODSETOR   NUMBER(6,0)  Código do setor que a autenticação está vinculado. CHAVE ESTRANGEIRA (FK)                    PCSETOR

---
*Documentação gerada automaticamente.*