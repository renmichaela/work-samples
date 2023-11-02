# Samples of Work

### [Revolutsia](https://revolutsia.com)
*PHP, ExpressionEngine, FoundationCSS, Sass*

One of my favorite "new build" projects I've done, this site was built for a local retail space made completely from reclaimed shipping containers. I love how the design turned out, and I had fun adding different hover effects to make the site playful and lively. 

### [The Parts Trading Network](https://partstradingnetwork.com)
*PHP, Laravel, VueJS, InertiaJS, TailwindCSS*

 Although most of the site is private to Bobcat Dealers apart from the [help articles](https://partstradingnetwork.com/articles) that explain some of the site functionality, I am immensely proud of this application. I was responsible not only for building the app from scratch, I also architected the infrastructure and oversaw user support as our user base expanded to nearly 200 dealerships across the US and Canada. Utilizing PHP generator functions and Laravel Queues, it can process dealer-submitted CSV files with millions of lines without exhausting server resources. 

### [Promot Depot](https://4mypromo.com)
*PHP, Laravel, Blade, VueJS*

I inherited this application after some developer turnover and maintained it for about a year. Most notably I was in charge of a refactor of the Vue component for the "Size/Color/Quantity" selector on a product page.

The customer can choose multiple colors before adding to their cart. For each color selection, the component will render either a quantity selector for that color, or if applicable, a quantity selector for each size available in the given color.Every quantity selector rendered validates the amount entered against a minimum quantity set in the backend.

The previous developer had misused javascript `objects` and `arrays` in place of each other to store the data which made it quite difficult to work with, and due to constraints in the backend I was not able to change the API that served the data. I perservered and was able to refactor the component to render correctly and efficiently, and retain all the requirements it needed to meet.