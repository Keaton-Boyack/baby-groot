<img alt="Baby Groot" src="https://github.com/user-attachments/assets/10e0fff3-fec1-4255-9d69-4262ac2d4020">

<h1 align="center">Baby Groot</h1>
<p align="center">
  An open-source AI-powered personal tutor, built on Llama 3 70B and Together.ai.
</p>


2DUvnwF4ydHya3y4UJjmd1oFiY4THg1fgYkK2tKXpump
## Tech Stack
- Meta's Llama 3.1 70B as the language model
- Together AI to handle LLM inference
- Next.js (app router) with Tailwind for the frontend
- Exa.js for search functionality
- Helicone for monitoring and observability
- Plausible for site analytics

## Getting Started
1. Fork or clone this repository
2. Sign up for a Together AI account to access the LLM
3. Sign up for an Exa account
4. Sign up for a Helicone account for observability
5. Create a `.env` file (reference `.example.env`) and fill in your API keys
6. Run `npm install` followed by `npm run dev` to install dependencies and launch the app locally

## Roadmap
- [ ] Add share and copy buttons for generated conversations
- [ ] Show suggested follow-up questions and a "new chat" option at the end of each conversation
- [ ] Split the current page into two separate pages and restore the footer
- [ ] Consolidate all icons into a dedicated TypeScript file (transform.tools)
- [ ] Build out a more polished landing page with a clear GitHub link section
- [ ] Implement a clean hamburger menu for mobile
- [ ] Experiment with Vercel's generative UI features
- [ ] Improve the styling of dropdown menus
