## This is Second Assignment of React js web series

Q.1 What is NPM
Ans. NPM is a package manager means it have a huge collection of packages something 800000 packages we can develop our own package and also can use any package from npm.

Q.2 what is parcel/webpack ? why we do need it.
Ans. parcel and web pack are bundler which bundles several file into one file it have different types of functionality to make the coders life easy.
example :
 p1.js + p2.js + p3.js = oneJs.js
 p1.css + p2.css + p3.css = oneCss.js

Q.3 what is '.parcel-cache'?
Ans. It is a folder stores your dev build file when you build next time it uses it to reduce the time.

Q.4 what is 'npx'?
Ans. npx is stand for node package executable which executes package with in the local or remote.

Q.5 what is difference between dependencies and dev dependencies?
Ans. dependencies : package require for the production.
dev - dependencies : package require for the development and testing.

Q.6 what is tree shaking?
Ans. Tree shaking means removing unused code .

Q.7 Hot Module Replacement
Ans. Hot Module Replacement means when you put any change it reflect to the server directly without restarting every time.

Q.8 List down the 5 parcel fetures and explain any of three .
Ans. Parcel :: Parcel is a beast
parcel have many feature :
1. File watching algorithm
2. Caching
3. Bundling
4. error handling
5. Tree shaking

## File watching algorithm :: 
This algorithm written in cpp and it makes the parcel fast check file every time when change and reflect to the server.
## caching
It is another best feature of parcel used in development mode that when ever parcel load to build the file it cache and when reloading of server it uses cache to reload fast.
## Error handling
Parcel provide connivent way to handle error by showing the error beautifully and clearly which make development so fast.

Q.9 What is gitignore?
Ans. .gitignore is file which is used to tell the git that particular file or folder should not push to the git repo.
Files that are generated after deleting should not be pushed to the Git repository and should be included in the .gitignore file.

Q.10 what is the difference between the package.json and package-lock.json?
package.json - contains the meta data about the project having the details of package that is used in the project.
package-lock.json - contains the versions of all the package that is used in the project.
keep tracks of all the version of the package.
helps to avoid the version conflicts

Q.11 why should not modified the package-lock.json?
Ans. Because it contains all the track of versions that is used in the project . if any dependencies change it keep record it and if it is updated any way than it will create the blunder.

Q.12 what is node_module why not push to git?
Ans. node_module is the local data base of the package that reside in it when ever any thing require from we can directly access to the node_module in the local.
node_module can be regenerate with the help of package.json file thats why we does not pushed it to get.

Q.13 what is 'dist-folder'?
Ans. dist-folder contains the build code of the project which can be directly deployed to the server we can generate this folder by running the npx parcel build.

Q.14 What is browser list ?
Ans. browser list is a way to list the browser in which version or browser should our application work.

