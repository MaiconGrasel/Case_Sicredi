# Case Sicredi - Projeto Orçamento Fácil

Repositorio para compartilhamento do case técnico do processo seletivo para o programa Sicredi Desenvolve Tech 2021<br>
Tema: “Construir juntos uma sociedade mais próspera através da tecnologia”

## Descrição do Projeto
<p align="left">O projeto visa inserir novas funcionalidades ao já existente App Sicredi usado pelos associados.<br>
Além de ferramentas para o controle das finanças, conteúdos sobre educação financeira desenvolvidos pela equipe da Cooperativa estarão a disposição do associado, diretamente ao acessar sua conta via App.<br>

Nesta ferramenta, o associado terá a capacidade de categorizar suas entradas e despesas, para a geração de mostradores gráficos (pizza/barras...) do andamento de suas finanças.<br>
Poderá também, definir suas metas/montantes de investimento, integrando as soluções ja oferecidas pela cooperativa em um só lugar, como poupança, fundos de investimentos, programando os aportes automáticos conforme sua necessidade/realidade, e também terá a possibilidade de definir montantes para doação, destinado aos programas socias da Cooperativa, ou a entidades de cunho social.
<br>A ferramenta deve ser intuitiva, e de fácil uso, porém para humanizar e aproximar a Cooperativa de seus associados, dentro do módulo é possível acessar (ou ser direcionado à) vídeos de explicação do uso da mesma e de educação financeira. Estes vídeos, seriam "apresentados" pelos gerentes de contas, onde cada associado terá acesso ao seu gerente de conta, lhe fornecendo tais informações. Esta abordagem visa humanizar o atendimento, e estreitar os laços entre os associados a instituição;
  
<br>Inicialmente, o módulo conta com 3 níveis distintos de operação, que se validados podem ter tarifas de adesão distintas conforme demanda para seu funcionamento. A precificação não será tratada neste projeto, porém será abordada a ideia de que o primeiro nivel é  gratuito, garantindo o acesso a ferramenta a todos os associados.
<br>O acesso aos niveis mais elevados do módulo também pode ser realizado de forma gratuita, via resgate de pontos no programa Juntos.
<br>Para associados que definirem montantes destinados a doação, há redução ou amortização das taxas do módulo.

<br>Nivel 1 - Gratuito
<br>Ao aderir ao modulo, o associado tem acesso a um orçamento padrão, pré estabelecido pela equipe da Cooperativa.
<br>Exemplo:
Orçamento 60 20 10 5 5, onde:
<br>60% - Configuram o teto das despesas fixas do mês
<br>20% - Parcela do orçamento destinada a investimentos de liquidez rapida, reserva de emergencia...
<br>10% - Parcela do orçamento livre, podendo ser usada para compras, lazer...
<br>5%   - Parcela do orçãmento destinada a investimentos de longo prazo, como previdência privada.
<br>5%   - Parcela do orçamento destinada a doação. 

<br>Este padrão serve como exemplo, podendo o associado alterar todas as porcentagens e destinações de saldo conforme a sua necessidade/realidade.
<br>Tem acesso também, aos vídeos de seu gerente explicando a funcionalidade da ferramenta, e dando dicas de como montar um orçamento familiar. 

<br>Nivel 2 - $
<br>Possui todas as funções do Nivel 1, e adiciona um canal de comunicação com o seu gerente, para que este possa guiar o associado na criação e elaboração deste orçamento de acordo com a realidade do mesmo.
<br>Este atendimento é agendado no momento da adesão ao módulo, e pode ser realizado presencialmente na agencia, ou via video-chamada (Inicialmente, utilizando ferramentas como Google Meet e/ou WhatsApp. 
<br>Após a evolução do módulo, o atendimento aconteceria dentro do próprio App Sicredi)

