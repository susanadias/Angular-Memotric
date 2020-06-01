# Angular-Memotric
Template 

npm install --save-dev typescript




https://thecodebuzz.com/cannot-find-module-angular-devkit-build-angular-package-json/




I solved the issue by following 2 steps

1) First remove "ngx-daterangepicker-material": "^2.2.1" from package.json

2) Run "npm i ngx-daterangepicker-material@2.2.0"

3) "ng serve"

It will compile successfully
