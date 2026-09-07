# 📊 Tabela: PCMYFROTA_VIAGEM

### Estrutura de Colunas e Restrições

          Tabela              Coluna  Tipo/Tamanho                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMYFROTA_VIAGEM IDINTEGRACAOMYFROTA           RAW              Número da integração com myfrota            OPERACIONAL                        NaN
PCMYFROTA_VIAGEM                NOME VARCHAR2(200)           Descrição da integração com myfrota            OPERACIONAL                        NaN
PCMYFROTA_VIAGEM          ATUALIZADO       CHAR(1) Status da atualização P=Pendente S=Atualizado            OPERACIONAL                        NaN
PCMYFROTA_VIAGEM          DTEXCLUSAO          DATE                              Data de exclusão            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*