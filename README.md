I did not develop this extension. It was removed from the chrome store so I forked the github repo and re-released it. 

### Summary
Well behaved browser tabs for Zendesk agents

Zendesk QuickTab for Chrome makes tab management a little easier by monitoring when a new browser tab is navigating to a Zendesk Support /agent link. Zendesk QuickTab checks if you have an agent browser tab already open. If you do, QuickTab opens the link on the existing agent tab. This keeps the number of Zendesk Support browser tabs down to just one.

QuickTab begins working as soon as installed. No set up needed!

### What permissions does QuickTab need?
The extension will request permission to read and change your data on all zendesk.com sites. It needs this permission in order to keep your browser tabs in check.

### Running locally

You need to have `grunt`, `ruby`, and ruby `sass` installed on your path.

Then install node modules with 

```
npm install
```

Then you can compile the project with

```
grunt build
```

or watch the assets for selective rebuilding with:

```
grunt watch
```

### Contributing

Please feel free to open issues or submit pull requests. 