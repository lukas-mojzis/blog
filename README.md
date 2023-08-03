# Blog
Simple blog website written in Django, HTML and CSS, partially based on the [Django Girls tutorial](https://tutorial.djangogirls.org/en/).

## Getting Started
The website can be accessed by anyone at [lukasmojzis.eu.pythonanywhere.com](https://lukasmojzis.eu.pythonanywhere.com/).

If you'd like to work on the project, please [clone this repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) and [install Python](https://tutorial.djangogirls.org/en/python_installation/) and [Django together with its dependencies](https://tutorial.djangogirls.org/en/django_installation/).

## Features Overview
The website allows users to create, edit and delete blog posts and add comments on these posts.

Any operation involving the modification of posts requires user authentication via login. However, posts may be viewed and comments may be added by any user without authentication.

The website includes a simple graphical interface covering all of its features. The interface is based on text fields and buttons containing self-explanatory text or icons. In case of doubt, hover your cursor over any button to see its description.

Newly created posts are first saved in the database as drafts and are only visible to the authenticated users on the drafts page. Only after they are published can they be seen in the main part of the website.

Similarly, when a user posts a comment, it is only visible to the authenticated users who must approve it before it becomes visible to everyone.

## Contributing
Any feedback, suggestions and pull requests are welcome!

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Author
[Lukas Mojzis](https://github.com/lukas-mojzis)

You can also contact me via [e-mail](mailto:mojzis.lukas@gmail.com) or [LinkedIn](https://www.linkedin.com/in/lukas-mojzis/).
