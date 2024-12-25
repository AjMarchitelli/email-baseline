# Email Baseline for Development

## Master Email Info README
https://arteric.atlassian.net/wiki/spaces/TECH/pages/1296728098/Resources+and+Links+for+Email+Development

## About
This is a living document. We have expanded upon the Responsive Cerberus email template, based on work requests across multiple projects.

## baseline.html
- Top down approach
- Contains Cerberus responsive template with minor css tweaks (original Cerberus responsive template can be found here : https://github.com/TedGoas/Cerberus). 
- examples of different table layout stuctures (single column, multiple even columns, stacking columns, etc)

## starter.html
- Bottom up approach
- Contains all of the groundwork and CSS of baseline.html, however all of the layout components have been stripped out so that this file could be used as a fresh starting file. A separate style tag for project specific css under "Progressive Enhancements"
- Basically a blank email

## CodeSnippets.md
- small email code examples that could be reused

## email-components
- Larger code examples that could also be used as a template/starting point


## Feel free to Contribute
If you're fixing something annoying that is worth sharing, add it as a new `<tr>` or sub-table to the baseline.html file (depending what you're doing, of course). Please open a pull request and get 1 or 2 reviewers to look at it before merging with `master`.

## If it's a CRM email -- will live somewhere else
  * Litmus workflow 
    - Build email using either starter or baseline
    - Create folder for email in Litmus (make sure to label folder w/ job code)
    - Create template for email within that folder
        -> Keep in mind that this template name will be used as the subject when sent
    - Test Test Test (DEV)
    - Once RFT provide folder name & location AND make sure to specify the Litmus account that the email is in so that QA knows where to look



## If it's a RTE -- will live in Veeva 
- Build email using either starter or baseline
- Please read the Resources section on Veeva Emails from the above Master README (for info on Simulator setup, adding test users if necessary)
- Prepare files for upload (images mainly - This consists of zipping the folder that the images are in)
- Upload to veeva
- Template Info (naming, product info, email fields, general)
- Sync 
- Test Test Test (DEV)
- Once RFT provide template name in ticket so that QA can send their own tests when ready

- TODO: add commentary re: file structuring / handoff variants based on subjects/pre-headers
- TODO: add fragment info