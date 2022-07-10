# My-First-website
About Jawaharlal Nehru

CSS CODE

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  .container {
    background-color: #e5e5fd;
    min-height: 100vh;
    border: 10px solid #1d1e4c;
  }
  
  .content {
    max-width: 900px;
    margin: 0 auto;
  }
  .top_section {
    margin-top: 100px;
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
  }
  .top_section h1 {
    font-size: 50px;
    font-weight: bold;
    color: #1d1e4c;
    text-transform: uppercase;
  }
  .top_section h4 {
    font-size: 30px;
    text-align: end;
  }
  
  .image_container {
    border-radius: 50%;
    overflow: hidden;
  }
  
  .image_container,
  img {
    width: 300px;
    height: 320px;
  }
  .about_section {
    margin-top: 50px;
  }
  .about_section h2 {
    font-size: 70px;
    font-weight: 400;
    margin-bottom: 20px;
  }
  .about_section p {
    font-size: 20px;
    line-height: 30px;
    letter-spacing: 1.2px;
    text-align: justify;
  }
  .biography_section {
    margin: 50px 0;
  }
  .biography_section h3 {
    margin-bottom: 20px;
  }
  .biography_section ul {
    margin-left: 50px;
  }
  .biography_section li {
    margin-bottom: 15px;
  }
  
  footer {
    margin: 50px 0;
  }
  footer p {
    text-align: end;
  }
  
  HTML CODE
  
  <!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />

    <meta http-equiv="X-UA-Compatible" content="IE=edge" />

    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>The Tribute Website | Jawaharlal Nehru</title>
    <link rel="stylesheet" href="style.css" />
    <ul>
      <li>Home</li>
      <li>About</li>
    </ul>
  </head>
  <body>
    <div class="container">
      <div class="content">
        <section class="top_section">
          <div class="image_container">
            <img src="Jawaharlal Nehru.jpg" alt="tribute" />
          </div>
          <div>
            <h1>Jawaharlal Nehru</h1>
          </div>
        </section>
        <section class="about_section">
          <p>
            <b>Pandit Jawaharlal Nehru was born on 14th November 1889. He was the single child of Motilal Nehru and Swarup Rani Nehru. Nehru was one of the most renowned barristers and was known for his intellectual capabilities which soon made him one of the greatest politicians India had ever seen. Nehru, under the approval of Gandhi, his mentor, rose to become one of the most dominant figures in Indian politics from the 1930s onwards. Nehru, after much deliberations, accepted the partition proposal for India in 1947 and took oath as the First Prime Minister of India after attaining independence. His birthday on 14 November is widely celebrated in India as Children’s day.</b>
          </p>
        </section>
        <section class="about_section">
        <h3>Salt March: 1930</h3>
      </section>
      <section class="about_section">
        <p>
          Nehru and most of the Congress leaders were ambivalent initially about Gandhi's plan to begin civil disobedience with a satyagraha aimed at the British salt tax. After the protest had gathered steam, they realised the power of salt as a symbol. Nehru remarked about the unprecedented popular response, "it seemed as though a spring had been suddenly released". He was arrested on 14 April 1930 while on a train from Allahabad for Raipur. Earlier, after addressing a huge meeting and leading a vast procession, he had ceremoniously manufactured some contraband salt. He was charged with breach of the salt law and sentenced to six months of imprisonment at Central Jail.
        </p>
      </section>
      <section class="about_section">
          <h3>Points</h3>
        </section>
        <section class="about_section">
          <ul>
            <li>
              Born: 14 November 1889, Prayagraj
            </li>
            <li>
              Died: 27 May 1964, New Delhi.
            </li>
            <li>
              Spouse: Kamala Nehru (m. 1916–1936)
            </li>
            <li>
              AParents: Motilal Nehru
            </li>
            <li>
              Famously Known As: Chacha Nehru, Pandit Nehru
            </li>
          </ul>
        </section>
        <footer>
          <p>
            Read more about Jawaharlal Nehru on
            <big><i><a href="https://www.britannica.com/biography/Jawaharlal-Nehru/Achievements-as-prime-minister">Click here</a>></i></big>
          </p>
        </footer>
      </div>
    </div>
  </body>
</html>
