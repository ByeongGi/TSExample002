# 1. Typescript instll 

    npm install -g typescript
    npm install -g typings


### The TypeScript Definition Manager.
Typings is the simple way to manage and install TypeScript definitions.
It uses typings.json, which can resolve to the Typings Registry, GitHub, NPM, Bower, HTTP and local files. 
Packages can use type definitions from various sources and different versions, knowing they will never conflict for users.




# 2. Create  a tsconfig.json
    tsc --init // Create tsconfig.json


# 3. Create a typings.json file

    typings init

# 4. Typescript Definitions File Download 
##  Typescript Definition 파일을 관리하는 Tyyping 설정파일이다.
    typings install dt~node --save --global
    typings install dt~es6-shim --save --global
    typings install dt~express --save
    typings install dt~serve-static --save
    typings install dt~express-serve-static-core --save
    typings install dt~mime --save

# 5.tsc 를 통한 빌드 

    tsc // tsconfig.json에 지정된 설정으로 *.ts -> *.js 
    tsc --watch // 실시간으로 변경분에 대해서 빌드시킴 

