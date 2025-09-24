# Self-Evaluation: Emoji Vacation

## Checklist

### Correctness

- [x] Image background shows trees 60% of the time, and mountains 50% of the time (mountains and trees may both appear in one image)
- [x] The program draws a “family” of emojis, containing a number of emojis based on the parameters to `createFamily()`
- [x] Each emoji in the family is randomly selected, based on your implementation of `createRandomEmoji()`
- [x] When run, your program iterates through an endless slideshow of these emoji photos, each with randomized backgrounds and emoji styles
  - [x] There is a pause for three seconds on each image so that a viewer may enjoy the slideshow!
- [ ] (Optional) Additional randomly-selected background scenery
- [ ] (Optional) A dark transition between each slide of the slideshow
- [ ] (Optional) Child and adult emojis are shown in a random order
- [ ] (Optional) Modify the background to include multiple times of day in the random scenery

### Code Style

Check these items from the [Comp 127 Style Guide](https://comp127.innig.net/resources/style-guide/):

- [x] all classes are in packages
- [x] package names start with a lowercase letter
- [ ] newly created Java files have a header comment with
    - [ ] author name
    - [ ] brief description of class, and
    - [ ] acknowledgement, if appropriate
- [x] identifier (variable and method) names are descriptive
- [x] variable and method names are in lowerCamelCase (no CapitalizedNames,
  names_with_underscores)
- [x] class names are singular nouns
- [x] class names are in UpperCamelCase
- [x] proper indentation:
    - [x] opening curly braces (“{”) are at the end of the line
    - [x] closing curly braces (“}”) are on their own line
    - [x] the indentation of closing braces is the same as the indentation of the
      opening statements they match
    - [x] lines are indented according to how deeply they are nested
- [x] completed TODOs are deleted
- [x] extra blank lines are deleted
- [x] unneeded commented lines of code are deleted
- [x] print statements used for testing are deleted


## Reflection

Briefly reflect in writing on your experience solving this exercise. Just a
sentence or two in response to each question is plenty.

**What did you miss? What did you wish you did better?**

At first, I didn’t fully understand how to make the family or slideshow dynamic and I wish I had been quicker in figuring out the loops instead of relying so much on trial and error.

**What challenges did you face, and how did you overcome them?**

The biggest challenge was understanding how to create multiple emojis with flexible numbers. I overcame it by carefully reading the hints about lists and loops, and then testing small changes until it worked.


**What is something that was interesting or exciting, or a lesson you learned
  from this experience that you want to remember?**

I found it exciting to see the slideshow come alive with random emojis. It really made the project feel playful (comp sci can be fun after all!) I learned how important loops and randomness are for creating variety in programs.