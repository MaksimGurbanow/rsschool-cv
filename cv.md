<header style="display: flex; align-items: center; justify-content: space-between; width: 100%; margin-bottom: 20px;">
  <div>
    <h1 style="margin: 0;">Maksim Gurbanov</h1>
    <h3 style="margin: 0;">Frontend Developer</h3>
  </div>
  <img src="./images/photo.jpg" alt="My photo" width="200" style="border-radius: 50%; aspect-ratio: 1; object-fit: cover;" />
</header>


### Contacts
- **Phone:** +905010696899
- **E-mail:** maksim20051708@gmail.com
- **Telegram:** @maksim_gurbanow

## About me:

I'm motivated individual with a strong desire to obtain my first job as a Frontend Developer. I have a big interest in creating user-friendly web interfaces, sites. My goal is to make a meaningful contribution in the world. I'm excited to bring my skills and creativity and obtain neccessary knowledge from team of experienced developers. Please, contact me, if I interested you.

## 🛠 Skills: 
- **💻 Frontend** - TypeScript, JavaScript, HTML / CSS, React, Next.js, Redux Toolkit, Sass/Scss

- **⚙️ Backend** - Node.js, NestJS, Express.js, GraphQL, REST APIs

- **🗄️ Databases** - PostgreSQL, MySQL, MongoDB, Prisma ORM

- **☁️ DevOps & Tools** - Docker, Git & GitHub, CI/CD (GitHub Actions), Linux / Bash  

- **🎨 Other** - Responsive Design, Testing (Vitest, Jest, React Testing Library), Agile / Scrum, Chrome Extensions Development  

- **Languages** - Russian(Native Speaker), English(C1), Turkish(C1), French(B1)

## 🎓 Education

**Bachelor of Music**  
*Cukurova University, Adana, Türkiye*  
Expected Graduation: [Year]

**Courses** 
- JavaScript/Frontend - [certificate](https://app.rs.school/certificate/7p3wu71q)
- React - [certificate](https://app.rs.school/certificate/aa7h7he1)
- AWS Fundmentals by RS School - [certificate](https://app.rs.school/certificate/ko5r1395)
- AWS Cloud Developer by RS School - [certificate](https://app.rs.school/certificate/qw5kfi0y)
- AWS Cloud Quest: Cloud Practitioner - [Training Badge](AWS Cloud Quest: Cloud Practitioner - Training Badge)
- Angular - [certificate](https://app.rs.school/certificate/968hfuw5)

## Work Experience
**Frontend Developer — AppStruct**  
*1 year*  

- Developed a **no-code platform** aimed at businesses looking to create applications more easily and efficiently.  
- Designed and implemented **user-friendly interfaces** to improve customer experience.  
- Built and maintained reusable **React components** with TypeScript, ensuring scalability and consistency.  
- Integrated APIs and optimized application performance for smooth functionality.  
- Created a **Chrome extension** that allowed users to copy and extract structured elements directly from web pages, streamlining workflow.  
- Collaborated with a team of developers and designers, gaining experience in **Agile methodology** and version control with **Git/GitHub**.  

## Code Examples:
```JavaScript
function curryPartial(func, ...args) {
  if (args.length >= func.length) {
    return func(...args);
  } else {
    return function(...nextArgs) {
      return curryPartial(func, ...args, ...nextArgs);
    };
  }
}

```

```JavaScript
Array.prototype.map = function(callback, context) {
  const arr = new Array(this.length);
  for (let i = 0; i < this.length; i++) {
    const c = this[i];
    if (Object.prototype.hasOwnProperty.call(this, i)) {
      const result = callback.call(context || this, c, i, this);
      arr[i] = result;
    } else {
      arr[i] = c;
    }
  }
  return arr;
};
```