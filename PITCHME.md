---
marp: true
theme: gaia
paginate: true
---

# D3.js @far[clock]
## in 20 minutes

---
@title[What's D3]

@snap[north-west span-100 text-center]
### What's [D3](https://d3js.org/)

A JavaScript library for manipulating documents based on data.
@snapend

@snap[midpoint span-100 fragment text-left]
#### Glossary

@ul[text-07]
- HTML / CSS
- DOM = Document Object Model
- SVG = Scalable Vector Graphics
- Data Binding
@ulend
@snapend

---
@title[Why D3]

@snap[north-west span-90 text-center]
### Why D3
@snapend

@snap[mid-point span-60]
@ul[text-07]
- HTML / CSS
- DOM = Document Object Model
- SVG = Scalable Vector Graphics
- Data Binding
@ulend
@snapend

---
@title[Add A Little Imagination]

@snap[north-west span-50 text-center]
#### Engage your Audience
@snapend

@snap[west span-55]
@ul[list-spaced-bullets text-09]
- You will be amazed
- What you can achieve
- With a **little imagination**
- And GitPitch Markdown
@ulend
@snapend


---

@snap[north-east span-100 text-pink text-06]
Let your code do the talking!
@snapend

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

@snap[south span-100 text-gray text-08]
@[1-5](You can step-and-ZOOM into fenced-code blocks, source files, and Github GIST.)
@[6,7, zoom-13](Using GitPitch live code presenting with optional annotations.)
@[8-9, zoom-12](This means no more switching between your slide deck and IDE on stage.)
@snapend


---
@snap[north-west span-90 text-center text-06]
## Links you might like

<br /><br />
[D3 API page](https://github.com/d3/d3/blob/master/API.md)
[A collection of learning recourses](https://mode.com/blog/learn-d3)
[Big list of D3.js examples](https://christopheviau.com/d3list/)
[FREE Udacity course](https://www.udacity.com/course/data-visualization-and-d3js--ud507)
@snapend

