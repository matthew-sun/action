# Summary

> An easy and lazy solution for click-event-binding.

### Step 1

Define some actions:

```js
action.add({
    'my-action': function () {
        //do something...
    },
    ...
})
```

### Step 2

Create an element like this:

```html
<a href="#my-action" data-action>link</a>
```

or 

```html
<a href="#" data-action="my-action">link</a>
```

or

```html
<button data-action="my-action">btn</button>
```

### Step 3

You've done everything.

Clicking the element will trigger the action you defined.
