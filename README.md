# OSINT Infrastructure Automation

Automation workflow built with n8n for domain infrastructure analysis.

This project would improve to a more powerful tool for scanning data with OSINT, local LLMs (via Ollama) and LLMs via API.

This project pretends to be modular and adaptable to multi-use, and as a base for new projects using low-code and open-source tools for automation and interaction, with cost-efficient policy, using resources like tokens for LLM as last resort, but with full availability. (When not to use LLM/IA for cost efficiency).

I'm a Brazilian citizen, if you are too, please help and contribute, you know that in our country it is hard to work and develop at the same time. 

## Features

- DNS lookup
- Infrastructure analysis
- Automated reporting
- Markdown export

## Tech Stack

- n8n
- API integrations
- workflow automation

## Workflow

![Workflow](images/Workflow_pt_1.png)

## Example Output

In Markdown
![Example Output](images/Output_MARKDOWN_md.png)

In Json
![Example Output](images/output_JSON.png)

In TXT
![Example Output](images/Output_TXT.png)

And, it can be done with a lot more archive formats, like PDF.

## How it works

1. user inputs domain
2. workflow queries DNS API
3. data processed
4. report generated
