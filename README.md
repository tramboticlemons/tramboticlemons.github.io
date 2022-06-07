### Running and Testing LocallyPermalink
Once the project is configured with the github-pages environment, it’s quite hard to switch back and forth with the local settings and the production-level settings. For that we can use certain CLI options to make the workflow hassle-free.

```
bundle exec jekyll serve --baseurl=""
```

This will run the jekyll server on your local machine i.e. on http://localhost:4000. Refer server options for available options.