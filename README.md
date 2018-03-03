# SBE201 Markdown Resumes Assignment

## Resumes in this Repository

Open any resume to see *online basic view* of our resumes:

| Team Members | Resume Link |
|--------------|-------------|
| *Member 1* (replace with your name here) | [resume](member1.md) |
| *Member 2* (replace with your name here) | [resume](member2.md) |
| *Member 3* (replace with your name here) | [resume](member3.md) |
| *Member 4* (replace with your name here) | [resume](member4.md) |
| *Member 5* (replace with your name here) | [resume](member5.md) |
| *Member 6* (replace with your name here) | [resume](member6.md) |

## Guidelines

### Never Use the Online Editor

Make all your edits through your local machine, **commit**, **pull/push**.

### Adding an Image

Each member can add an image and include it in his profile, using the following steps:

1. Copy-paste your image (e.g `heisenberg.png`) into the repository folder.
2. `git add heisenberg.png`.
3. Include the image in your profile. Use the *Markdown Cheat Sheet Fold*.
4. Let the repository watch your image and take control:
    ```teminal
    git commit -a -m "Say my name!"
    ```
5. `git push origin master`, if rejected:
    ```terminal
    $ git pull origin master
    ```
    The **git** may automatically merge the outside updates and opens a window with a commit message. Just hit `CTRL+x`, then `git push origin master`.