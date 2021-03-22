# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
`
You can directly insert the value some JS resolves to using {{}}. Or in element attributes you can use the :attribute="" to have the inside of the quotes resolve instead of being interpreted literally.
`

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
`
Single Page Application
`
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
`
The server doesn't need to send an entire HTML page for nearly every action the user does. It also lets the app skip page reloading in multiple cases
`
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
`
It runs a block of code right after the parent component has been mounted to the page
`
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
`
It syncs the contents/value of an element to a variable, and adjusts the other when one is changed
`
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
`
It lets you assign a function to call back when the event occurs
`
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
`
v-if, v-else-if, v-else, v-show, and v-for
`
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
`
The key attribute lets vue differentiate each instance of the v-for element from each other, by using some value that is unique for each instance
`
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
`
A component can have the slot element, which allows for a parent component to insert content into the component.
`
`
For example, there can be a "modal.vue" component, which creates a bootstrap modal. The actual content of the modal template can put a slot in the modal body. Then when a page uses the modal component, it can insert some content in between the <modal></modal> element tags, and that would show up inside of the modal.
`