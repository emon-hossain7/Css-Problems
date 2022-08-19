# Css-Problems
have a some css heres


List of startToDeploy:

- [css](#css)
- [grid](#grid)
- [tailwindcss](#tailwindcss)
- [flex](#flex)
- [tailwindcss](#tailwindcss)
- [tailwindcss](#tailwindcss)
- [tailwindcss](#tailwindcss)
- [tailwindcss](#tailwindcss)


### css

```css

.carousel-img {
    height: 70vh;
    object-fit: cover;
}


```
        
### grid

```css
.Shop-area {
    display: flex;
    position: relative;
}

.products-area {
    width: 72%;
    margin: 50px 0;
    display: grid;
    gap: 50px 0;
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
}

.cart-area {
    width: 28%;
    max-width: 430px;
    padding: 20px;
    border-left: 1px solid black;
    background: #ddd;
    position: absolute;
    top: 0;
    height: 100%;
    right: 0;
}

```

### tailwindcss

```css
// step 1 
    npm install -D tailwindcss
    npx tailwindcss init

//step 2
    content: [
    "./src/**/*.{html,js}",
    './components/**/*.{html,js}',
    './pages/**/*.{html,js}',
    './index.html',
    ],

//step 3 (create src/input.css and paste)
    @tailwind base;
    @tailwind components;
    @tailwind utilities;

//step 4
    npm init -y
//step 5
    npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
//step -6
    "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
    },
// replace
    "scripts": {
    "build": "tailwindcss -i ./src/input.css -o ./dist/output.css --watch"
    },
//step -7
// use in index.html file
    <link href="/dist/output.css" rel="stylesheet">
//step - 8
    <h1 class="text-3xl font-bold underline">
    Hello world!
    </h1>

```

### flex

```css
.course-itmes {
    display: flex;
    flex: 0 0 50%;
    flex-wrap: wrap;
    align-items: center;
    justify-content: space-between;
}
   

```





### Table
<div class="overflow-x-auto">
  <table class="table w-full">
    <!-- head -->
    <thead>
      <tr>
        <th></th>
        <th>Name</th>
        <th>Job</th>
        <th>Favorite Color</th>
      </tr>
    </thead>
    <tbody>
      <!-- row 1 -->
      <tr>
        <th>1</th>
        <td>Cy Ganderton</td>
        <td>Quality Control Specialist</td>
        <td>Blue</td>
      </tr>
      <!-- row 2 -->
      <tr>
        <th>2</th>
        <td>Hart Hagerty</td>
        <td>Desktop Support Technician</td>
        <td>Purple</td>
      </tr>
      <!-- row 3 -->
      <tr>
        <th>3</th>
        <td>Brice Swyre</td>
        <td>Tax Accountant</td>
        <td>Red</td>
      </tr>
    </tbody>
  </table>
</div>



## 🌐 Socials: Connect with Emon Hossain!

[![Facebook Badge](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://fb.com/emonhossain6) [![Linkedin Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/emon007iu/) [![Twitter Badge](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/@emon_hossain7) [![Mail Badge](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:emon.hossain.wd@gmail.com)

<h4>❤️🤔 You can follow my Github and other social accounts 🤔❤️</h4>
<h2>❤️ Thank you very much! ❤️</h2>
