### adding new projects with their own git history
```sh
git subtree add --prefix=apps/anime-site https://github.com/valiantlynx/anime-site.git master --squash
git subtree pull --prefix=apps/anime-site https://github.com/valiantlynx/anime-site.git master --squash
git subtree push --prefix=apps/anime-site https://github.com/valiantlynx/anime-site.git master

```
