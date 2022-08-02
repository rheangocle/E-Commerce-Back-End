# E-Commerce-Back-End: Object-Relational-Mapping (ORM)

## Table of Contents

- [User Story](#user-story)
- [Summary](#Summary)
- [Software](#Software)
- [Installations](#Installations)
- [Mock-up](#Mock-up)

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Summary

Sequelize was used with a working Express.js API to interact with a MySQL database. When the server is starter and the user opens Insomnia, they can use the GET routes for categories, products, or tags. The user can use GET routes for individual products, categories, or tags. In addition, POST, PUT, and DELETE routes can be used to create, update, and delete categories, products, or tags data in the database.

## Software

- Node.js
- DBeaver: database administration
- Insomnia: testing server
- MySQL: database

## Installations

- Express.js
- Sequelize

## Mock-up

[Walkthrough Video](https://drive.google.com/file/d/1-oUOKFsO3K8RlP1-0iZk7r4T7zm7FhCK/view?usp=sharing)

GET Routes for all categories, all products, and all tags:

![In Insomnia, user showing GET routes for all products, categories, and tags](./assets/images/GET%20routes.gif)

GET routes for a single product, a single category, and a single tag:

![In Insomnia, user showing GET routes for a single category/tag/product](./assets/images/GET%20routes%20for%201.gif)

POST, PUT, and DELETE for categories:

![In Insomnia, user showing POST, PUT, and DELETE routes for a category](./assets/images/post%2Cput%2Cdelete%20category.gif)

POST, PUT, and DELETE for products:

![In Insomnia, user showing POST, PUT, and DELETE routes for a new product](./assets/images/post%2Cput%2Cdelete%20for%20product.gif)

POST, PUT, and DELETE for tags:

![In Insomnia, user showing POST, PUT, and DELETE routes for a tag](./assets/images/post%2Cput%2Cdelete%20for%20tag.gif)

---

MIT License

Copyright (c) 2022 Rhea Le

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
