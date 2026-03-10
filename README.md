# Formal Security Group Website

This is the research group's website for **Formal Security for Web Technologies** @ INESC-ID Lisboa.
Built with **Jekyll** and hosted on **GitHub Pages**.

## How to update content

The website's content is managed using the `_data` directory. No HTML changes are needed for most updates:

- **Projects**: Edit `_data/projects.yml`. Add a name, description, repo, and tags. 
  - `repo`: The repository slug (e.g., `formalsec/smtml`).
  - `homepage`: The link to the project's own documentation/webpage (e.g., `https://formalsec.github.io/smtml`).
- **People**: Edit `_data/people.yml`. Add name, GitHub username, role, and description.
- **Publications**: Edit `_data/publications.yml`. Add title, authors, venue, and a link to the paper.

## Local Development

To preview the site locally, you need Jekyll installed:

1. Install dependencies: `bundle install`
2. Run the server: `bundle exec jekyll serve`
3. Visit `http://localhost:4000`

## Structure

- `_layouts/default.html`: The main website template (header, footer, styles).
- `_data/`: YAML files containing the actual content.
- `index.html`: The home page using Liquid to render content from `_data`.
- `assets/`: Logos and other media.
