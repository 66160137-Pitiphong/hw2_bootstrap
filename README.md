# hw2_bootstrap
git clone
git commit -m 
git checkout -b development
touch index.html places.html contact.html
touch css/style.css
git add .
git commit -m 
git checkout -b feature/home-page
git checkout -b feature/places-page
git add index.html 
git add places.html
git add contact.html 
git add css/style.css 
git checkout development 
git merge feature/home-page 
git merge feature/places-page 
git merge feature/contact-page
git push origin development