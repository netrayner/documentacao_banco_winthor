# 📊 Tabela: PCCAIXASFATURAMENTOAUTOSERV

### Estrutura de Colunas e Restrições

                     Tabela           Coluna Tipo/Tamanho                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCAIXASFATURAMENTOAUTOSERV         NUMCAIXA  NUMBER(4,0)                                     Número do caixa.            OPERACIONAL                        NaN
PCCAIXASFATURAMENTOAUTOSERV        DESCRICAO VARCHAR2(40)                                  Descrição do caixa.            OPERACIONAL                        NaN
PCCAIXASFATURAMENTOAUTOSERV          USUARIO VARCHAR2(10)                           Usuário do banco de dados.            OPERACIONAL                        NaN
PCCAIXASFATURAMENTOAUTOSERV            SENHA  VARCHAR2(8)                             Senha do banco de dados.            OPERACIONAL                        NaN
PCCAIXASFATURAMENTOAUTOSERV         ENDERECO VARCHAR2(15)                                   Endereço do caixa.            OPERACIONAL                        NaN
PCCAIXASFATURAMENTOAUTOSERV         SENHAVNC VARCHAR2(20)                                        Senha do VNC.            OPERACIONAL                        NaN
PCCAIXASFATURAMENTOAUTOSERV            ATIVO  VARCHAR2(1) Situação do caixa dentro do ambiente de faturamento.            OPERACIONAL                        NaN
PCCAIXASFATURAMENTOAUTOSERV NOMESERVICOBANCO VARCHAR2(40)                   Nome do serviço do banco de dados.            OPERACIONAL                        NaN
PCCAIXASFATURAMENTOAUTOSERV       SENHABANCO VARCHAR2(30)                             Senha do banco de dados.            OPERACIONAL                        NaN
PCCAIXASFATURAMENTOAUTOSERV     USUARIOBANCO VARCHAR2(30)                           Usuário do banco de dados.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*