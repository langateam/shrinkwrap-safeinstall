# shrinkwrap-safeinstall

shrinkwrap.io manages shrinkwraps for your npm modules. Connect your Github
Account at [**shrinkwrap.io**](https://shrinkwrap.io), and the SaaS
(shrinkwrap-as-a-service) will automatically issue a Pull Request with the
necessary configuration. Manual setup steps are below.

### Reasons to use safeinstall

- Shrinkwrap dependency tree for production safety
- 5x Faster npm installation
- Avoid the [npm worm](https://www.infoq.com/news/2016/03/npm-infection) and [left-pad](http://blog.npmjs.org/post/141577284765/kik-left-pad-and-npm) issues.
- Avoid unwieldy diffs in source control

Install this module to support shrinkwrap.io [**safeinstall**](https://shrinkwrap.io)
in your project.

## Install

```
npm install --save shrinkwrap.io
```

### Configure package.json
```json
{
  "scripts": {
    "safeinstall": "safeinstall"
  }
}
```
