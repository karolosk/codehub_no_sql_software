
# Software needed for NoSQL sessions

### Redis
Redis is a NO-SQL, key-value in-memory remote database that offers high performance, replication, and a unique data model. 

#### Windows
- Go to https://github.com/microsoftarchive/redis/releases/tag/win-3.0.504
![redis_windows_release](https://github.com/karolosk/codehub_no_sql_software/blob/gh-pages/images/redis_windows_release.PNG)

- Download the msi file. You can download alterantively the zip file but you will need to add manually environmental variables.
- Assuming that we are using the msi file, go over the typical installation wizard but do not forget to check the add to path variable.
![alt text](https://github.com/karolosk/codehub_no_sql_software/blob/gh-pages/images/redis_windows_path.PNG)

- Let the port number and the add exception as it is and continue with the default values in the wizard
- With msi installer the redis-server will automatically run in the background when the system starts
![redis_process](https://github.com/karolosk/codehub_no_sql_software/blob/gh-pages/images/redis_windows_redis_server.PNG)

- In order to connect to the redis server open a cmd and type `redis-cli`. If everything is correct you will connect to your local instance and you will be able to start interacting with the redis server. You can try `SET key value` and it should return `OK` and then `GET key` to get the assigned value.
![redis_cli](https://github.com/karolosk/codehub_no_sql_software/blob/gh-pages/images/redis_windows_redis_cli.PNG)


#### Linux

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/karolosk/codehub_no_sql_software/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/karolosk/codehub_no_sql_software/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
