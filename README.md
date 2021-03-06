[![npm](https://img.shields.io/npm/v/serverless-yandex-cloud.svg)](https://www.npmjs.com/package/serverless-yandex-cloud)
[![License](https://img.shields.io/github/license/yandex-cloud/serverless-plugin.svg)](https://github.com/yandex-cloud/serverless-plugin/blob/master/LICENSE)


# Serverless Yandex Cloud Functions Plugin

This plugin enables support for Yandex Cloud Functions within the [Serverless Framework](https://github.com/serverless/serverless).

## Quick Start

First of all, you need to install `serverless` command-line tool. Check official [get started](https://www.serverless.com/framework/docs/getting-started/) guide. Fastest way to do this is to use `npm`:

    npm install serverless -g

Now you can create new project from template provided by this plugin:

    serverless create \
      --template-url https://github.com/yandex-cloud/serverless-plugin/tree/master/templates/nodejs

Before you deploy your first functions using Serverless, you need to configure Yandex.Cloud credentials. Easiest way to do that
is to install `yc` command-line tool and use wizard to provide all required parameters. All required guides and in-depth documentation availabe at [Yandex.Cloud website](https://cloud.yandex.com/docs/cli/quickstart).

To deploy your project use:

    serverless deploy

To invoke (test) your function:

    serverless invoke -f simple

To remove all deployed resources:

    serverless remove
