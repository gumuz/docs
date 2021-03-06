## Local builds

Besides running builds on the wercker platform you can run builds
locally as well. See the [wercker CLI section](/learn/basics/the-wercker-cli.html) for more information of
setting up your local wercker environment.

### Using the CLI to run a local build

From within your project folder run the following command.

```sh
wercker build
```

If your build is dependent on any environment variables, for instance
when running [after-steps](/learn/steps/after-steps.html), your
local build will fail unless you explicitely set these.

In the next section we'll look at how to pull builds into your local
environment.

- - -
> Want to learn more about using local environment variables? Read more about this on the
> [docs](/docs/environment-variables/index.html)

[&lsaquo; Introduction to build](/learn/build/introduction.html "nav previous build")
[Pulling builds &rsaquo;](/learn/build/pulling-builds.html "nav next build")
