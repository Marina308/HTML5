<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="author" content="Marina309">
    <meta name="description" content="This page contains all the things I am learning how to create as I learn HTML.">
    <title>My First Web Page</title>
    <link rel="icon" href="html.png" type="image/x-icon">
    <link rel="stylesheet" href="main.css" type="text/css">
</head>

<body>
    <header>
        <h1>My Goals for the Year</h1>

        <nav aria-label="primary-navigation">
            <ul>
                <li>
                    <a href="#html">Learning HTML</a>
                </li>
                <li>
                    <a href="#vacation">Planning a Vacation</a>
                </li>
                <li>
                    <a href="#contact">Contact Me</a>
                </li>
            </ul>
        </nav>
    </header>

    <hr>
    <main>
        <article id="html">
            <h2>I'm Ready to Learn HTML</h2>
            <p>This is my first web page.</p>
            <section>
                <h3>HTML5</h3>
                <img src="img/html_logo_300x300.png" alt="HTML5 Logo" title="I am learning HTML5" width="300"
                    height="300">
                <figure>
                    <figcaption>An Example of HTML5 code</figcaption>
                    <p>
                        <code>&lt;h1&gt;Hello World!&lt;/h1&gt;</code>
                    </p>
                </figure>
            </section>
            <section>
                <h3>My Daily Schedule</h3>
                <p>Let me tell you how:</p>
                <ol>
                    <li>...I learn more about web dev.</li>
                    <li>...I plan out my schedule.</li>
                    <li>...I use resources from <abbr title="Mozilla Developer Network">
                            <a href="https://developer.mozilla.org/">MDN</a>
                        </abbr>.</li>
                </ol>
                <aside>
                    <details>
                        <summary>Guess the <mark>number of hours</mark> I code per day</summary>
                        <p>I start at <time datetime="08:00">8 am</time> and I write code for <time datetime="PT3H">3
                                hours</time> every morning.</p>
                    </details>
                </aside>
                <br>
                <table>
                    <caption>My Daily Schedule</caption>
                    <thead>
                        <tr>
                            <th>&nbsp;</th>
                            <th scope="col">Time</th>
                            <th scope="col">Activity</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <th scope="row">Morning</th>
                            <td>
                                <time datetime="08:00">8am</time>-<time datetime="11:00">11am</time>
                            </td>
                            <td>Write Code</td>
                        </tr>
                        <tr>
                            <th scope="row">Break</th>
                            <td>
                                <time datetime="11:00">11am</time>-<time datetime="12:00">12pm</time>
                            </td>
                            <td>Eat Lunch</td>
                        </tr>
                        <tr>
                            <th scope="row">Afternoon</th>
                            <td>
                                <time datetime="12:00">12pm</time>-<time datetime="17:00">5pm</time>
                            </td>
                            <td>Study for Other Courses</td>
                        </tr>
                        <tr>
                            <th scope="row">Evening</th>
                            <td rowspan="2">All Other Times</td>
                            <td>Free Time</td>
                        </tr>
                        <tr>
                            <th scope="row">Night</th>
                            <td>Sleep</td>
                        </tr>
                    </tbody>
                    <tfoot>
                        <tr>
                            <td colspan="3">And that's what I do every day, 5 days a week. Just eat, sleep, code ..and
                                recharge!</td>
                        </tr>
                    </tfoot>
                </table>
            </section>
        </article>

        <hr>

        <article id="vacation">
            <h2>I Am Also Planning a Vacation</h2>
            <p>I've been working hard and <em>really need a getaway</em>.</p>
            <p>I live in <abbr title="Kansas">KS</abbr> so I want visit a beach.</p>

            <section>
                <h3>Places I'd Like to Visit</h3>
                <ul>
                    <li>
                        <p>I've heard good things about the Caribbean.</p>
                        <figure>
                            <img src="img/caribbean.jpg" alt="Caribbean Beach"
                                title="I want to visit a Caribbean beach." width="400" height="225" loading="lazy">
                            <figcaption>
                                Caribbean Beach Getaway
                            </figcaption>
                        </figure>
                    </li>
                    <li>
                        <p>I've heard good things about going here:</p>
                        <address>
                            Margaritaville Island Reserve Riviera Cancún<br>
                            Bahia Petempich Puerto Morelos, Mexico<br>
                            Colonia Morelos, México 77580
                        </address>
                        <figure>
                            <img src="img/vacation.jpg" alt="Cancun Vacation" title="It's 5 o'Clock Somewhere!"
                                width="400" height="267" loading="lazy">
                            <figcaption>
                                A Caribbean Vacation Image
                            </figcaption>
                        </figure>
                    </li>
                </ul>
            </section>
            <!-- TODO: Add more places -->
            <section>
                <h3>Places I Want to Avoid</h3>
                <dl>
                    <dt>North Pole</dt>
                    <dd>I hear this is <strong>cold</strong>!</dd>

                    <dt>South Pole</dt>
                    <dd>This is also cold.</dd>

                    <dt>Mountain Tops</dt>
                    <dd>These are also cold.</dd>
                </dl>
            </section>
        </article>

        <hr>

        <article id="contact">
            <h2>Contact Me</h2>
            <p>I'd really like to hear from you!</p>

            <form action="https://httpbin.org/get" method="get">
                <fieldset>
                    <legend>Personal Info</legend>
                    <p>
                        <label for="firstName">First Name:</label>
                        <input type="text" name="firstName" id="firstName" placeholder="Jane" autocomplete="on" required
                            autofocus>
                    </p>
                    <p>
                        <label for="lastName">Last Name:</label>
                        <input type="text" name="lastName" id="lastName" placeholder="Doe" autocomplete="on" required>
                    </p>
                    <p>
                        <label for="password">Password:</label>
                        <input type="password" name="password" id="password" placeholder="your secret" required>
                    </p>
                    <p>
                        <label for="phone">Phone:</label>
                        <input type="tel" name="phone" id="phone" placeholder="5555555555"
                            pattern="[0-9]{3}[0-9]{3}[0-9]{4}" required>
                    </p>
                    <p>
                        <label for="decade">Favorite Decade:</label>
                        <input type="number" name="decade" id="decade" min="1950" max="2020" step="10" value="1980">
                    </p>
                    <p>
                        <label for="coffee">Favorite Coffee:</label>
                        <select name="coffee" id="coffee" multiple size="5">
                            <optgroup label="Coffees">
                                <option value="regular coffee">Regular Coffee</option>
                                <option value="iced coffee">Iced Coffee</option>
                            </optgroup>
                            <optgroup label="Espresso Drinks">
                                <option value="latte" selected>Latte</option>
                                <option value="cappuccino">Cappuccino</option>
                                <option value="cortado">Cortado</option>
                                <option value="americano">Americano</option>
                            </optgroup>
                            <option value="other">Other</option>
                        </select>
                    </p>
                    <!-- <p>
                    <label for="coffee">Favorite Coffee:</label>
                    <input type="text" name="coffee" id="coffee" list="coffee-list">
                    <datalist id="coffee-list">
                        <option value="coffee">
                        <option value="latte">
                        <option value="espresso">
                        <option value="cortado">
                        <option value="americano">
                        <option value="other">
                    </datalist>
                </p> -->
                </fieldset>
                <br>
                <fieldset>
                    <legend>What is your favorite food?</legend>
                    <p>
                        <input type="radio" name="food" id="tacos" value="tacos">
                        <label for="tacos">Tacos</label>
                    </p>
                    <p>
                        <input type="radio" name="food" id="pizza" value="pizza">
                        <label for="pizza">Pizza</label>
                    </p>
                    <p>
                        <input type="radio" name="food" id="other" value="other">
                        <label for="other">Other</label>
                    </p>
                </fieldset>
                <br>
                <fieldset>
                    <legend>Do you have pets?</legend>
                    <p>
                        <input type="checkbox" name="pets" id="dog" value="dog">
                        <label for="dog">Dog</label>
                    </p>
                    <p>
                        <input type="checkbox" name="pets" id="cat" value="cat">
                        <label for="cat">Cat</label>
                    </p>
                    <p>
                        <input type="checkbox" name="pets" id="fish" value="fish">
                        <label for="fish">Fish</label>
                    </p>
                    <p>
                        <input type="checkbox" name="pets" id="otherPet" value="otherPet">
                        <label for="otherPet">Other</label>
                    </p>
                </fieldset>
                <br>
                <fieldset>
                    <legend>Send Me A Note</legend>
                    <label for="message">Your Message:</label>
                    <br>
                    <textarea name="message" id="message" cols="30" rows="10"
                        placeholder="Type your message here"></textarea>
                </fieldset>
                <br>
                <button type="submit">Submit</button>
                <button type="submit" formaction="https://httpbin.org/post" formmethod="post">Post</button>
                <button type="reset">Reset</button>
            </form>
        </article>
    </main>
    <hr>
    <footer>
        <p>
            &lt;&lt;&lt; &copy; <a href="about.html">Marina309</a> &gt;&gt;&gt;
        </p>
        <p>
            <a href="#">Back to Top</a>
        </p>
    </footer>
</body>

</html>
