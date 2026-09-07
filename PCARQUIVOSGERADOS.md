# 📊 Tabela: PCARQUIVOSGERADOS

### Estrutura de Colunas e Restrições

           Tabela      Coluna Tipo/Tamanho                                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCARQUIVOSGERADOS   CODFILIAL  VARCHAR2(2)                                                Código da filial que gerou o arquivo            OPERACIONAL                        NaN
PCARQUIVOSGERADOS TIPOARQUIVO VARCHAR2(20)                               Responsável por identificar o arquivo que foi gerado.            OPERACIONAL                        NaN
PCARQUIVOSGERADOS   DTINICIAL         DATE Responsável por armazenar a Data Inicial selecionada no momento de gerar o arquivo.            OPERACIONAL                        NaN
PCARQUIVOSGERADOS     DTFINAL         DATE   Responsável por armazenar a Data Final selecionada no momento de gerar o arquivo.            OPERACIONAL                        NaN
PCARQUIVOSGERADOS   DTGERACAO         DATE                           Responsável por armazenar a Data que o arquivo foi gerado            OPERACIONAL                        NaN
PCARQUIVOSGERADOS  CODUSUARIO  NUMBER(8,0)                                              Código do usuário que gerou o arquivo.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*