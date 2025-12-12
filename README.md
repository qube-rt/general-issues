# General Issues

This project provides a temporary workflow for creating GitHub issues that can be reviewed before being published.

## Workflow

### 1. Create an issues file

Add a new Markdown file containing the issue content. 

Place it in `oss/<repo_name>/`

### 2. Push to `main` 

Commit and push your Markdown file to the main branch.
 
### 3. Review Process

The pushed content will go through a review process. If approved, the issue will be considered ready to create on GitHub.

### 4 Create the github issue

Once approved, manually create the issue on GitHub using the reviewed Markdown content.

## Notes

This is a work-around until we can create issues directly from within qit-proxy.

Test with checkEmptyBranch 
