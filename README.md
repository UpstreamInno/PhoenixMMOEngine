# PhoenixMMOEngine
Develop a MMO engine using Phoenix/Elixir with some unique things


#Features

 - Dashboard is a set of maps, only users directly invited or via team can see maps
 - Users can see when another users moves between maps on dashboard
- Types of updates
 - Transactional updates
  - Optimistic UI update in anticipation of commit
 - Non-transactional view updates

- Ability to follow other users, in which case your UI sync (movements only)
- Detection of user coming online and appearing in map
- Online/offline tracking
- Transactional semantics - guaranteed message ordering
- Permissions management, organizations, teams, invitations

# Implementation details
- AJAX upward path, but websockets return
- Runs in HTML5 with Websockets

# What is this useful for
 - mmo game engine
 - chat engines
 - strategy/skill games, like poker
