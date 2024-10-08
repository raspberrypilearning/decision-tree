## Classify the dinosaurs

<html>
  <div style="position: relative; overflow: hidden; padding-top: 56.25%;">
    <iframe style="position: absolute; top: 0; left: 0; right: 0; width: 100%; height: 100%; border: none;" src="https://www.youtube.com/embed/3op4RCy1wRc?rel=0&cc_load_policy=1" allowfullscreen allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"></iframe>
  </div>
</html>


<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
**Aim of the project:** Each dinosaur has a <span style="color: #0faeb0">**category**</span>. A category describes a group of dinosaurs with similar characteristics. You need to tell which category a dinosaur is in, using the facts you have about the dinosaur.
</p>

Here are some facts about two different dinosaurs:

(mya = million years ago)

| Name         | Length (m)  | Diet        | Continent      | Lived (mya)  | Category  |
|--------------|-------------|-------------|----------------|--------------|-----------|
| Concavenator | 6           | Carnivorous | Europe         | 130          | Theropod  |
| Diplodocus   | 26          | Herbivorous | North America  | 152          | Sauropod  |

You could separate this data into the two <span style="color: #0faeb0">**categories**</span> of dinosaur by asking this question:

![Image of a decision tree with the question 'Was it longer than 6 metres?'](images/decision1.png)

If the answer is **yes**, the dinosaur must be a Sauropod, and if it is **no** then it must be a Theropod. 

--- task ---
Think of a different question you could ask to separate out these two categories of dinosaur.

--- collapse ---
--- 
title: Show me the answer
---

- Did it live in North America?
- Was it carnivorous?
- Does its name begin with 'C'?
- Did it live more than 130 million years ago?

--- /collapse ---

--- /task ---
