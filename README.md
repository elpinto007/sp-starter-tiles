## sp-starter-tiles

This web part is an individually packaged extension from the SharePoint Starter Kit provided by the Community. You can find more information about them here. https://github.com/SharePoint/sp-starter-kit

### Building the code

```bash
git clone the repo
npm i
npm i -g gulp
gulp serve
```

### Build options
```
gulp clean
gulp build
gulp bundle --ship
gulp package-solution --ship
```
There are no list or feature configurations you need to do. Here are the steps to get you going:
1. Once you package the solution, drag the sppkg solution from the SharePoint > Solution folder to your app catalog on your dev tenant.
2. Deploy the solution.
3. Add the app to your hub site (I have not tested it with other sites yet). 
4. Search and add the tiles web part to your page.
5. Configure the links, urls and the icons for the webpart.
Pro tip: you can find the names of the different app icons available in the Office UI Fabric:
https://developer.microsoft.com/en-us/fabric#/styles/icons
 
Finally I want to iterate, this isn't source code, I am not the author of this code. It was used from the PnP-Starter-Kit in the SharePoint repo. I may update this code as needed, and it should only be deployed into test tenants. This is just the tiles web part from the solution.
