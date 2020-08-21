Este documento reúne observações sobre o modelo de preenchimento dos relatórios de reporte de actividades ao meu supervisor/manager.

## Como preencher

Alguns campos que considero não precisarem de explicação alguma para o seu preenchimento foram deixados de lado, como é o caso do campo *Estado* (Concluído/Aberto).

| **Campo** | **Como preencher** | **Observações** |  
| :--- | :--- | :--- |
|**Actividade**| Preencher com requisito ou subtarefa do requisito. Ex: Criar mecanismo de busca de mensagens num intervalo de datas. | - |  
|**Objectivo**| Que problema esta funcionalidade irá resolver. Ex: Permitir que o usuário possa visualizar mensagens enviadas num dado período. | - |  
|**Dificuldades**| Quais dificuldades enfrentou? Seja específico e directo. Ex: Restringir que sejam apresentadas apenas mensagens enviadas no intervalo de datas fornecido. | - |  
|**Tentativas de resolução e resultados**| Explique o fez e não deu certo e o resultado que obteve disso. Ex: Usei a query ``` SELECT * FROM messages WHERE mo_ts BETWEEN '2020-08-01 00:00:00' AND '2020-08-15 15:20:15' ``` para realizar a pesquisa, onde as datas são substituídas com o input do usuário, no entanto o resultado desta query não incluí mensagens que enviadas no dia 01 de Agosto de 2020, como previsto. | - |  
|**Passos seguintes**| Ler a documentação sobre a função between no PostgreSQL para saber se ela é inclusiva ou exclusiva. | - |  

**Nota:** O exemplo é de mera ilustração.

## Checklist
- [ ] Preencher nome do autor.
- [ ] Preencher período de actividade.
- [ ] Adicionar código da actividade na worksheet de Legendas.
- [ ] Preencher o código do projecto.
- [ ] Preencher os campo referentes a cada tarefa seguindo as recomendações acima.
- [ ] Preencher devidamente o estado da actividade e a duração.
- [ ] Revisar o documento.
- [ ] Enviar.
