function roll(lever){
  const output = document.getElementById("output");
  const rarity = document.getElementById("rarity");

  lever.classList.add("pulled");

  let spins = 0;
  let speed = 60;

  const spin = setInterval(() => {

    const val = letters[Math.floor(Math.random() * letters.length)];
    output.textContent = val;
    output.style.color = getColor(val);

    spins++;

    if(spins > 8) speed = 90;
    if(spins > 14) speed = 140;
    if(spins > 18) speed = 200;

    if(spins > 24){

      clearInterval(spin);
      lever.classList.remove("pulled");

      const pick = Math.random() < 1/220
        ? "0"
        : letters[Math.floor(Math.random() * letters.length)];

      stats[pick]++;
      inventory[pick]++;

      output.textContent = pick;
      output.style.color = getColor(pick);

      rarity.textContent = pick === "0"
        ? "MYTHIC (0)"
        : "Rank " + getRank(pick);

      save();
      updateBoard();
    }

  }, speed);
}
