# .eslintrc.json
## Notes

It's the same than the Microverse one, but it corrects the problem with stickler

# .eslintrc.microverse.json

## Source

https://github.com/microverseinc/linters-config/blob/master/javascript/.eslintrc.json

# .stickler.yml

## Note
After copying this file to the root directory. You need to activate it in the [stickler website]()

# package.json

## Used in:

https://github.com/IvanDerlich/weather-app
Shooter Game

## Notes

The command
    
    "deploy": "webpack --mode production && git add -A && git commit -m 'Deploy to gh-pages' && git push -d origin gh-pages && git push && git subtree push --prefix dist origin gh-pages && xdg-open https://github.com/IvanDerlich/weather-app/tree/gh-pages",

  Is deprecated, using surge.sh app is better

# webpack.config.js

## Used in:

Weather app
