# Conhecendo o SCRUM

## Retrospective Meeting

O último timebox dentro de uma Sprint é o que chamamos de reunião de Retrospectiva. Em toda Sprint, problemas acontecem e sempre temos como crescer e melhorar. Para isso, contudo, é necessário parar e pensar em o que foi legal, para mantermos, e no que não foi bom, para mudarmos.

A ideia de uma Retrospectiva é pôr em prática o conceito de **melhoria contínua**. Nessa reunião, o time todo (PO, Scrum Master e Desenvolvedores) se foca em descobrir como melhorar ainda mais o time, o processo e o projeto já na próxima Sprint.

Há diversas mecânicas para essa reunião. Para saber mais sobre elas, você sempre pode olhar referências como o blog [Fun Retrospectives](https://www.funretrospectives.com/) ou a [Retrospectives Wiki](http://retrospectivewiki.org/). Aqui, vamos mostrar um modelo básico e bastante utilizado.
Nesse modelo, levantaremos pontos positivos e negativos da Sprint anterior, para aprendermos com ela. Costumamos fazer isso em silêncio, para que cada um dê a própria opinião, sem enviesar os outros.

Para os pontos negativos, buscamos entender o que aconteceu para causá-los, claro, mas mais importante do que isso, definimos ações de melhoria para que tais problemas sejam evitados (ou reduzidos) no futuro.

Similarmente, analisamos os pontos positivos e, se o time sentir necessidade, definimos também lembretes para os pontos que ainda não viraram rotina.
É comum também que durante a retrospectiva, discutam-se também os itens da retrospectiva anterior, com o objetivo de validar se os problemas se repetiram e se as ações anteriores deram o efeito esperado.

Ao final da reunião, o time possui uma lista de **ações** a fazer na próxima Sprint. Essa lista deve ficar visível durante o andamento da próxima Sprint, para que o time se relembre delas.

### Ações

É importante também notar que a lista de itens a fazer que sai de uma retrospectiva contém apenas **ações**, isto é, atividades que membros do time vão efetivamente fazer para obter algum resultado.

Note que o time não pode decidir que o cliente vá mudar seu comportamento ou que outra área da empresa vá passar a ajudá-los. Essas não são ações, são desejos de que algo magicamente vá mudar. No mundo da agilidade, isso é frequentemente chamado de wishful thinking.

Ações, por outro lado, envolvem os membros do time. Se o problema em questão é que o cliente desaparece e não conseguimos tirar dúvidas com eles:

    * desejo: o cliente vai entender a importância de estar presente
    * uma ação: o Scrum Master vai explicar as perdas e ganhos de uma maior participação do cliente
    * outra ação: em toda história daqui para a frente, haverá também o contato de quem pode sanar dúvidas dos desenvolvedores desse item em particular.

O resultado de uma retrospectiva é uma lista, preferencialmente curta, de ações que serão tomadas durante o próximo Sprint para melhorar ainda mais o time e o andamento do projeto.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Daily Scrum

No capítulo de Retrospectiva você aprendeu sobre essa importante ferramenta para promover melhoria contínua, mas esperar o fim da Sprint para resolver probleminhas do dia-a-dia seria um grande desperdício de tempo.

Para resolver obstáculos do dia-a-dia e para todos saberem como está o andamento das tarefas e histórias nessa Sprint, o Scrum tem ainda mais uma cerimônia. Todos os dias, **no mesmo horário e no mesmo local**, a equipe se reúne para responder 3 perguntas simples:

	* O que fiz desde o último Daily Scrum?
	* O que pretendo fazer até o próximo?
	* Quais problemas me atrapalharam?

O timebox para essa reunião é de apenas 15 minutos por dia e, como qualquer outro timebox, deve ser respeitado. Para isso, é importante lembrar que essa é uma reunião expositiva: o objetivo aqui não é resolver o problema, mas sim apontá-lo. Se alguém souber como ajudar, apenas indica que sabe e **após o fim do Daily** os interessados se reúnem para conversar.

Há uma divergência de opiniões sobre quem deve estar presente nessa reunião. O Scrum Guide aponta que os desenvolvedores respondem as perguntas e o Scrum Master apenas assiste a reunião, eximindo a participação do P.O.

Na prática, vemos uma real vantagem em ter o P.O. presente nessa reunião, já que ele precisa saber do andamento da Sprint, entender os problemas que estão desacelerando desenvolvedores e ainda ajudar a alterar o plano de ação, se o time estiver atrasado. Assim, recomendamos fortemente que o P.O. esteja, sim, presente nessa reunião.
Com o Daily Scrum, o time evita com que problemas durem muitos dias e que desenvolvedores façam trabalhos repetidos - tanto trabalhando sobre uma mesma feature, quanto sofrendo para resolver um problema que outro sabe solucionar.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Product e Sprint Backlogs

 O P.O. deve chegar à reunião de Planning com o topo do Product Backlog devidamente atualizado, isto é, com os itens mais relevantes para o negócio, já granulares o bastante para caber no Sprint. Falamos também que sairemos de cada Planning Meeting com um Sprint Backlog. Faltou, no entanto, estudarmos mais a fundo o que é o Product e os Sprint Backlogs e quais regras do Scrum se aplicam a eles.

### Product Backlog

Assim que imaginamos um projeto, já temos uma lista de funcionalidades que gostaríamos de ter nele! Essa lista é frequentemente usada para decidir se o projeto realmente será desenvolvido e, quando vamos começar a transformar esses desejos em realidade é importante fazê-lo de forma consciente, para maximizar o valor produzido a cada interação.

O Product Backlog, a lista ordenada de itens a serem feitos no projeto, é o artefato que ajuda o P.O. a manter todos esses pedidos organizados. O P.O. é responsável por mantê-lo atualizado e priorizado de modo a agregarmos o máximo de valor possível para o cliente a cada iteração.

Embora clientes, usuários e o próprio time tenham a liberdade de influenciar mudanças no Product Backlog, a única pessoa que de fato o altera é o Product Owner -- inclusive, o papel é chamado dessa forma porque o P.O. é dono do Product Backlog! Os itens do Product Backlog são sempre mutáveis: o P.O. pode adicionar itens, removê-los e re-priorizá-los sempre que achar que consegue agregar mais valor ao projeto dessa forma.

A proposta do Product Backlog é, também, que evitemos colocar trabalho em itens pouco importantes ou que sequer sabemos se serão feitos: os itens mais prioritários de um backlog têm que ter sua importância de negócio estudada e ser pequenos o bastante para que o time estime e os aloque em Sprints, mas os mais distantes e menos prioritários podem permanecer em blocos maiores e mais grosseiros, que serão refinados conforme sua prioridade cresce.

### Sprint Backlog

Uma vez que itens cheguem ao topo do Product Backlog, eles serão discutidos em uma Planning Meeting, quebrados em alguns sub-itens técnicos e, se escolhidos para serem executados, esses itens e sub-itens comporão o chamado Sprint Backlog: a lista ordenada de itens funcionais e seus sub-itens técnicos que serão feitos durante essa Sprint.

Diferente do Product Backlog, apenas o time pode influenciar e alterar o Sprint Backlog. Existe uma razão para isso: o Sprint Backlog é formado dos itens mais prioritários do Product Backlog e é uma indicação séria de problemas sistêmicos se os itens mais prioritários precisarem sofrer grandes modificações. Se os itens mais prioritários não fizerem sentido nas, digamos, 2 semanas de Sprint, isso indica que o P.O. não fez um bom trabalho de refinamento e de descobrir com usuários o que eles realmente precisam.

### Histórias e tarefas

Cada item que compõe um Product Backlog representa uma funcionalidade, algo que agrega valor para o usuário final -- note, portanto, que "documentação técnica" não é um item válido, já que o usuário não se beneficia disso.

Esses itens podem ter o formato que você quiser -- por exemplo, um conjuntinho de casos de uso do sistema pode ser um item válido. Há uma forte preferência entre agilistas, no entanto, de usar um formato especial para representar esses itens: uma história de usuário (user story).

Uma história é um formato criado em eXtreme Programming (XP) para representar um item que agrega valor a usuários e agrega, de uma forma bastante simples, três informações importantíssimas para a priorização e posterior desenvolvimento da funcionalidade: por que é importante, para quem é importante e, só então, o que a pessoa quer, em si. O modelo que costumamos preencher é o seguinte:

    [TÍTULO]**Para...**
    [por que o pedido é importante]**No papel de...**
    [para quem é importante]**Quero...** 
    [o pedido em si]

Em um sistema de vagas online como o OndeTrabalhar.com, por exemplo, poderíamos ter a história:

            VAGAS POR LOCALIDADE
    **Para...** não perder tempo olhando cada vaga para descobrir se é na minha cidade
    **No papel de...** pessoa procurando trabalho
    **Quero...** ter a opção de filtrar as vagas de trabalho por cidade

Durante o Planning é comum verificarmos o entendimento da história quebrando-a em itens menores, técnicos, que não necessariamente agregam valor ao usuário individualmente. Esses sub-itens técnicos de histórias são chamados tarefas. A história acima poderia ser quebrada nas seguintes tarefas:

		* Cadastro de cidades no banco de dados;
		* Mudança no formulário de postagem de vaga para limitar à lista de cidades;
		* Filtro de busca de vagas no menu principal.

Muito comumente também, embora não seja regra, é vermos histórias em cartões (fichas pautadas) e tarefas em post-its.

---------------------------------------------------------------------------------------------------------------------------------------------------------------

## Scrum Master

### Papéis: Scrum Master
Assim como o Product Owner, há outro papel que é executado por uma pessoa: o de Scrum Master. Enquanto o P.O. foca no produto a ser desenvolvido e em atender as necessidades do cliente, a função principal do Scrum Master é focar no processo e se assegurar que o time esteja tirando o maior proveito possível dele.

Como o próprio nome diz, a pessoa que tem o papel de Scrum Master tem que entender muito bem o Scrum e ser capaz de passar isso para todos os envolvidos no projeto: desenvolvedores, Product Owner, clientes e a própria organização na qual o time está inserido.

O Scrum Master **não é**, contudo, chefe do time e não deve agir como tal. Um bom Scrum Master é um facilitador e coach excelente, que atua como Líder Servidor, isto é, livrando o time dos problemas que o impede de ter uma melhor performance.

### O dia-a-dia de um Scrum Master
Durante o andamento do projeto que usa Scrum, o Scrum Master deve:

		* Facilitar as reuniões, quando necessário;
		* Atentar para o cumprimento dos time-boxes e explicar o porquê deles;
		* Educar desenvolvedores, product owner e clientes sobre o processo;
		* Remover ou reduzir impedimentos (não problemas!);
		* Buscar continuamente ferramentas para ajudar o time a evoluir.
		* E no que pode estar impedindo o time de melhorar sua performance.

### Evolução do papel
Note que performance é um termo muito mais abrangente que produtividade. Produzir vários incrementos é interessante, claro, mas a performance do time está, também, em decidir quais funcionalidades agregam mais valor, em evitar reuniões desnecessárias, em melhorar a qualidade da comunicação, etc.

### Problemas e Impedimentos
Há uma enorme confusão em implantações do Scrum pelo mundo sobre o que é um problema e o que é um impedimento. O mau entendimento da diferença entre eles faz com que diversos Scrum Masters se comportem mais como babás de times do que deveriam - e isso também prejudica a evolução do time.

Como Scrum Master, portanto, é importante que você deixe claro para o time a diferença entre um problema e um impedimento.

Tudo o que atrapalha o time, interno ou externo, é considerado um **problema** do time e, como tal, é responsabilidade do próprio time (qualquer membro, não apenas o Scrum Master!) resolvê-lo.

Se o time tentou resolver o problema **e não conseguiu**, isso pode ser considerado um Impedimento.

Assim, lembre-se que Scrum Master não é a pessoa que vai resolver problemas técnicos (ele nem precisa ser técnico!) ou cotidianos ("Acabou o café!"). O time deve trabalhar junto para resolver esses problemas.

Você, Scrum Master, evite acostumar mal o time: isso pode tirar o senso de responsabilidade das pessoas e você pode acabar se tornando uma muleta.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Product Owner

### Papéis:  (P.O.)
Agora que já vimos os timeboxes e artefatos do Scrum, também já falamos um bocado da atuação de cada um dos três papéis que pessoas desenvolvem no Scrum. Nessa e nas próximas sessões, faremos uma grande revisão e consolidação do conhecimento já visto até agora, focando nos papéis do Scrum.

Certamente, o papel mais comentado nas sessões anteriores é o do Product Owner. Essa terminologia é bastante expressiva e, até por isso, acabou sendo utilizada informalmente mesmo em equipes que não trabalham com Scrum, mas cuidado para não entendê-la errado: quando trabalhamos com métodos ágeis o time todo se sente responsável pelo produto que está sendo produzido e o cliente se interessa por ele, portanto a palavra Owner do nome do papel não exime o resto do time dessa responsabilidade. O P.O. é, no entanto, o dono do Product Backlog.

### O dia-a-dia de um Product Owner
Durante o andamento do projeto que usa Scrum, o Product Owner (P.O.) deve:

	* participar das reuniões;
	* responder dúvidas dos desenvolvedores sobre histórias ou indicar quem poderia respondê-las melhor;
	* deixar claro para o time qual o valor de negócios de cada Sprint;
	* obter feedback e expectativas dos diversos clientes e extrair delas as necessidades;
	* MANTER O PRODUCT BACKLOG ATUALIZADO, isto é:
	* adicionar itens novos;
	* remover itens desatualizados;
	* revisar a priorização do backlog constantemente;
	* refinar histórias mais importantes em preparação para o próximo Planning.

### Refinamento do backlog
Uma dúvida frequente é o que o P.O. faz durante a maior parte da Sprint, quando os desenvolvedores estão trabalhando em incrementos de software. Há várias atividades listadas acima que tornam a disponibilidade diária do P.O. como para tirar dúvidas, repriorizar o Sprint backlog conforme necessidade, etc. Conforme o time amadurece e aprende a lidar consigo mesmo e com a organização, no entanto, é comum que esses trabalhos diminuam consideravelmente.

Algo que não diminui tanto, contudo, é o refinamento do topo do Product Backlog.

Vimos que, para que o planejamento de uma Sprint caiba nos 5% da duração da Sprint, é preciso que o P.O. saiba explicar histórias e que elas estejam em uma granularidade (tamanho) adequado para desenvolvedores conseguirem estimá-las. Portanto, para o próximo Planning correr bem, o P.O. já começa a se preparar para a reunião refinando os itens mais prioritários do Product Backlog, isto é, quebrando eles nas menores histórias possíveis e fazendo perguntas relevantes aos clientes.

Pense que a segunda história mais importante de nosso Backlog é a seguinte:

                        Opção de boleto
    **Para...**atender aos pedidos de 15 pessoas que foram na conferência ano passado
    **No papel de...**organização da Agile Brazil
    **Quero...**oferecer a opção de pagamento em boleto no site e controlar as inscrições feitas com essa forma de pagamento no sistema.
	
Essa simples história já poderia ser quebrada em pelo menos duas menores, que individualmente já agregam valor para papéis diferentes e nem mesmo precisam ser feitos no mesmo Sprint!

                        Inscrição em boleto
    **Para...** conseguir pagar minha inscrição no caixa eletrônico do meu banco
    **No papel de...** participante da Agile Brazil
    **Quero...** escolher pagar minha inscrição em boleto e emití-lo direto da próxima página

E, também:
						Pagamentos de boleto
    **Para...** não vender mais ingressos do que devia, nem menos do que podia
    **No papel de...** organizador da Agile Brazil
    **Quero...** reservar vagas na conferência quando alguém gerar um boleto e, ou criar a inscrição quando receber a confirmação do pagamento do gateway, ou abrir a vaga para vendas novamente, quando o boleto vencer sem ser pago.
	
Note que, graças ao refinamento, foi preciso perguntar melhor os porquês daquela história original e o que exatamente está sendo pedido. Assim, será mais fácil gerenciar essas histórias no Planning Meeting que está por vir.

### Uma pessoa só!
Outra informação importante sobre o P.O. é que ele é **uma pessoa, não um comitê**. A razão para isso é bastante simples: o time precisa saber quem está no comando do que será feito e, se tivéssemos diversos P.O.s correríamos um maior risco de informações conflitantes atrapalharem o time.

Assim, consideramos essas várias pessoas como clientes e tanto elas quanto o time podem influenciar o P.O., mas a palavra final e o plano de como maximizar o valor entregue pelo time é do Product Owner.
