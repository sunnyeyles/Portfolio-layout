npm init -init package.json file and setup project

--install dependencies--

--save flag -save packages to the project

*check in package.json if dependencies were installed after installing

npm install --save-dev sass -install first package

npm i bootstrap@5.2.0 --save -install bootstrap 5 and save as dependency

npm install --save @fortawesome/fontawesome-free -install font awesome package

npm install postcss-cli autoprefixer --save -install autoprefixer package

--making scrips and folders--

"compile:sass":"sass scss:assets/css" -create script and tell it where to go

create scss folder with style.scss

npm run compile:sass -run the script we just made to compile sass, this will create an assets folder with style.css and style.css.map, this folder will keep all compiled css

"compile:sass":"sass --watch scss:assets/css" - --watch flag will tell it to watch for changes

*check if scss is compiling to css file


--overriding bootstrap variables--

create _custom.scss folder to create variables - _filename.scss, the underscore will tell it to not compile to css

@import "../node_modules/bootstrap/scss/bootstrap.scss" -inside _custom.scss file to import bootstrap

@use "custom"; -into style.scss file

*copy variables from bootstrap variables file


@use"../custom" as * - in all sections and component files to use the custom variables














