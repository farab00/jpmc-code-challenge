=======================
JPMC Code Challenge

Project Information

1) This AEM project structure was created using Lazybones (Lazybones CLT + ACS AEM Multi module template). 
2) AEM Version: AEM 6.3
3) Developed on MacOS

OBJECTIVE: Create a breadcrumbs component which is compatible with AEM 6.0 or higher. The deliverable should be an AEM package.

ACCEPTANCE CRITERIA:

As a Content Author: I want to be able to exclude pages from the breadcrumb listing so that structural pages or pages not meant to be navigated to directly are not presented in this context.
==> Enabling 'Hide in Navigation' property of a page, will exclude the page from the breadcrumb. 


As a Site User: I want to be able to see where I am in the site’s content tree so that I understand the context of what I am viewing. I want to be able to navigate to where I have come from in the site so that I can easily jump back and forth between site sections.
==> A bread crumb trial will be displayed on the page allowing users to navigate back and forth.




Page Template =>  /apps/jpmc-code-challenge/templates/jpmc-one-col-template. It includes client libs of category jpmc-code-challenge.all

Page Component => /apps/jpmc-code-challenge/components/structure/jpmc-one-col

Global Components => /apps/jpmc-code-challenge/components/global/*. Includes jpmc-global-nav, jpmc-global-breadcrumbs, jpmc-global-footer

Global files =>  /apps/jpmc-code-challenge/global/*

Sling Model => com.jpmc.code.challenge.models.BreadCrumbs

UI resources => /etc/designs/jpmc-code-challenge
