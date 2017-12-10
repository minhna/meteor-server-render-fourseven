# meteor-react-ssr
it doesn't work, there is a bug in server render.

To make it work, just comment line 7 in file `imports/ui/layouts/site/site.js`:
`import './site.scss';`
