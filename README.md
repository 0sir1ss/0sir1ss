```python
from GitHub import ReadMe

class osiris(ReadMe):
    def __init__(self):
        self.username = "0sir1s"
        self.name = "James"
        self.language = "English"
        self.used_programming_languages = ["Python", "Javascript", "C++"]
        self.location = "United Kingdom"
        self.education = "2 Years of Computer Science"

    def about(self):
        print(f"""
Hi, I'm {self.name}, or {self.username} online.
In my free time I create projects to help deepen my understanding of programming languages and concepts. I find the best way to learn is through experience.
I have previously used the following programming languages ordered from most to least used: {', '.join(i for i in self.used_programming_languages)}.
You may find some of these projects on my GitHub profile.""")

me = osiris()
me.about()
```
