# frontend-nanodegree-mobile-portfolio
P4 Udacity Front-end Nanodegree Program


#### How to start
* Serve on localhost If you're familiar with python run these commands on your terminal

```
git clone https://github.com/mona949/frontend-nanodegree-mobile-portfolio-master
cd frontend-nanodegree-mobile-portfolio-master
sudo python -m SimpleHTTPServer 80 

```

Open your browser and navigate to `http://localhost`

* Live website
[Here](https://github.com/mona949/frontend-nanodegree-mobile-portfolio-master)

### Optimizing index.html
- External link to `style.css` has been removed, Implemented internal `<style>` instead.
- media=print add to `<link href="css/print.css" rel="stylesheet" media="print">`
- async js `<script async src="https://www.google-analytics.com/analytics.js"></script>`
- minimize  the images size 
### Optimizing main.js 
- Removed `determineDx()` function.
- replace `selectorAll` with `getElement`
- remove some functions and variables outside the loop 
- update `changePizzaSizes()` and `updatePosition()` functions.
## Optimizing pizza.html
- minimize  the images size 
- async js `<script async src="js/perfmatters.js"></script>`
- remove .js from the head and add it in the last .
