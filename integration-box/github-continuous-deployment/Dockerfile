FROM szyn/docker-digdag:latest

LABEL "com.github.actions.name"="Github Deploy to Treasure Wofklow"
LABEL "com.github.actions.description"="Continuous deployment for your project to Treasure Workflow"
LABEL "repository"="https://github.com/treasure-data/treasure-boxes"
LABEL "maintainer"="Toru Takahashi <torutakahashi.ayashi@gmail.com>"

COPY entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
