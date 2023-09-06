# MySite

Link: https://cherry247.github.io/MySite/

## Deployment
* Clone this github repo :
 
   ```bash
     git clone https://github.com/<your-username>/home.git
   ```

* Change URL in package.json -> homepage :
   ```json
    "homepage": "https://<your-username>.github.io/home"
   ```
* Deploy website by running
  ```bash
    npm run build
    npm run deploy
   ```
Now your site is up at : `https://<your-username>.github.io/home`
