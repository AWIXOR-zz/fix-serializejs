# How fix serialize-javascript vulnerability found in yarn.lock

if you are a react Developper, you might face this problem when you create an app with `create-react-app` and push it to github.


## The fix is very simple
you can just add serialize-javascript to resolutions in your `package.json`, so you force it to use the last update, then run the command  `yarn upgrade`
