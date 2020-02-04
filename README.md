This action allow you to remove files and dependencies for clean projet.

You need to replace the inputs commands:

```
      - name: building
        uses: PoulainMaxime/github-action-clean-before-deploy@master
        with:
          path: $PATH for folder vue | you can leave it blank if the project and has the root
```
