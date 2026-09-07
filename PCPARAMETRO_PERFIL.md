# 📊 Tabela: PCPARAMETRO_PERFIL

### Estrutura de Colunas e Restrições

            Tabela                    Coluna  Tipo/Tamanho                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPARAMETRO_PERFIL                 CODPERFIL   NUMBER(5,0)                     Coluna que liga ao codigo do perfil    CHAVE PRIMÁRIA (PK)                   PCPERFIL
PCPARAMETRO_PERFIL CODDICIONARIOCONFIGURACAO        NUMBER Coluna que liga ao codigo do dicionario da configuração    CHAVE PRIMÁRIA (PK)   PCDICIONARIOCONFIGURACAO
PCPARAMETRO_PERFIL                 PARAMETRO VARCHAR2(100)                            Nome do parametro cadastrado            OPERACIONAL                        NaN
PCPARAMETRO_PERFIL                     VALOR VARCHAR2(250)              Valor dado atribuido ao parametro cadastro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*