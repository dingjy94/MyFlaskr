## MyFlaskr

The flask blog application from [flask tutorial](http://flask.pocoo.org/docs/1.0/tutorial/)

### Run
```bash
export FLASK_APP=flaskr
export FLASK_ENV=development
flask init-db
flask run   
```

### Main Dependencies
```
python 3.7
Flask 1.0.2 
pip 10.0.1
pytest 4.3.1
```

### test coverage

| Module | coverage |
| ------ | -------- |
| \__init\__.py | 100% |
| auth.py | 100% |
| blog.py | 100% |
| db.py | 100% |
| __Total__ | __100%__ |

### TODO
- [ ] A detail view to show a single post. 

- [ ] Click a post’s title to go to its page.

- [ ] Like / unlike a post.

- [ ] Comments.

- [ ] Tags. Clicking a tag shows all the posts with that tag.

- [ ] A search box that filters the index page by name.

- [ ] Paged display. Only show 5 posts per page.

- [ ] Upload an image to go along with a post.

- [ ] Format posts using Markdown.

- [ ] An RSS feed of new posts.