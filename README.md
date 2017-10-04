# veen.xyz

Main website for [veen.xyz](https://veen.xyz), my consulting business

## Running it locally
This site is built using Jekyll. This means you need Jekyll.

    $ gem install jekyll

Then in the folder you've cloned this repo to

    $ jekyll server

The site is then available on your local machine at http://localhost:4000.
Optionally you can add `--host 0.0.0.0` to make it run on any IP.

When you change anything in one of the files, Jekyll will automatically reload
these changes, so you just need to save your changes and reload your browser.

There's also a convenience script that does this for you

    $ ./run

## Deploying it
Pushing to master automatically triggers a build and deploy on Codeship
