<template>
  <div>
    <!-- Splash Page -->
    <div id="splash">
      <div class="">
        <div>
          <h1>Jonathan Salfen</h1>
          <h3>A Web Developer</h3>
          <div>
            <a href="#about">About</a>
            <a href="#portfolio-section">Portfolio</a>
            <a href="https://github.com/jonathansalfen">Github</a>
            <a href="https://www.linkedin.com/in/jonathansalfen/">LinkedIn</a>
          </div>
        </div>
      </div>
    </div>

    <!-- About -->
    <div id="about">
      <div id="about-top">
        <h1>About</h1>
        <div class="">
          <p>Hello, I'm Jonathan, a web developer.</p>

          <p>
            I am looking for a position in a web development shop where I can
            learn, grow, and contribute.
          </p>

          <p>
            With a background in small business and international relations, I
            excel in fast-paced environments where I am able to wear multiple
            hats throughout the day. I pride myself on my ability to work with
            and guide a team and teach myself new technologies and skills.
          </p>

          <p>
            I reside in a suburb of Portland, Oregon. In my free time, I enjoy
            hiking, gardening, traveling, baking, going to the gym, and spending
            time with family and friends.
          </p>
        </div>
      </div>
      <div id="about-bottom">
        <img
          src="../assets/jonathan-trevi.jpeg"
          alt="Jonathan in front of the Trevi fountain"
        />
      </div>
    </div>

    <div id="portfolio-section"></div>
    <!-- Portfolio -->
    <div id="portfolio">
      <div class="section_sepertor" id="portfolio_section">
        <div class="container-fluid section_headline">
          <h1>Portfolio</h1>
        </div>

        <h3>Code Challenges</h3>
        <div class="portfolio_items">
          <table class="table">
            <thead>
              <tr>
                <th>GitHub Link</th>
                <th>Technologies Used</th>
                <th>Description</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>
                  <a
                    href="https://github.com/jonathansalfen/epicodus-week-11-solo-project"
                    target="_blank"
                  >
                    Foodee Review
                  </a>
                </td>
                <td>Ruby, Rails, PSQL</td>
                <td>
                  An app with full CRUD functionility for users to review
                  specialty food products.
                </td>
              </tr>
              <tr>
                <td>
                  <a
                    href="https://github.com/jonathansalfen/epicodus-week-12-solo-project"
                    target="_blank"
                  >
                    Cult Classic Quoter
                  </a>
                </td>
                <td>Ruby, Rails, PSQL</td>
                <td>
                  An API to connect people with their favorite cult classic
                  movie and TV show quotes.
                </td>
              </tr>
              <tr>
                <td>
                  <a
                    href="https://github.com/jonathansalfen/epicodus-week-14-solo-project"
                    target="_blank"
                  >
                    Brewprint
                  </a>
                </td>
                <td>Javascript, React</td>
                <td>
                  An app for pubs and breweries to track the status of their
                  kegs on tap and other keg inventory.
                </td>
              </tr>
              <tr>
                <td>
                  <a
                    href="https://github.com/jonathansalfen/bloc-jams-react"
                    target="_blank"
                  >
                    Bloc Jams
                  </a>
                </td>
                <td>Javascript, React</td>
                <td>A Spotify-esq music app built in React.</td>
              </tr>
            </tbody>
          </table>
        </div>

        <h3>Live Projects</h3>
        <div class="portfolio_items">
          <div class="portfolio_item">
            <a
              href="http://jonathansalfen.pythonanywhere.com/story_intro/"
              target="_blank"
            >
              <img
                src="../assets/story_screenshot.png"
                class="portfolio_pics"
                alt="Responsive image"
              />
            </a>
            <div class="portfolio_text">
              <a
                href="http://jonathansalfen.pythonanywhere.com/story_intro/"
                target="_blank"
              >
                <h4>A Walk Without Someone</h4>
              </a>
              <table>
                <tr>
                  <th>Tech:</th>
                  <td>Python, Django, Bootstrap</td>
                </tr>
              </table>
              <p class="body_paragraphs">
                With a Django framework, this project uses CSS, Python, and
                Bootstrap to experiment with storytelling. The user is
                manipulated emotionally by integrating their personal details
                into the anecdote.
              </p>
              <a
                href="https://github.com/jonathansalfen/jon_projects_pythonanywhere/tree/master/a_walk_without_someone"
                target="_blank"
              >
                Check it out on GitHub
              </a>
            </div>
          </div>
          <div class="portfolio_item">
            <a href="/alphabet_reader/" target="_blank">
              <img
                src="../assets/alphabetreader_thumb.png"
                class="portfolio_pics"
                alt="Responsive image"
              />
            </a>
            <div class="portfolio_text">
              <a href="/alphabet_reader/" target="_blank">
                <h4>Alphabet Reader</h4>
              </a>
              <table>
                <tr>
                  <th>Tech:</th>
                  <td>Javascript, JQuery, Bootstrap</td>
                </tr>
              </table>
              <p class="body_paragraphs">
                A program that helps language learners familiarize themselves
                with a new alphabet, this app was created with Javascript and
                JQuery. Now in an MVP state, future editions will allow the
                developer to drop in language extensions while the app updates
                automatically.
              </p>
              <a
                href="https://github.com/jonathansalfen/alphabet_reader"
                target="_blank"
              >
                Check it out on GitHub
              </a>
            </div>
          </div>
          <div class="portfolio_item">
            <a href="/prototype_lumber/" target="_blank">
              <img
                src="../assets/lumber_thumb.jpg"
                class="portfolio_pics"
                alt="Responsive image"
              />
            </a>
            <div class="portfolio_text">
              <a href="/prototype_lumber/" target="_blank">
                <h4>Concannon Lumber</h4>
                <h5>Proof of Concept Website</h5>
              </a>
              <table>
                <tr>
                  <th>Tech:</th>
                  <td>Wordpress, X Theme</td>
                </tr>
              </table>
              <p class="body_paragraphs">
                This website was developed for a Portland lumber company. It
                uses Wordpress and X Theme to allow for easy editing by
                non-programmers.
              </p>
            </div>
          </div>
          <div class="portfolio_item">
            <a href="/three_challenges/" target="_blank">
              <img
                src="../assets/threechallenges_thumb.png"
                class="portfolio_pics"
                alt="Responsive image"
              />
            </a>
            <div class="portfolio_text">
              <a href="/three_challenges/" target="_blank">
                <h4>Three Challenges</h4>
              </a>
              <table>
                <tr>
                  <th>Tech:</th>
                  <td>Javascript, JQuery, Bootstrap</td>
                </tr>
              </table>
              <p class="body_paragraphs">
                Three coding challenges given to me by a local development shop.
              </p>
              <a
                href="https://github.com/jonathansalfen/three_challenges"
                target="_blank"
              >
                Check it out on GitHub
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div id="footer"></div>
  </div>
</template>

<script>
export default {};
</script>
