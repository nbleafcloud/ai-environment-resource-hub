# AI & Environment Resource Hub

A curated, public database of resources at the intersection of AI and the environment — podcasts, scientific papers, policy documents, multimedia, organizations, tools, courses, conferences, and people.

This repo is the version-controlled mirror of [The AI & Environment Resource Hub Google Sheet](https://docs.google.com/spreadsheets/d/1KGEzhkZVK-VKwbFKeuUPDDpYfTzhhfzkD7hSrG4wmgU/), maintained by [Nathaniel Burola](https://github.com/nbleafcloud) as part of [The Climate Code](https://the-climate-code.beehiiv.com/) newsletter project.

## Structure

Each resource type lives in its own JSON file under `data/`:

| File | Resources |
|---|---|
| `data/podcast.json` | Podcast episodes |
| `data/scientific_paper.json` | Peer-reviewed papers and preprints |
| `data/policy_document.json` | Policy reports, white papers, legislation |
| `data/multimedia.json` | Videos, talks, documentaries |
| `data/organization.json` | Companies, nonprofits, research labs |
| `data/tool.json` | Software tools and platforms |
| `data/course.json` | Online courses and educational programs |
| `data/conference.json` | Events and conferences |
| `data/people_of_interest.json` | Researchers and practitioners |

Each entry is a JSON object with fields like `title`, `url`, `description`, `date`, `domain`, etc. — exact fields vary by resource type.

## Contributing

Resources are added weekly through The Climate Code newsletter workflow. To suggest a new resource, fill out the [submission form](https://docs.google.com/spreadsheets/d/1KGEzhkZVK-VKwbFKeuUPDDpYfTzhhfzkD7hSrG4wmgU/) on the Google Sheet.

## License

The data in this repo is provided as-is for research, journalism, and educational use.
