<!-- Rivison React.js -->
  Day 01 to 75 hard day challange 

    *********These Topics are coverd today***********
- What is `NPM`?
● - What is `Parcel/Webpack`? Why do we need it?
● - What is `.parcel-cache`
● - What is `npx` ?
● - What is difference between `dependencies` vs `devDependencies`
● - What is Tree Shaking?
● - What is Hot Module Replacement?
● - List down your favourite 5 superpowers of Parcel and describe any 3 of them in your
own words.
● - What is `.gitignore`? What should we add and not add into it?
● - What is the difference between `package.json` and `package-lock.json`
● - Why should I not modify `package-lock.json`?
● - What is `node_modules` ? Is it a good idea to push that on git?
● - What is the `dist` folder?
● - What is `browserlists`
Read about dif bundlers: vite, webpack, parcel
● Read about: ^ - caret and ~ - tilda

Ans With all >

Today i was seprated the files like html , css, app.js and create own create-react-app to make production ready app
 
 these points always on our mind when you build production app
<!--  first thing i need to minify the code and optimize the app bundl it the on server i learned that react is powerfull tool but it can not do everything alone thats why we use bundlers like ->01 vite,
02>parcel
03>webpack

in this project i used to parcel just bcz its very easy to understand and zero config and provieds to lot of feathures 
 -->
 <!--  first thing how to write a command 
 01--->Npm init -->which is given me package.json along with exiting file 
 package.json data containes my project inculde data which is required for me 

 02--> Npm install -D parcel 
 when we install this command then i got a pakage-lock-json file which is ensured that my app used to exact verison of the package 

 03--> caret(^),and (~) tilde is sign in font version like which verions my app is run suposed  if you use caret that time it is used when changed in miner changes that time we used but when we used so that time we used tilde bcz of it show to major changes handle it 
  
  03---> Npm react install,npm react-dom,
  and when we install than removed to our cdn links 

  04--->Test command->Npx parcel index.html which is used to entry point it runs our localhost:1234
  and when you want to build our app then
  We can used to {npm parcel build index.html}

   
  -->
  <!-- Psrcel is best -->
  <!-- 01--HMR(hot module replacement)
       02--File wacther algorithn in c++ writen
       03--Bundling
       04--Code MiniFication
       05--Image Optimization
       06--Chaching
       07--Consitent hashing
       08--Code spiliting
       09--Differentiol bundling -it support to older verison of browser
        -->