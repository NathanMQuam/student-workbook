# Day 11
Nathan Quam

---

(Nathan's Poke-Zoo)[https://github.com/NathanMQuam/zoo-keeper]

---
---

## Daily Journal

Read Advancing with JS > ES6 modules and answer the following questions

1. What problem does using exports solve?

2. How does export differ from export default?

3. What is a benefit of using the Module System?

### My Responses

1. Exports allow a module to have public and private variables and functions. This allows for proper encapsulation, solving the problem of anything being able to access anything else whenever and however it wants.

2. There can be multiple regular exports, or 'Named Exports', in a single method. But there can only be one default export. The named export, when imported elsewhere, must be given the same name as it's export name, while a default export can be imported with any name.

3. The module system allows for much more rigidly defined and enforced design patters or architectures. Modules enforce encapsulation, and are a must-have for the MVC design pattern. Modules also make applications more secure from malicious users and even from the application itself (where it was not designed to have interactions)