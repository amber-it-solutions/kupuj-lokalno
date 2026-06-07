# Chat handoff — kupuj-lokalno

This file bridges the Cursor chat from **koralj-app** into this new project.

## What was requested (before the full product prompt)

1. Create a GitHub repository named **kupuj-lokalno**
2. Create local directory: `Documents/GitHub/kupuj-lokalno`
3. Connect local git to GitHub remote
4. Continue planning and building **kupuj-lokalno** in a fresh Cursor workspace (separate from ŠRD Koralj / koralj-app)

## Open this project in Cursor

1. **File → Open Folder…**
2. Select: `C:\Users\Korisnik\Documents\GitHub\kupuj-lokalno`
3. Start a **new Agent chat** in that window (or continue here after switching folder)

## Carry context from the previous chat

Cursor chats are tied to a workspace. To bring context over:

- In the new workspace chat, say: *"Read docs/CHAT-HANDOFF.md — this is a new project, kupuj-lokalno. I will give you the full build prompt next."*
- Optionally attach or paste your full product prompt in that first message.

## GitHub

Repository: **https://github.com/amber-it-solutions/kupuj-lokalno**

```powershell
git remote -v
# origin  https://github.com/amber-it-solutions/kupuj-lokalno.git

git push origin main
```

## Status

- [x] GitHub repository created (`amber-it-solutions/kupuj-lokalno`)
- [x] First push to `origin/main`
- [ ] Full product prompt provided
- [ ] Implementation started
