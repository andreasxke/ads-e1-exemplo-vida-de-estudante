# Especificações do Projeto

## Perfis de Usuários

<table>
<tbody>
<tr>
<th colspan="2">Perfil 1: Paciente </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">
Paciente diagnosticado com uma doença crônica, como hipertensão ou diabetes, que requer acompanhamento constante e uso regular de medicamentos. 
</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>
1. Lembretes de dosagem e horário de medicamentos.
2. Registro de medições, como pressão arterial e glicemia.
3. Informações sobre dietas e atividades físicas que ajudem na gestão da condição.
4. Informações sobre serviços de saúde próximos para facilitar o acesso aos cuidados médicos e aos medicamentos.
5. Histórico de consultas médicas e receitas para referência.  
</td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr>
<th colspan="2">Perfil 2: Cuidador </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">
Pessoa que auxilia e monitora o paciente nas atividades diárias de saúde, incluindo administração de medicamentos e dosagens. 
</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>
1. Consulta do histórico médico do paciente, incluindo os procedimentos e remédios utilizados.
2. Notificações de futuras consultas médicas e dados sobre o estado do paciente.
3. Capacidade para documentar eventos médicos, como sintomas incomuns ou efeitos secundários da medicação.
4. Facilidade de comunicação com familiares e instruções em caso de emergências.
</td>
</tr>
</tbody>
</table>


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE`                                             |PARA ... `MOTIVO/VALOR`                 |
|--------------------|--------------------------------------------------------------------------------|----------------------------------------|
| Cuidadora de idosos | Controlar todas as medicações | Monitorar a medicação utilizada, suas doses e horários para garantir que o tratamento seja seguido corretamente. |
| Portador de Hipertensão | Lembrar de todas as medicações ao longo do dia e da semana | Manter o controle e evitar elevação da pressão arterial, evitando complicações. |
| Portador de Diabetes | Registrar os níveis glicêmicos diariamente | Elaborar um histórico detalhado de medicações ao longo da semana para ajustar o tratamento conforme necessário. |
| Portador de Diabetes | Calcular a dose das medicações com base nos resultados das medições de glicemia | Evitar tomar doses erradas que possam comprometer minha saúde. |
| Portador de doença crônica | Receber notificações caso um medicamento não seja tomado no horário prescrito | Manter o controle das medicações e assegurar que o tratamento está sendo seguido corretamente. |
| Responsável | Saber quando será a próxima consulta médica | Garantir que o paciente esteja presente na consulta. |
| Paciente com Insuficiência Cardíaca | Receber lembretes para medir e registrar minha frequência cardíaca e pressão arterial diariamente | Monitorar minha condição e relatar qualquer alteração significativa ao médico. |
| Cuidador de Paciente Idoso | Ter acesso a uma agenda de medicamentos e consultas | Gerenciar todas as necessidades de saúde do paciente de forma sólida, evitando complicações. |
| Portador de Hipertensão | Poder registrar a medição da minha pressão arterial após atividades físicas ou situações de estresse | Monitorar como essas condições afetam minha pressão e ajustar a medicação de acordo com as recomendações do meu médico. |

## Requisitos

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
| RF-01 | Possibilitar o registro dos horários para cada medicação. | ALTA |
| RF-02 | Envio de lembretes diários aos usuários para tomar seus medicamentos ou realizar consultas. | ALTA |
| RF-03 | Registrar e acompanhar as datas das consultas médicas e retornos. | MÉDIA |
| RF-04 | Permitir que os usuários registrem seus níveis de glicemia e pressão arterial. | ALTA |
| RF-05 | Possibilitar o registro dos resultados de exames e receitas médicas. | MÉDIA |
| RF-06 | O sistema deve manter um histórico das medicações, receitas, exames, e permitir que os usuários o acessem a qualquer momento. | MÉDIA |
| RF-07 | Possibilitar a emissão de relatórios detalhados, completos e precisos. | BAIXA |
| RF-08 | Permitir que os usuários registrem sintomas como dor, fadiga ou tontura para identificar padrões e possíveis complicações. | MÉDIA |
| RF-09 | Permitir que os dados monitorados sejam facilmente compartilhados. | BAIXA |
| RF-10 | Possibilitar o cálculo da quantidade de medicação baseado no resultado da medição da glicemia. | ALTA |
| RF-11 | Personalização das preferências de notificação pelos usuários. | BAIXA |
| RF-12 | Exibir informações sobre dietas e atividades físicas que ajudem na gestão da condição. | MÉDIA |

**Prioridade: Alta / Média / Baixa.  

### Requisitos Não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
| RNF-01 | A interface deve ser intuitiva e de fácil navegação. | ALTA |
| RNF-02 | Garantir a segurança dos dados dos usuários, com uso de criptografia para proteger informações pessoais e de saúde. | ALTA |
| RNF-03 | Sistema de fácil manutenção, permitindo que atualizações e correções de bugs sejam realizadas sem dificuldades. | MÉDIA |
| RNF-04 | Acessibilidade para pessoas com deficiências auditivas e visual. | MÉDIA |
| RNF-05 | Possibilidade de geração de backup de dados. | BAIXA |
| RNF-06 | Interação de usuários para exposição de feedback e sugestões de melhorias. | BAIXA |
| RNF-07 | O sistema deve estar acessível na web. | ALTA |
| RNF-08 | Atualizações recorrentes para incrementação de novas features. | MÉDIA |
| RNF-09 | O aplicativo deve ser capaz de lidar com um grande número de usuários simultâneos. | ALTA |
| RNF-10 | Funcionar em diferentes dispositivos e sistemas operacionais (iOS, Android, etc.). | ALTA |
| RNF-11 | O código da aplicação deve ser documentado e seguir boas práticas de desenvolvimento, com a utilização de padrões de reusabilidade e versionamento de código. | MÉDIA |
| RNF-12 | A aplicação deve garantir que os usuários forneçam consentimento explícito e informado antes de qualquer coleta, armazenamento e tratamento de seus dados de saúde. | ALTA |

**Prioridade: Alta / Média / Baixa.

