# opendocs.rootwire.co.uk

Open Source Documentation

## Installation

For more information on the installation process see our installation documentation, but if you want to jump right in then the easiest way is using NVM and then running:

    nvm install
    npm i -g yarn
    yarn
    yarn start

## Building your content

During development you will almost certainly want to use the yarn development server, however you will sometimes need to build the content to use certain features.

This is easily achieved with yarn:

    yarn build

This command will compile all of the documentation into static HTML files complete with all appropriate resources.

As part of this build, the validity of all internal links will be checked. For this reason we strongly recommend building the content locally before submitting a pull request as broken internal links will lead to a build failure immediately.

You may also need to configure the build to view it locally. This can be achieved using a .env file in the project root. For more information on the format of the .env file, see the documentation in the .env.default file.