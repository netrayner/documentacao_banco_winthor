# 📊 Tabela: PCLOGVIASMAPA

### Estrutura de Colunas e Restrições

       Tabela        Coluna Tipo/Tamanho                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGVIASMAPA          DATA         DATE            Data de emissão do mapa            OPERACIONAL                        NaN
PCLOGVIASMAPA        NUMCAR NUMBER(10,0)             Numero de carregamento            OPERACIONAL                        NaN
PCLOGVIASMAPA        NUMPED NUMBER(10,0)                   Numero do pedido            OPERACIONAL                        NaN
PCLOGVIASMAPA NUMTRANSVENDA NUMBER(10,0)      Nº trans. nf. Simples remessa            OPERACIONAL                        NaN
PCLOGVIASMAPA       CODFUNC  NUMBER(8,0)         Cód. Func. Emissor do mapa            OPERACIONAL                        NaN
PCLOGVIASMAPA       MAQUINA VARCHAR2(30) Maquina de onde foi emitido o mapa            OPERACIONAL                        NaN
PCLOGVIASMAPA       USUARIO VARCHAR2(50)   Nome do funcionario emissor mapa            OPERACIONAL                        NaN
PCLOGVIASMAPA      PROGRAMA VARCHAR2(20)       Programa gerador do registro            OPERACIONAL                        NaN
PCLOGVIASMAPA   NUMVIASMAPA  NUMBER(2,0)     Numero de vias da emissao mapa            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*