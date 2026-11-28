this project is made using html and css and tailwind css 4.3.5 in order to start using tailwind if you want to modify later follow these steps 

1 open the terminal and type this command "npm install tailwindcss @tailwindcss/cli"

2 open the input.css file and type this '@import "tailwindcss";'

3 open terminal and type this command 'npx @tailwindcss/cli -i ./public/css/input.css -o ./public/css/output.css --watch'

i used also a different font for the titles if you want to use it u can put it in the input.css file and use it in your code like this 
'@import url('https://fonts.googleapis.com/css2?family=Bodoni+Moda:ital,opsz,wght@0,6..96,400..900;1,6..96,400..900&display=swap');'

i also used a navbar component for daisy.ui website in order to use it go to your code and put this line 
<!-- '<link href="https://cdn.jsdelivr.net/npm/daisyui@5" rel="stylesheet" type="text/css" />' -->

in this website i used the following colors :

#713310 for main titles buttons  footer background navigation links

#B34A22 for decorative lines links and secondary buttons

#FDF4E9 for main section background

#F9DAB8 for icon background and decorative elements

#FFFFFF for cards and text in dark backgrounds

#4A4A57 for paragraphs and description text

for responsive design i used the max-sm given that i worked desktop first and mostly changing the flex direction column 

for the overall layout i gave every section a px-[2rem] and py-[4rem] 

for the bodoni moda font i used it mainly on main headings section titles body text and navigation and buttons

the project structure:

finale/
│
├── index.html
├── README.md
├── package.json
├── package-lock.json
│
└── public/
    │
    ├── css/
    │   ├── input.css
    │   └── output.css
    │
    ├── images/
    │   ├── hero-women-shield.svg
    │   ├── card-home.svg
    │   ├── card-help.svg
    │   ├── card-laws.svg
    │   ├── card-finding-help.svg
    │   ├── finding-help-pin.svg
    │   ├── help-lantern.svg
    │   └── star.svg
    │
    └── pages/
        ├── help.html
        └── laws.html

to run the project locally from github 

1 download the project from github or clone it using the commande 'git clone https://github.com/oussama-aitmahdi/oussama-aitmahdi-final-project.git

2 open the project folder

3 install the dependencies mentioned earlier