# Revisão rápida da base e tarefas sugeridas

## Contexto
A base atual contém apenas um `README.md` com descrição de alto nível do projeto.

## Problemas encontrados e tarefas sugeridas

1. **Erro de digitação / inconsistência de naming**
   - **Problema:** O nome no título é `MusiCompAi`, mas na descrição aparece `MusicCompAi`.
   - **Tarefa sugerida:** Padronizar o nome do produto em todos os arquivos e futuros artefatos para evitar confusão de marca e importações/pacotes inconsistentes.

2. **Bug (falta de estrutura mínima executável)**
   - **Problema:** Não há código-fonte, scripts de execução, nem instruções de setup; o projeto está não executável no estado atual.
   - **Tarefa sugerida:** Criar um esqueleto mínimo da aplicação (ex.: `src/`, comando de inicialização e arquivo de configuração), garantindo que `README` descreva como rodar localmente.

3. **Discrepância de documentação**
   - **Problema:** O README afirma funcionalidades amplas (PDF, MIDI, áudio, edição, reprodução por naipes, exportação), mas não há documentação técnica de escopo, status (planejado vs implementado) ou limitações.
   - **Tarefa sugerida:** Reescrever o README com seções de `Status do Projeto`, `Funcionalidades Implementadas`, `Roadmap` e `Limitações Conhecidas`.

4. **Melhoria de testes**
   - **Problema:** Não existe suíte de testes.
   - **Tarefa sugerida:** Adicionar testes iniciais de contrato para parsing/importação (ex.: validação de formatos PDF/MIDI), incluindo pelo menos um teste positivo e um negativo por formato suportado.
