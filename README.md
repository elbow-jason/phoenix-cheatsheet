phoenix-cheatsheet
==================

A cheatsheet for the Phoenix Framework

TODO
-----

+ ROUTER
+ CONTROLLLER
+ PLUG


ROUTER
------

#### Actions:

| Action  | Route           | Method | Description 
|---------|-----------------|--------|---------------
| :index  | /thing          | GET    | load all the things
| :new    | /thing/new      | GET    | show creation form for thing
| :show   | /thing/:id      | GET    | show thing that matched id
| :edit   | /thing/:id/edit | GET    | show edit form for thing that matches id
| :create | /thing          | POST   | save the new thing to data store
| :update | /thing/:id      | PATCH  | update the thing in data store that matches id
| :update | /thing/:id      | PUT    | update the thing in data store that matches id
| :delete | /thing/:id      | DELETE | delete the thing in data store that matches id