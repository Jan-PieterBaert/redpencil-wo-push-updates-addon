ember-wo-push-updates
==============================================================================

This addon will provide the necessary functions to interact with push updates.
This addon will also provide a tab-id which is stored in `window.identifier`

See [frontend-mu-push-poc-chat](https://github.com/redpencilio/frontend-mu-push-poc-chat) for an example of how this addon is used.
The application is part of [app-mu-push-poc](https://github.com/redpencilio/app-mu-push-poc).


Compatibility
------------------------------------------------------------------------------

* Ember.js v3.16 or above
* Ember CLI v2.13 or above
* Node.js v10 or above


Not yet published
Installation
------------------------------------------------------------------------------

```
ember install ember-wo-push-updates
```


Usage
------------------------------------------------------------------------------

Only one function is provided, `addPollCallbackFunction`.
This function will register a callback to happen when a push update is received, the callback will be given 3 arguments: the data, type and realm of the push received update.

