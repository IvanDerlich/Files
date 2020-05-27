## Used in:

https://github.com/IvanDerlich/weather-app
Shooter Game

## Notes

The command
    
    "deploy": "webpack --mode production && git add -A && git commit -m 'Deploy to gh-pages' && git push -d origin gh-pages && git push && git subtree push --prefix dist origin gh-pages && xdg-open https://github.com/IvanDerlich/weather-app/tree/gh-pages",

  Is deprecated, using surge.sh app is better