# Ignite Middlewares

Node Track - Ignite - @Rocketseat. It consists of an API to creating todos with a Pro plan for limit a quantity in the plan free.

## Middleware Requirements

### checksExistsUserAccount

- Should be able to find user by username in header and pass it to request.user
- Should not be able to find a non existing user by username in header

### checksCreateTodosUserAvailability

- Should be able to let user create a new todo when is in free plan and have less than ten todos
- Should not be able to let user create a new todo when is not Pro and already have ten todos
- Should be able to let user create infinite new todos when is in Pro plan

### checksTodoExists

- Should be able to put user and todo in request when both exits
- Should not be able to put user and todo in request when user does not exists
- Should not be able to put user and todo in request when todo id is not uuid
- Should not be able to put user and todo in request when todo does not exists

### findUserById

- Should be able to find user by id route param and pass it to request.user
- Should not be able to pass user to request.user when it does not exists

#### You can see then all rules are correct running the tests of the application.
