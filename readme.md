# axe-core Linter 

Axe is an accessibility testing engine for websites and other HTML-based user interfaces. It's fast, secure, lightweight, and was built to seamlessly integrate with any existing test environment so you can automate accessibility testing alongside your regular functional testing.

In this Demo, I demonstarte the capabilities of axe-core linter of helping developer capturing accessibility issues through the browser's dev console log.

# Getting started


Install packages
```sh
$ npm install
```

Run the app in the browser 
```sh
$ npm run dev
```
Project is running at [http://localhost:3000][PlGh]

Example will run through a simple heading ranks validations 

```
class App extends React.Component {
  render() {
    return (
      <div>
        <h1>Hello World Axe-coe linter</h1>
        <h2>Second heading rank</h2>
      </div>
    )
  }
}

```

## If you change the rank of the headings like the following:


```
class App extends React.Component {
  render() {
    return (
      <div>
        <h1>Hello World Axe-coe linter</h1>
        <h3>Second heading rank</h3>
      </div>
    )
  }
}
```
The app will refresh in the browser and the developer will be prompt inside the dev console with corresponding accessibility issue

![](https://s3.amazonaws.com/cds-2019/axe-linter-devconsole.png)

# References 

1. [Web Accessibility Tutorials](https://www.w3.org/WAI/tutorials/page-structure/headings/)
2. [axe-core API](https://github.com/dequelabs/axe-core)

# Demo
 [visual demo link](https://www.useloom.com/share/74507a6c271f4ed9b1df3d0c3262f175)



