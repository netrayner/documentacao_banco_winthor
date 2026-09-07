# 📊 Tabela: PCROTACLIFIXAC

### Estrutura de Colunas e Restrições

        Tabela          Coluna Tipo/Tamanho                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCROTACLIFIXAC     CODROTAFIXA  NUMBER(8,0)             Código rota faixa de visitas            OPERACIONAL                        NaN
PCROTACLIFIXAC       DESCRICAO VARCHAR2(80)      Descrição da rota faixa de clientes            OPERACIONAL                        NaN
PCROTACLIFIXAC         CODUSUR  NUMBER(8,0)                        RCA da rota faixa            OPERACIONAL                        NaN
PCROTACLIFIXAC        DTINICIO         DATE          Data início da vigência da rota            OPERACIONAL                        NaN
PCROTACLIFIXAC         DTFINAL         DATE           Data final da vigência da rota            OPERACIONAL                        NaN
PCROTACLIFIXAC      DTEXCLUSAO         DATE                            Data exclusão            OPERACIONAL                        NaN
PCROTACLIFIXAC CODFUNCEXCLUSAO  NUMBER(8,0) Código do funcionário que excluiu a rota            OPERACIONAL                        NaN
PCROTACLIFIXAC      DTMXSALTER         DATE                                      NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*