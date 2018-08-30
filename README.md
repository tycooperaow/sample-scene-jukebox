# sample scene jukebox

This scene is based on a tutorial that [HardlyDifficult](https://github.com/hardlydifficult) created for us.

It shows how to handle and animate buttons, as well as how to play sound files in a Decentraland scene.

You can find a full tutorial including video and written content [here](https://steemit.com/tutorial/@hardlydifficult/decentraland-tutorial-creating-a-music-jukebox)

[Explore the scene](https://dcl-project-nvahvjzeiz.now.sh/?position=42%2C42): this link takes you to a copy of the scene deployed to a remote server where you can interact with it. You can also achieve the same by following the steps below and running it locally.

**Install the CLI**

Download and install the Decentraland CLI by running the following command

```bash
npm i -g decentraland
```

For a more details, follow the steps in the [Installation guide](https://docs.decentraland.org/documentation/installation-guide/).


**Previewing the scene**


Once you've installed the CLI, download this example and navigate to its directory from your terminal or command prompt.

_from the scene directory:_

```
$:  dcl start
```

Any dependencies are installed and then the CLI will open the scene in a new browser tab automatically.

**Usage**

Click the jukebox buttons to play songs. Each button plays a different song, and pressing one dissables all others.