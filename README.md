# Fligoo Challenge Hotels 
#### by Maximiliano Ulibarrie ([linkedin](https://www.linkedin.com/in/maxiulibarrie) / [resume](https://maxiulibarrie.github.io/resume))

## Requirements:
- Docker

## Steps to run locally: 

1. Clone the repository into the local machine.
2. Get into the main folder `fligoo-challenge-hotels`.
3. Run docker command: `docker build -t fligoo-ch-hotels .`
4. After building the image run the docker command: `docker run -p 8888:8888 fligoo-ch-hotels`
5. Look into the logs for a `http://127.0.0.1:8888/tree?token={TOKEN}` link. Copy this link including the token. 
6. Open a browser and paste the link copied in the previous step.
7. The file `fligoo_take_home_data_scientist.ipynb` has all the parts of the challenge.

