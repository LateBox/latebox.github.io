**Only edit the input.css file the files inside src folder, a GitHub action automatically pushes it to the gh-pages branch**  

input.css is not inside the source folder to have a fast loading speed since Tailwind CSS only outputs the necessary CSS.  

# Development
1 - npm install  
2 - npx tailwindcss -i ./input.css -o ./src/output.css --watch  
