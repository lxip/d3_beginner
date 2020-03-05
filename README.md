---
marp: true
theme: gaia
paginate: true
<style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.12.1/css/solid.min.css">
</style>
---

# D3.js <i class="far fa-clock"></i>
## in 20 minutes

---
### What's [D3](https://d3js.org/)

A JavaScript library for manipulating documents based on data.

#### Glossary

- HTML / CSS
- DOM = Document Object Model
- SVG = Scalable Vector Graphics
- Data Binding


---
### Why D3



---
Let your code do the talking!

```sql zoom-18
CREATE TABLE "topic" (
    "id" serial NOT NULL PRIMARY KEY,
    "forum_id" integer NOT NULL,
    "subject" varchar(255) NOT NULL
);
ALTER TABLE "topic"
ADD CONSTRAINT forum_id
FOREIGN KEY ("forum_id")
REFERENCES "forum" ("id");
```


---
## Links you might like

<br /><br />
[D3 API page](https://github.com/d3/d3/blob/master/API.md)
[A collection of learning recourses](https://mode.com/blog/learn-d3)
[Big list of D3.js examples](https://christopheviau.com/d3list/)
[FREE Udacity course](https://www.udacity.com/course/data-visualization-and-d3js--ud507)


