# ACME Anvil Corporation Compliance Program

This repository consolidates all documents related to the ACME Anvil Corporation Compliance Program.

This example leverages the great work of the: [strongdm comply](https://github.com/strongdm/comply) compliance automation framework.    

# Structure

Compliance documents are organized as follows:

```
narratives/     Narratives provide an overview of the organization and the compliance environment.
policies/       Policies govern the behavior of employees and contractors.
procedures/     Procedures prescribe specific steps that are taken in response to key events.
standards/      Standards specify the controls satisfied by the compliance program.
templates/      Templates control the output format of the HTML Dashboard and PDF assets.
```

# Building & Publishing

1. Clone this repository.    
1. Make the required edits to the policy markdown files.    
1. Check it back in:     

```shell
git add --all && git commit -m'edited some policy file' && git push
```  

4. a cicleci job will run and render policy files as PDF.

# Publishing

The `output/` directory contains all generated assets. Links in the HTML dashboard a relative, and all dependencies are included via direct CDN references. The entire `output/` directory therefore may be uploaded to an S3 bucket or other static asset host without further modification.    

# Convert source documentation to MarkDown     
[Pandoc Demos](https://pandoc.org/demos.html)     

//TODO:
1. Integrate with GitHub Pull Request functionality.
2. Option to push to GoogleDocs vs GitHub.
3. Enable a corporate branding template option.

---    

2019 gjyoung1974@gmail.com

