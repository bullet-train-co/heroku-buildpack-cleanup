Note: We've forked this buildpack to help mitigate the risk of a [supply chain attack](https://en.wikipedia.org/wiki/Supply_chain_attack) where applications can become compromised via the compromised repo of a third-party buildpack. You should also consider forking this repo and linking to your own copy of it for the same reason. 

Big thanks to [Hirotaka Ikoma](https://github.com/hikoma) for making this available to everyone!

--- 

# heroku-buildpack-cleanup

Remove files that are specified in a .slugcleanup file.

## Usage

    $ heroku buildpacks:add https://github.com/syginc/heroku-buildpack-cleanup.git

    $ cat .slugcleanup
    gradle*
    node_modules

## License

MIT
