---
title: "What My Internship Taught Me About Secure Coding in Java"
categories:
  - Reflections
tags:
  - College
excerpt: "I went into my internship thinking secure coding was a checklist. I left realizing it’s a way of thinking and unit tests are one of the quickest ways to train that muscle."
---

This past summer, I was a software engineer intern at JPMorgan Chase. I had no idea what I was walking into and certainly didn’t expect the amount of secure coding concepts I had to think about. I thought all I had to do was avoid obvious mistakes, but I left realizing it’s a mindset, and unit tests are one of the easiest ways to apply it.

In Java, it was easy to feel safe because the language does most of the work for you, but what I learned was that big security issues show up in small things like trusting inputs or trusting a function would only be called the right way. How idealistic.

The best practice is to treat everything like it’s hostile:
- Validate input early
- Limit permissions and access
- Use immutable data when possible
- Avoid logging sensitive data

Unit tests are security training in disguise. I use to write tests just to boost coverage and check the box, but during my internship, I started writing tests to prove behavior and test around edge cases. The best tests I wrote were focused on the question what if someone tries to mess with this?

Some advice I received that helped me:
- Test input validation
- Test authentication and role logic
- Test failure modes
- Add regression tests

As I start to study cybersecurity in the Fall, I am taking back the lessons of this summer. Security isn’t something you bolt on after the fact, it has to be built early and everyone has to onboard. And unit tests aren’t just about correctness or checking a box, it’s a way to thinking skeptically and defending the code from future mistakes.

If I’m honest, I still feel early in the journey, but I now know what getting better looks like. I’m thankful for this past summer, for the things I learned, and especially the friends I made.