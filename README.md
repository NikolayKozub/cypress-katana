## clone this repo to a local directory
git clone https://github.com/NikolayKozub/cypress-katana.git

## cd into the cloned repo
cd cypress-katana

## install the node_modules
npm ci

## create local file 'cypress-katana/cypress.env.json' and add username, password 
{
"username": "testUser...",
"password": "pass..."
}

## run test
npx run cypress open 
