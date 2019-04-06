#esctestgen
Angular Jasmine Unit Test Spec Generator

## How It Works


1. Run esctestgen my.component.ts 
2. write a unit test to my.directive.spec.ts in the same folder 
3. if the file name exists it generates the file name with -s # write a unit test to my.directive.spec.YYYMMDDHHMM.ts


## Install & Run
```
$ npm install esctestgen -g # to run this command anywhere
$ esctestgen my.component.ts 
$ esctestgen my.directive.ts 
$ esctestgen my.pipe.ts 
$ esctestgen test my.service.ts