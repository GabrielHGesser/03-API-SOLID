# Aplicativo

Aplicativo no estilo GymPass.  
App in the style of GymPass.

## RFs (Requisitos Funcionais)

- [ ] Deve ser possível se cadastrar;
  - It must be possible to register.
- [ ] Deve ser possível se autenticar;
  - It must be possible to authenticate.
- [ ] Deve ser possível obter o perfil de um usuário logado;
  - It must be possible to obtain the profile of a logged-in user.
- [ ] Deve ser possível obter o número de check-ins realizados pelo usuário logado;
  - It must be possible to obtain the number of check-ins performed by the logged-in user.
- [ ] Deve ser possível o usuário obter o seu histórico de check-ins;
  - The user must be able to obtain their check-in history.
- [ ] Deve ser possível o usuário buscar academias próximas;
  - The user must be able to search for nearby gyms.
- [ ] Deve ser possível o usuário buscar academias pelo nome;
  - The user must be able to search for gyms by name.
- [ ] Deve ser possível o usuário realizar check-in em uma academia;
  - The user must be able to check in at a gym.
- [ ] Deve ser possível validar o check-in de um usuário;
  - It must be possible to validate a user's check-in.
- [ ] Deve ser possível cadastrar uma academia;
  - It must be possible to register a gym.

## RNs (Regras de Negócio)

- [ ] O usuário não deve poder se cadastrar com um e-mail duplicado;
  - The user must not be able to register with a duplicate email.
- [ ] O usuário não pode fazer 2 check-ins no mesmo dia;
  - The user cannot make 2 check-ins on the same day.
- [ ] O usuário não pode fazer check-in se não estiver perto (100m) da academia;
  - The user cannot check in if they are not near (100m) the gym.
- [ ] O check-in só pode ser validado até 20 minutos após ser criado;
  - The check-in can only be validated up to 20 minutes after it is created.
- [ ] O check-in só pode ser validado por administradores;
  - The check-in can only be validated by administrators.
- [ ] A academia só pode ser cadastrada por administradores;
  - The gym can only be registered by administrators.

## RNFs (Requisitos Não-Funcionais)

- [ ] A senha do usuário precisa estar criptografada;
  - The user's password needs to be encrypted.
- [ ] Os dados da aplicação precisam estar persistidos em um banco PostgreSQL;
  - The application data needs to be persisted in a PostgreSQL database.
- [ ] Todas as listas de dados precisam estar paginadas com 20 itens por página;
  - All data lists need to be paginated with 20 items per page.
- [ ] O usuário deve ser identificado por um JWT (JSON Web Token);
  - The user must be identified by a JSON Web Token (JWT).
