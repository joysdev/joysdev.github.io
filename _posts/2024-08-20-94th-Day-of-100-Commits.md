const animals = ['Hen', 'elephant', 'llama', 'leopard', 'ostrich', 'Whale', 'octopus', 'rabbit', 'lion', 'dog'];

// Create the secretMessage array below
const secretMessage = animals.map(animal => {
  return animal[0]
});

Considering the above JavaScript, how does the console "know" 'animal'? animal != animals... 

Considering the following, how was I supposed to know randomNumbers should be changed to num?

const randomNumbers = [375, 200, 3.14, 7, 13, 852];

// Call .filter() on randomNumbers below
const smallNumbers = randomNumbers.filter(randomNumber => {
  return randomNumber.length < 250;
});

This was the example to follow:
const words = ['chair', 'music', 'pillow', 'brick', 'pen', 'door']; 

const shortWords = words.filter(word => {
  return word.length < 6;
});


Deeply frustrated by what I can and can't assume here... And I'm now completely lost again. I did attempt to shift some styles on my app. I failed. Even though I put everything back the way it was, looks like it still wants me to sync changes, so I will get my commit-but I don't feel good about it. I also probably did study at least an hour but I don't feel good about that either since it wasn't concentrated. I don't feel good about anything atm. 
