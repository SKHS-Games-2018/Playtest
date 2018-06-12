# Game Design Playtest Page

After you have built your game and published it on your website, add a link to the playtest page, index.md in this repository.

To do this:

1. **Fork this repository** on that you can edit it and add your game.
1. **Click on the index.md file** and play around a bit to see how it works.
1. Then **click on the edit pencil** so you can look at the structure of the file. You will see that each of the sections looks something like this:

``` html
<details>
  <summary markdown="span">
    Defender
  </summary>
  
  * [Defender: Doug Urner](https://douglasurner.github.io/prototypes/Defender/index.html) --- I modified this
    game to use the night sky background, I thought that that would look better with the laser. The next thing
    I want to fix is the way the game ends.
  
</details>
```

This file is a mixture of Markdown and HTML. Each section consists of some HTML markup to create the collapsing sections around a Markdown list of games. You will be adding an entry to the list for your game. Your entry will look like this:

``` markdown
* [GAME_NAME: YOUR_NAME](GAME_URL) --- Short description of your game.
```

4. After you have edited the `index.md` file in your fork of the Playtest repository, **commit the changes and test that the link to your game works.**
1. When evrery thing looks good and is working, **create a pull request**:
   - **Click on the `Pull requests` tab** near the top of the page --- it's between `Issues` and `Projects`.
   - On the right, **click on the green `New pull request` button**.
   - **Enter a description of your pull request.**
   - **Click on the Create pull request button.**
