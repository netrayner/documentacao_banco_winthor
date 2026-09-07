# 📊 Tabela: PCAUTPERFIL

### Estrutura de Colunas e Restrições

     Tabela    Coluna Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAUTPERFIL    CODCLI  NUMBER(6,0)                           Código do cliente PC    CHAVE PRIMÁRIA (PK)               PCAUTLICENCA
PCAUTPERFIL CODPERFIL  NUMBER(6,0)                    Código do perfil do cliente    CHAVE PRIMÁRIA (PK)                        NaN
PCAUTPERFIL CODMODULO  NUMBER(6,0) Código do módulo do Winthor permitido o acesso    CHAVE PRIMÁRIA (PK)                        NaN
PCAUTPERFIL CODROTINA  NUMBER(6,0) Código da rotina do Winthor permitido o acesso    CHAVE PRIMÁRIA (PK)                        NaN
PCAUTPERFIL    PERFIL VARCHAR2(60)                                            NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*