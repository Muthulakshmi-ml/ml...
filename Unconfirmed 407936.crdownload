document.getElementById('showGifButton').addEventListener('click', () => {
  const gifContainer = document.getElementById('gifContainer');
  
  // Create an img element to show the GIF
  const gifImage = document.createElement('img');
  gifImage.src = 'E:PM1.gif'; // You can replace this with any GIF URL
  gifImage.alt = 'Love...';
  gifImage.style.width = '400px'; // Adjust the size as needed

  // Clear the container and append the new GIF image
  gifContainer.innerHTML = '';
  gifContainer.appendChild(gifImage);

  // Launch confetti celebration
  confetti({
    particleCount: 100,
    spread: 70,
    origin: { y: 0.6 }
  });
});
