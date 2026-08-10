# 📊 Tabela: PCBIONEXONIVELSERVICO

### Estrutura de Colunas e Restrições

               Tabela             Coluna Tipo/Tamanho                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBIONEXONIVELSERVICO               TIPO  VARCHAR2(5)                   Tipo de nível de serviço            OPERACIONAL                        NaN
PCBIONEXONIVELSERVICO              TOKEN NUMBER(10,0)                       Token para validação            OPERACIONAL                        NaN
PCBIONEXONIVELSERVICO            ARQUIVO         CLOB Arquivo a ser validado no nível de serviço            OPERACIONAL                        NaN
PCBIONEXONIVELSERVICO         PROCESSADO  VARCHAR2(1)             Identificador de processamento            OPERACIONAL                        NaN
PCBIONEXONIVELSERVICO         DTCADASTRO         DATE                           Data de cadastro            OPERACIONAL                        NaN
PCBIONEXONIVELSERVICO DTULTPROCESSAMENTO         DATE               Data do último processamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*