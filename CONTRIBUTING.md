# Contributing Guide

🎉 Thank you for your interest in contributing opportunities to this repository!  
We welcome submissions for internships, hackathons, fellowships, competitions, grants, and any other student/early-career opportunities.

---

## How to Contribute

### ✅ Easiest way (Recommended)
1. Go to the [New Opportunity Submission Form](../../issues/new?template=add_opportunity.yml).
2. Fill in the fields about the opportunity (title, organization, link, deadline, type, etc.).
3. Submit the issue — that’s it!
   - A GitHub Action will automatically parse the issue and add the opportunity to our `opportunities.csv` file.
   - The README table will be regenerated with the new entry.

### 🛠 Alternative: Edit the CSV directly
If you prefer, you can directly edit [`opportunities.csv`](./opportunities.csv):
1. Fork this repository.
2. Add your entry as a new row at the bottom of the file (following the same schema).
3. Submit a Pull Request (PR).
4. Our maintainers will review and merge your contribution.

---

## CSV Schema

The `opportunities.csv` file contains the following columns:

| Column Name      | Description                                                                 | Example                                    |
|------------------|-----------------------------------------------------------------------------|--------------------------------------------|
| `title`          | Name of the opportunity                                                     | `Headstarter AI Fellowship`                |
| `organization`   | Hosting company, org, or sponsor                                            | `Headstarter`                              |
| `type`           | Category of opportunity (Internship, Hackathon, Fellowship, Grant, etc.)    | `Fellowship`                               |
| `link`           | Official webpage / application link                                         | `https://headstarter.co/ai-fellowship`     |
| `deadline`       | Application deadline (YYYY-MM-DD) or `Rolling` if ongoing                   | `2025-01-15`                               |
| `location`       | Remote / Hybrid / In-person city/country                                    | `Remote`                                   |
| `eligibility`    | Who can apply (students, recent grads, open to all, etc.)                   | `Open to students worldwide`               |
| `description`    | Short one-line summary                                                      | `10-week AI fellowship with mentorship`    |
| `tags`           | Comma-separated tags                                                        | `AI, Fellowship, Remote`                   |
| `added_by`       | Contributor GitHub username (auto-filled by GitHub Actions)                 | `@username`                                |

---

## Contribution Guidelines
- Please avoid duplicates. Check if the opportunity already exists in the README before submitting.
- Use accurate deadlines and official links only.
- Keep descriptions short (1 sentence).
- Use proper capitalization for `organization` and `title`.
- Tags should be comma-separated keywords (e.g., `AI, Startup, Grant`).

---

## Recognition
We use the [all-contributors](https://allcontributors.org/) bot to recognize all contributors. 🎉  
After your contribution is merged, you’ll automatically be added to the contributors list in the README.

Thanks for helping us build this resource 🚀

