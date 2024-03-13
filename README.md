# hugo-mock-landing-page-autodeployed
In the GitHub Actions workflow we've created, whenever there is a new push action to the main branch of the GitHub repo, a new job is triggered.<br>
The job consists of four steps:<br>
1. Checks out the repository code onto the runner.
2. Sets up the Hugo environment on the runner using the peaceiris/actions-hugo action.
3. Compiles the static files for the website.
4. Publishes the compiled static files to the gh-pages branch of the repository, which is used by GitHub Pages to serve the website.
