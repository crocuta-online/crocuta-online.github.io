\# Testing website edits before pushing live



\## Step 1: Clone the repo to your local machine, duh

\* There are other resources to tell you how to do this

\## Step 2: Make whatever edits you want, duh

\* Try to stick to copying existing HTML blocks and simply changing the content

\* The styling for the existing blocks is already set up to scale consistently

\## Step 3: You will need Python3 installed in some way

\* There are other resources to tell you how to do this

\## Step 4: It's trivial to set up a local HTTP server with Python3

\* Open a console and make sure the working directory is the root of the repo (if you run `ls` or `dir` you should see `index.html`)

\* When that's true, run this command: `python3 -m http.server 1234` (or arbitrary sensible port number)

\* The console should begin running the HTTP server locally, the command won't "finish" because it is running.

\* Then you can open your browser of choice and type `localhost:1234` (or whatever port number) into the URL bar. Press enter of course

\* This should represent your local changes as if it were live online

\## Step 5: I recommend testing your changes in multiple browsers / screen sizes

\* Chrome and Firefox or whatever

\* Change size of window to be thin to pretend it's mobile, or full for desktop

\## Step 6: If everything looks good you can commit to the main branch

\* I don't care to use branches properly because the point of inviting everyone to the repo is that you can edit it without me.

\* Don't break anything! If you change anything unorthodox, it's worth asking

