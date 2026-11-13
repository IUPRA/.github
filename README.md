# Institute for Urban Policy Research and Analysis (IUPRA)

**College of Liberal Arts · The University of Texas at Austin**
 
IUPRA is an interdisciplinary policy research institute that produces research to inspire intersectional policy solutions. This organization holds the code behind IUPRA's digital scholarship: the research databases, archives, and web tools that make our work searchable and public.

 ## About

The repositories here support that work. They include digitized historical documents from Central Texas and its Black communities, census and demographic data, and the web interfaces researchers and the public use to explore them.

## Tech Stack
 
Our platform is serverless and runs on AWS, so there are no servers for us to maintain and costs stay low between semesters.
 
- **Frontend:** Static HTML and JavaScript.
- **API:** Amazon API Gateway routes requests to AWS Lambda functions, which handle search, filtering, and admin tasks.
- **Storage:** Amazon S3 holds source files such as scanned documents and OCR output. Amazon DynamoDB stores structured metadata (dates, places, people, document types) for fast filtering.
- **Search:** Full-text and semantic search across OCR'd documents, so researchers can find material by meaning and not only by exact keywords.
- **Infrastructure as code:** AWS resources are defined with the AWS CDK and versioned in GitHub next to the application code, so every environment can be rebuilt from the repo.

## Contributing
[coming soon]

## Data & Access
 
Some collections include archival materials with usage restrictions. For those items, our public sites show **metadata only** and do not display the original documents. Please respect these restrictions in any tool or export you build.
 
## Links & Contact
 
- 🌐 [IUPRA website](https://liberalarts.utexas.edu/iupra/)
- 📄 [Research](https://liberalarts.utexas.edu/iupra/research/) · [Policy briefs & reports](https://liberalarts.utexas.edu/iupra/research/policy-briefs-reports.html)
- 📷 [Instagram](https://instagram.com/iupra_utexas)
