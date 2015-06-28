yesod-fay
=========

Utilities for using the [Haste](http://haste-lang.org/) Haskell-to-JS compiler with [Yesod](http://www.yesodweb.com).

The code is forked from [`yesod-fay`](http://hackage.haskell.org/package/yesod-fay) and provides similar APIs.

For an example of a Yesod application with Haste integrated, have a look at the `sample/` directory in this repository.


<!--
Usage with cabal sandboxes
--------------------------

You are highly encouraged to create a cabal sandbox for your Yesod app. This feature is available in cabal 1.18+.

Use the following command to set an environment variable (this is a workaround, needed until Fay integrates with [haskell-packages](http://hackage.haskell.org/package/haskell-packages), only possible after cabal 1.20 is released). 

    export HASKELL_PACKAGE_SANDBOX=`echo .cabal-sandbox/*-packages.conf.d/`

Make sure to run this from the root of the Yesod project.
-->
