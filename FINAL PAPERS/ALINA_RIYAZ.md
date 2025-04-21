# Focus Garden – Final Paper  
**Alina Riyaz, IS 340: Integrative Project Management, Spring 2025**

---

## Abstract  
Focus Garden is an open-source solo project born out of a deeply personal need to stay grounded, focused, and emotionally aware in a world that is increasingly fast-paced and disconnected. By offering a simple yet effective way for individuals to log their daily focus and mood, the project provides a space to pause and reflect, without any pressure or judgment. Through daily journaling and CSV-based tracking, Focus Garden enables users to "grow" their awareness over time, building a kind of digital garden that reflects their own growth, setbacks, and resilience. Using GitHub to manage issues, documentation, and collaborative opportunities, the project demonstrates how deeply personal projects can still embrace and benefit from working open principles. This paper explores how the Focus Garden project was designed, implemented, and aligned with core open-source project management concepts covered in IS 340.

---

## Introduction and Project Motivation  
I created Focus Garden during a time when I felt scattered and overcommitted. Between balancing school, work, and personal responsibilities, I realized I had no reliable way to pause, reflect, or even notice how I was feeling on a day-to-day basis. That sense of disconnection was taking a toll not only on my productivity but on my emotional health. I didn’t need a complicated app or subscription-based wellness tracker. I needed a lightweight, open, honest system that would help me reflect without friction. Focus Garden was born out of that realization.

The idea was simple: allow people to log their daily mood and focus level on a scale of 1 to 5, and write a few sentences about how their day went. No dashboards. No analytics. Just a habit of checking in. But as I began developing it for IS 340, I saw how this deeply personal system could also be shared, adapted, and sustained using open-source principles. By placing the project on GitHub and creating a clean, modular structure, I could invite others into the process without losing what made the idea so personal to begin with.

Focus Garden not only became a system for personal growth but also a foundation for exploring deeper questions about self-discipline, emotional resilience, and community sharing. What began as a self-improvement tracker grew into a vehicle for community collaboration and potential collective healing. The act of working openly also shifted my mindset: instead of building alone, I began thinking about how my tools and practices could be useful to others. This transformation from inward to outward thinking became the emotional heartbeat of the project.

---

## Design and Implementation  
Focus Garden is built on two simple foundations: a CSV tracker (`focus_log.csv`) and a Markdown-based journal template. The tracker allows users to log daily entries that include the date, a 1–5 focus rating, a 1–5 mood rating, and a few notes. The Markdown journal prompts encourage deeper reflection, with open-ended questions like "What helped you focus today?" and "What challenges did you face?" The simplicity is intentional. As emphasized in our lectures on working open, good design prioritizes transparency, accessibility, and sustainability. These principles guided every aspect of Focus Garden's structure.

The GitHub repository is organized with clear folders: `/data` for the CSV, `/docs` for templates and project planning materials, and root-level files like `README.md` and `CONTRIBUTING.md`. Each of these files plays a role in inviting contributors and maintaining the project’s long-term health. The project board was set up using GitHub’s Kanban-style layout, with columns for Planned Features, In Progress, and Completed. I created labeled issues with detailed descriptions, following best practices from Lectures 15 and 18.

To ensure traceability and modularity, each feature of the project is managed as its own issue, with commit messages that clearly correspond to individual tasks. For example, creating the Markdown journal template was tracked as a distinct GitHub issue and closed only after full implementation and testing. In addition, the use of `open_canvas.md` as a strategic planning tool served as a touchstone for aligning tasks with broader goals—a practice encouraged throughout our course as a way to preserve project coherence over time.

---

## Working Open and Community Invitation  
One of the most powerful takeaways from IS 340 is that working open is not just about making code public. It's about designing a system where others can enter, contribute, and build something meaningful. With Focus Garden, I made sure to lower the barrier to entry for contributors. The `CONTRIBUTING.md` guide explains exactly how someone can add a journal prompt, suggest a new metric (like sleep quality or energy level), or improve documentation. Every issue is scoped as an Earth Shot—small, clear, and actionable. The language is friendly, not technical.

