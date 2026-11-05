# Personal webpage: planning conversation

*Exported 2026-11-05*

---

## User

I would like to create a personal webpage. I do not know a lot about how to do it and how to get a web domain. I have a Github account. What are my options?

## Claude

Since you already have a GitHub account, the simplest route is **GitHub Pages**. It's free, needs no server, and a lot of academics use it.

### Part 1: Hosting, where the site lives

| Option | Cost | Your address | Notes |
|---|---|---|---|
| **GitHub Pages** (recommended) | Free | `yourusername.github.io` | You put files in a repo and GitHub publishes them. You can add your own domain later. |
| University staff page | Free | nottingham.ac.uk/... | Official, but it's tied to your job and has limited layouts. Worth keeping alongside a personal site. |
| Netlify / Cloudflare Pages | Free | `something.netlify.app` | Similar to GitHub Pages with a few extra features. You don't need them for a personal site. |
| Squarespace / Wix / WordPress.com | About £10–20 a month | Your domain | Drag-and-drop editing with no code, but you pay every month and it's harder to move away later. |

### Part 2: How to build the site

On GitHub Pages you have three main choices:

1. **A plain HTML/CSS page.** This is one or a few files. It's the simplest and fastest, and nothing breaks. I can write it for you here, and you edit the text whenever you need to.
2. **An academic template** such as [academicpages](https://github.com/academicpages/academicpages.github.io) or [al-folio](https://github.com/alshedivat/al-folio). You copy ("fork") it on GitHub and fill in your details. These come with ready-made sections for publications, talks, teaching and your CV. They're powerful, but there are more files to understand.
3. **Quarto or Hugo.** You write pages in Markdown and a tool turns them into the site. This suits you if you want a blog or lots of pages.

For a personal research page (bio, research interests, publications, CV, contact), **option 1 or 2 is usually enough**.

### Part 3: A domain name (optional)

You don't need one at the start, because `yourusername.github.io` works right away. If you want something like `yourname.com`:

- **Where to buy it:** Cloudflare Registrar, Porkbun or Namecheap. These charge about £8–15 a year and keep the price the same when you renew. Avoid registrars that look cheap in year one and then charge much more.
- **Connecting it:** in your GitHub repo's Settings → Pages, enter the domain. Then at the registrar, add a few DNS records that GitHub's documentation lists. It takes about 10 minutes, and HTTPS is set up for you for free.
- **Tip:** a domain you own (rather than a university address) stays with you when you change jobs.

### What I'd suggest

1. Create a repo named `yourusername.github.io` on GitHub.
2. I build a clean, simple personal page here in this folder (bio, research, publications, CV, contact).
3. You upload it to that repo, and it's live within minutes.
4. Later, if you want to, buy a domain and point it at the site.

Should I start on step 2? If so, send me a short bio, your research topics, a link to your publication list (for example Google Scholar or ORCID), and any colours or style you like. One practical note: this folder is inside OneDrive, and git and OneDrive syncing can occasionally clash. It's fine for a small site, but a folder outside OneDrive is safer if you plan to use git regularly.

---

## User

export conversation to markdown and we will move to the github repo

## Claude

Saved this conversation as `conversation.md`.
