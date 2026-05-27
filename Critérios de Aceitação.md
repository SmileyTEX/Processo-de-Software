# Histórias de Usuário e Critérios de Aceitação

## RF04 – Seleção de evento

**História de usuário**  
Como usuário, quero acessar a página de um evento específico para visualizar suas informações, detalhes e atividades relacionadas.

### Critérios de aceitação
- O usuário deve conseguir acessar a página de detalhes de um evento a partir da lista de eventos ou de um link direto.
- A página do evento deve exibir, no mínimo, nome do evento, descrição, data, horário, local e situação do evento.
- A página deve apresentar as atividades relacionadas ao evento, quando existirem.
- Cada atividade relacionada deve exibir, no mínimo, título, horário e local.
- Quando o evento não possuir atividades cadastradas, o sistema deve informar isso de forma clara ao usuário.
- Quando o evento informado não existir ou não estiver disponível, o sistema deve exibir uma mensagem de erro ou indisponibilidade.
- As informações exibidas devem corresponder ao evento selecionado pelo usuário.

## RF01 – Calendário do Cronograma

**História de usuário**  
Como usuário, quero visualizar um calendário com horários e locais dos eventos para poder me organizar e acompanhar a programação.

### Critérios de aceitação
- O sistema deve disponibilizar uma visualização de calendário com os eventos programados.
- Cada item do calendário deve exibir, no mínimo, nome do evento, data, horário e local.
- O usuário deve conseguir identificar visualmente em que dia e horário cada evento ocorrerá.
- Ao selecionar um item do calendário, o usuário deve conseguir acessar os detalhes do evento correspondente.
- O calendário deve exibir apenas eventos válidos e cadastrados na programação.
- Quando não houver eventos programados para o período exibido, o sistema deve informar isso claramente.
- As informações de data, horário e local mostradas no calendário devem ser consistentes com os dados cadastrados do evento.

## RF09 – Gerar certificados

**História de usuário**  
Como organizador, quero gerar certificados após a finalização do evento para disponibilizá-los aos participantes.

### Critérios de aceitação
- Apenas usuários com perfil de organizador devem poder gerar certificados.
- A geração de certificados só deve ser permitida para eventos finalizados.
- O sistema deve permitir gerar certificados para os participantes aptos do evento.
- Cada certificado gerado deve conter, no mínimo, nome do participante, nome do evento, data do evento, carga horária ou tipo de participação e identificação do organizador.[4]
- Após a geração, os certificados devem ficar disponíveis para consulta ou download pelos participantes.
- O sistema deve informar o sucesso da geração dos certificados ou apresentar mensagem de erro em caso de falha.
- Caso não existam participantes aptos para certificação, o sistema deve informar essa condição ao organizador.
- O organizador não deve conseguir gerar certificados duplicados para o mesmo participante e mesmo evento sem confirmação explícita.
