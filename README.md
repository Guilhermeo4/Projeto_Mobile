# Histórias de usuários
# Funcionalidades: Sistema de Reservas de Áreas Comuns (ASCIJA)

---

## História 1: Autenticação (Login)

**Como um morador**  
Eu quero acessar o sistema com meu e-mail e senha  
Para gerenciar minhas reservas  

### Cenário 1: Login com sucesso
Dado que estou na tela de login  
E informo um e-mail válido  
E informo uma senha correta  
Quando clico em “Acessar”  
Então devo ser redirecionado para a tela de reservas  

### Cenário 2: Login com erro
Dado que estou na tela de login  
E informo dados inválidos  
Quando clico em “Acessar”  
Então devo ver uma mensagem de erro  

---

## História 2: Cadastro de Usuário

**Como um novo morador**  
Eu quero me cadastrar no sistema  
Para poder realizar reservas  

### Cenário 1: Cadastro com sucesso
Dado que estou na tela de cadastro  
E preencho e-mail, senha e confirmação corretamente  
Quando clico em “Cadastrar”  
Então minha conta deve ser criada  

### Cenário 2: Senhas diferentes
Dado que estou na tela de cadastro  
E informo senhas diferentes  
Quando tento cadastrar  
Então devo ver uma mensagem de erro  

---

## História 3: Visualizar Áreas Disponíveis

**Como um morador**  
Eu quero visualizar as áreas disponíveis (quadras/campo)  
Para escolher onde fazer minha reserva  

### Cenário 1: Listagem de áreas
Dado que estou na tela de reservas  
Quando acesso a lista de áreas  
Então devo ver opções como:
- Quadra de Tênis  
- Quadra Poliesportiva  
- Campo de Futebol  

---

## História 4: Selecionar Data para Reserva

**Como um morador**  
Eu quero escolher uma data no calendário  
Para agendar minha reserva  

### Cenário 1: Seleção de data
Dado que estou na tela de agendamento  
Quando seleciono uma data disponível  
Então essa data deve ficar marcada  

---

## História 5: Selecionar Horário

**Como um morador**  
Eu quero escolher um horário disponível  
Para definir quando usarei a área  

### Cenário 1: Horário disponível
Dado que selecionei uma data  
Quando escolho um horário livre  
Então o horário deve ser destacado  

### Cenário 2: Horário indisponível
Dado que selecionei uma data  
E existem horários ocupados  
Quando visualizo os horários  
Então horários indisponíveis devem aparecer desabilitados  

---

## História 6: Confirmar Reserva

**Como um morador**  
Eu quero confirmar minha reserva  
Para garantir o uso da área escolhida  

### Cenário 1: Reserva confirmada
Dado que selecionei área, data e horário  
Quando clico em “Confirmar”  
Então a reserva deve ser registrada  
E exibida na tela de confirmação  

---

## História 7: Visualizar Reserva Confirmada

**Como um morador**  
Eu quero ver os detalhes da minha reserva  
Para acompanhar meus agendamentos  

### Cenário 1: Exibir reserva
Dado que tenho uma reserva feita  
Quando acesso a tela de confirmação  
Então devo ver:
- Área reservada  
- Data  
- Horário  
- Nome do morador  

---

## História 8: Criar Nova Reserva

**Como um morador**  
Eu quero iniciar uma nova reserva  
Para agendar outro horário  

### Cenário 1: Nova reserva
Dado que estou na tela de confirmação  
Quando clico em “Nova Reserva”  
Então devo voltar ao fluxo de agendamento  

https://aicsvirtual.org/examen-de-certificacion-asfc/
