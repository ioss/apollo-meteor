# Orionsoft Apollo

A better Apollo integration for Meteor.

```
meteor add orionsoft:apollo
```

### Why it's better?

- Official Apollo integration it's not very updated.

- This package passes the ```userId``` to methods.

### Why do I need to pass the ```userId``` to methods?

So you can use ```this.userId``` in your meteor methods and also use packages
collection hooks out of the box.
