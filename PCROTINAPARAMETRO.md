# 📊 Tabela: PCROTINAPARAMETRO

### Estrutura de Colunas e Restrições

           Tabela        Coluna  Tipo/Tamanho                                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCROTINAPARAMETRO     CODROTINA   NUMBER(6,0)                                                       Código da rotina    CHAVE PRIMÁRIA (PK)                        NaN
PCROTINAPARAMETRO    COMPONENTE  VARCHAR2(50)                                        Componente que receberá o valor    CHAVE PRIMÁRIA (PK)                        NaN
PCROTINAPARAMETRO     DESCRICAO VARCHAR2(100)                                                 Descrição do parâmetro            OPERACIONAL                        NaN
PCROTINAPARAMETRO         VALOR VARCHAR2(100)                                                     Valor do parâmetro            OPERACIONAL                        NaN
PCROTINAPARAMETRO    DTINCLUSAO          DATE                                                       Data de inclusão            OPERACIONAL                        NaN
PCROTINAPARAMETRO   DTALTERACAO          DATE                                                      Data de alteração            OPERACIONAL                        NaN
PCROTINAPARAMETRO CODUSUARIOALT   NUMBER(8,0)                                              Código do usuário alterou            OPERACIONAL                        NaN
PCROTINAPARAMETRO         SECAO  VARCHAR2(50) Seção ou aba, local onde se encontra o componente que será controlado.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*