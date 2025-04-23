# landscape-data-template

Template for a local-first landscape technology data repo.

## How to use this template

1. Fork this repo and clone your forked repo.
2. If there's already sample data for your technology, head over to the [temporary-technology-info](https://github.com/localfirstfm/local-first-landscape/tree/main/temporary-technology-info) folder and copy the `data.js` file to your repo.
3. If there's no sample data, just start filling things out in `data.js`.
4. Run `npm install` to install the schema dependency. In your IDE, you should now get type safety for the data you're adding.

## How to preview my `data.js`?

Go to the Local-first Landscape staging server. (ask Johannes or Jess for access)
You can drag & drop it on this drop zone to preview it:

![](https://share.cleanshot.com/bw8Q94Zh+)

## How to add my project to the hosted landscape page?

1. Add your data repo to this [repos.ts file](https://github.com/localfirstfm/local-first-landscape/edit/main/landscape-fetch-content/src/repos.ts) by forking the [local-first-landscape](https://github.com/localfirstfm/local-first-landscape) repo and creating a pull request.
2. The landscape project maintainers will review your pull request and merge it if everything looks good.

## Resources

- Examples for different technologies: [temporary-technology-info](https://github.com/localfirstfm/local-first-landscape/tree/main/temporary-technology-info)
- Schema: [landscape-schema](https://github.com/localfirstfm/local-first-landscape/blob/main/landscape-schema/src/schema.ts)
