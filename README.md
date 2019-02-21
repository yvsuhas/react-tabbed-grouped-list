## spfx-webpart-internal-projects

A SharePoint Framework web part that demonstrates a way to organize and display SharePoint list items using PnPJS and the Pivot and GroupedList Fabric UI components

### Building the code

```bash
git clone the repo
npm i
gulp serve
```

This package produces the following:

* lib/* - intermediate-stage commonjs build artifacts
* dist/* - the bundled script, along with other resources
* deploy/* - all resources which should be uploaded to a CDN.

### Build options

gulp build
gulp serve
gulp bundle
gulp package-solution
