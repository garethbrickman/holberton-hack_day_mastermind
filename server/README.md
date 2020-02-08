2 terminal windows

SSH into the server on both

To run Jekyll in the background:
cd into /mastermind_blog
$ bundle exec jekyll serve --detach # when changing configs, sites or posts you must stop and restart the jekyll process using pkill

To run ngrok on 1:
$ ngrok http 4000 # selecting port 4000 will direct incoming http connections to the localhost
Copy the link provided in Forwarding (will look like http://e8d59098.ngrok.io)
