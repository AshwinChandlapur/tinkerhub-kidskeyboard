# TinkerHub – Kids Keyboard

Live at **[tinkerhub.xyz/kidskeyboard](https://tinkerhub.xyz/kidskeyboard)**

A fun kids typing website where every keystroke pops a letter or emoji with a piano sound.

## Project Structure

```
kids-keyboard/
├── index.html                      ← root redirect → /kidskeyboard
├── staticwebapp.config.json        ← Azure SWA routing + security headers
├── kidskeyboard/
│   └── index.html                  ← the actual app
└── .github/
    └── workflows/
        └── deploy.yml              ← GitHub Actions CI/CD
```

## Deploy (Azure Static Web Apps + GoDaddy)

See deployment steps below.
