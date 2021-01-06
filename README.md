# portfolio-traversy
Responsive Portfolio Website - Traversy

[![PayPal][badge_paypal_donate]][paypal-donations]
<!-- [![Support me on Patreon][badge_patreon]][patreon]  -->

<!-- <a href="https://www.buymeacoffee.com/" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/yellow_img.png" alt="Buy Me A Coffee"></a> -->

<br>
<br>

**A static Portfolio Website using Sass**. If you find any tips, please share them with me and let me know what can be improved.

[![portfolio-traversy](https://i.imgur.com/dkYR3DX.png)](https://hsaade-algo.github.io/portfolio-traversy/index.html)



## :anchor: Installation

```sh
git clone https://github.com/hsaade-algo/portfolio-traversy.git
cd portfolio-traversy
npm install
npm run sass
```

To build the app for production, run the following command:
```
npm run build
```
<br>
<br>

## Preparation For Deployment on Github Pages
- Make sure your repository is Public
- Make sure Github Pages is enabled on the repository (in Settings)
- In package.json, make sure you have the deployment script like:
```
    "scripts": {
        "sass": "node-sass -w scss/ -o dist/css/ --recursive",
        "deploy": "gh-pages -d dist"
    },
```
- Commit and Push changes
- Deploy ``` npm run deploy ```

<br>
<br>
## :wrench: Features

<!-- **Curriculum version**: `8.0.0` (see [CHANGELOG](CHANGELOG.md)) -->

<!-- - ReactJS
- React DatePicker
- Moment.js -->
:heavy_check_mark: Sass

:heavy_check_mark: JavaScript

:heavy_check_mark: Responsive



<br>
Enjoy!

[Hussein Saade][website]






[website]: https://maranello.hopto.org
[badge_patreon]: https://ionicabizau.github.io/badges/patreon.svg
[badge_amazon]: https://ionicabizau.github.io/badges/amazon.svg
[badge_paypal]: https://ionicabizau.github.io/badges/paypal.svg
[badge_paypal_donate]: https://ionicabizau.github.io/badges/paypal_donate.svg
[patreon]: https://www.patreon.com/
[amazon]: http://amzn.eu/
[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=V8XLXREDEEPYC&currency_code=USD
