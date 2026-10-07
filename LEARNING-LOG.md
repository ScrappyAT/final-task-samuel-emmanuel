# Learning Log

## Part 1.1 — Role Targeting and Skills Gap Analysis

This exercise helped me narrow my career positioning instead of trying to present myself as everything at once. I chose Product Engineer as my primary target and Software Engineer as my secondary target, while keeping Infrastructure/DevOps and AI Product Engineering as areas that complement that direction.

Looking at real Product Engineer roles also showed me that the role is broader than simply being a full-stack developer. Employers expect engineers to understand the product problem, work across the stack, make technical decisions, communicate trade-offs, and take ownership of features through production.

The analysis also helped me separate skills I already have from skills I can actually prove publicly. I have experience with TypeScript, APIs, PostgreSQL, product design, infrastructure, and AI-assisted development, but some of that experience does not yet have strong portfolio evidence. The remaining graduation projects will therefore be used deliberately to close those evidence gaps rather than just being completed as assignments.

## Part 1.2 — Positioning and Remote Readiness

Defining my positioning made me think more carefully about how my existing IT and infrastructure experience connects with where I am going as an engineer. Instead of treating infrastructure, software development, product engineering, DevOps, and AI as unrelated interests, I can build a clearer progression between them.

I also learned that being ready for a remote role involves more than technical ability. Availability, time-zone overlap, reliable internet, and backup power are part of being dependable on a distributed team.

My current setup gives me multiple internet options and basic backup power, but it also exposed areas I need to improve. I plan to add FibreX for additional internet redundancy and improve my power setup with an inverter and generator. The goal is to remove avoidable infrastructure problems that could affect my reliability when working remotely.

## Part 1.6 — Portfolio

Building my portfolio made me think differently about how I present myself as an engineer. The goal was not just to create a website that looks good, but to make it clear what I do, what I have actually built, and where I am currently growing.

One decision I made was to position myself primarily as a Product Engineer instead of trying to list every area I have worked in. My background in IT and infrastructure is still part of my story, but the portfolio shows the progression from infrastructure into software engineering and product engineering, while AI product engineering is presented as an area I am expanding into.

I also learned that a portfolio does not need every project to have an impressive user interface. Subslice and ReviewSlice are mainly engineering projects, so I presented them as case studies around the problems I solved and the engineering decisions involved. For the Property Listings project, I had an actual consumer-facing interface, so I included a screenshot. This made the project presentation reflect the real work instead of creating visuals just for the portfolio.

Responsive design was another important part of the process. The first mobile version technically worked, but the layout did not feel balanced. I had to rethink the hero section, navigation, spacing, project cards, and content containers for smaller screens. I learned that responsive design is not simply shrinking a desktop layout. Some parts of the layout need to be reorganized based on the available space.

I also implemented light and dark themes. One issue I encountered was a conflict between the browser's system colour preference and the theme class used by the application. I fixed this by making the theme class the source of truth, storing the user's preference locally, and applying the correct theme before the page renders. This helped prevent the theme from behaving differently after a refresh.

I kept technologies I am still learning, such as Docker, CI/CD, Redis, queues, observability, and RAG, separate from the technologies I can already demonstrate. I think this is important because a portfolio should show ambition without presenting planned skills as proven experience.

Finally, I deployed the portfolio to Vercel from the GitHub repository. This gave me a live production version that I can use on GitHub, LinkedIn, job applications, and outreach.

**Live portfolio:**
https://samuel-emmanuel-portfolio.vercel.app