# Reproducer

In some cases the file move detection step of the CE can take a long time.

1. Checkout `HEAD^` and run SonarQube analysis -> should complete in about a minute
2. Checkout `master` and run SonarQube analysis -> would not complete for hours (if timeout is not enforced)

## Links

Original repo: https://github.com/vasu-rbt/kentico12-mvc-widgets
(The original repo is publicly available at the time of this writing)
