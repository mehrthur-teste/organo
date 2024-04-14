"# organo" 
echo "# organo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/mehrthur-teste/organo.git
git push -u origin main

#npx create-react-app organo

npm start 
         Starts the development server.

npm run build
        Bundles the app into static files for productions.


npm test
        Starts the test runner.

npm run eject
        Removes this tool and copies build dependencies, configurations files and scripts into the app directory. If you do this, you can't go back!