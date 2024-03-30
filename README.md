# EX01 Developing a Simple Webserver
## Date: 30/03/2024

## AIM:
To develop a simple webserver to serve html pages.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My page</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <style>
        /* Basic styling for the page */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image:url('SSS.jpeg');
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        /* Header styles */
        .header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        .logo {
            font-size: 24px;
            font-weight: bold;
            text-decoration: none;
            color: #fff;
        }
        .nav-items {
            margin-top: 10px;
        }
        .nav-items a {
            margin-right: 20px;
            text-decoration: none;
            color: #fff;
        }
        /* Main content styles */
        .intro {
            text-align: center;
            margin-top: 40px;
        }
        .intro h1 {
            font-size: 36px;
        }
        .intro p {
            font-size: 18px;
            color: #555;
        }
        .achievements {
            display: flex;
            justify-content: space-between;
            margin-top: 40px;
        }
        .work {
            text-align: center;
           }
        .work i {
            font-size: 24px;
            color: #333;
        }
        .work-heading {
            font-size: 18px;
            font-weight: bold;
            margin-top: 10px;
        }
        .work-text {
            font-size: 16px;
            color: #777;
        }
        /* Footer styles */
        .footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
        }
        .border{

            border-radius: 25%;
            border-left: 25%;
            border-right: 25%;
        }
       </style>
</head>
<body>
    <div class="container">
        <header class="header">
            <a href="#" class="logo">my page</a>
            <nav class="nav-items">
                <a href="#" class="bi bi-house">Home</a>
                <a href="#" class="bi bi-file-earmark-person">About</a>
                <a href="#" class="bi bi-person-rolodex">Contact</a>
            </nav>
        </header>
        <main>
            <div class="intro">
                <h1 style="color: red;">A Web Developer</h1>
            </div>
            <div>
            </div>
            <div class="achievements">
               <div class="work">
                    <i class="fas fa-atom"></i>
                    <p class="work-heading" style="color: white;">Projects</p>
                    <p class="work-text" style="color:white;">I have worked on many projects.</p>
                </div>

            </div>
        </main>
<div>
    <div class="container">
        <div class="background-image">
          <!-- Login Form -->
          <div class="login-form">
              <h2>Login:</h2>
              <form action="your_login_script.php" method="POST">
                  <input type="text" name="username" class="border" style="color: red;"placeholder="Username" required><br>
                  <input type="password" style="color: red;" name="password"class="bi bi-person border" placeholder="Password" required><br>
                  <button type="submit" style="color:green" class="bi bi-box-arrow-in-left border">Login</button>
              </form>
          </div>
      </div>
</div>
<div>
    <h6 style="color: white;">
  Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias obcaecati beatae delectus nisi error est animi, voluptas ducimus sunt inventore officiis dolorem esse maxime doloribus aliquam, recusandae facilis itaque sit atque architecto quae sint officia. Neque placeat et debitis possimus suscipit odio non, aut laboriosam saepe, a vitae ea. Asperiores nemo atque aspernatur, cupiditate quam possimus voluptatibus? Corporis quidem, saepe, culpa minima ad dolor accusantium placeat quos voluptatem necessitatibus obcaecati vel ipsa! Blanditiis a excepturi atque exercitationem cum sed delectus ratione dolor qui similique. Fugit atque consequuntur autem blanditiis rerum excepturi cum velit vitae esse inventore? Sit deleniti amet excepturi, reprehenderit nemo eos architecto aperiam ab assumenda sint. Dolores porro doloribus eos doloremque eveniet velit incidunt repellendus eaque ea eum maxime exercitationem ratione officiis mollitia error impedit dignissimos, aperiam libero aliquam quod sed! Repudiandae perferendis amet, ducimus, blanditiis est modi perspiciatis architecto nostrum ratione aut velit necessitatibus iste magni consequuntur.
    </h6>
</div>          
        <footer class="footer">
            thank you for visiting...
        </footer>
    </div>
</body>
</html>
```

## OUTPUT:
![WhatsApp Image 2024-03-30 at 15 37 04_a13eea50](https://github.com/Neethiventhan123/simplewebserver/assets/148514848/dc35f312-289c-4fff-b058-6420d7f76a1a)

## RESULT:
The program for implementing simple webserver is executed successfully.
