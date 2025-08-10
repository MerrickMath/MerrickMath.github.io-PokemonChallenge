<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>Pokémon Challenge Overview</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    /* Optional: mild styling for the referenced classes */
    .prof { max-width: 220px; height: auto; }
    .frame { width: 100%; max-width: 720px; height: 405px; }
    body { font-family: system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, sans-serif; line-height: 1.6; padding: 1rem; color: #111; }
    h1, h2, h3 { line-height: 1.25; }
    img { display: block; margin: 0 auto; }
    iframe { display: block; margin: 0.75rem auto; border: 0; }
    ul { padding-left: 1.2rem; }
  </style>
</head>
<body>

  <p>Vince Ketchum is a <strong>famous</strong> Pokémon trainer. Recently, he has become very curious about the nature of Pokémon and has hired you, a young, budding statistician, to conduct a research project.</p>

  <p align="center">
    <img class="prof" src="https://merrickmath.github.io/MerrickMath.github.io-PokemonChallenge/trainer.png" alt="Trainer Vince Ketchum">
  </p>

  <p>
    Vince has collected data on 802 species of Pokémon and has entered his data into the
    <a href="https://merrickmath.github.io/MerrickMath.github.io-PokemonChallenge/challenge.csv">challenge.csv</a>
    file (right-click to download to your home desktop). Vince has also noted that there is a more detailed dataset that can be found
    <a href="https://www.kaggle.com/rounakbanik/pokemon">here</a>.
  </p>

  <p>The dataset contains 802 observations and 12 variables:</p>
  <ul>
    <li><strong>Name:</strong> Name of Pokémon</li>
    <li><strong>Type:</strong> Type of Pokémon</li>
    <li><strong>Height:</strong> Height of Pokémon in <strong>metres</strong></li>
    <li><strong>Weight:</strong> Weight of Pokémon in <strong>kilograms</strong></li>
    <li><strong>Capture Rate</strong></li>
    <li><strong>Happiness:</strong> Baseline happiness of Pokémon</li>
    <li><strong>HP:</strong> Hit Points of a given Pokémon</li>
    <li><strong>Attack:</strong> Base Attack of Pokémon</li>
    <li><strong>Defense:</strong> Base Defense of Pokémon</li>
    <li><strong>Speed:</strong> Base Speed of Pokémon</li>
    <li><strong>Generation:</strong> Generation in which the Pokémon was first introduced</li>
    <li><strong>Is_legendary:</strong> Whether the Pokémon is legendary or non-legendary</li>
  </ul>

  <p>Vince has formulated some <strong>important</strong> questions that will help him defeat the notorious Team Rocket:</p>

  <ul>
    <li>
      <p><strong>What is the strongest Pokémon? Why?</strong><br>
      What makes a Pokémon strong? Do some Pokémon have higher attributes than others?</p>
    </li>

    <li>
      <p><strong>Do a Pokémon’s attributes (Attack, Defense, weight, height, Speed, etc.) vary based on its type?</strong><br>
      For this question, Vince is trying to understand how all attributes of a Pokémon vary based on type. Perhaps “Dragon” Pokémon are significantly heavier than “Bug” Pokémon. Perhaps “Fire” Pokémon have higher attack than “Water” Pokémon.</p>
    </li>

    <li>
      <p><strong>Are legendary Pokémon significantly stronger than non-legendary Pokémon?</strong><br>
      Vince has discovered a type of Pokémon referred to as “legendary” that he believes are significantly stronger than regular Pokémon. He would like to know if the data provides sufficient evidence for his hypothesis.</p>
    </li>

    <li>
      <p><strong>Emotional Pikachu:</strong><br>
      Vince’s Pikachu has a base happiness of 120. He would like to know if this can be considered a <strong>significantly</strong> “high” or “low” happiness score.</p>
    </li>

    <li>
      <p><strong>Is there an association between a Pokémon’s weight and height?</strong><br>
      Vince has noticed that Pokémon come in all different shapes and sizes; he is curious if a Pokémon’s weight is associated with its height.</p>
    </li>

    <li>
      <p><strong>Have Pokémon from newer generations become stronger or weaker than those in older generations?</strong><br>
      Pokémon are released in generations. Vince is curious if there is a significant difference between the attributes of Pokémon based on their generation.</p>
    </li>
  </ul>

  <p>
    For your report, Vince asks that you explore 2 (or more) of these questions. You are also <strong>encouraged</strong> to raise questions of your own that you may answer or explore in your report. Your report may be delivered in <strong>any</strong> format (PDF, Word document, video, website, etc.). You will be judged on a 20-point scale made up of two categories:
  </p>
  <ul>
    <li><strong>Mathematical and statistical argumentation</strong> (10 points)</li>
    <li><strong>Aesthetic</strong> (10 points)</li>
  </ul>

  <p>Good luck, and have fun!</p>

  <p align="center">
    <iframe
      src="https://www.youtube.com/embed/6xKWiCMKKJg"
      class="frame"
      title="Pokémon Challenge Video"
      allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
      allowfullscreen>
    </iframe>
  </p>

  <h3>Challenge submission</h3>
  <ul>
    <li>Submissions are now <strong>closed</strong>. Check out the winning report
      <a href="https://merrickmath.github.io/MerrickMath.github.io-PokemonChallenge/Winner.pdf">here</a>.
    </li>
  </ul>

</body>
</html>
