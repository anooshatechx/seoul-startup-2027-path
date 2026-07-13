# Founder Insights

## July 13, 2026 — I Am Kognit's First User

Tonight I was building Layer 2 (sqlite-vec vector search). I had the code working 
but I didn't actually understand *why* the subquery was necessary.

I stared at the SQL for 20 minutes. `FROM (SELECT ... ) AS v JOIN ...` made no 
sense to me. I could copy it but I couldn't explain it.

Then someone explained it using a bookshelf analogy:

- `vec_analogies` = **books cover** on the shelf. You can see the title 
  and topic from the outside, light, fast to scan, enough to know what is inside.
- `Academic_Library` = **the actual pages inside the book**. The formal chapters, the reference pictures, the glossary, the explanation, everything heavy and detailed.
- The subquery = **"look at the book covers first, find the right one then open 
  only that book."**

You don't open every book on the shelf to find the right book. You look at the covers 
first, pick the right one you need then read the pages inside. That is exactly what the 
subquery does: search the covers first (the vectors) then open the book (the real data).

I understood it instantly. Not from the code. From the analogy.

That's when I realized: **I just experienced the exact problem Kognit solves.**

I don't learn from dense definitions. I learn when someone maps the unknown to 
something I already know. I am a university student, a tutor and a founder 
and I still need analogies to understand technical concepts.

If I need this, my students need this more.

Kognit is real because I am not building it from theory. I am building it because 
I live the problem every single day between tutoring sessions, during my own 
coursework and while debugging code at 2 AM.

This insight is now part of the product.