# RadMovies
Android app project created for "Developing Android Apps" course on Udacity

## Setup
To run this project locally, you will need your own API key from <a href="https://www.themoviedb.org/faq/api" target="_blank">TMDB</a>. Once you have signed up for an account and obtained a key, add a line in the gradle.properties file that looks like this:
<pre><code>
TMDB_API_KEY = your-api-key
</code></pre>
The Gradle build should pick up your key and set it as the Build.TMDB_API_KEY that is used throughout the application.
