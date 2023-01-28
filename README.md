# World-Attacks


 Advanced Cyber Threat Map (Simplified, customizable and responsive. It uses D3.js with TOPO JSON, has 247 countries, ~100,000 cities, and can be used in an isolated environment **without external lookups!**.



## Offline - Demo [Firefox, Chrome or Safari]

![sciat](https://user-images.githubusercontent.com/123240124/215275575-07f811be-dde0-42b3-a4b7-123b9aa03668.png)


## Features
- Uses D3.js (Not Anime.js)
- Plot by gussing feature (Mix name, ip or coordinates)
- Active threat map (Live and replay)
- IP, country, city, and port info for each attack
- Attacks stats for countries (Only known attacks)
- Responsive interface (Move, drag, zoom in and out)
- Customize options for countries and cites
- 247 countries are listed on the interface (Not 174)
- Optimized worldmap for faster rendering
- Includes IP lookup, port information
- Random simulation (IP, country, city)
- Can be used online or offline (Static)
- Theme picker module
- Handles large number of attacks

## Data
You have different options `ip`, `name`, and `coordinates`


#Running 
- Clone to your local machine.
- Move to `cd world-attacks`
- Open terminal build `sudo docker build -t simulation .`

- Run `sudo docker run -p 5678:5678 -p 8080:8080 -it simulation`

- Open browser to `http://localhost:8080/simulation.html`

![bb](https://user-images.githubusercontent.com/123240124/215275811-e165ee76-2fe4-42cd-99c7-b017f9440ddb.png)
