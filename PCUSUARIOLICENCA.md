# 📊 Tabela: PCUSUARIOLICENCA

### Estrutura de Colunas e Restrições

          Tabela         Coluna  Tipo/Tamanho                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCUSUARIOLICENCA      USUARIOID  VARCHAR2(32)           Identificador do usuário            OPERACIONAL                        NaN
PCUSUARIOLICENCA      CODPERFIL   NUMBER(6,0)                   Código do Perfil            OPERACIONAL                        NaN
PCUSUARIOLICENCA  IDENTIFICADOR VARCHAR2(100) Identificador do device autorizado            OPERACIONAL                        NaN
PCUSUARIOLICENCA USUARIOWINTHOR   NUMBER(8,0)       Código do usuário no WinThor            OPERACIONAL                        NaN
PCUSUARIOLICENCA      USUARIOOS  VARCHAR2(60)          Usuário logado no windows            OPERACIONAL                        NaN
PCUSUARIOLICENCA        MAQUINA  VARCHAR2(60)       Dóminio e máquina do usuário            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*