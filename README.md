This work is in early Alpha stage and is led by the GSA FICAM Program in coordination with the ICAM Subcommittee of the Federal CIO Council.

# FICAM Playbooks
This repository is for the collaborative development of the Federal Identity, Credential, and Access Management Playbooks. These playbooks will be collections of guidance documents, separated by core topic, that provide federal agencies with information and step-by-step guidance on how to implement various ICAM solutions at their organization.

## General Practices
This content is Vendor neutral. Marketing materials for Commercial Products should not be submitted. If you would like to contribute a page or content which includes Commercial Products and a specific references for development and engineering, please review the Commercial Product trademark or copyright guides from the Product Vendor and reference those guides in your Pull Request.  

## Plain Language
Contributors should consider the audience when submitting content. Plain language benefits a broad audience. Review your proposed content for use of acronyms and specialized jargon before submitting.

## How to Contribute
For information on how to contribute to the site, visit the Contribute page [here]({{site.baseurl}}/contribute.md/). The source repository exists [here](https://github.com/GSA/ficam-guides/). 

Direct changes and line edits to the content may be submitted through a pull request by clicking 'Edit this page'. You do not need to install any software to submit content. You can use GitHub's in-browser editor to edit files and submit a pull request for your changes to be merged.

### Public domain

This project is in the worldwide [public domain](LICENSE.md). 

> This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
>
> All contributions to this project will be released under the CC0 dedication. By submitting a pull request, you are agreeing to comply with this waiver of copyright interest.

### Special Thanks

This site was derived from the [NIEM.github.io](https://NIEM.github.io) site.  Thank you to the NIEM program and contributors for your open and transparent model, and your Sharing Spot. 


### Considerations for local builds

This site relies on the following **submodules**:

./vendor/bootstrap-sass

https://github.com/twbs/bootstrap-sass.git

./vendor/bootstrap

https://github.com/twbs/bootstrap.git

./vendor/Font-Awesome

https://github.com/FortAwesome/Font-Awesome.git

_If_ you need to init the submodules locally, run the following from the command line:

    git submodule update --init vendor/Font-Awesome
	git submodule update --init vendor/bootstrap
	git submodule update --init vendor/bootstrap-sass