<br>Nivel 3 - $$
<br>Possui todas as funcões dos niveis 1 e 2 , e adiciona uma analise mais apurada da conta pela instituição, podendo consultar histórico de movimentações por um especialista financeiro, para que seja criado o orçamento ideal para o cliente.
<br>Nesta modalidade, toda a configuração do módulo é realizada pela Cooperativa após aprovação do cliente. 

<br>Todos os niveis - 

<br>Categorização de debitos:
<br>Cada operação de débito da conta, dispara uma notificação no app do associado, onde ele pode selecionar a qual categoria de despesa esta se refere. Este sistema seria o responsável para a geração dos graficos que irão apresentar a saúde da conta ao associado. 
<br>O sistema ja contará com categorias pré-estabelecidas, como Aluguel, Mercado, Conta de Energia (despesas padrão), além de categorias personalizaveis, que o associado pode designar conforme preferir.

<br>Categorização de créditos:
<br>Similar aos débitos, créditos em conta também disparam uma notificação e passam por uma categorização, dando ao associado um extrato totalmente personalizável de suas movimentações financeiras. 
<br>Operações de crédito também possuem categorias pré-definidas, como Salário, Benefício... além de categorias personalizaveis.

</p>

## Objetivo

Auxiliar os associados a obterem uma boa educação financeira, e consequentemente, mais tranquilidade a cada mês.

#### Features

- [ ] Controle do orçamento, com planos desenvolvidos por especialistas em finanças da Cooperativa
- [ ] Controle do orçamento pessoal customizavel
- [ ] Mostrador gráfico da saúde da conta
- [ ] Acesso a Materiais de educação financeira
- [ ] Categorização de créditos e débitos
- [ ] Atendimento Online Personalizado 
- [ ] Atendimento Online em tempo real
- [ ] Automatização de investimentos
- [ ] Automatização de Doações para Entidades Sociais


### Roadmap

- [ ] Aprovaçaõ do projeto;
- [ ] Validação dos 3 niveis de atendimento propostos, e elaboração de sua precificação;
- [ ] Definição de orçamentos, débitos e créditos padrões por parte de equipe com expertise financeira da Cooperativa;
- [ ] Fase inicial do desenvolvimento da solução, trazendo as seguintes funcionalidades para um ambiente de testes:
    <br>Configuração do orçamento;
		<br>Categorização de débitos;
		<br>Categorização de créditos;
		<br>Apresentação dos gráficos;
		<br>Agendamento dos aportes automáticos(investimentos, doações);
- [ ] Após protótipo inicial passar nos testes, elaboração de documentação de uso da ferramenta;
- [ ] Apresentação da documentação e treinamento do uso da ferramenta aos gerentes de conta;
- [ ] Criação dos materiais personalizados (Videos onde os gerentes de conta explicam a funcionalidade da ferramenta aos associados)
- [ ] Desenvolvimento da Api Consulta_Conteudo, responsável por proporcionar a cada associado, os conteúdos gerados pelo seu gerente de conta diretamente no App Sicredi;
- [ ] Desenvolvimento da Api Agenda_Atendimento, responsável por agendar data e horário de atendimento personalizado online. Esta API precisará ser integrada ao Google Agenda ou outra solução solução de gestão de tempo;
- [ ] Preparação da equipe de gerentes para o atendimento remoto/online, provendo-lhes:
  <br>Computador, Webcam, microfone e fone de ouvido para atendimento online;
	<br>Treinamento no uso da plataforma escolhida para atendimento (Inicialmente, Google Meets e WhatsApp);
- [ ] Criação do banco de dados das instituições amparadas pela cooperativa, gerando a lista de instituições para as quais os associados podem direcionar doações;
- [ ] Criação de novo produto para resgate no programa Juntos. (Isenção da tarifa Orçamento Fácil)
- [ ] Faze final dos testes de validação e usabilidade em todos os módulos e funcionalidade do projeto;
- [ ] Lançamento da ferramenta no App Sicredi.

