# 📊 Tabela: PCCONFIGURACAO

### Estrutura de Colunas e Restrições

        Tabela              Coluna Tipo/Tamanho                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONFIGURACAO CODTIPOCONFIGURACAO  NUMBER(5,0)                             Chave da configuração que o usuário persiste.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONFIGURACAO           CODPERFIL NUMBER(22,0) Compoem a chave da tabela e liga ao codigo do perfil para um configuração            OPERACIONAL                        NaN
PCCONFIGURACAO        CONFIGURACAO         CLOB        Campo para big strings,  que contem dados que o usuário persistiu.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*