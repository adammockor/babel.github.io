---
layout: default
custom_js:
- index.js
third_party_js:
- //cdn.rawgit.com/thejameskyle/slick/lazy-load-responsive-2/slick/slick.min.js
- //unpkg.com/babel-standalone@6/babel.min.js
- //cdnjs.cloudflare.com/ajax/libs/ace/1.1.3/ace.js
---

<div class="hero">
  <div class="hero__content">
    <h1>Babel is a JavaScript compiler.</h1>
    <p>Use next generation JavaScript, today.</p>

    <div class="hero-repl">
      <div class="hero-repl__editor">
        <div class="hero-repl__pane hero-repl__pane--left">
          <h3>You put JavaScript in</h3>
          <div id="hero-repl-in" class="hero-repl__code"></div>
        </div>

        <div class="hero-repl__pane hero-repl__pane--right">
          <h3>And get JavaScript out</h3>
          <div id="hero-repl-out" class="hero-repl__code"></div>
        </div>
      </div>
      <div class="hero-repl__footer">
        <a href="http://babeljs.io/repl/#?babili=false&evaluate=true&lineWrap=false&presets=latest%2Creact%2Cstage-2&experimental=false&loose=false&spec=false&code=%5B1%2C2%2C3%5D.map(n%20%3D%3E%20n%20%2B%201)%3B&playground=true">
          Check out our REPL to experiment more with Babel!
        </a>
      </div>
    </div>

    <div class="hero-actions">
      <div class="hero-actions-blog">
        <a href="/blog/2016/12/07/the-state-of-babel">
          <span class="hero-actions-blog__label">Latest From Our Blog:</span>
          <span class="hero-actions-blog__post">The State of Babel</span>
        </a>
      </div>
    </div>
  </div>
</div>

<div class="container">
  <div class="row featurette text-center featurette--get-started">
    <h2>Ready to get started?</h2>

    <div class="col-lg-6">
      <h3>Install the Babel CLI and a preset</h3>
      <div class="text-left">
<div markdown="1">
```shell
npm install --save-dev babel-cli babel-preset-env
```
</div>
      </div>
    </div>
    <div class="col-lg-6">
      <h3>Create a <a href="/docs/usage/babelrc"><code>.babelrc</code></a> file (or use your <a href="/docs/usage/babelrc#use-via-package-json">package.json</a>)</h3>
      <div class="text-left">
<div markdown="1">
```json
{
  "presets": ["env"]
}
```
</div>
      </div>
    </div>

    <p>
      For more information on setting up Babel with your build system, IDE,
      and more, check out our <a href="/docs/setup">interactive setup
      guide</a>.
    </p>
  </div>

  <hr class="featurette-divider">

  <div class="row featurette">
    <div class="col-md-6">
      <h2 id="es2015-and-beyond">ES2015 and beyond</h2>
      <p>
        Babel has support for the latest version of JavaScript through syntax transformers.
        These <a href="https://babeljs.io/docs/plugins/">plugins</a> allow you to use new syntax, <strong>right now</strong> without waiting for browser support.
        Check out our <a href="https://babeljs.io/docs/plugins/preset-env">env preset</a> to get started.
      </p>

      <p>You can install this preset with</p>
