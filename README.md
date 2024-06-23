# Projeto Disciplina: Requisitos de Software

Olá! Este repositório faz parte do projeto da disciplina de Requisitos de Software da UTFPR - Campus Cornélio Procópio.

## 1. Introdução

### 1.1. Nome do Grupo

Grupo: **App Barber**
- Integrantes:
  - [Marcelo Augusto de Oliveira](https://github.com/marceloaugustooliveira)
  - [Renato de Matos Junior](https://github.com/renatomatosjr)
  - [Rodolfo Depieri Gindri](https://github.com/rodolfodepierigindri)
  - [Renan Gabriel Bueno](https://github.com/renangabrielbueno)

### 1.2. Nome do Sistema

Nome do Sistema: **Nova Era Barber Lounge**

### 1.3. Propósito do Sistema

Este documento apresenta os requisitos dos usuários a serem desenvolvidos pela **Nova Era Tecnologia**, fornecendo aos desenvolvedores as informações necessárias para o projeto e implementação, assim como para a realização dos testes e homologação do sistema.

O objetivo do sistema Nova Era Barber Lounge é revolucionar a experiência de agendamento e gestão de serviços em barbearias, integrando tecnologia de ponta para oferecer conveniência, segurança e qualidade aos clientes e estabelecimentos.

### 1.4. Público Alvo

Este documento se destina a homens de qualquer idade que buscam facilidade e praticidade na hora de cuidar da sua aparência, além dos proprietários e funcionários de barbearias.

### 1.5. Descrição dos usuários

Os usuários finais do sistema Nova Era Barber Lounge incluem:
- Clientes: Homens que desejam agendar serviços de barbearia.
- Proprietários e Funcionários de Barbearias: Responsáveis pela gestão dos agendamentos e prestação dos serviços.

[Anexo: Perfil do usuário](https://github.com/appbarbeiro/requisitos-software/blob/main/assets/tabela%20perfil%20do%20usuario.jpeg)

#### Personas:

[Anexo: Personas de usuário](https://github.com/appbarbeiro/requisitos-software/blob/main/assets/Personas.pdf)

### Cenários:

**Cenário: Antes**

Carlos é um cliente regular de um barbeiro chamado Miguel. Ele gosta de manter seu visual sempre impecável e costuma frequentar o salão de Miguel a cada duas semanas. No entanto, Carlos sempre enfrenta dificuldades ao tentar marcar um horário com Miguel. Eles usam o WhatsApp para essa comunicação, mas muitas vezes Miguel está ocupado cortando cabelos e não consegue responder imediatamente. Isso leva a atrasos na confirmação do horário, e Carlos fica frustrado por não conseguir agendar sua visita com antecedência. Além disso, quando finalmente consegue uma resposta de Miguel, pode acontecer de o horário desejado já estar ocupado, o que complica ainda mais a situação e aumenta a ansiedade de Carlos em garantir seu lugar na agenda do barbeiro.

**Cenário: Depois**

Lucas é outro cliente fiel de Miguel, o barbeiro. Ele sempre foi pontual em seus cortes de cabelo, mas enfrentava problemas para agendar horários devido à comunicação via WhatsApp. No entanto, recentemente, Miguel começou a utilizar um aplicativo chamado "App Barber", que permite aos clientes visualizar disponibilidade de horários e agendar suas visitas de forma simples e rápida, além de saber quais são as barbearias mais próximas da sua casa e seus melhores cortes. Agora, Lucas pode facilmente selecionar o horário desejado e confirmar sua reserva, tudo através do aplicativo, sem depender da disponibilidade de Miguel para responder mensagens. Isso não só tornou o processo de agendamento mais conveniente para Lucas, mas também para Miguel, que não precisa mais interromper seu trabalho para responder mensagens, e não precisa mais fazer agendas manuais, podendo focar melhor em atender seus clientes com excelência.

[Anexo: Cenários](https://github.com/appbarbeiro/requisitos-software/blob/main/assets/cenario.jpeg)

## 2. Documentos gerais no repositório

### 2.1. Requisitos de usuário

- Os clientes podem desmarcar ou trocar horários com até 24 horas de antecedência.
- Pagamento de taxa para desmarcar horário.
- Localização de barbearias próximas.
- Feedback dos clientes.
- Barberias verificadas.
- Fotos exemplificando cortes.
- Pagamento pelo site.

- Mais detalhes serão fornecidos posteriormente

### 2.2. Requisitos de sistema

- Interface intuitiva para clientes desmarcarem ou alterarem horários com 24 horas de antecedência.
- Funcionalidade para pagamento de taxa de desmarcação.
- Processamento seguro e eficaz de pagamentos.
- Verificação de barbearias cadastradas para autenticidade e qualidade.
- Exibição de selo de "barbearia verificada".
- Upload de fotos de cortes pelas barbearias.
- Visualização de fotos pelos clientes.
- Pagamento online integrado com sistema seguro.
  
### Requisitos Funcionais

| Identificador | Descrição                                        |
|---------------|--------------------------------------------------|
| RF01          | Barbeiro pode fazer login no aplicativo para gerenciar minha barbearia. |
| RF02          | Barbeiro pode adicionar informações sobre barbearia, como nome, endereço, horário de funcionamento e serviços oferecidos. |
| RF03          | Barbeiro pode adicionar fotos da barbearia para apresentar aos clientes em potencial. |
| RF04          | Barbeiro pode visualizar e gerenciar as reservas feitas pelos clientes. |
| RF05          | Cliente pode visualizar os horários disponíveis para reserva em uma barbearia. |
| RF06          | Cliente pode fazer uma reserva em um horário disponível em uma barbearia. |
| RF07          | Cliente pode cancelar uma reserva previamente feita. |
| RF08          | Cliente pode pagar pelas reservas feitas através do aplicativo. |
| RF09          | CLiente pode ver as avaliações e comentários de outras pessoas sobre uma barbearia. |
| RF10          | Cliente pode marcar como assinar um plano para uma barbearia que gostou para garantir reservas posteriormente. |

### Requisitos não Funcionais

| Identificador | Descrição                                        |
|---------------|--------------------------------------------------|
| RNF11	        | O aplicativo deve ser responsivo e rápido, com tempos de carregamento curtos e navegação fluida, mesmo em dispositivos móveis com recursos limitados.|
| RNF12	        | O sistema deve ser capaz de suportar um alto número de usuários simultâneos, garantindo estabilidade.|
| RNF13	        | A arquitetura do aplicativo deve ser escalável para acomodar um número crescente de usuários, serviços e barbearias sem afetar o desempenho ou a confiabilidade do sistema.|
| RNF14	        | O sistema deve ser resistente a ataques comuns, como injeção de SQL, malwares e phishing, para garantir a integridade das informações.|
| RNF15	        | A interface do aplicativo deve ser intuitiva e fácil de usar, tanto para barbeiros quanto para clientes, com navegação clara, menus organizados e ícones explicativos.|
| RNF16	        | O aplicativo deve ser acessível a pessoas com deficiências, seguindo as diretrizes de acessibilidade.|
| RNF17	        | O sistema deve ser capaz de se adaptar a novas demandas e funcionalidades, garantindo flexibilidade e agilidade no desenvolvimento.|
| RNF18	        | O sistema deve ter mecanismos de backup para garantir que, em caso de problemas técnicos, os dados sejam preservados.|
| RNF19	        | O código fonte deve ser bem estruturado, documentado e modular, facilitando a compreensão, modificação e manutenção do sistema.|
| RNF20	        | O aplicativo deve ser atualizado regularmente, para garantir que atenda às necessidades dos usuários e acompanhe as tendências do mercado.|


### Histórias de usuários

| Identificador | Descrição |
|---------------|--------------------------------------------------|
| 1 | Como barbeiro, quero adicionar informações sobre minha barbearia, como nome, endereço e horário de funcionamento. |
| 2 | Como barbeiro, quero adicionar fotos da minha barbearia para mostrar aos clientes o ambiente e os serviços que ofereço. |
| 3 | Como barbeiro, quero visualizar e gerenciar as reservas feitas pelos clientes, para que eu possa me organizar e atender a todos com eficiência. |
| 4 | Como barbeiro, quero receber notificações quando um cliente fizer uma reserva, para que eu possa confirmar a reserva e me preparar para o atendimento. |
| 5 | Como barbeiro, quero analisar as avaliações e comentários dos clientes para que eu possa melhorar meus serviços e a experiência dos clientes. |
| 6 | Como cliente, quero encontrar barbearias perto de mim e ver informações sobre elas, como nome, endereço, horário de funcionamento, fotos e avaliações. |
| 7 | Como cliente, quero visualizar os horários disponíveis para reserva em uma barbearia e escolher o horário que melhor me atender. |
| 8 | Como cliente, quero pagar pela minha reserva online com segurança e tranquilidade, utilizando diferentes formas de pagamento. |
| 9 | Como cliente, quero cancelar ou reagendar minha reserva online, caso precise fazer alguma alteração. |
| 10 | Como cliente, quero assinar um plano de fidelidade para uma barbearia que eu gosto e ter acesso a descontos e benefícios exclusivos. |

### 2.3. Protótipos

- [Site: Protótipo em HTML](https://appbarbeiro.github.io/requisitos-software/)
- [Protótipo para inserir no NinjaMock](https://drive.google.com/drive/folders/1hG6ZIEAQV1bZO6faVGajxqtPyz5OWqdm?usp=sharing)
- [Site com banco de dados](https://shavee.shop/)

### 2.4. Diagramas

- [Anexo: Diagramas](https://github.com/appbarbeiro/requisitos-software/blob/main/diagramas/)

## Referências

Ainda não disponíveis.

---

### Objetivo do Sistema:

O Nova Era Barber Lounge tem como objetivo simplificar o processo de agendamento de serviços de barbearia, proporcionando aos clientes uma plataforma fácil de usar para marcar, desmarcar e alterar horários com facilidade. Além disso, o sistema visa promover a confiança dos clientes, fornecendo informações sobre barbearias verificadas e exemplificando os serviços oferecidos através de fotos de cortes disponíveis. A integração de um sistema de pagamento seguro permite uma transição suave do agendamento para o pagamento, garantindo conveniência e segurança em todo o processo.

Com este projeto, esperamos modernizar a indústria das barbearias, proporcionando uma experiência digitalizada que atenda às necessidades dos clientes e dos estabelecimentos, ao mesmo tempo em que simplifica a gestão operacional para os proprietários das barbearias.

Este documento de requisitos de software fornecerá a base necessária para o desenvolvimento, implementação, teste e homologação do sistema, garantindo que atenda às expectativas dos usuários e cumpra seu propósito de forma eficaz.

--- 
