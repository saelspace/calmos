let time = 1500;

function startTimer() {
  let interval = setInterval(() => {
    let minutes = Math.floor(time / 60);
    let seconds = time % 60;

    document.getElementById("timer").innerText =
      `${minutes}:${seconds < 10 ? "0" : ""}${seconds}`;

    time--;

    if (time < 0) clearInterval(interval);
  }, 1000);
}
