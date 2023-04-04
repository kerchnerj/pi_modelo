# Projeto Integrador - Modelo

Um modelo para o desenvolvimento do Projeto Integrador do Curso de Técnico em Desenvolvimento de Sistemas para a Internet Integrado ao Ensino Médio do IFC - Campus Araquari.

Professores: [Marco André Mendes](github.com/marcoandre) e [Alann Perini](https://github.com/AlannKPerini).

Links do projeto:

-   [Documentação (esse documento)](github.com/marcoandre/pi-modelo)
-   [Backend](github.com/marcoandre/pi-backend)
-   [Frontend](github.com/marcoandre/pi-frontend)

# Como usar esse modelo para o Projeto Integrador

1. Faça um fork desse repositório para a sua conta do GitHub.
2. Clone o repositório para o seu computador.
3. Abra o arquivo README.md no seu editor de texto favorito (recomendamos o [Visual Studio Code](https://code.visualstudio.com/)).
4. Tenha instalada a extensão [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) no seu editor de texto.
5. Edite o arquivo README.md com as informações do seu projeto.

# Desenvolvimento

-   As equipes serão avaliadas por cada etapa da documentação e entregas realizadas.
-   Cada equipe deverá escolher um sistema para o desenvolvimento das atividades, a partir dos modelos apresentados.

# Modelos de Sistemas

**Nessa parte a equipe deve escolher um dos modelos de sistemas para desenvolver o projeto. Ao escolher, escreva uma breve descrição do sistema e o motivo da escolha e pode apagar os outros modelos.**

## 1- Ponto de Vendas (PDV)

**Gerenciamento de vendas para uma padaria**

O nosso cliente, Sr. Genival, tem uma padaria de bairro chamada padaria Pão Genial e, devido a qualidade de seus produtos, ela está crescendo rapidamente. Recentemente, ele contratou mais funcionários para atendimento, caixa, panificação, etc.
Assim, atualmente, ele consegue concentrar seus esforços para melhorar a gestão da padaria. Para isso, ele quer instalar um sistema de controle de vendas que permita ao caixa lançar as vendas realizadas. Como sua intenção
é melhorar a gestão do negócio, é muito importante que ele consiga ter
relatórios, como por exemplo, de vendas.

# Situação Problema

Gerenciamento de uma Clínica de Estética 

A Sra. Isabela, nossa cliente, depois de se aprimorar em seu curso de estética resolveu abrir sua própria clínica. Nos dias atuais Isabela usa uma planilha no excel para controle de vendas e faturamento. Seus procedimentos, valores, pacotes e promoções são apresentados em folhetos de papel o que acaba gerando uma desorganização. Para marcar o procedimento, é feito por whatsapp ou telefone, e após a confirmação do cliente será agendado no papel. 
O pagamento é feito diretamente na empresa, podendo ser cartão, pix ou dinheiro. Seu relatório de faturamento semanal é feito manualmente.
Ela viu a necessidade de um software que auxilie em seu trabalho, para facilitar a comunicação com seus clientes e melhorar a organização de seus funcionários. 
Para isso, ela deseja um sistema que gerencie os clientes, pacotes, procedimentos e relatório de faturamento.

# Descrição da proposta

O software será de fácil acesso para clientes e administradores, aos clientes será disponibilizado um bom parâmetro para conhecer e se interessar pelo trabalho realizado na clínica. Aos administradores (Dona e gerente, pois demais funcionários não terão acesso), o controle de vendas, relatório de faturamento,acesso e cadastros.
Para marcar um procedimento será disponibilizado um link de direcionamento para contato com a clínica, em que procedimentos, pacotes e algumas perguntas padrão serão apresentadas, após a confirmação do cliente, automaticamente será agendado no software e o cliente receberá um e-mail de confirmação. Ou o cliente tem a opção de entrar em contato diretamente pelo telefone e o administrador irá registrar o procedimento no software.
Depois que o procedimento é realizado, é disponibilizado um link de pagamento (pix,cartão débito ou crédito) onde o software irá confirmar o pagamento para a clínica e irá registrar no relatório de faturamento.

#  Regras de negócio

RN01- Para fazer o agendamento é necessário os dados do cliente e o procedimento no horário disponível.
RN02 - Se o cliente não comparecer o horário ficará vago para encaixe.
RN03- Para a confirmação do comparecimento do cliente, o sistema irá mandar uma mensagem no whatsapp um dia antes do procedimento.
RN04- Cadastros de Cliente: Atualmente somente os administradores cadastram clientes.
RN05 - Cadastro de procedimentos: Todos os funcionários têm permissão para cadastrar procedimentos estéticos. 
RN06- Pagamento do procedimento: Após ser feito o procedimento é feito o pagamento.
RN07- Relatório de Fluxo de Caixa: O relatório de fluxo de caixa será permitido somente para o administrador.
RN08- Relatório de faturamento: Somente os administradores acessam os itens de faturamento. 
RN09- Relatório de Procedimento: O sistema deverá emitir um relatório semanal/mensal de procedimentos.
 
