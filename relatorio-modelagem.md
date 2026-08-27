Relatório de Arquitetura e Modelagem
1. Identificação do Projeto
Nome do projeto: PainelFila Escolar
Disciplina: Projeto Integrador II
Etapa: 2 — Planejamento Operacional e Gestão Ágil
2. Introdução
O PainelFila Escolar é uma proposta de solução para organizar o atendimento dos alunos na direção da escola por meio de um sistema de gerenciamento de filas.
A solução tem como objetivo organizar a ordem de atendimento, permitindo que o aluno retire uma senha, aguarde sua vez e seja chamado pela direção. A senha chamada é apresentada em um painel eletrônico, facilitando a identificação do aluno que deve se dirigir ao local de atendimento.
3. Objetivo da Modelagem
A modelagem tem como objetivo representar visualmente o funcionamento básico do PainelFila Escolar, mostrando as principais etapas realizadas desde a chegada do aluno à direção até o momento em que ele é chamado para o atendimento.
O fluxo facilita a compreensão da solução e serve como referência para as próximas etapas de desenvolvimento do projeto.
4. Fluxo da Solução
O fluxo desenvolvido representa as seguintes etapas:
Aluno chega na direção: o aluno chega ao local onde será realizado o atendimento.
Aluno retira senha no dispositivo: o aluno utiliza o dispositivo disponibilizado para retirar sua senha.
Senha entra na fila de espera: a senha retirada é registrada na fila, aguardando sua vez de atendimento.
Direção chama a próxima senha: a direção realiza a chamada da próxima senha da fila.
Senha aparece no painel eletrônico: a senha chamada é apresentada no painel eletrônico para que o aluno possa identificá-la.
Aluno se dirige à direção: ao visualizar sua senha no painel, o aluno se dirige à direção para ser atendido.
5. Diagrama de Fluxo
O diagrama foi desenvolvido utilizando a ferramenta Draw.io (diagrams.net) e representa visualmente o fluxo principal da solução.
O fluxo segue uma sequência linear:
Aluno chega na direção
↓
Aluno retira senha no dispositivo
↓
Senha entra na fila de espera
↓
Direção chama a próxima senha
↓
Senha aparece no painel eletrônico
↓
Aluno se dirige à direção
O arquivo do diagrama está armazenado no repositório dentro da pasta /docs.
6. Componentes Principais da Solução
A modelagem inicial considera os seguintes elementos:
Aluno: usuário que solicita atendimento e acompanha sua senha.
Dispositivo de retirada de senha: utilizado pelo aluno para obter uma senha.
Fila de espera: responsável por representar a ordem dos atendimentos.
Direção: responsável por chamar a próxima senha.
Painel eletrônico: apresenta a senha que está sendo chamada.
7. Funcionamento Geral
O funcionamento inicia quando o aluno chega à direção e retira uma senha no dispositivo. Essa senha passa a fazer parte da fila de espera.
Quando chega a vez do aluno, a direção chama a próxima senha. A senha chamada é apresentada no painel eletrônico, permitindo que o aluno identifique que chegou o momento de ser atendido.
Após visualizar sua senha, o aluno se dirige à direção para realizar o atendimento.

- **Link para o Trello** https://trello.com/b/pd5N1CC0/painelfila-escolar
9. Considerações Finais
A modelagem apresentada representa o funcionamento inicial do PainelFila Escolar de maneira simples e organizada. O fluxo permite visualizar as principais etapas da solução e estabelece uma base para o desenvolvimento das próximas fases do projeto.
O diagrama poderá servir como referência durante a execução e validação da solução, contribuindo para manter o desenvolvimento alinhado ao objetivo definido no projeto.
