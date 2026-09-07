# 📊 Tabela: PCCONFIGURACOESSMTP

### Estrutura de Colunas e Restrições

             Tabela            Coluna  Tipo/Tamanho                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONFIGURACOESSMTP            CODIGO  NUMBER(10,0)                   Identificador único para a configuração    CHAVE PRIMÁRIA (PK)                        NaN
PCCONFIGURACOESSMTP          HOSTSMTP VARCHAR2(100)                                              Host de SMTP            OPERACIONAL                        NaN
PCCONFIGURACOESSMTP         PORTASMTP  NUMBER(10,0)                                    Porta do servidor SMTP            OPERACIONAL                        NaN
PCCONFIGURACOESSMTP        SENHAEMAIL VARCHAR2(100)                         Senha de usuario do servidor SMTP            OPERACIONAL                        NaN
PCCONFIGURACOESSMTP      USUARIOEMAIL VARCHAR2(100)                                  Usuario do servidor SMTP            OPERACIONAL                        NaN
PCCONFIGURACOESSMTP      DOMINIOEMAIL VARCHAR2(100)                               Dominio para envio de email            OPERACIONAL                        NaN
PCCONFIGURACOESSMTP        EMAILCOPIA VARCHAR2(100)                     Endereço de email para envio de copia            OPERACIONAL                        NaN
PCCONFIGURACOESSMTP     EMAILRESPOSTA VARCHAR2(100)                           Endereço de email para resposta            OPERACIONAL                        NaN
PCCONFIGURACOESSMTP    EMAILREMETENTE VARCHAR2(100)                               Endereço de email remetente            OPERACIONAL                        NaN
PCCONFIGURACOESSMTP     NOMEREMETENTE VARCHAR2(100)                                Nome do remetente do email            OPERACIONAL                        NaN
PCCONFIGURACOESSMTP         ATIVARSSL   VARCHAR2(1)                       Ativar SSL para configuraçao S ou N            OPERACIONAL                        NaN
PCCONFIGURACOESSMTP         ATIVARTLS   VARCHAR2(1)                       Ativar TLS para configuraçao S ou N            OPERACIONAL                        NaN
PCCONFIGURACOESSMTP CONFIG_IMPORTACAO   VARCHAR2(1)         Indica com S ou N se a configuração foi importada            OPERACIONAL                        NaN
PCCONFIGURACOESSMTP    CONFIG_DEFAULT   VARCHAR2(1) Indica com S ou N se a configuração é a padrão para envio            OPERACIONAL                        NaN
PCCONFIGURACOESSMTP      CONFIG_ATIVO   VARCHAR2(1) Indica com S ou N se a configuração está em funcionamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*