# <span class="display-name">CdrButton</span>


<span class="file">src/components/button/cdrButton.vue<span>


Cedar 2 component for button



<span class="modifiers">Modifiers</span>

Modifiers can be combined 1 from each grouping.

{secondary} | {sm,xs} | {block, fixed, responsive} **OR** link

Use of the 'link' modifier depends on including the css for cdrA.

A modifier list that contains 'link' exposes the same modifiers as cdrA and the other modifiers shouldn't be combined with it.

Responsive makes the button full width and block @ sm breakpoint.

### <button class='title'>PROPS, METHODS, EVENTS, SLOTS</button>

Prop Name | Type | Default | Require | Description
--- | --- | --- | --- | ---
type | string | "button" | false | Defines the button type. Possible values: {button, submit, reset}.
onClick | func | function() { return function () { return null; }; } | false | Add custom click actions.

Slot | Description
--- | ---
default | innerHTML on the inside of the button component