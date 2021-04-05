
# To develop locally:
1. In config.toml, set line 3 to:
baseURL       = "https://msirikasem.com/"
2. In config.toml, set line 5 to:
#baseURL       = "https://msirikasem.github.io/msirikasem.com/"
3. Start the server in development mode, by opening a terminal in the project folder and running this command:
hugo server -D

# Before pushing to github:
1. In config.toml, set line 3 to:
#baseURL       = "https://msirikasem.com/"
2. In config.toml, set line 5 to:
baseURL       = "https://msirikasem.github.io/msirikasem.com/"
3. Run the command to generate static site content, and add everything in the "docs/" to be staged for the commit before pushing:
hugo
