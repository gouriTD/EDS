# A Brief Introduction To Edge Delivery Services

### Content Outline
* What is EDS and its benefits over traditional way of website development?

* What is content authoring in EDS?

* How to get help while in project development with EDS?

## What is EDS and its benefits over traditional way of website development? 

EDS or Edge Delivery Services is a service offering from AEM cloud services which focuses on 3 major areas :

    1) Decouple content creation from content delivery.
    2) Faster user centric content creation.
    3) Faster site creation with perfect lighthouse score for performance measurement.

Via EDS , AEM decouples the content creation from content delivery process. 

Irrespective of the source of content creation, whether document based authoring via Google docs in Gdrive or Word documents in Sharepoint, or AEM authoring through universal editor , the content from different sources gets ingested via edge delivery services.

EDS allows or rather encourages content creators using different sources to contribute towards content creation which leads to a high velocity of content creation. The EDS codebase for website development is maintained in github so once the content is previewed and published the site pages are live and available on the website.
Any modifications to the page functionality is maintained via github, hence no separate build process for website deployment is required. Thus once the content gets pushed to the main branch it is available on the live site.

EDS code base has RUM (Real Use Monitoring) enabled which allows live performance measurement for the site created.

Eventhough the website is created quickly supporting huge content, the sites are ensured to achieve perfect lighthouse score.

## Content Authoring In EDS 

There are 2 basic formats in which content is authored :

    1) Document based authoring.
    2) AEM authoring via Universal Editor (WYSIWYG).

### 1) Document Based Authoring
    * Through document based authoring content creators can levarage their understanding of Word docs / Google docs to create content that would get converted to pages for the sites.

    * No extra training is required to learn new tools as prior knowledge of authoring tools with Google docs and Word docs would help.
    
    * This allows content creators to quickly convert their contents to live pages on website.


#### Advantages of using document based authoring:
 * Cost effectiveness as no additional training is required for content creation.
 * Increased velocity of content creation.
 * Providing the creators with flexibility to create meaningful content for their sites.

### 2) WYSIWYG content authoring with universal editor :
    * Apart from document based authoring via Google docs and Word docs , content authroing could be done with universal editor as well. Here in we make use of content authoring from AEM services opening doors for content being authored in universal editor as well being consumed by the EDS framework.

#### Advantages of using universal editor:  
 * With universal editor we can have a more intutive content authoring experience.
 * There are many pre-built blocks which can be utilised for content creation and see them live as site pages.
 * AEM's content authoring could be used for content creation.

### Advantages of having EDS as a content delivery services :
 1) EDS boilerplate code is maintained in github hence, website created can be built and deployed once code pushes to github, there is no additional build cycle required.
	
 2) As content delivery is decoupled from content authoring, hence multiple content authoring sources can be supported.

 3) We need not learn any new frameowrk, knowledge of plain Javascript and CSS would help in adding and modifying features.

## How to get help from Adobe for sites on EDS ?
    1) Going through community resources , engaging with Experience league community , wherein you can ask questions , and get understanding of some problems through like minded people, adobe experts/Adobe champs.
	
	2) Raising ticket with Adobe for trouble shooting the problem. The ticket raised should have "Edge deliery services " in the title and description should mention the problem with url to the site.
	
	3) When a project is initiated with EDS a slack channel between the user and team is created for asking question, raising issues and highlighting pitfalls with the team.   