# test-storefrontui-nuxt
Basic SfCallToAction with Nuxt &amp; Storefront UI showing a discrepancy in styles between the dist folder and "yarn dev"

Use first `yarn install` then:
- `yarn dev` will show you the correct styles
- `yarn start` will show you the `dist` folder where the button has a different layout. Loading directly the index.html file in a browser brings the same result

![](README.png)

`yarn dev` vs the `dist` folder
