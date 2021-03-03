# Day 23
Nathan Quam

---

[Da Planets](https://github.com/NathanMQuam/Da-Planets)

---
---

## Daily Journal

Read Servers with Node/Express > MongoDb Relationships and answer the following questions

1. In simple terms what is a sub-document?
`A sub-document is an entire object or document that is literally contained within another. As opposed to storing only a foreign key reference to a separate document within the original.`
---

2. When might you use a sub-document?
`For example, a forum post will have many replies/comments, in this example these replies are only accessed with the original post, and can be stored within the forum post itself. *But,* if the forum is expected to be very large (such as with hundreds or thousands of replies), it may be better to move the comments into their own separate document.`
---

3. How do you add to a collection of sub-documents? What about editing them?
`To add to a collection of sub-documents, you must access the top-level document, get the parameter that is storing the sub-documents, and push the sub-document into the top doc. To edit them, you instead access the top-level doc, access the parameter containing the sub-docs, access the particular doc you want to edit (such as by it's _id), and apply your changes to that one sub-doc.`