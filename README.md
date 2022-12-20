# /to
A really simple JS redirect for your social media links

## Deployment
1. Fork this repo
2. Change the `index.html` files in each folder (and add more folders!)
3. Go to the `Actions` tab and click the `I understand my workflows, go ahead and enable them` button to get your site deploying!

## Usage

You can send people to your https://[username].github.io/to page to give them a list of all the links, or send them directly to https://[username].github.io/to/[site] to give them a link to that site.

## How it works

Rather than using 301 or 302 redirects, this tool uses javascript to rewrite the URL after 50 milliseconds. It's a little harder to block than your usual shortener.