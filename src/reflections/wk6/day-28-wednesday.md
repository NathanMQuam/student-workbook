# Day 28
Nathan Quam

---

[Greg's Vue List](https://github.com/NathanMQuam/gregs-vue-list)

---
---

## Daily Journal

Read Frontend Frameworks with Vue3 > Understanding VueJs Lifecycle Hooks and answer the following questions

1. What are lifecycle hooks? What are lifecycle hooks used for?
`
Vue instances have a specific lifecycle under the hood, which is all of the processes associated with that instance, such as it's creation, template creation, instance mounting, DOM updates with data changes, and destroying. These lifecycle hooks are used for performing specific custom actions on a vue instance during a specific step of it's lifecycle, such as capturing it's data before destroying it.
`

2. How have you utilized lifcycle hooks in your afternoon projects?
`
For the NASA photo of the day, I use onMounted() to retrieve that day's photo (or video/panoramic in the case of tuesday, 2021/03/09) when the page loads. Before Vue3, we used the AppState/ProxyState provided by CodeWorks to run code or update DOM elements whenever an observed value was set, which acts similar to Vue's watch-compute-render lifecycle with the beforeUpdated() and updated() hooks.
`

3. What are mounting hooks? When might you use them?
`
Mounting hooks are hooks specifically for when a Vue instance is mounted to the DOM. These are useful for when you want to perform actions on data before or after the instance is mounted to the DOM. Similarly, the beforeDestroy() and destroyed() hooks are for right before and after the instance has been removed from the DOM.
`