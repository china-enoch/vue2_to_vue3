## Vue2 to Vue3 practice

### Vue2
> [Course 1 : Create Vue](LD_01/index.html)

**Summary**

1. Include Vue.js in your project.
2. Create a Vue instance and pass in a configuration object.
3. Configure the object properties `el` to specify the presentation container.
4. The configuration object property `data` specifies the contents of the presentation container.
5. **_Instances and containers can only be one-to-one._**
---

> [Course 2 : Template syntax](LD_02/index.html)

**Summary**

1. Interpolation syntax.
2. Instructions syntax.
---

> [Course 3 : Data binding](LD_03/index.html)

**Summary**

1. Unidirectional binding.
2. Bidirectional binding.
---

> [Course 4 : Two ways of writing `el` and `data`](LD_04/index.html)

**Summary**

Nothing

---

> [Course 5 : Data proxy](LD_05/index.html)

**Summary**

1. Add all attributes in the `data` object to the VM through `Object.defineProperty()`.
2. Specify a `getter/setter` for each property added to the VM.
3. Operate (`read/write`) the data in `data` in getter / setter
---

>[Course 6 : Event processing](LD_06/index.html)

> **Summary**

1. `@click` = `v-on:click`
---

>[Course 7 : Event modifier](LD_07/index.html)

> **Summary**

1. `preventDefault()` or `prevent` : Block default events.
2. `stop`: Prevent event bubbling.
3. `once`: Trigger only once.
4. `capture`: Capture mode using events.
5. `self`: The event is triggered only if `event.target` is the element of the current operation.
6. `passive`: The default behavior of the event is executed immediately without waiting for the event callback to complete.
---