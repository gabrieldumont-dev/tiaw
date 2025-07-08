# Especificações Do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Contexto.md"> Documentação de Contexto</a></span>

> Apresente uma visão geral do que será abordado nesta parte do
> documento, enumerando as técnicas e/ou ferramentas utilizadas para
> realizar a especificações do projeto

## Personas

João Silva tem 28 anos, é analista de TI e disciplinado. Busca melhorar seu físico e saúde. Usa apps de treino, smartwatch e Spotify para acompanhar e registrar seu desempenho. Valoriza sistemas organizados, com recomendações e gráficos que mostrem sua evolução.

Ana Pereira tem 35 anos, é personal trainer e muito comunicativa. Usa tablet, cronômetro e planilhas digitais para organizar os treinos dos alunos. Trabalha no estúdio e na academia, sempre focada em facilitar o acompanhamento e engajamento dos alunos. Busca ferramentas que economizem tempo e ajudem na gestão eficiente dos treinos.

Carlos Mendes tem 42 anos, é dono de academias e muito estratégico. Usa softwares de gestão e redes sociais para organizar processos e divulgar o negócio. Trabalha no escritório da academia, acompanhando métricas e relatórios. Busca soluções que otimizem a operação e destaquem sua academia no mercado.


> Enumere e detalhe as personas da sua solução. Para
> tanto, baseie-se tanto nos documentos disponibilizados na disciplina
> e/ou nos seguintes links:
>
> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
> Lembre-se que você deve ser enumerar e descrever precisamente e
> personalizada todos os clientes ideais que sua solução almeja.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

Como usuário iniciante, quero criar um perfil com meus dados físicos e objetivos,
para que o aplicativo possa me sugerir treinos adequados ao meu nível e metas.

Como usuário regular, quero montar meus próprios treinos escolhendo os exercícios,
repetições e dias da semana, para seguir uma rotina que funcione para mim.

Como usuário sem experiência, quero receber sugestões de treinos automáticas
baseadas no meu perfil, para começar a treinar mesmo sem muito conhecimento.

Como usuário ativo, quero acompanhar minha evolução ao longo do tempo através
de gráficos e relatórios, para entender meu progresso e ajustar meus objetivos.

Como usuário que busca emagrecimento, quero saber quantas calorias estou
gastando nos treinos, para acompanhar meu déficit calórico diário.

Como usuário com rotina corrida, quero receber lembretes de treino nos dias e
horários programados, para não esquecer de me exercitar.

Como usuário com pouca experiência em tecnologia, quero navegar com facilidade
pelo aplicativo, para que eu possa usar todas as funções sem dificuldade.

Como usuário em evolução, quero atualizar meus objetivos sempre que necessário,
para que o app continue adaptando meus treinos ao meu progresso.
>
> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

RF01. O sistema deve permitir o cadastro de usuários com informações pessoais e
objetivos físicos.

RF02. O sistema deve permitir que o usuário crie, edite e salve seus próprios treinos.

RF03. O sistema deve exibir o histórico de treinos e desempenho do usuário em
forma de gráficos e relatórios.

RF04. O sistema deve calcular e exibir a estimativa de calorias gastas em cada sessão
de treino.

RF05. O sistema deve enviar lembretes de treino nos dias e horários definidos pelo
usuário.

RF06. O sistema deve permitir a alteração de metas e dados físicos do usuário.


### Requisitos não Funcionais

RNF01. A interface do sistema deve ser responsiva, adaptando-se a dispositivos
móveis e desktops.

RNF02. O sistema deve apresentar uma navegação simples e intuitiva para usuários
com diferentes níveis de familiaridade com tecnologia.

RNF03. O sistema deve garantir a segurança dos dados do usuário, incluindo uso de
criptografia em senhas e informações sensíveis.

RNF04. O sistema deve ter tempo de resposta inferior a 2 segundos para todas as
principais funcionalidades.

RNF05. O sistema deve estar disponível para uso em, no mínimo, 99% do tempo (alta
disponibilidade).

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


> Enumere as restrições à sua solução. Lembre-se de que as restrições
> geralmente limitam a solução candidata.
> 
> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)
