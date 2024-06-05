In this article, I’ll walk you through the process of creating a simple React app and connecting it to a simple Node/Express API that we will also be creating.The objective here is to give you a practical guide on how to set up and connect the front-end client and the back-end API.
Create a React App {
npx create-react-app client
cd client
npm start
localhost{http://localhost:3000}

}
Create an Express App{
npm init -y
npm i nodemon
npm i express
"scripts": {
  "start": "node server/index.js"
},
npm start
}
Create an MongoDB{
After installing MongoDB, the next step would be the opening of your command line, then create a new directory for the project we will be working on using this command mkdir directory_name this would quickly create your new directory, then you would need to be in the newly created directory by using the following command cd directory_name this would give you access to the directory you have created.
In this project, we would be working with the express generator to quickly create our application skeleton. For earlier Node versions, install the generator as a global npm package and then launch it using the following command npm install -g express-generator. This would automatically install the express generator globally on your local machine, after installation, you would be required to type 
express in your command line, this will create all the required files to set up your express app skeleton.Running the express command in the command line, after installing express-generator automatically created an index.js file. Once created, we will need to require all our packages at the top of our app.js file, for the file created using the express command, you will already have the
express dependency declared at the top of the index.js file, all you will need to do is require the dotenv and mongoose packages.
app.listen(4000)
}
