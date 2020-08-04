# dockle-orb

# How to publish

1. Pack the orb `circleci config pack src > .circleci/config.yml`
2. Validate it `circleci config validate`
3. Publish `circleci orb publish .circleci/config.yml streetbees/dockle@dev:first`
4. Premote it `circleci orb publish promote streetbees/dockle@dev:first patch`