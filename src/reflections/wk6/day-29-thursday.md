# Day 29
Nathan Quam

---

[Pokedex](https://github.com/isabellesavannah/poke)

---
---

## Daily Journal

Read Frontend Frameworks with Vue3 > Using Nested Routes in Vue.js and answer the following questions

1. What is a nested route?
`
A nested route is a child route of a parent route, such as '/travel/america' and '/travel/china'. The the vue files, the App.vue will have the router-link, and the travel page will have multiple router-links in it, each with the 'to=""' attribute specifying the route. So there would be a ```<router-link to="/travel/america">``` and ```<router-link to="/travel/china">```
`

2. When might you use a nested route? (other than the provided example)
`
You might use a nested route for a page which serves multiple purposes but only needs one parent route page. For example, a single page might have multiple tabs inside, which act as 'sub-pages'.
`

3. Can you pass parameters through nested routes? When might you use them?
`
You can pass parameters through nested routes. You might want to send someone a link to a specific comment on a blog post, which would need a parameter for the blog id, and for the comment id.
`