<div markdown="1">
```shell
npm install --save-dev babel-preset-env
```
</div>
      <p>and add <code>"env"</code> to your <code>.babelrc</code> presets array.</p>
    </div>

    <div class="col-md-6">
      <div class="col-md-6">
        <ul class="babel-tick-list">
          <li><a href="/docs/plugins/transform-es2015-arrow-functions">Arrow functions</a></li>
          <li><a href="/docs/plugins/syntax-async-functions">Async functions</a></li>
          <li><a href="/docs/plugins/syntax-async-generators">Async generator functions</a></li>
          <li><a href="/docs/plugins/transform-es2015-block-scoping">Block scoping</a></li>
          <li><a href="/docs/plugins/transform-es2015-block-scoped-functions">Block scoped functions</a></li>
          <li><a href="/docs/plugins/transform-es2015-classes">Classes</a></li>
          <li><a href="/docs/plugins/transform-class-properties">Class properties</a></li>
          <li><a href="/docs/plugins/transform-es2015-computed-properties">Computed property names</a></li>
          <li><a href="/docs/plugins/check-es2015-constants">Constants</a></li>
          <li><a href="/docs/plugins/transform-decorators">Decorators</a></li>
          <li><a href="/docs/plugins/transform-es2015-parameters">Default parameters</a></li>
          <li><a href="/docs/plugins/transform-es2015-destructuring">Destructuring</a></li>
          <li><a href="/docs/plugins/transform-do-expressions">Do expressions</a></li>
          <li><a href="/docs/plugins/transform-exponentiation-operator">Exponentiation operator</a></li>
          <li><a href="/docs/plugins/transform-es2015-for-of">For-of</a></li>
        </ul>
      </div>

      <div class="col-md-6">
        <ul class="babel-tick-list">
          <li><a href="/docs/plugins/transform-function-bind">Function bind</a></li>
          <li><a href="/docs/plugins/transform-regenerator">Generators</a></li>
          <li><a href="/docs/plugins/#modules">Modules</a></li>
          <li><a href="/docs/plugins/transform-export-extensions">Module export extensions</a></li>
          <li><a href="/docs/plugins/transform-es2015-literals">New literals</a></li>
          <li><a href="/docs/plugins/transform-object-rest-spread">Object rest/spread</a></li>
          <li><a href="/docs/plugins/transform-es2015-shorthand-properties">Property method assignment</a></li>
          <li><a href="/docs/plugins/transform-es2015-shorthand-properties">Property name shorthand</a></li>
          <li><a href="/docs/plugins/transform-es2015-parameters">Rest parameters</a></li>
          <li><a href="/docs/plugins/transform-es2015-parameters">Spread</a></li>
          <li><a href="/docs/plugins/transform-es2015-sticky-regex">Sticky regex</a></li>
          <li><a href="/docs/plugins/transform-es2015-template-literals">Template literals</a></li>
          <li><a href="/docs/plugins/syntax-trailing-function-commas">Trailing function commas</a></li>
          <li><a href="/docs/plugins/transform-flow-strip-types">Type annotations</a></li>
          <li><a href="/docs/plugins/transform-es2015-unicode-regex">Unicode regex</a></li>
        </ul>
      </div>

      <br>
      <p class="text-center"><a href="/docs/learn-es2015/">Learn more about ES2015 &rarr;</a></p>
    </div>
  </div>

    <hr class="featurette-divider">

    <div class="row featurette">
      <div class="col-md-6">
        <h2 id="polyfill">Polyfill</h2>
        <p>Since Babel only transforms syntax (like arrow functions), you can use babel-polyfill in order to support new globals such as Promise or new native methods like String.padStart (left-pad). It uses <a href="https://github.com/zloirock/core-js">core-js</a> and <a href="https://facebook.github.io/regenerator/">regenerator</a>. Check out our <a href="/docs/usage/polyfill">babel-polyfill</a> docs for more info.</p>

        <p>You can install the polyfill with</p>
<div markdown="1">
```shell
npm install --save-dev babel-polyfill
```
</div>
        <p>Use it by requiring it at the top of the entry point to your application or in your bundler config.</p>
      </div>

      <div class="col-md-6">
        <div class="col-md-6">
          <ul class="babel-tick-list">
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/ArrayBuffer">ArrayBuffer</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/from">Array.from</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/of">Array.of</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/copyWithin">Array#copyWithin</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/fill">Array#fill</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/find">Array#find</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/findIndex">Array#findIndex</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/name">Function#name</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map">Map</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/acosh">Math.acosh</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/hypot">Math.hypot</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/imul">Math.imul</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/isNaN">Number.isNaN</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/isInteger">Number.isInteger</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/assign">Object.assign</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyDescriptors">Object.getOwnPropertyDescriptors</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/is">Object.is</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/entries">Object.entries</a></li>
          </ul>
        </div>

        <div class="col-md-6">
          <ul class="babel-tick-list">
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/values">Object.values</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/setPrototypeOf">Object.setPrototypeOf</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise">Promise</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect">Reflect</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/flags">RegExp#flags</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set">Set</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/codePointAt">String#codePointAt</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/endsWith">String#endsWith</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/fromCodePoint">String.fromCodePoint</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/includes">String#includes</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/raw">String.raw</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/repeat">String#repeat</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/startsWith">String#startsWith</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/padStart">String#padStart</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/padEnd">String#padEnd</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol">Symbol</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakMap">WeakMap</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakSet">WeakSet</a></li>
          </ul>
        </div>

        <br>
        <p class="text-center"><a href="https://github.com/zloirock/core-js#index">Learn about more features &rarr;</a></p>
      </div>
    </div>


  <hr class="featurette-divider">

  <div class="row featurette">

    <div class="col-md-7">
      <h2 id="jsx-and-flow">JSX and Flow</h2>
      <p>Babel can convert JSX syntax and strip out type annotations. Check out our <a href="https://babeljs.io/docs/plugins/preset-react/">React preset</a> to get started. Use it together with the <a href="https://github.com/babel/babel-sublime">babel-sublime</a> package to bring syntax highlighting to a whole new level.</p>

      <p>You can install this preset with</p>
<div markdown="1">
```shell
npm install --save-dev babel-preset-react
```
</div>
      <p>and add <code>"react"</code> to your <code>.babelrc</code> presets array.</p>
    </div>
    <div class="col-md-5">
