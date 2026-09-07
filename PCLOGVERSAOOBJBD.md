# 📊 Tabela: PCLOGVERSAOOBJBD

### Estrutura de Colunas e Restrições

          Tabela        Coluna Tipo/Tamanho                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGVERSAOOBJBD     CODROTINA  NUMBER(6,0) Código da rotina que foi executada sem a atualização do objeto. CHAVE ESTRANGEIRA (FK)                   PCROTINA
PCLOGVERSAOOBJBD     MATRICULA  NUMBER(8,0)      Código do usuário que executou a rotina sem a atualização. CHAVE ESTRANGEIRA (FK)                     PCEMPR
PCLOGVERSAOOBJBD    NOMEOBJETO VARCHAR2(30)                               Nome do objeto no banco de dados.            OPERACIONAL                        NaN
PCLOGVERSAOOBJBD      VERSAOPC NUMBER(10,0)               Versão da rotina de atualização de objetos atual.            OPERACIONAL                        NaN
PCLOGVERSAOOBJBD VERSAOCLIENTE NUMBER(10,0)          Versão da rotina de atualização de objetos no cliente.            OPERACIONAL                        NaN
PCLOGVERSAOOBJBD    DTREGISTRO TIMESTAMP(6)                                    Data/Hora de geração do log.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*