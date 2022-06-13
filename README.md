Quick start guide for Ionic (with Angular)





















Basic requirements :



- Node Js ( Any LTS version )
- Angular CLI ( Latest version )


Installing Angular from CLI :

- Use below command to install angular CLI ( before proceeding make sure Nodejs is installed )
  - `  `npm install -g @angular/cli    

Installing Ionic :

- Use below command to install Ionic 
  - npm install -g @ionic/cli

Starting new Ionic application :

- To create new ionic app follow below steps :
  - ` `ionic start  appName

`	`By running ionic start command in terminal it will ask you for other required informations like below


















Select supporting framework like Angular, 

After selecting angular, it will ask you for sample template to start with 



Selected Tab template, after selecting template the boilerplate code will get generated with Angular framework 
















Now empty project directory is ready to get started with our business requirements 

The project structure will look like below

viveks@Viveks-MacBook-Air app % tree      

.

├── app-routing.module.ts

├── app.component.html

├── app.component.scss

├── app.component.spec.ts

├── app.component.ts

├── app.module.ts

├── explore-container

│   ├── explore-container.component.html

│   ├── explore-container.component.scss

│   ├── explore-container.component.spec.ts

│   ├── explore-container.component.ts

│   └── explore-container.module.ts

├── tab1

│   ├── tab1-routing.module.ts

│   ├── tab1.module.ts

│   ├── tab1.page.html

│   ├── tab1.page.scss

│   ├── tab1.page.spec.ts

│   └── tab1.page.ts

├── tab2

│   ├── tab2-routing.module.ts

│   ├── tab2.module.ts

│   ├── tab2.page.html

│   ├── tab2.page.scss

│   ├── tab2.page.spec.ts

│   └── tab2.page.ts

├── tab3

│   ├── tab3-routing.module.ts

│   ├── tab3.module.ts

│   ├── tab3.page.html

│   ├── tab3.page.scss

│   ├── tab3.page.spec.ts

│   └── tab3.page.ts

└── tabs

`    `├── tabs-routing.module.ts

`    `├── tabs.module.ts

`    `├── tabs.page.html

`    `├── tabs.page.scss

`    `├── tabs.page.spec.ts

`    `└── tabs.page.ts

5 directories, 35 files

Running sample template :

- To make the sample app run we need to make use of below command:
  - ionic serve

By running this command a development server will get started in the default port 8200, with live changes enabled 

After serving the app we can access it on localhost:8200 , running sample example look like this 












Advantage of using ionic framework.

- Easy to build mobile compatible applications / Sites
- Can build web, ios, Android apps with existing JS/TS files 


Steps to build an android application.

- Install Android studio 
  - Download and install android studio <https://developer.android.com/studio>


6
