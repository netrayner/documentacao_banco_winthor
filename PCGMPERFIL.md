# 📊 Tabela: PCGMPERFIL

### Estrutura de Colunas e Restrições

    Tabela         Coluna Tipo/Tamanho                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGMPERFIL         CODIGO NUMBER(10,0)                              Código do perfil    CHAVE PRIMÁRIA (PK)                        NaN
PCGMPERFIL      DESCRICAO VARCHAR2(50)                           Descrição do perfil            OPERACIONAL                        NaN
PCGMPERFIL TIPOIDENTIDADE  VARCHAR2(1)             Tipo de identidade do colaborador            OPERACIONAL                        NaN
PCGMPERFIL      TIPOBONUS  VARCHAR2(1) Tipo de bonus utilizado para esse colaborador            OPERACIONAL                        NaN
PCGMPERFIL           FIXO  NUMBER(3,0)                Percentual de remuneração fixo            OPERACIONAL                        NaN
PCGMPERFIL       VARIAVEL  NUMBER(3,0)            Percentual de remuneração variável            OPERACIONAL                        NaN
PCGMPERFIL   DATAEXCLUSAO         DATE                    Data da exclusão do perfil            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*