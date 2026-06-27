# Folio Language Support

Language support for `.folio` files used by FolioScript, a portfolio-focused DSL.

## Features

- Syntax highlighting for `.folio` files
- Support for FolioScript keywords such as `portfolio`, `theme`, `hero`, `about`, `skills`, `projects`, and `contact`
- Basic language configuration for comments, brackets, and quoted strings

## Example

```folio
portfolio "João Silva" {
  theme dark accent="#7c3aed"

  hero {
    title "Desenvolvedor Full Stack"
    subtitle "Crio produtos digitais com IA."
    cta "Falar comigo" link="mailto:joao@email.com"
  }

  projects {
    project "Strongy" {
      description "IA de treinos personalizados no WhatsApp."
      stack ["WhatsApp", "IA", "Node.js"]
      link "https://strongy.app"
    }
  }

  contact {
    email "joao@email.com"
    github "github.com/joao"
    linkedin "linkedin.com/in/joao"
  }
}