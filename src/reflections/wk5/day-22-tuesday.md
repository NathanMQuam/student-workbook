# Day 22
Nathan Quam

---

(Greg's-List front-end)[https://github.com/NathanMQuam/gregs-list-axios]
(Greg's-List node/mongodb server)[https://github.com/NathanMQuam/greg-mongo-list]

---
---

## Daily Journal

Read Servers with Node/Express > MongoDb Relationships and answer the following questions

1. What are the three types of relationships?
```
One-to-one, one-to-many, and many-to-many
```

2. What are the benefits of the traditional linking of relationships instead of Embedding
```
Embedding the relationship means there's only one read operation when getting the information, and is the preferred method of linking for one-to-one relationships. With a one-to-many relationship where there may be a high volume of the many entities, traditional linking is preferred as it prevents many problems from arising. Bucketing can also be useful for the one-to-many relationships, such as when you are grouping items into discrete categories such as by date, or when paginating a set of data.
```

3. What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?
```
In the given example authors of many books and books with many authors, using two way embedding is useful, because the books store the foreign keys of their authors, and the authors store the foreign keys of their books.

With many books and only a few categories, it's better to store the foreign id's of a book's categories on the book entry, preventing the categories doc from getting bloated.

Finally there's third collection embedding, where the model stores the foreign id of a book and it's name as well as the foreign id's of that book's categories and authors. This keeps the relationship entries small and readable, as well as making it faster to query.
```

> TIP
>
>`Establish Relationship Balance`
>
>Establish the maximum size of `N` and the size of `M`. For example if `N` is a maximum of 3 categories for a book and `M` is a maximum of 500000 books in a category you should pick One Way Embedding. If `N` is a maximum of 3 and `M` is a maximum of 5 then Two Way Embedding might work well.