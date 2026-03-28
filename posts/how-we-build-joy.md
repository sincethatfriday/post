---
title: "How we built Joy — our website chatbot"
date: "2025-03-28"
author: "Sam"
tag: "Story"
excerpt: "We wanted a chatbot that sounds like us, not a robot. Here's how we built Joy using LLaMA and Node.js."
---

![Evil eye illustration](https://raw.githubusercontent.com/sincethatfriday/post/main/images/evileye.png)

## Why we built Joy

We didn't want the usual chatbot. You know the ones — "Hi! How can I assist you today?" That's not us.

We wanted something that sounds like Abi and Sam actually wrote it. Warm, a little fun, and honest about what we can and can't do.

## The tech behind it

Joy runs on LLaMA via Groq's free API. The whole thing is a Node.js service with three layers — a prompt that defines her personality, a knowledge base with everything about Since That Friday, and a handoff flow that collects leads and emails them directly to us.

## What we learned

The hardest part wasn't the code — it was the prompt. Getting an AI to sound like a real person instead of a brochure took a lot of iteration.

## What's next

If you want a chatbot like Joy for your business — reach out at hola@sincethatfriday.in
```

Nothing after the last line. Commit it to `main` and test:
```
GET http://localhost:3000/api/blog/how-we-built-joy
