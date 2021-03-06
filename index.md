## Amit Marcus (@marxus) CV

### 1️⃣ One Liner:

FullStack Developer (Python/JavaScript) with a DevOps orientation for a good neat and clean app deployment (containerized/serverless) on the cloud (mostly AWS experience).

### 🔍 Looking For:

A place I can enjoy acquiring and improving my current skills in larger scales, with new tech, modern best-practices and a strong dev team, mainly in the Backend/DevOps fields.

I have a lot of experience working solo or in small development teams (2-3 members) where I performed the broad spectrum of roles, and self-taught myself new techs and expertise, as shown in my skill set and past experience.

### 💼 Experience:

**_2019-2020: Drorsoft (a web-dev cooperative)_**
*   **Roles:**  
    FullStack Web Developer  
    DevOps & AWS Administrator  
    Teaching and Mentorship

*   **Tech Used:** <tech-used>#python #django #jupyter #flask #aws #aws-lambda #ecs #docker #terraform #javascript #react #nginx #linux #mariadb #postgresql</tech-used>

*   **Activities:** websites, integration and deployment pipelines, infrastructure as code services, cloud migration services, teaching and mentoring newbies on python and javascript

**_2014-2019: ITmyWay (salesforce integration services)_**
*   **Roles:**  
    FullStack Salesforce Developer

*   **Tech Used:** <tech-used>#salesforce #apex #visualforce #javascript #react</tech-used>

*   **Activities:** customer facing services such as api integration, data manipulation, user communities & portals, mobile-first single page apps (basically it’s like fullstack within the salesforce cloud ecosystem)

**_2010-2013: 4P-Tech (one stop shop for web-dev)_**
*   **Roles:**  
    Co-Founder & CTO  
    FullStack Web Developer  
    DevOps

*   **Tech Used:** <tech-used>#python #turbogears #django #fabric #node.js #express #aws #ec2 #rds #linux #nginx #supervisord #javascript #angularjs</tech-used>

*   **Activities:** customer facing services such as websites building, facebook integrations, customized information system and crm, include hosting and maintenance

**_2009-2020: HaNoar HaOved VeHaLomed (NGO, social movement, as a volunteer)_**
*   **Roles:**  
    FullStack Web, Game & Mobile Apps Developer  
    DevOps & AWS Administrator

*   **Tech Used:** <tech-used>#python #turbogears #django #jquery #angularjs #react #node.js #webpack #phonegap #cordova #linux #aws #docker #terraform #mariadb #postgresql #actionscript</tech-used>

*   **Activities:** various websites, web games, in-house apps for crm, budget accounting management and membership registration, mobile app dev

**_2009-2012: Dror Israel (NGO, social movement)_**
*   **Roles:**  
    Network & NT Domain Administrator (“IT”)  
    FullStack Web Developer

*   **Tech Used:** <tech-used>#window-server #exchange #active-directory #office365 #fortigate #vmware #c# #dotnet #iis #mssql</tech-used>

*   **Activities:** ~500 users domain administration, on-prem to cloud migration project (office365/azure), establishing new physical sites (fw/routers/switches/vlans…), in-house web information system/portal development

### Skills:

**_🐍 Python:_**

*   Backend - various frameworks such as Flask/Bottle/TurboGears and Django
*   Worked with popular tooling such as venv/pipenv/poetry, pytest/unittest/nose, standard libs and other open source packages
*   Automation and general purpose scripts for *nix envs
*   Can work with the now EOL py2 branch when and if needed
*   Familiar with static type annotation and checkers such as mypy, although really like python’s dynamic duck-type nature, monkey-patchable import system 🐒(see [destructipy](https://github.com/marxus/destructipy))

**_📜 JavaScript/Node.js:_**

*   Frontend - using React ⚛️ (+1 for hooks), familiar with AngularJS and some VueJS. undoubtedly prefers React for it’s immutable one-way data flow design
*   Browser (“html5”) api and interacting with the dom, using vanilla js and legacy libs such as jQuery💲
*   Good understanding of the async event loop nature of the language
*   Bundle tools, transpilers and preprocessors - npm/yarn, webpack, babel and less/sass/postcss, compiled-to-js languages such as typescript and coffeescript ☕ (see [babel-plugin-transform-property-prefix-symbol](https://github.com/marxus/babel-plugin-transform-property-prefix-symbol))
*   Backend - some express.js experience
*   Mobile - Android 🤖/iOS dev using Cordova/PhoneGap 📱

**_☁️ Cloud:_**

*   AWS General usage using IAM roles, S3, Route53, SES, SQS, RDS, CloudWatch
*   AWS Deploying serverless Lambda λ apps behind API-Gateway/ALB
*   AWS Deploying containerized apps on ECS using Fargate
*   AWS More advanced VPC usages: EC2, networking, security groups, setting up bastion hosts and vpn access
*   Some experience with deploying apps on Google Cloud Platform and Microsoft's Azure
*   Salesforce platform fullstack developer - apex extensions, visualforce, api integrations

**_⚙️ DevOps:_**

*   Infrastructure as Code - Terraform 🌎 used for provision cloud resources (also wrote a small opinionated wrapper for terraform)
*   CI/CD on the cloud - using AWS CodePipeline
*   Docker 🐳 - writing Dockerfile and docker-compose.yml files
*   Deploying and maintaining web apps on linux🐧 servers using nginx and supervisord
*   Worked with PostgreSQL/MySQL/MariaDB locally and on AWS RDS
*   Accustomed to the GNU/Linux toolchain, bash scripting, git, curl, etc…

### 💻 Setup:

*   Usually working under Linux (currently KDE Neon/Ubuntu 20.04) with PyCharm, WebStorm and VSCode

### ⁉️ About:

*   35 years old
*   Coding on and off since the bar mitzvah (started with the good ol’ Turbo Pascal). on a regular basis since 2009
*   Currently lives in Beer-Sheva 🐪, Israel
*   In a relationship. expecting +1 soon 👶
*   Languages: Hebrew, English
*   Bachelor of Education from Beit-Berl College
*   Tour and Moreshet guide from HaMeorer institute
*   For sports and fun: rock climbing 🧗‍♂️, running 🏃‍♂️ and road cycling 🚴🏿

### 📨 Contact:

*   Email: [marxus@gmail.com](mailto:marxus@gmail.com)
*   LinkedIn: [marxus](https://www.linkedin.com/in/marxus)
*   Mobile: 972-54-6734595

<script>
// O(a*b)
for (const techUsed of document.querySelectorAll('tech-used')) { // a
    techUsed.innerHTML = techUsed.innerText
        .split(' ')
        .map(tech => { // b
            const tag = encodeURIComponent(tech.substr(1))
            return `<a href="https://stackoverflow.com/questions/tagged/${tag}" target="_blank">${tech}</a>`
        })
        .join(' ')
}
</script>
