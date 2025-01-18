# 👋 Hi there!


```sql
CREATE TABLE profile (
    id INT AUTO_INCREMENT PRIMARY KEY,
    firstName VARCHAR(30),
    lastName VARCHAR(30),
    school VARCHAR(100),
    degree VARCHAR(200),
    email VARCHAR(100) NOT NULL
);

CREATE TABLE hobbies (
    hobby_id INT AUTO_INCREMENT PRIMARY KEY,
    id INT NOT NULL,
    hobby VARCHAR(255) NOT NULL,
    FOREIGN KEY (id) REFERENCES profile(id)
);

INSERT INTO profile (firstName, lastName, school, degree, email)
VALUES ('Priyankkumar', 'Patel', 'Northeastern University', 
        'M.S. in Computer Science', 'patelpriyank396@gmail.com');

INSERT INTO hobbies (id, hobby)
VALUES (1, 'Movies 🎞️'), (1, 'Lifting 💪'), 
       (1, 'Gaming 🎮'), (1, 'Reading 📚');
```



Welcome to my GitHub portfolio! My name is **Priyankkumar Patel**, a 24-year-old programmer from **Boston, MA**. 🚀

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=priyank1510&show_icons=true&theme=dracula)






## Tech Stack

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS">
   <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white" alt="R">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  <img src="https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white" alt="Markdown">
  <img src="https://img.shields.io/badge/Visual%20Studio%20Code-0078D4?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="VS Code">
  <img src="https://img.shields.io/badge/Eclipse-2C2255?style=for-the-badge&logo=eclipse&logoColor=white" alt="Eclipse">
  <img src="https://img.shields.io/badge/Photoshop-31A8FF?style=for-the-badge&logo=adobephotoshop&logoColor=white" alt="Photoshop">
</div>

---

## Connect with Me

<div align="center">
  <a href="mailto:patel.priyankk@northeastern.edu"><img src="https://img.shields.io/badge/Email-patel.priyankk%40northeastern.edu-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</div>
