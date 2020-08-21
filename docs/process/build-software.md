# Processo de desenvolvimento

> **Nota**: O documento se refere ao desenvolvimento no sentido geral, mas é aplicável no desenvolvimento de novas funcionalidades também.

O único objectivo deste é **guiar o processo de desenvolvimento**, da recolha de requisitos ao deploy.

Penso que o principal objectivo dos desenvolvedores seja soluccionar problemas. Para fazê-lo com excelência é necessário entender muito bem o problema a ser resolvido antes de propor uma solução, por isso algumas etapas são colocadas para ajudar o desenvolvedor a internalizar o problema.

1. Recolha de requisitos
2. Protótipos de baixa fidelidade
3. Desenvolvimento
   1. Frontend
   2. Backend
   3. Integração
4. Validação
5. Documentação
6. Deploy

# Recolha de requisitos

O processo começa com a recolha dos requisitos funcionais e entender o que é pretendido com o software ou funcionalidade.

### Como recolher requisitos

1. Cada requisito deve ser descrito na forma de uma acção a ser tomada por um usuário
2. Abaixo de cada requisito coloque uma lista de tarefas que te ajudarão a atingir o objectivo

Para descrever o requisito use o template:

- Como _<tipo de usuário>_ quero [poder] _<acção/lista de accões relaccionadas>_.

**Exemplo**:  
Como _administrador_ quero poder _visualizar o número de mensagens enviadas por operadora, por shortcode (ex: 94521) e por intervalo de datas, sendo possível usar todos esses parâmetros em conjunto e baixar o resultado para um ficheiro excel_.

- [ ] Mostrar menu de estatísticas somente para usuários com previlégios de administrador.
- [ ] Agregar número de mensagens enviadas por operadora.
- [ ] Agregar número de mensagens enviadas por shortcode.
- [ ] Agregar número de mensagens enviadas por intervalo de datas.
- [ ] Criar mecanismo de busca do número de mensagens por operadora, shortcode e intervalo de data.
- [ ] Possibilitar o usuário baixar o resultado em excel.

# Protótipos de baixa fidelidade

De seguida para entender como tudo funcionará visualmente deverão ser desenvolvidos protótipos de baixa fidelidade para obrigar o cérebro a pensar realmente em como tudo vai funcionar.

Esses protótipos de baixa fidelidade serão importantes durante a fase de desenvolvimento das interfaces no frontend.

Pense em como será a interface tendo em conta a usabilidade da interface. Leve em consideração os requisitos colhidos para se manter fiel à necessidade do usuário e não à aparência somente.

O protótipo não precisa ser cheio de detalhes apenas deve indicar a direcção que deverá seguir durante o desenvolvimento do frontend.

# Desenvolvimento

Dê vida ao software. Mantenha-se fiel ao objectivo, não acrescente nada que não seja útil para o usuário.

## Frontend

Os protótipos de baixa fidelidade serão de especial utilidade nesta fase porque serão base para as interfaces que serão apresentadas ao usuário.

Mantendo-se fiel aos protótipos de baixa fidelidade, crie interfaces elegantes, simples e fáceis de usar.

## Backend

Depois de recolher os requisitos e criar protótipos de baixa fidelidade a esta altura deve já estar claro o que precisa ser desenvolvido.

Observando aos requisitos recolhidos crie serviços que forneçam o esperado e isso somente. Use as tarefas abaixo de cada requisito para guiar o seu desenvolvimento.

## Integração

Depois de desenvolver o frontend e backend nesta fase as duas partes serão integradas e se certificar de que funcionam muito bem juntas. Caso não funcionem conforme esperado os devidos ajustes devem ser feitos nesta fase.

# Validação

Neste momento o software já deve estar a todo vapor, mas antes de ir em produção deve ser validado.

1. Verificar se todos requisitos recolhidos são contemplados
2. Verificar se o software se comporta bem em diversos testes de uso normal

Se software passa os testes acima, então prossiga para próxima fase.

# Documentação

O sistema já está desenvolvido e completamente funcional, porém por questões de registro e organização o sistema deve ser documentado.

A documentação consiste em compilar num documento os requisitos recolhidos, os protótipos de baixa fidelidade e outros recursos que possam ter sido usados durante o desenvolvimento do software.

Crie uma pasta e coloque os ficheiros referentes ao projecto (ex: imagens, etc.s).

# Deploy

**Você está de parabéns por mais um sucesso 😀!**  
Se todas as etapas foram obedecidas correctamente então prossiga em efectuar o deploy da aplicação.
