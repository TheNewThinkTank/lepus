# Welcome to the Rabbit Gallery

This site is dedicated to showcasing adorable moments of rabbit!

<button id="randomFactBtn">Show a Random Rabbit Fact</button>
<p id="rabbitFact"></p>

<script>
const facts = [
  "Rabbits have 28 teeth that never stop growing.",
  "Rabbits can turn their ears 180 degrees to hear better.",
  "A group of rabbits is called a fluffle.",
  "Rabbits can jump up to 3 feet high.",
  "Rabbits love to chew to keep their teeth healthy."
];

document.getElementById("randomFactBtn").addEventListener("click", function() {
  const randomIndex = Math.floor(Math.random() * facts.length);
  document.getElementById("rabbitFact").textContent = facts[randomIndex];
});
</script>
