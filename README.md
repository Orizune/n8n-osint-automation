# OSINT Infrastructure Automation

Automation workflow built with n8n for domain infrastructure analysis.

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
