# 📊 Tabela: PCLICENCAPRODUTO

### Estrutura de Colunas e Restrições

          Tabela         Coluna  Tipo/Tamanho                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLICENCAPRODUTO      LICENCAID VARCHAR2(100)                               Identificador da licença    CHAVE PRIMÁRIA (PK)                        NaN
PCLICENCAPRODUTO FORMAVALIDACAO   NUMBER(1,0)                                Forma que será validado            OPERACIONAL                        NaN
PCLICENCAPRODUTO   TOTALUSUARIO   NUMBER(5,0) Quantidade máxima de usuário conectados ao mesmo tempo            OPERACIONAL                        NaN
PCLICENCAPRODUTO      CODPERFIL   NUMBER(6,0)                                       Código do perfil    CHAVE PRIMÁRIA (PK)                        NaN
PCLICENCAPRODUTO  IDENTIFICADOR VARCHAR2(100)                                Identificador permitido    CHAVE PRIMÁRIA (PK)                        NaN
PCLICENCAPRODUTO    DATAINICIAL          DATE                   Data inícial permitido para o acesso            OPERACIONAL                        NaN
PCLICENCAPRODUTO      DATAFINAL          DATE                     Data final permitido para o acesso            OPERACIONAL                        NaN
PCLICENCAPRODUTO    ACESSOTOTAL   VARCHAR2(1)       Se esta licença permite acesso a qualquer módulo            OPERACIONAL                        NaN
PCLICENCAPRODUTO          ORDEM   NUMBER(5,0)                          Ordem do registro no cadastro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*