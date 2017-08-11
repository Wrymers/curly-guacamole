# curly-guacamole
# components
You have to import the webbrowser function from the Python Standard Library using:

`import webbrowser`

You will then create a class called Video and allow it to accept arguments under the: title, storyline, poster, trailer and rating.

`class Video:
    def__init__(self, title, duration)
class Movie(Video):`

This class will provide a way to store movie related information    

        `VALID_RATINGS = ["G", "PG", "PG-13", "R"]
    def __init__(self, movie_title, movie_storyline, poster_image, trailer_youtube):
        self.title = movie_title
        self.storyline = movie_storyline
        self.poster_image_url = poster_image
        self.trailer_youtube_url = trailer_youtube)`

You then create a function to show the trailer for whichever movie is selected:

`def show_trailer(self):
        webbrowser.open(self.trailer_youtube_url)`