I also created a standalone issue focused on potential rescoping. As contributors join, the project might evolve to include visualizations, integrations with tools like Google Sheets, or even mobile support. The rescoping issue documents these possibilities, ensuring that the project remains adaptable without becoming bloated. Following Lecture 22, I carefully avoided over-automation. This is a project rooted in self-reflection, and too much automation might remove the very pause the tracker is meant to create.

In future iterations, I envision integrating features like scheduled reminders for journaling or anonymized community stats to foster a sense of connection among users. While GitHub is the current platform, expanding to user-friendly platforms like Notion or developing a lightweight app version may allow Focus Garden to reach more people. At every step, however, the project will preserve its open-source heart by encouraging transparent development logs, shared decision-making through issues, and decentralized input.

---

## Sustainability and Long-Term Vision  
While Focus Garden began as a personal tool, I wanted to ensure that it could outlast me. Sustainability, as we learned in Lecture 19, isn’t just about code quality. It’s about documentation, contributor support, and process transparency. I ensured that every feature was documented, every file was clearly named, and every potential contributor had a clear path to involvement.

If someone forks the project a year from now, they should understand its purpose, how to contribute, and how to expand it without breaking its core values. That’s sustainability. The use of Markdown, CSV, and plain-text formats ensures long-term accessibility and avoids tool lock-in. The project is also designed to be modular: contributors can expand templates or swap out metrics without having to understand or rewrite the whole system.

One additional approach I’ve taken is to maintain an evolving backlog of feature ideas as open issues, which allows contributors to engage with the roadmap in an organic way. Community engagement doesn’t need to happen all at once—a slow build of collaborators is more sustainable than a spike of interest that fizzles. Like a real garden, this project is designed to grow at its own pace, with steady nurturing.

Over time, Focus Garden could grow into a broader wellness community—an open-source hub where people share their own daily journaling templates, track creative progress, or build tools for other mental health needs. But even if it remains small, it has already succeeded in creating something open, helpful, and deeply human.

---

## Reflection and Learning  
Completing this project has been one of the most meaningful experiences I’ve had as a student. It forced me to engage deeply with open-source principles, not in the abstract, but in practice. I had to think about onboarding, issue scoping, project decay, documentation, and communication strategy. I learned how to make a project that not only works for me but could work for someone else tomorrow. That shift—from making something for myself to making something shareable—was powerful.

I also learned the value of simplicity. In a world where productivity tools often emphasize dashboards and gamification, Focus Garden is a return to the basics: write things down, reflect, and repeat. That simplicity is its power, and protecting that simplicity became a design goal in itself.

Through this course, I now understand how open-source projects rely not just on good ideas, but on good infrastructure. Working open is about clarity, kindness, and care. It’s about inviting people into your process. That’s what I’ve tried to do with Focus Garden, and what I hope to carry with me as I continue to build.

---

## Conclusion  
Focus Garden is a deeply personal project that became something much larger than I expected. It represents everything we studied in IS 340: working open, documenting clearly, thinking sustainably, and designing for collaboration. It is a project rooted in care—for myself, for contributors, and for anyone who might stumble across it in the future.

As a student, this was my first time building an open-source project from scratch. But it won’t be the last. I now have the tools, the mindset, and the confidence to create things that matter—not just for me, but for others too. Focus Garden taught me that you don’t need a big idea to make a meaningful one. With intention, transparency, and a willingness to be open, even the smallest seeds can grow into something beautiful.

Thank you.

---

## References  
- Mozilla Working Open Guide: https://mozillascience.github.io/open-science-leadership-workshop/01.2-working_open.html  
- Fogel, K. (2005). *Producing Open Source Software*. https://producingoss.com  
- GitHub Docs: https://docs.github.com/en  
- IS 340 Lecture Slides, Lectures 1–22  
- Bainbridge, L. (1983). *Ironies of Automation*
