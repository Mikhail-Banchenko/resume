
Resume Website — Two-Column Layout
----------------------------------

Structure:
- Left column: About me, Personal info, Skills
- Right column: Experience, Education
- Photo placeholder (photo.jpg) at the top.

To deploy:
1. Create a public GitHub repo.
2. Copy these files into it.
3. Run in terminal:
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/USERNAME/REPO.git
   git push -u origin main
4. In GitHub -> Settings -> Pages -> select branch `main` -> `/ (root)`.
5. Your site will appear at https://USERNAME.github.io/REPO/

Add your own `photo.jpg` to replace the placeholder.
