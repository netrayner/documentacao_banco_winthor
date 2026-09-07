# 📊 Tabela: PCPERFIL

### Estrutura de Colunas e Restrições

  Tabela           Coluna  Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPERFIL               ID  NUMBER(10,0)                                   ID do Perfil    CHAVE PRIMÁRIA (PK)                        NaN
PCPERFIL             NOME VARCHAR2(255)                                 Nome do Perfil            OPERACIONAL                        NaN
PCPERFIL            ATIVO       CHAR(1)                                 Perfil Ativado            OPERACIONAL                        NaN
PCPERFIL IDESTADOTIMEZONE  NUMBER(22,0) Identificador do timezone vinculado ao perfil.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*