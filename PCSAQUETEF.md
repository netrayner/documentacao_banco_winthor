# 📊 Tabela: PCSAQUETEF

### Estrutura de Colunas e Restrições

    Tabela           Coluna  Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSAQUETEF        NUMPEDECF  NUMBER(26,6) Numeração do pedido frente de caixa    CHAVE PRIMÁRIA (PK)                        NaN
PCSAQUETEF        DTEMISSAO          DATE            Data de emissao do saque            OPERACIONAL                        NaN
PCSAQUETEF         NUMCUPOM  NUMBER(10,0)                     Numero do cupom            OPERACIONAL                        NaN
PCSAQUETEF              CCF  NUMBER(10,0)                       Numero do CCF            OPERACIONAL                        NaN
PCSAQUETEF          VLSAQUE  NUMBER(10,2)                      Valor do Saque            OPERACIONAL                        NaN
PCSAQUETEF       ROTINALANC  VARCHAR2(20)                Rotina do Lançamento            OPERACIONAL                        NaN
PCSAQUETEF        MATRICULA   NUMBER(8,0)                Matricula do Usuário            OPERACIONAL                        NaN
PCSAQUETEF         NUMCAIXA   NUMBER(4,0)                     Numero do Caixa    CHAVE PRIMÁRIA (PK)                        NaN
PCSAQUETEF RAZAOBENEFICIADA  VARCHAR2(60)            Razao social beneficiada            OPERACIONAL                        NaN
PCSAQUETEF             CNPJ  VARCHAR2(14)                   CNPJ do Saque TEF            OPERACIONAL                        NaN
PCSAQUETEF           MD5PAF VARCHAR2(200)   Assinatura MD5 do registro do PAF            OPERACIONAL                        NaN
PCSAQUETEF        CODFILIAL   VARCHAR2(2)                    Código da Filial            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*