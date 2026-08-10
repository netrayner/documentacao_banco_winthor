# 📊 Tabela: PCPERFILACESSO

### Estrutura de Colunas e Restrições

        Tabela    Coluna  Tipo/Tamanho           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPERFILACESSO CODPERFIL   NUMBER(6,0) Identificador único do perfil    CHAVE PRIMÁRIA (PK)                        NaN
PCPERFILACESSO      NOME VARCHAR2(155)      Nome do perfil de acesso            OPERACIONAL                        NaN
PCPERFILACESSO     ATIVO   VARCHAR2(1)              Status do perfil            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*