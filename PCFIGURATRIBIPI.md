# 📊 Tabela: PCFIGURATRIBIPI

### Estrutura de Colunas e Restrições

         Tabela            Coluna Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFIGURATRIBIPI      CODFIGURAIPI  NUMBER(8,0)                   Código da figura tributária.    CHAVE PRIMÁRIA (PK)                        NaN
PCFIGURATRIBIPI         DESCRICAO VARCHAR2(50)                Descrição da figura tributaria.            OPERACIONAL                        NaN
PCFIGURATRIBIPI  CODSITTRIBIPIENT  NUMBER(3,0)                      Cód.Sit.Trib.IPI Entrada.            OPERACIONAL                        NaN
PCFIGURATRIBIPI CODSITTRIBIPISAID  NUMBER(3,0)                        Cód.Sit.Trib.IPI Saída.            OPERACIONAL                        NaN
PCFIGURATRIBIPI  GERABASEALIQZERO  VARCHAR2(1) Gerar Base de Cálculo do IPI com Aliquota Zero            OPERACIONAL                        NaN
PCFIGURATRIBIPI     CODENQENTRADA  VARCHAR2(3)                                            NaN            OPERACIONAL                        NaN
PCFIGURATRIBIPI       CODENQSAIDA  VARCHAR2(3)                                            NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*