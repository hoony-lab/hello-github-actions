FROM debian:9.5-slim

LABAL "com.github.actions.name"="Hello World"
LABAL "com.github.actions.description"="Write arguments to the std output"
LABAL "com.github.actions.icon"="mic"
LABAL "Com.github.actions.color"="purple"

LABEL "repository"="http://github.com/octocat/hello-world"
LABEL "homepage"="http://github.com/actions"
LABEL "maintainer"="Octocat <octocat@github.com>"

ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
