# Tomás | Personal Site

My personal site and online CV, built with [Hugo](https://gohugo.io/) and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme.

🌐 **Live site:** [tom-cor.github.io](https://tom-cor.github.io)

## About

This site serves as my online CV, showcasing my:
- Work experience and skills
- Diplomas and certifications
- Personal projects
- Hobbies

## Tech Stack

- **Framework:** Hugo (Go-based static site generator)
- **Theme:** PaperMod
- **Styling:** Solarized Dark background with custom CSS overrides

## Local Development

### Prerequisites
- [Hugo Extended](https://gohugo.io/installation/) v0.128+
- [Go](https://golang.org/dl/) 1.21+

### Running locally

```bash
# Clone the repo
git clone https://github.com/tom-cor/tom-cor.github.io.git
cd tom-cor.github.io

# Install theme dependencies
hugo mod tidy

# Start local server
hugo server
```

Then open **http://localhost:1313** in your browser.

## Deployment

This site is automatically deployed to [GitHub Pages](https://pages.github.com/) via GitHub Actions on every push to `main`.

## License

Content © Tomás. All rights