# Course Assignment: Development Platforms


**Website Hosting:** [Netlify](https://developmentplatforms.netlify.app/)  
**Project Report:** [GitHub Markdown](https://github.com/siljeangelvik/development_platforms_ca/blob/main/report.md)    
**GitHub Project Repo:** [Development Platforms ca](https://github.com/siljeangelvik/development_platforms_ca)  
**Repository Fork:** [development-platforms](https://github.com/NoroffFEU/development-platforms)  
**Report Format Template:** [GitHub Flavoured Markdown](https://github.com/siljeangelvik/development_platforms_ca/blob/main/template.md)  


## Introduction  
Because Karen wanted to publish and share her recipes easily, we were thinking something like WordPress would be a good solution.
We wanted to make it easy and intuitive for her to add these recipes, and manage her own website, but at the same time, WordPress was more of a monolithic CMS, which we didn't want.
After some researching on different development tools and platforms, we found that GraphCMS/Hygraph was a solid alternative to WordPress, as well as replacing the back end with NextJS.


### Our approach:
Because Karen wanted to publish and share her recipes easily, we were thinking something like WordPress would be a good solution. We wanted to make it easy and intuitive for her to add these recipes, and manage her own website, but at the same time, WordPress was more of a monolithic CMS, which we didn't want. After some research on different development tools and platforms, we found that GraphCMS/Hygraph was a solid alternative to WordPress, as well as replacing the back end with NextJS.
We would build it with the newest technologies such as React JS, NextJS, Tailwind CSS, GraphQL and GraphCMS.

## Why?
* We wanted easy production builds
* We wanted server-side rendering
* Static exporting options
* GraphCMS/Hygraph replaced the CMS part of WordPress
* GraphQL replaced both SQL and NoSQL but still keeping their respective benefits
* Read more below on _Pros_


## Comparison
### Nextjs vs Svelte

### GraphQL vs REST
GraphQL has many advantages over REST.
GraphQL is faster than REST because you can easily pick the fields you have to query. GraphQL provides a better learning curve as compared to REST.
![REST vs GraphQL](./public/rest_graphql.png)

### GraphCMS vs WordPress
Next JS is specifically designed for server-side rendering and offers a range of features to make it easy for developers to build server-rendered React applications. Svelte also offers support for server-side rendering; however, compared to Next JS, it requires more setup and configuration.


## Strengths vs Weaknesses
**Strengths**
* Easy to use for both the client and the developer
* The GraphQL syntax is not so different from JSON
* Hygraph acts as both a Headless CMS and a powerful GraphQL database
* Delivers performance and scalability with the available features
* Offers a free plan

**Weaknesses**
* Cost money for bigger or more projects
* We have yet to figure out more cons...


## Features
**React** makes it easier to create dynamic web applications because it requires less coding and offers more functionality, as opposed to JavaScript, where coding often gets complex very quickly. Improved performance: React uses Virtual DOM, thereby creating web applications faster.

**Nextjs** gives developers the ability to do things like server-side rendering, which means the server reads through code and tells the browser what to display on the page. Server-side rendering creates faster, more versatile web applications.

**GraphQL** simplifies the task of aggregating data from multiple sources or APIs and then resolving the data to the client in a single API call.

**Hygraph** features content modeling where developers and content managers can easily set up content structures, or models, create custom workflows, and connect models to speed up creation.

![Features Hygraph](./public/features_hygraph.png)


## Journey
We started making an account for the **GraphCMS**, when we were logged in,   
we got the option of choosing a schema to work with or start blank.   
We went for starting on a new blank project.

#### We added some details to the new project:
**Project Name:** karen_blog  
**Project Description:** A virtual recipe book delivered by Karen   
**Region:** Germany (Frankfurt)

**! Note:** _Hygraph allows you to select which region to host your content in._  
_All content will be served from a globally distributed CDN_.
<img src="./public/developmentplatforms_graphcms-1.png" data-canonical-src="./public/developmentplatforms_graphcms-1.png" width="600" height="auto" />

GraphCMS has 4 different plan options: community, professional, scale and enterprise.  
In this case we went for the community version, which is the "free forever" option.
<img src="./public/developmentplatforms_graphcms-2.png" data-canonical-src="./public/developmentplatforms_graphcms-2.png" width="600" height="auto" />

After entering the dashboard, the first this we did was go to schema to make models.  
The models we created was Author, Category, Comment and Post. 
<img src="./public/developmentplatforms_graphcms-3.png" data-canonical-src="./public/developmentplatforms_graphcms-3.png" width="600" height="auto" />

**! Note:** _Summary with more images or video will come..._



The video shows where to create the models using Hypgraph, and where to create the website content.
[<img src="./public/developmentplatforms_graphcms-3.png" width="100%">](https://www.youtube.com/watch?v=7hnxVRcmN94)


## References
**Docs:** [ReactJS](https://reactjs.org/)  
**Docs:** [NextJS](https://nextjs.org/)  
**Docs:** [TailwindCSS](https://tailwindcss.com/)  
**Docs:** [GraphQL](https://graphql.org/)  
**Docs:** [GraphCMS / Hygraph](https://hygraph.com/)  
**Video:** [Build and Deploy THE BEST Modern Blog App with React](https://www.youtube.com/watch?app=desktop&v=HYv55DhgTuA)   
**Gist:** [Tutorial Featured Post Card](https://gist.github.com/adrianhajdin/2b2e8509a48229baf9bb9b53d4a31c91)  
**Gist:** [Image Resize in GitHub Markdown](https://gist.github.com/uupaa/f77d2bcf4dc7a294d109)  
**Images:** [Pixabay](https://pixabay.com/no/photos/search/chicken%20fried%20rice/?manual_search=1)  
**GitHub:** [Add local repo to GitHub using GitHub CLI](https://docs.github.com/en/get-started/importing-your-projects-to-github/importing-source-code-to-github/adding-locally-hosted-code-to-github)  
**Recipe:** [Chicken Fried Rice](https://www.delish.com/cooking/recipe-ideas/a25635966/chicken-fried-rice-recipe/)  