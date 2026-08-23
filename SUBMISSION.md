# Three Roads: Choose Your Stack with AI

## Constraints

I only want free tools. My skill level is comfortable with coding: I have worked with Flutter/Dart, C#, SQL, JavaScript, HTML/CSS, PHP, and ASP.NET, but I still want a stack I can maintain without unnecessary complexity.

My portfolio has four pages:

- Home: states that I ship working software end-to-end.
- Work: case studies for my SASL app, banking application, and sneaker e-commerce site.
- About: a short professional biography.
- Contact: one clear way to contact me about opportunities.

The portfolio must display image galleries, embedded demos where useful, links to code repositories, long-form case-study writing, and potentially video or audio. Nothing needs to be dynamic at launch. I can use an email or LinkedIn link instead of building a contact form immediately.

## Options considered

### 1. No-code: Carrd

I would build the portfolio with Carrd's visual editor and host it on Carrd's free tier. It would not need a backend. I could add images, written case studies, external GitHub links, and embedded media.

The trade-off is speed versus control. Carrd would let me publish quickly, but the free version may limit multi-page structure, advanced galleries, custom layouts, and embedded technical demos. It would also show less evidence of my development skills.

### 2. Plain HTML, CSS, and JavaScript: GitHub Pages or Netlify

I would create a small static website using HTML, CSS, and limited JavaScript. Each sitemap page would have its own HTML file, with CSS controlling the visual system and JavaScript used only for useful interactions such as image galleries or filtering case studies.

I could host it for free on GitHub Pages or Netlify. GitHub would also give me a public repository that demonstrates how I build and document software.

It would not need a backend at launch. The Contact page could use a mailto link or LinkedIn link. A form could be added later using a hosted form service if it becomes necessary.

The trade-off is that I would need to manage the files, deployment, accessibility, and responsive design myself. However, this is also useful practice, and the stack is simple enough for me to understand and maintain.

### 3. React or another framework: Vite with Netlify, Vercel, or Cloudflare Pages

I would build reusable React components for the navigation, case-study pages, gallery, embedded demos, and contact section. I would use a free GitHub repository and deploy the application through Netlify, Vercel, or Cloudflare Pages.

It would not need a backend unless I later added accounts, a database, a working contact form, or other server-side features.

The trade-off is flexibility versus maintenance. React would make repeated components and future interactions easier, but it adds project configuration, dependencies, build tooling, and debugging overhead. For four mostly static pages, it may be more technology than the portfolio currently needs.

## Pressure test

If I choose the simplest option, Carrd, I could finish quickly, but I might struggle to present detailed technical case studies, custom galleries, embedded demos, and code-related evidence exactly as I want. I would also have less control over the structure and less opportunity to demonstrate development ability.

If I choose the most powerful option, React, I would maintain dependencies, the build process, component structure, deployment configuration, and more complicated debugging. I could finish in two weeks, but only by spending time on setup that does not directly improve the portfolio.

Plain HTML, CSS, and JavaScript should be finishable within two weeks because the sitemap is small and the content already exists. It can show screenshots, repositories, written case studies, videos, and embedded demos. It also lets me fix or replace the broken contact form without making the whole site dependent on a backend.

## Decision

I chose plain HTML, CSS, and JavaScript hosted on GitHub Pages or Netlify.

I did not choose Carrd because it would be faster but could restrict how well I present technical projects and interactive evidence. I did not choose React because its extra setup and maintenance are not justified by my current four-page sitemap.

The plain-code option gives me enough control to display my apps, screenshots, repositories, demos, and case studies properly while remaining free. I can maintain this because I understand the technologies involved and can update individual files without managing a large framework. It also gives me a public code repository that supports my claim that I ship working software end-to-end.

Most importantly, can I maintain this? Yes. Does it show my work well? Yes. I can start with a static Contact page and add dynamic functionality only when it is genuinely needed.

## Empty but live evidence

Live URL: https://marvelous-cocada-664268.netlify.app

Temporary Netlify password: My-Drop-Site

The site must be claimed through a free Netlify account before the one-hour temporary URL expires. After claiming it, replace the temporary URL above with the permanent URL in the assignment submission.

## Submission checklist

- [ ] Claim the Netlify site with a free account.
- [ ] Open the permanent URL on a phone and confirm it works.
- [ ] Replace the temporary URL above with the permanent URL.
- [ ] Upload the included screenshot of the near-blank homepage under Files.
- [ ] Paste this rationale into Notes or the assignment deliverable field.
- [ ] Add the permanent URL as a deliverable link.