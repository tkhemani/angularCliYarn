**Setup:**

* Create package.json 
* Run this to set offline cache: yarn config set yarn-offline-mirror ./npm-packages-offline-cache
* This will create a .yarnrc file in your HOME directory (c:\users\<userName>. Move this file to the project root.
* Install angular cli as either one of below:
    * **global dependency**: `yarn global add @angular/cli` 
    * **dev dependency**: `yarn add @angular/cli -D`. Note that in this case, you'll have to add your local project path (eg. _C:\code\ngCli\node_modules\.bin_) to env variables for `ng new PROJECT_NAME` and other commands to work.

_ref: https://yarnpkg.com/blog/2016/11/24/offline-mirror/_
