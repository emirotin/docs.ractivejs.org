[[Home]] > [[API reference]] > [[ractive.teardown()]]

Unrenders this Ractive instance, removing any event handlers that were bound automatically by Ractive.

Calling `ractive.teardown()` causes a `teardown` [event](events) to be fired - this is most useful with [[Ractive.extend()]] as it allows you to clean up anything else (event listeners and other bindings) that are part of the subclass.


> ### ractive.teardown([ complete ]);
> > #### complete *`Function`*
> > An optional function, called (with `ractive` as `this`) when any [[transitions]] are complete