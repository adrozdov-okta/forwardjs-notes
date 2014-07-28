# React and Flux: Building applications with a unidirectional data flow
#### Bill Fisher, Jing Chen

- speakerdeck.com/fisherwebdev/flux~something

- Flux is open sourced (today)
- github.com/facebook/flux
- miniurl.com/fluxreact

### Flux

- "hey, something has changed" vs what has updated
- "simple mental model"
- Stores
  - "all data for a logical domain" + application logic
- Dispatcher
  - pub sub system

- dispatcher, action
- store handles action
- getters, no setters! (in store)

- bugs are some set of events that put you in state you did not foresee

- Controller-views
  - type of react component
  - listen to change event, call stores they're interested in, and re-render

- Dispatcher has method "waitfor" in case there are dependencies between stores
  - sequenced update
  - hierarchy of stores

- Inspired by (look up):
  - dataflow programming
  - CQRS (command query response segregation)
  - Reactive
  - MVC
  - Functional & FRP

- Future
  - flux boilerplate & CLI tasks
  - Needed: Utils & Routers
  - Look at slides for extra stuff
