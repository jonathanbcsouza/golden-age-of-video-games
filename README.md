## Course Project: Golden Age of Video Games
<p><img src="https://images.unsplash.com/photo-1632256347173-298f7407d1df?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=987&q=80" alt="A video game player choosing a game to play on Nintendo Switch." width="200"></p>

<p>Photo by <a href="https://unsplash.com/@retromoon">Dan Schleusser</a> on <a href="https://unsplash.com">Unsplash</a>.
</p>
This was a project delivered to <a href="https://www.datacamp.com"> Datacamp</a>. This challenge was to compare a dataset on game sales with critics and user reviews to determine whether or not video games have improved over time.
<p>The database used for this contained two tables, and it was limited to 400 rows. The complete dataset with over 13,000 games can be found on <a href="https://www.kaggle.com/holmjason2/videogamedata">Kaggle</a>.
</p>

### Databases used for this project

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

### Full analysis
Please refer to [golden-age-of-video-games.ipynb](golden-age-of-video-games.ipynb) file.