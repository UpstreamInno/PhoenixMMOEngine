# PhoenixMMOEngine
Develop a MMO engine using Phoenix/Elixir with some unique things


#Features
- Runs in HTML5 with Websockets
- Dashboard is a set of maps, only users directly invited or via team can see maps
- Users can see when another users moves between maps on dashboard
- Ability to follow other users, in which case your UI sync (movements only)
- Optimistic UI update in anticipation of commit
- Transactional updates
- Non-transactional view updates
- AJAX upward path, but websockets return
- Detection of user coming online and appearing in map
- Online/offline tracking
- Transactional semantics - guaranteed message ordering
- Permissions management, organizations, teams, invitations


