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
