<a href="https://project-types.github.io/#toy">
  <img src="https://img.shields.io/badge/project%20type-toy-blue" alt="Toy Badge"/>
</a>

# Description

This repo includes poems (and maybe other creative works later on? That sort of defeats the purpose of naming the repo `poetry`, I suppose) written by me. 

# Inspiration

I started thinking about the relationship between version control and creativity, and wondered what it'd be like to use `git` to track changes in the creative work I come up with over time.

This is also a way for me to think about writing creatively in a different way because the medium (my keyboard) is different than my normal paper and pen. This is compounded by the fact that markup languages like Markdown, RST, etc. can add more visual components than I could with a plain text file.

At some point, I'm wondering if integrating code and poetry in a more fundamental way would enhance or detract from the quality of the final creative output. I'm personally imagining a Python module whose functions you can call to either:
- construct a unique poem you come up with
- print out beautifully-formatted poems someone else has come up with E.g.:
    ```python
    import poetry
    
    print(poetry.livit())

    # the fun ensues!
    ```