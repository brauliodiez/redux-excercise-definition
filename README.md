# redux-excercise-definition

## Basic pieces:
  - Communication.
  - Redux version.
  - React Hooks version.

## Communication

Create simple application to check how HTTP backend works, convert to reusable module.

Create simple applicatin to check how socket backend works, convert to reusable module.

## Redux version

- Start from boiler plate repo.


### Layout 

- Login Layout (not much to show here)
- Applicaton Layout (display user nick name on the header).

### Lobby POD

 - Create validation store temporal form information in componente.
 - Store final data into Redux (room, user).
 - Create Redux actions / sagas to connect with HTTP api.
 
 
### Chat room POD     

  - Create scene (check whether to componentize).
  - Connect (redux).
  - Send message to the socket (via redux).
  - Recieve message from the socket (via redux).
  - Fire initial messages request (via redux).
 

### Additional cases
  - Chat room allow filter messages.
  - Configure react promise tracker 
