## Datacamp Course Project
## Golden Age of Video Games

Description:

## 1. The ten best-selling video games
<p><img src="https://assets.datacamp.com/production/project_1413/img/video_game.jpg"
        alt="A video game player choosing a game to play on Nintendo Switch." width="400"></p>
<p>Photo by <a href="https://unsplash.com/@retromoon">Dan Schleusser</a> on <a href="https://unsplash.com">Unsplash</a>.
</p>
<p>In this project, I was challenged to compare a dataset on game sales with critic and user reviews collected over time
    to determine whether or not video games have improved as the gaming market has grown.</p>
<p>The database contained two tables, and were limited to 400 rows for this project. The complete dataset with over
    13,000 games can be found on <a href="https://www.kaggle.com/holmjason2/videogamedata">Kaggle</a>.
</p>
<h3 id="game_sales"><code>game_sales</code></h3>
<table>
    <thead>
        <tr>
            <th style="text-align:left;">column</th>
            <th>type</th>
            <th>meaning</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="text-align:left;"><code>game</code></td>
            <td>varchar</td>
            <td>Name of the video game</td>
        </tr>
        <tr>
            <td style="text-align:left;"><code>platform</code></td>
            <td>varchar</td>
            <td>Gaming platform</td>
        </tr>
        <tr>
            <td style="text-align:left;"><code>publisher</code></td>
            <td>varchar</td>
            <td>Game publisher</td>
        </tr>
        <tr>
            <td style="text-align:left;"><code>developer</code></td>
            <td>varchar</td>
            <td>Game developer</td>
        </tr>
        <tr>
            <td style="text-align:left;"><code>games_sold</code></td>
            <td>float</td>
            <td>Number of copies sold (millions)</td>
        </tr>
        <tr>
            <td style="text-align:left;"><code>year</code></td>
            <td>int</td>
            <td>Release year</td>
        </tr>
    </tbody>
</table>
<h3 id="reviews"><code>reviews</code></h3>
<table>
    <thead>
        <tr>
            <th style="text-align:left;">column</th>
            <th>type</th>
            <th>meaning</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="text-align:left;"><code>game</code></td>
            <td>varchar</td>
            <td>Name of the video game</td>
        </tr>
        <tr>
            <td style="text-align:left;"><code>critic_score</code></td>
            <td>float</td>
            <td>Critic score according to Metacritic</td>
        </tr>
        <tr>
            <td style="text-align:left;"><code>user_score</code></td>
            <td>float</td>
            <td>User score according to Metacritic</td>
        </tr>
    </tbody>
</table>
<p>Let's begin by looking at some of the top selling video games of all time!</p>

The analysis can be found at [this](golden-age-of-video-games.ipynb) link.