# 📊 Tabela: PCDOCFISCALNODES

### Estrutura de Colunas e Restrições

          Tabela       Coluna Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDOCFISCALNODES           IP VARCHAR2(15)          IP da máquina onde está o DocFiscal    CHAVE PRIMÁRIA (PK)                        NaN
PCDOCFISCALNODES     HOSTNAME VARCHAR2(60)       Nome da máquina onde está o DocFiscal.    CHAVE PRIMÁRIA (PK)                        NaN
PCDOCFISCALNODES         PORT  NUMBER(5,0)    Porta em que a instancia do esta rodando.            OPERACIONAL                        NaN
PCDOCFISCALNODES DATA_STARTUP         DATE Data e Hora que instancia entrou no cluster.            OPERACIONAL                        NaN
PCDOCFISCALNODES       STATUS  VARCHAR2(7)             Situação do perfil da instancia.            OPERACIONAL                        NaN
PCDOCFISCALNODES       PERFIL  VARCHAR2(6)      Indica qual perfil a instancia assumiu.            OPERACIONAL                        NaN
PCDOCFISCALNODES   DATASTATUS         DATE     Data e hora que o status foi atualizado.            OPERACIONAL                        NaN
PCDOCFISCALNODES   LAST_CHECK         DATE              Data e hora da última checagem.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*