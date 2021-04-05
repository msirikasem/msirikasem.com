
# To develop locally:
1. In config.toml, set line 3 to:
baseURL       = "https://msirikasem.com/"
2. In config.toml, set line 6 to:
#baseURL       = "https://msirikasem.github.io/msirikasem.com/"
3. Start the server in development mode, by opening a terminal in the project folder and running this command:
hugo server -D
4. Visit http://localhost:1313 to see your site, running locally from your computer (nobody else can see this)

# Before pushing to github:
1. In config.toml, set line 3 to:
#baseURL       = "https://msirikasem.com/"
2. In config.toml, set line 6 to:
baseURL       = "https://msirikasem.github.io/msirikasem.com/"
3. Run the command to generate static site content, and add everything in the "docs/" to be staged for the commit before pushing:
hugo
4. Visit https://msirikasem.github.io/msirikasem.com/ to see your site on github (this is public)
