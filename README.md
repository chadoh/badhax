# #badhax

Site built with Middleman.

Slides made to run with [big](https://github.com/tmcw/big), but that's not implemented yet.

# Run it locally

Clone the source code, install Ruby, and then:

    bundle install
    middleman

That'll start middleman in development mode, and tell you that you can visit it at `localhost:4567`.

# Deploying

To deploy, you need to have the main repo set up as your `origin` remote on Github. You'll need to be a collaborator.

Assuming you have that out of the way, all you need to do is

    middleman deploy
