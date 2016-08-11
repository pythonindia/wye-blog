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

To deploy `master` brach to `gh-pages` just run this command from root directory.

```sh
lektor deploy --username <username> --password <password>
```

## Help

If you have any queries about this project, please open a github issue.