<div class="language-javascript highlighter-rouge"><pre class="highlight"><code><span class="kr">export</span> <span class="k">default</span> <span class="nx">React</span><span class="p">.</span><span class="nx">createClass</span><span class="p">({</span>
  <span class="nx">getInitialState</span><span class="p">()</span> <span class="p">{</span>
    <span class="k">return</span> <span class="p">{</span> <span class="nx">num</span><span class="o">:</span> <span class="k">this</span><span class="p">.</span><span class="nx">getRandomNumber</span><span class="p">()</span> <span class="p">};</span>
  <span class="p">},</span>

  <span class="nx">getRandomNumber</span><span class="p">()</span><span class="o">:</span> <span class="nx">number</span> <span class="p">{</span>
    <span class="k">return</span> <span class="nb">Math</span><span class="p">.</span><span class="nx">ceil</span><span class="p">(</span><span class="nb">Math</span><span class="p">.</span><span class="nx">random</span><span class="p">()</span> <span class="o">*</span> <span class="mi">6</span><span class="p">);</span>
  <span class="p">},</span>

  <span class="nx">render</span><span class="p">()</span><span class="o">:</span> <span class="nx">any</span> <span class="p">{</span>
    <span class="k">return</span> <span class="nx">&lt;div&gt;</span>
      <span class="s2">Your dice roll:</span>
      <span class="p">{</span><span class="k">this</span><span class="p">.</span><span class="nx">state</span><span class="p">.</span><span class="nx">num</span><span class="p">}</span>
    <span class="nx">&lt;/div&gt;;</span>
  <span class="p">}</span>
<span class="p">});</span></code></pre></div>

      <p class="text-center">Learn more about <a href="https://facebook.github.io/jsx/">JSX</a> and <a href="http://flowtype.org/">Flow</a></p>
    </div>
  </div>

  <hr class="featurette-divider">

  <div class="row featurette">
    <div class="col-md-6">
      <h2 id="pluggable">Pluggable</h2>
      <p>Babel is built out of plugins. Compose your own transformation pipeline using existing plugins or write your own. Easily use a set of plugins by using or creating a <a href="/docs/plugins/#presets">preset</a>. <a href="/docs/plugins/">Learn more &rarr;</a></p>
      <p>Create a plugin on the fly with <a href="https://astexplorer.net/#/KJ8AjD6maa">astexplorer.net</a></p>
    </div>
    <div class="col-md-6">
<div markdown="1">
```javascript
// A plugin is just a function
export default function ({types: t}) {
  return {
    visitor: {
      Identifier(path) {
        let name = path.node.name;
        // reverse the name: JavaScript -> tpircSavaJ
        path.node.name = name.split('').reverse().join('');
      }
    }
  };
}
```
</div>
    </div>
  </div>

  <hr class="featurette-divider">

  <div class="row featurette">
    <div class="col-md-4">
      <h2 id="debuggable">Debuggable</h2>
      <p><strong>Source map</strong> support so you can debug your compiled code with ease.</p>
    </div>
    <div class="col-md-8">
      <img src="{{ site.baseurl }}/images/featurettes/debuggable.png?t={{ site.time | date_to_xmlschema }}" alt="Debuggable Sourcemaps" class="featurette-image img-responsive">
    </div>
  </div>

  <!--<div class="row featurette">
    <div class="col-md-4">
      <h2>Readable</h2>
      <p>
        Formatting is retained if possible so your generated code is as similar
        as possible.
      </p>
    </div>
    <div class="col-md-4 col-sm-6">
<div markdown="1">
```javascript

```
</div>
      </div>
      <div class="col-md-4 col-sm-6">
<div markdown="1">
```javascript

```
</div>
    </div>
  </div>

  <!--<hr class="featurette-divider">

  <div class="row featurette">
    <div class="col-md-4 col-md-push-8">
      <h2>Compact</h2>
      <p>Babel uses the least amount of code possible with no dependence on a bulky runtime.</p>
    </div>
    <div class="col-md-4 col-md-pull-4 col-sm-6">
<div markdown="1">
```javascript

```
</div>
    </div>
    <div class="col-md-4 col-md-pull-4 col-sm-6">
<div markdown="1">
```javascript

```
</div>
    </div>
  </div>-->

  <hr class="featurette-divider">

  <div class="featurette">
    <h2 class="text-center">
      <a href="{{ site.baseurl }}/users/">
        Who's using Babel?
      </a>
    </h2>

    <div class="babel-user-container babel-slider">
      {% for user in site.data.users limit:18 %}
        <div class="col-md-4 col-sm-6">
          <a class="babel-user" href="{{user.url}}" title="{{user.name}}">
            <img class="img-responsive" data-lazy="/images/users/{{user.logo}}" alt="{{user.name}}" data-proofer-ignore>
          </a>
        </div>
      {% endfor %}
    </div>

    <div class="text-center">
      <div class="btn-wrapper">
        <a href="{{ site.baseurl }}/users/" class="btn btn-sm btn-featured">Meet more Users</a>
      </div>
    </div>
  </div>

  <link rel="stylesheet" href="//cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.4.1/slick.css">
</div>
