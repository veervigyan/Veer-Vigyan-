<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Veer Vigyan</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      color: white;
      background: linear-gradient(135deg, red, orange, yellow, green, blue, indigo, violet);
      background-size: 400% 400%;
      animation: rainbow 20s ease infinite;
    }

    @keyframes rainbow {
      0% {background-position: 0% 50%;}
      50% {background-position: 100% 50%;}
      100% {background-position: 0% 50%;}
    }

    nav {
      background: rgba(0, 0, 0, 0.6);
      padding: 1rem;
      text-align: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    section {
      padding: 2rem;
      margin-top: 1rem;
      background: rgba(0, 0, 0, 0.4);
      border-radius: 12px;
      max-width: 800px;
      margin-left: auto;
      margin-right: auto;
    }

    h1, h2 {
      text-align: center;
    }

    .quiz {
      margin-top: 20px;
    }

    .question {
      margin-bottom: 15px;
    }

    .question p {
      margin: 0;
      font-weight: bold;
    }

    label {
      display: block;
      margin-left: 20px;
    }
  </style>
</head>
<body>

  <nav>
    <a href="#home">Home</a>
    <a href="#pdf">PDF</a>
    <a href="#books">Books</a>
    <a href="#classes">Classes</a>
    <a href="#quiz">Quiz</a>
    <a href="#mcqs">MCQs</a>
  </nav>

  <section id="home">
    <h1>Welcome to Veer Vigyan</h1>
    <p>Veer Vigyan means "All Science". This website is built by Veer, a passionate student dedicated to helping others learn and grow. Here, students can access free books, PDFs, quizzes, classes, and much more. Let's learn together!</p>
  </section>

  <section id="pdf">
    <h2>PDF Section</h2>
    <p>Here you can find helpful PDFs for your studies. (Coming soon...)</p>
  </section>

  <section id="books">
    <h2>Books Section</h2>
    <p>Explore books recommended for science learners. (Coming soon...)</p>
  </section>

  <section id="classes">
    <h2>Classes Section</h2>
    <p>Watch classes and tutorials to boost your knowledge. (Coming soon...)</p>
  </section>

  <section id="quiz" class="quiz">
    <h2>Quiz Section</h2>
    <div class="question">
      <p>1. What is the boiling point of water?</p>
      <label><input type="radio" name="q1"> 90°C</label>
      <label><input type="radio" name="q1"> 100°C</label>
      <label><input type="radio" name="q1"> 120°C</label>
    </div>
    <div class="question">
      <p>2. Which planet is known as the Red Planet?</p>
      <label><input type="radio" name="q2"> Earth</label>
      <label><input type="radio" name="q2"> Mars</label>
      <label><input type="radio" name="q2"> Jupiter</label>
    </div>
  </section>

  <section id="mcqs" class="quiz">
    <h2>MCQ Practice</h2>
    <div class="question">
      <p>1. What is the symbol of Sodium?</p>
      <label><input type="radio" name="m1"> So</label>
      <label><input type="radio" name="m1"> Na</label>
      <label><input type="radio" name="m1"> S</label>
    </div>
    <div class="question">
      <p>2. Which gas do plants absorb?</p>
      <label><input type="radio" name="m2"> Oxygen</label>
      <label><input type="radio" name="m2"> Carbon Dioxide</label>
      <label><input type="radio" name="m2"> Hydrogen</label>
    </div>
  </section>

</body>
</html>
