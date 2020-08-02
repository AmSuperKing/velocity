##Velocity (0.11.6)

**Docs**  
[VelocityJS.org](http://VelocityJS.org)

**Quickstart**  

`bower install velocity`  
`npm install velocity-animate`  
`<script src="//cdn.jsdelivr.net/jquery.velocity/0.11.7/jquery.velocity.min.js"></script>`

**Which file should I use?**

`jquery.velocity.js` will soon be renamed to `velocity.js` as the jQuery dependency is dropped. See [VelocityJS.org/#dependencies](http://VelocityJS.org/#dependencies) for more information.

###**Learn**

- **UI effects**: http://smashingmagazine.com/2014/06/18/faster-ui-animations-with-velocity-js
- **Perf. comparisons**: http://davidwalsh.name/css-js-animation
- **Workflow**: http://css-tricks.com/improving-ui-animation-workflow-velocity-js

###**New**

- 0.11.4: AMD and CommonJS module loading without having to shim jQuery.
- 0.11.1: **Huge performance boost, and elements are no longer dirtied with inline styles.**
- 0.11.0: CSS transform setting/getting. [VelocityJS.org/#hook](http://VelocityJS.org/#hook)
- 0.10.0: Infinite looping. [VelocityJS.org/#loop](http://VelocityJS.org/#loop)
- 0.9.0: Hex colors. [VelocityJS.org/#colors](http://VelocityJS.org/#colors)
- 0.8.0: vw/vh CSS units.
- 0.6.0: `display: "auto"` and `visibility`. [VelocityJS.org/#displayAndVisibility](http://VelocityJS.org/#displayAndVisibility)
- 0.5.0: Promises. [VelocityJS.org/#promises](http://VelocityJS.org/#promises)
- 0.3.0-0.4.0: SVG animation. [VelocityJS.org/#svg](http://VelocityJS.org/#svg)
- 0.1.0: `stop` now stops animations *immediately* (instead of just clearing the remainder of the animation queue). No other backwards-incompatible changes were made. [VelocityJS.org/#stop](http://VelocityJS.org/#stop)

###**Comparisons**

- **Famo.us** is a full-fledged *mobile app framework* built around a physics engine.
- **CSS transitions** are meant for simple interface flourishes triggered by hover states.
- **jQuery's $.animate()** is slow and poorly-equipped for motion design.
- **Velocity** allows you to inject rich motion design into your UI.

###**Credits**

- <a href="https://stripe.com/blog/stripe-open-source-retreat">Stripe</a> sponsors Velocity's development.
- <a href="http://browserstack.com">BrowserStack</a> provides Velocity's testing services. 

====

[MIT License](LICENSE.md). © Julian Shapiro (http://twitter.com/shapiro).
