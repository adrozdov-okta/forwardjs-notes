# Enemy of the state
#### Amy Palamountain @ammrep

- Server side uses datastore to achieve statelessness
- There is a difference between client & server, server tries super hard to be stateless

### Modules

- Contains state & events of controllers (?)
- module views never place themselves on the application shell
- LayoutManager
  - Application shell
  - Decides when each module should be
  - Marionette.js

### Dispatcher

- Listens for events on (?), and then creates instance and hands off to LayoutManager (i.e. from Router)
- Loads new modules, disposes of old

### Application

- Bootsrapper, entry, exit, composer of thing
- Chaplain.js has dispatcher
