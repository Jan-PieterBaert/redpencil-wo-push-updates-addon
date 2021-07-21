ember-wo-push-updates
==============================================================================

This addon will provide the necessary functions to interact with push updates.


Compatibility
------------------------------------------------------------------------------

* Ember.js v3.16 or above
* Ember CLI v2.13 or above
* Node.js v10 or above


Installation
------------------------------------------------------------------------------

```
ember install ember-wo-push-updates
```


Usage
------------------------------------------------------------------------------

Only one function is provided, `addPollCallbackFunction`.
This function will register a callback to happen wwhen a push update is received, the callback will be given 3 arguments: the data, type and realm of the push received update.

