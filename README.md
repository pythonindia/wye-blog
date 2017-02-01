## Python Express Blog

You can read the blog at http://blog.pythonexpress.in


## Setup

Clone repo to your local system.

```sh
git clone https://github.com/pythonindia/wye-blog.git
```

Make sure Python 2.7 is installed in your system and then install [lektor]() in your system.

```sh
pip install lektor
```

Start server using

```sh
lektor server
````

Go to browser and open http://127.0.0.1:5000/


## Writing blog posts

To write a new blog post, create a new folder with slug name in `content/posts/` directory. Inside that directory, create a file called `contents.lr`. Write blog post content in that file.

For formatting and other options, check existing files. For more information, you can read [lektor docs][] about creating content.


## Deployment

Any commit you make to master brach on github gets deployed automatically.

### Manual Deployment

Incase auto deployment fails or if you want to deploy from your system, follow these steps.

- Make sure you have setup your sytem as mentioned in setup section

- You need to have write permission to the repo as you have to commit on `gh-pages` branch.

- Run `lektor deploy ghpages` from home directory and it will get deployed.


## Help

If you have any queries about this project, please open a github issue.
