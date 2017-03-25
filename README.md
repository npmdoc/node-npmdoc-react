# api documentation for  [react (v15.4.2)](https://facebook.github.io/react/)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react)
#### React is a JavaScript library for building user interfaces.

[![NPM](https://nodei.co/npm/react.png?downloads=true)](https://www.npmjs.com/package/react)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-react_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-react/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "browserify": {
        "transform": [
            "loose-envify"
        ]
    },
    "bugs": {
        "url": "https://github.com/facebook/react/issues"
    },
    "dependencies": {
        "fbjs": "^0.8.4",
        "loose-envify": "^1.1.0",
        "object-assign": "^4.1.0"
    },
    "description": "React is a JavaScript library for building user interfaces.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "41f7991b26185392ba9bae96c8889e7e018397ef",
        "tarball": "https://registry.npmjs.org/react/-/react-15.4.2.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "LICENSE",
        "PATENTS",
        "addons.js",
        "react.js",
        "addons/",
        "dist/",
        "lib/"
    ],
    "homepage": "https://facebook.github.io/react/",
    "keywords": [
        "react"
    ],
    "license": "BSD-3-Clause",
    "main": "react.js",
    "maintainers": [
        {
            "name": "fb",
            "email": "opensource+npm@fb.com"
        },
        {
            "name": "gaearon",
            "email": "dan.abramov@gmail.com"
        },
        {
            "name": "graue",
            "email": "scott@oceanbase.org"
        },
        {
            "name": "jeffmo",
            "email": "lbljeffmo@gmail.com"
        },
        {
            "name": "sebmarkbage",
            "email": "sebastian@calyptus.eu"
        },
        {
            "name": "spicyj",
            "email": "ben@benalpert.com"
        },
        {
            "name": "tomocchino",
            "email": "tomocchino@gmail.com"
        },
        {
            "name": "zpao",
            "email": "paul@oshannessy.com"
        }
    ],
    "name": "react",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/facebook/react.git"
    },
    "scripts": {},
    "version": "15.4.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module react](#apidoc.module.react)
1.  [function <span class="apidocSignatureSpan">react.</span>Component (props, context, updater)](#apidoc.element.react.Component)
1.  [function <span class="apidocSignatureSpan">react.</span>PropTypes.any ()](#apidoc.element.react.PropTypes.any)
1.  [function <span class="apidocSignatureSpan">react.</span>PropTypes.array ()](#apidoc.element.react.PropTypes.array)
1.  [function <span class="apidocSignatureSpan">react.</span>PropTypes.bool ()](#apidoc.element.react.PropTypes.bool)
1.  [function <span class="apidocSignatureSpan">react.</span>PropTypes.element ()](#apidoc.element.react.PropTypes.element)
1.  [function <span class="apidocSignatureSpan">react.</span>PropTypes.func ()](#apidoc.element.react.PropTypes.func)
1.  [function <span class="apidocSignatureSpan">react.</span>PropTypes.node ()](#apidoc.element.react.PropTypes.node)
1.  [function <span class="apidocSignatureSpan">react.</span>PropTypes.number ()](#apidoc.element.react.PropTypes.number)
1.  [function <span class="apidocSignatureSpan">react.</span>PropTypes.object ()](#apidoc.element.react.PropTypes.object)
1.  [function <span class="apidocSignatureSpan">react.</span>PropTypes.string ()](#apidoc.element.react.PropTypes.string)
1.  [function <span class="apidocSignatureSpan">react.</span>PropTypes.symbol ()](#apidoc.element.react.PropTypes.symbol)
1.  [function <span class="apidocSignatureSpan">react.</span>PureComponent (props, context, updater)](#apidoc.element.react.PureComponent)
1.  [function <span class="apidocSignatureSpan">react.</span>ReactElement (type, key, ref, self, source, owner, props)](#apidoc.element.react.ReactElement)
1.  [function <span class="apidocSignatureSpan">react.</span>ReactTransitionGroup ()](#apidoc.element.react.ReactTransitionGroup)
1.  [function <span class="apidocSignatureSpan">react.</span>__spread ()](#apidoc.element.react.__spread)
1.  [function <span class="apidocSignatureSpan">react.</span>cloneElement (element, props, children)](#apidoc.element.react.cloneElement)
1.  [function <span class="apidocSignatureSpan">react.</span>createClass (spec)](#apidoc.element.react.createClass)
1.  [function <span class="apidocSignatureSpan">react.</span>createElement (type, props, children)](#apidoc.element.react.createElement)
1.  [function <span class="apidocSignatureSpan">react.</span>createFactory (type)](#apidoc.element.react.createFactory)
1.  [function <span class="apidocSignatureSpan">react.</span>createMixin (mixin)](#apidoc.element.react.createMixin)
1.  [function <span class="apidocSignatureSpan">react.</span>isValidElement (object)](#apidoc.element.react.isValidElement)
1.  object <span class="apidocSignatureSpan">react.</span>Children
1.  object <span class="apidocSignatureSpan">react.</span>Component.prototype
1.  object <span class="apidocSignatureSpan">react.</span>DOM
1.  object <span class="apidocSignatureSpan">react.</span>KeyEscapeUtils
1.  object <span class="apidocSignatureSpan">react.</span>LinkedStateMixin
1.  object <span class="apidocSignatureSpan">react.</span>PooledClass
1.  object <span class="apidocSignatureSpan">react.</span>PropTypes
1.  object <span class="apidocSignatureSpan">react.</span>PureComponent.prototype
1.  object <span class="apidocSignatureSpan">react.</span>ReactAddonsDOMDependenciesUMDShim
1.  object <span class="apidocSignatureSpan">react.</span>ReactChildren
1.  object <span class="apidocSignatureSpan">react.</span>ReactClass
1.  object <span class="apidocSignatureSpan">react.</span>ReactComponentTreeDevtool
1.  object <span class="apidocSignatureSpan">react.</span>ReactComponentWithPureRenderMixin
1.  object <span class="apidocSignatureSpan">react.</span>ReactElementValidator
1.  object <span class="apidocSignatureSpan">react.</span>ReactFragment
1.  object <span class="apidocSignatureSpan">react.</span>ReactNoopUpdateQueue
1.  object <span class="apidocSignatureSpan">react.</span>ReactStateSetters
1.  object <span class="apidocSignatureSpan">react.</span>ReactTransitionChildMapping
1.  object <span class="apidocSignatureSpan">react.</span>ReactTransitionGroup.prototype
1.  object <span class="apidocSignatureSpan">react.</span>ReactUMDEntry
1.  string <span class="apidocSignatureSpan">react.</span>version

#### [module react.Children](#apidoc.module.react.Children)
1.  [function <span class="apidocSignatureSpan">react.Children.</span>count (children, context)](#apidoc.element.react.Children.count)
1.  [function <span class="apidocSignatureSpan">react.Children.</span>forEach (children, forEachFunc, forEachContext)](#apidoc.element.react.Children.forEach)
1.  [function <span class="apidocSignatureSpan">react.Children.</span>map (children, func, context)](#apidoc.element.react.Children.map)
1.  [function <span class="apidocSignatureSpan">react.Children.</span>only (children)](#apidoc.element.react.Children.only)
1.  [function <span class="apidocSignatureSpan">react.Children.</span>toArray (children)](#apidoc.element.react.Children.toArray)

#### [module react.Component](#apidoc.module.react.Component)
1.  [function <span class="apidocSignatureSpan">react.</span>Component (props, context, updater)](#apidoc.element.react.Component.Component)

#### [module react.Component.prototype](#apidoc.module.react.Component.prototype)
1.  [function <span class="apidocSignatureSpan">react.Component.prototype.</span>forceUpdate (callback)](#apidoc.element.react.Component.prototype.forceUpdate)
1.  [function <span class="apidocSignatureSpan">react.Component.prototype.</span>setState (partialState, callback)](#apidoc.element.react.Component.prototype.setState)
1.  object <span class="apidocSignatureSpan">react.Component.prototype.</span>isReactComponent

#### [module react.DOM](#apidoc.module.react.DOM)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>a ()](#apidoc.element.react.DOM.a)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>abbr ()](#apidoc.element.react.DOM.abbr)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>address ()](#apidoc.element.react.DOM.address)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>area ()](#apidoc.element.react.DOM.area)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>article ()](#apidoc.element.react.DOM.article)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>aside ()](#apidoc.element.react.DOM.aside)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>audio ()](#apidoc.element.react.DOM.audio)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>b ()](#apidoc.element.react.DOM.b)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>base ()](#apidoc.element.react.DOM.base)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>bdi ()](#apidoc.element.react.DOM.bdi)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>bdo ()](#apidoc.element.react.DOM.bdo)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>big ()](#apidoc.element.react.DOM.big)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>blockquote ()](#apidoc.element.react.DOM.blockquote)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>body ()](#apidoc.element.react.DOM.body)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>br ()](#apidoc.element.react.DOM.br)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>button ()](#apidoc.element.react.DOM.button)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>canvas ()](#apidoc.element.react.DOM.canvas)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>caption ()](#apidoc.element.react.DOM.caption)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>circle ()](#apidoc.element.react.DOM.circle)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>cite ()](#apidoc.element.react.DOM.cite)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>clipPath ()](#apidoc.element.react.DOM.clipPath)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>code ()](#apidoc.element.react.DOM.code)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>col ()](#apidoc.element.react.DOM.col)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>colgroup ()](#apidoc.element.react.DOM.colgroup)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>data ()](#apidoc.element.react.DOM.data)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>datalist ()](#apidoc.element.react.DOM.datalist)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>dd ()](#apidoc.element.react.DOM.dd)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>defs ()](#apidoc.element.react.DOM.defs)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>del ()](#apidoc.element.react.DOM.del)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>details ()](#apidoc.element.react.DOM.details)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>dfn ()](#apidoc.element.react.DOM.dfn)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>dialog ()](#apidoc.element.react.DOM.dialog)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>div ()](#apidoc.element.react.DOM.div)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>dl ()](#apidoc.element.react.DOM.dl)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>dt ()](#apidoc.element.react.DOM.dt)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>ellipse ()](#apidoc.element.react.DOM.ellipse)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>em ()](#apidoc.element.react.DOM.em)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>embed ()](#apidoc.element.react.DOM.embed)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>fieldset ()](#apidoc.element.react.DOM.fieldset)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>figcaption ()](#apidoc.element.react.DOM.figcaption)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>figure ()](#apidoc.element.react.DOM.figure)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>footer ()](#apidoc.element.react.DOM.footer)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>form ()](#apidoc.element.react.DOM.form)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>g ()](#apidoc.element.react.DOM.g)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>h1 ()](#apidoc.element.react.DOM.h1)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>h2 ()](#apidoc.element.react.DOM.h2)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>h3 ()](#apidoc.element.react.DOM.h3)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>h4 ()](#apidoc.element.react.DOM.h4)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>h5 ()](#apidoc.element.react.DOM.h5)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>h6 ()](#apidoc.element.react.DOM.h6)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>head ()](#apidoc.element.react.DOM.head)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>header ()](#apidoc.element.react.DOM.header)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>hgroup ()](#apidoc.element.react.DOM.hgroup)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>hr ()](#apidoc.element.react.DOM.hr)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>html ()](#apidoc.element.react.DOM.html)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>i ()](#apidoc.element.react.DOM.i)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>iframe ()](#apidoc.element.react.DOM.iframe)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>image ()](#apidoc.element.react.DOM.image)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>img ()](#apidoc.element.react.DOM.img)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>input ()](#apidoc.element.react.DOM.input)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>ins ()](#apidoc.element.react.DOM.ins)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>kbd ()](#apidoc.element.react.DOM.kbd)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>keygen ()](#apidoc.element.react.DOM.keygen)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>label ()](#apidoc.element.react.DOM.label)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>legend ()](#apidoc.element.react.DOM.legend)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>li ()](#apidoc.element.react.DOM.li)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>line ()](#apidoc.element.react.DOM.line)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>linearGradient ()](#apidoc.element.react.DOM.linearGradient)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>link ()](#apidoc.element.react.DOM.link)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>main ()](#apidoc.element.react.DOM.main)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>map ()](#apidoc.element.react.DOM.map)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>mark ()](#apidoc.element.react.DOM.mark)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>mask ()](#apidoc.element.react.DOM.mask)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>menu ()](#apidoc.element.react.DOM.menu)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>menuitem ()](#apidoc.element.react.DOM.menuitem)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>meta ()](#apidoc.element.react.DOM.meta)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>meter ()](#apidoc.element.react.DOM.meter)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>nav ()](#apidoc.element.react.DOM.nav)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>noscript ()](#apidoc.element.react.DOM.noscript)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>object ()](#apidoc.element.react.DOM.object)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>ol ()](#apidoc.element.react.DOM.ol)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>optgroup ()](#apidoc.element.react.DOM.optgroup)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>option ()](#apidoc.element.react.DOM.option)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>output ()](#apidoc.element.react.DOM.output)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>p ()](#apidoc.element.react.DOM.p)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>param ()](#apidoc.element.react.DOM.param)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>path ()](#apidoc.element.react.DOM.path)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>pattern ()](#apidoc.element.react.DOM.pattern)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>picture ()](#apidoc.element.react.DOM.picture)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>polygon ()](#apidoc.element.react.DOM.polygon)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>polyline ()](#apidoc.element.react.DOM.polyline)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>pre ()](#apidoc.element.react.DOM.pre)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>progress ()](#apidoc.element.react.DOM.progress)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>q ()](#apidoc.element.react.DOM.q)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>radialGradient ()](#apidoc.element.react.DOM.radialGradient)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>rect ()](#apidoc.element.react.DOM.rect)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>rp ()](#apidoc.element.react.DOM.rp)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>rt ()](#apidoc.element.react.DOM.rt)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>ruby ()](#apidoc.element.react.DOM.ruby)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>s ()](#apidoc.element.react.DOM.s)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>samp ()](#apidoc.element.react.DOM.samp)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>script ()](#apidoc.element.react.DOM.script)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>section ()](#apidoc.element.react.DOM.section)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>select ()](#apidoc.element.react.DOM.select)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>small ()](#apidoc.element.react.DOM.small)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>source ()](#apidoc.element.react.DOM.source)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>span ()](#apidoc.element.react.DOM.span)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>stop ()](#apidoc.element.react.DOM.stop)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>strong ()](#apidoc.element.react.DOM.strong)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>style ()](#apidoc.element.react.DOM.style)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>sub ()](#apidoc.element.react.DOM.sub)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>summary ()](#apidoc.element.react.DOM.summary)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>sup ()](#apidoc.element.react.DOM.sup)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>svg ()](#apidoc.element.react.DOM.svg)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>table ()](#apidoc.element.react.DOM.table)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>tbody ()](#apidoc.element.react.DOM.tbody)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>td ()](#apidoc.element.react.DOM.td)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>text ()](#apidoc.element.react.DOM.text)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>textarea ()](#apidoc.element.react.DOM.textarea)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>tfoot ()](#apidoc.element.react.DOM.tfoot)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>th ()](#apidoc.element.react.DOM.th)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>thead ()](#apidoc.element.react.DOM.thead)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>time ()](#apidoc.element.react.DOM.time)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>title ()](#apidoc.element.react.DOM.title)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>tr ()](#apidoc.element.react.DOM.tr)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>track ()](#apidoc.element.react.DOM.track)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>tspan ()](#apidoc.element.react.DOM.tspan)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>u ()](#apidoc.element.react.DOM.u)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>ul ()](#apidoc.element.react.DOM.ul)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>var ()](#apidoc.element.react.DOM.var)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>video ()](#apidoc.element.react.DOM.video)
1.  [function <span class="apidocSignatureSpan">react.DOM.</span>wbr ()](#apidoc.element.react.DOM.wbr)

#### [module react.KeyEscapeUtils](#apidoc.module.react.KeyEscapeUtils)
1.  [function <span class="apidocSignatureSpan">react.KeyEscapeUtils.</span>escape (key)](#apidoc.element.react.KeyEscapeUtils.escape)
1.  [function <span class="apidocSignatureSpan">react.KeyEscapeUtils.</span>unescape (key)](#apidoc.element.react.KeyEscapeUtils.unescape)

#### [module react.LinkedStateMixin](#apidoc.module.react.LinkedStateMixin)
1.  [function <span class="apidocSignatureSpan">react.LinkedStateMixin.</span>linkState (key)](#apidoc.element.react.LinkedStateMixin.linkState)

#### [module react.PooledClass](#apidoc.module.react.PooledClass)
1.  [function <span class="apidocSignatureSpan">react.PooledClass.</span>addPoolingTo (CopyConstructor, pooler)](#apidoc.element.react.PooledClass.addPoolingTo)
1.  [function <span class="apidocSignatureSpan">react.PooledClass.</span>fourArgumentPooler (a1, a2, a3, a4)](#apidoc.element.react.PooledClass.fourArgumentPooler)
1.  [function <span class="apidocSignatureSpan">react.PooledClass.</span>oneArgumentPooler (copyFieldsFrom)](#apidoc.element.react.PooledClass.oneArgumentPooler)
1.  [function <span class="apidocSignatureSpan">react.PooledClass.</span>threeArgumentPooler (a1, a2, a3)](#apidoc.element.react.PooledClass.threeArgumentPooler)
1.  [function <span class="apidocSignatureSpan">react.PooledClass.</span>twoArgumentPooler (a1, a2)](#apidoc.element.react.PooledClass.twoArgumentPooler)

#### [module react.PropTypes](#apidoc.module.react.PropTypes)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.</span>any ()](#apidoc.element.react.PropTypes.any)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.</span>array ()](#apidoc.element.react.PropTypes.array)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.</span>arrayOf (typeChecker)](#apidoc.element.react.PropTypes.arrayOf)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.</span>bool ()](#apidoc.element.react.PropTypes.bool)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.</span>element ()](#apidoc.element.react.PropTypes.element)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.</span>func ()](#apidoc.element.react.PropTypes.func)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.</span>instanceOf (expectedClass)](#apidoc.element.react.PropTypes.instanceOf)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.</span>node ()](#apidoc.element.react.PropTypes.node)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.</span>number ()](#apidoc.element.react.PropTypes.number)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.</span>object ()](#apidoc.element.react.PropTypes.object)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.</span>objectOf (typeChecker)](#apidoc.element.react.PropTypes.objectOf)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.</span>oneOf (expectedValues)](#apidoc.element.react.PropTypes.oneOf)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.</span>oneOfType (arrayOfTypeCheckers)](#apidoc.element.react.PropTypes.oneOfType)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.</span>shape (shapeTypes)](#apidoc.element.react.PropTypes.shape)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.</span>string ()](#apidoc.element.react.PropTypes.string)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.</span>symbol ()](#apidoc.element.react.PropTypes.symbol)

#### [module react.PropTypes.any](#apidoc.module.react.PropTypes.any)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.</span>any ()](#apidoc.element.react.PropTypes.any.any)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.any.</span>isRequired ()](#apidoc.element.react.PropTypes.any.isRequired)

#### [module react.PropTypes.array](#apidoc.module.react.PropTypes.array)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.</span>array ()](#apidoc.element.react.PropTypes.array.array)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.array.</span>isRequired ()](#apidoc.element.react.PropTypes.array.isRequired)

#### [module react.PropTypes.bool](#apidoc.module.react.PropTypes.bool)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.</span>bool ()](#apidoc.element.react.PropTypes.bool.bool)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.bool.</span>isRequired ()](#apidoc.element.react.PropTypes.bool.isRequired)

#### [module react.PropTypes.element](#apidoc.module.react.PropTypes.element)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.</span>element ()](#apidoc.element.react.PropTypes.element.element)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.element.</span>isRequired ()](#apidoc.element.react.PropTypes.element.isRequired)

#### [module react.PropTypes.func](#apidoc.module.react.PropTypes.func)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.</span>func ()](#apidoc.element.react.PropTypes.func.func)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.func.</span>isRequired ()](#apidoc.element.react.PropTypes.func.isRequired)

#### [module react.PropTypes.node](#apidoc.module.react.PropTypes.node)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.</span>node ()](#apidoc.element.react.PropTypes.node.node)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.node.</span>isRequired ()](#apidoc.element.react.PropTypes.node.isRequired)

#### [module react.PropTypes.number](#apidoc.module.react.PropTypes.number)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.</span>number ()](#apidoc.element.react.PropTypes.number.number)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.number.</span>isRequired ()](#apidoc.element.react.PropTypes.number.isRequired)

#### [module react.PropTypes.object](#apidoc.module.react.PropTypes.object)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.</span>object ()](#apidoc.element.react.PropTypes.object.object)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.object.</span>isRequired ()](#apidoc.element.react.PropTypes.object.isRequired)

#### [module react.PropTypes.string](#apidoc.module.react.PropTypes.string)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.</span>string ()](#apidoc.element.react.PropTypes.string.string)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.string.</span>isRequired ()](#apidoc.element.react.PropTypes.string.isRequired)

#### [module react.PropTypes.symbol](#apidoc.module.react.PropTypes.symbol)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.</span>symbol ()](#apidoc.element.react.PropTypes.symbol.symbol)
1.  [function <span class="apidocSignatureSpan">react.PropTypes.symbol.</span>isRequired ()](#apidoc.element.react.PropTypes.symbol.isRequired)

#### [module react.PureComponent](#apidoc.module.react.PureComponent)
1.  [function <span class="apidocSignatureSpan">react.</span>PureComponent (props, context, updater)](#apidoc.element.react.PureComponent.PureComponent)

#### [module react.PureComponent.prototype](#apidoc.module.react.PureComponent.prototype)
1.  boolean <span class="apidocSignatureSpan">react.PureComponent.prototype.</span>isPureReactComponent
1.  [function <span class="apidocSignatureSpan">react.PureComponent.prototype.</span>constructor (props, context, updater)](#apidoc.element.react.PureComponent.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">react.PureComponent.prototype.</span>forceUpdate (callback)](#apidoc.element.react.PureComponent.prototype.forceUpdate)
1.  [function <span class="apidocSignatureSpan">react.PureComponent.prototype.</span>setState (partialState, callback)](#apidoc.element.react.PureComponent.prototype.setState)
1.  object <span class="apidocSignatureSpan">react.PureComponent.prototype.</span>isReactComponent

#### [module react.ReactAddonsDOMDependenciesUMDShim](#apidoc.module.react.ReactAddonsDOMDependenciesUMDShim)
1.  [function <span class="apidocSignatureSpan">react.ReactAddonsDOMDependenciesUMDShim.</span>getReactDOM ()](#apidoc.element.react.ReactAddonsDOMDependenciesUMDShim.getReactDOM)
1.  [function <span class="apidocSignatureSpan">react.ReactAddonsDOMDependenciesUMDShim.</span>getReactPerf ()](#apidoc.element.react.ReactAddonsDOMDependenciesUMDShim.getReactPerf)
1.  [function <span class="apidocSignatureSpan">react.ReactAddonsDOMDependenciesUMDShim.</span>getReactTestUtils ()](#apidoc.element.react.ReactAddonsDOMDependenciesUMDShim.getReactTestUtils)

#### [module react.ReactChildren](#apidoc.module.react.ReactChildren)
1.  [function <span class="apidocSignatureSpan">react.ReactChildren.</span>count (children, context)](#apidoc.element.react.ReactChildren.count)
1.  [function <span class="apidocSignatureSpan">react.ReactChildren.</span>forEach (children, forEachFunc, forEachContext)](#apidoc.element.react.ReactChildren.forEach)
1.  [function <span class="apidocSignatureSpan">react.ReactChildren.</span>map (children, func, context)](#apidoc.element.react.ReactChildren.map)
1.  [function <span class="apidocSignatureSpan">react.ReactChildren.</span>mapIntoWithKeyPrefixInternal (children, array, prefix, func, context)](#apidoc.element.react.ReactChildren.mapIntoWithKeyPrefixInternal)
1.  [function <span class="apidocSignatureSpan">react.ReactChildren.</span>toArray (children)](#apidoc.element.react.ReactChildren.toArray)

#### [module react.ReactClass](#apidoc.module.react.ReactClass)
1.  [function <span class="apidocSignatureSpan">react.ReactClass.</span>createClass (spec)](#apidoc.element.react.ReactClass.createClass)
1.  object <span class="apidocSignatureSpan">react.ReactClass.</span>injection

#### [module react.ReactComponentTreeDevtool](#apidoc.module.react.ReactComponentTreeDevtool)
1.  [function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>getChildIDs (id)](#apidoc.element.react.ReactComponentTreeDevtool.getChildIDs)
1.  [function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>getCurrentStackAddendum (topElement)](#apidoc.element.react.ReactComponentTreeDevtool.getCurrentStackAddendum)
1.  [function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>getDisplayName (id)](#apidoc.element.react.ReactComponentTreeDevtool.getDisplayName)
1.  [function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>getElement (id)](#apidoc.element.react.ReactComponentTreeDevtool.getElement)
1.  [function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>getOwnerID (id)](#apidoc.element.react.ReactComponentTreeDevtool.getOwnerID)
1.  [function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>getParentID (id)](#apidoc.element.react.ReactComponentTreeDevtool.getParentID)
1.  [function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>getRegisteredIDs ()](#apidoc.element.react.ReactComponentTreeDevtool.getRegisteredIDs)
1.  [function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>getRootIDs ()](#apidoc.element.react.ReactComponentTreeDevtool.getRootIDs)
1.  [function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>getSource (id)](#apidoc.element.react.ReactComponentTreeDevtool.getSource)
1.  [function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>getStackAddendumByID (id)](#apidoc.element.react.ReactComponentTreeDevtool.getStackAddendumByID)
1.  [function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>getText (id)](#apidoc.element.react.ReactComponentTreeDevtool.getText)
1.  [function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>getUpdateCount (id)](#apidoc.element.react.ReactComponentTreeDevtool.getUpdateCount)
1.  [function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>isMounted (id)](#apidoc.element.react.ReactComponentTreeDevtool.isMounted)
1.  [function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>onBeforeMountComponent (id, element, parentID)](#apidoc.element.react.ReactComponentTreeDevtool.onBeforeMountComponent)
1.  [function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>onBeforeUpdateComponent (id, element)](#apidoc.element.react.ReactComponentTreeDevtool.onBeforeUpdateComponent)
1.  [function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>onMountComponent (id)](#apidoc.element.react.ReactComponentTreeDevtool.onMountComponent)
1.  [function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>onSetChildren (id, nextChildIDs)](#apidoc.element.react.ReactComponentTreeDevtool.onSetChildren)
1.  [function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>onUnmountComponent (id)](#apidoc.element.react.ReactComponentTreeDevtool.onUnmountComponent)
1.  [function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>onUpdateComponent (id)](#apidoc.element.react.ReactComponentTreeDevtool.onUpdateComponent)
1.  [function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>purgeUnmountedComponents ()](#apidoc.element.react.ReactComponentTreeDevtool.purgeUnmountedComponents)

#### [module react.ReactComponentWithPureRenderMixin](#apidoc.module.react.ReactComponentWithPureRenderMixin)
1.  [function <span class="apidocSignatureSpan">react.ReactComponentWithPureRenderMixin.</span>shouldComponentUpdate (nextProps, nextState)](#apidoc.element.react.ReactComponentWithPureRenderMixin.shouldComponentUpdate)

#### [module react.ReactElement](#apidoc.module.react.ReactElement)
1.  [function <span class="apidocSignatureSpan">react.</span>ReactElement (type, key, ref, self, source, owner, props)](#apidoc.element.react.ReactElement.ReactElement)
1.  [function <span class="apidocSignatureSpan">react.ReactElement.</span>cloneAndReplaceKey (oldElement, newKey)](#apidoc.element.react.ReactElement.cloneAndReplaceKey)
1.  [function <span class="apidocSignatureSpan">react.ReactElement.</span>cloneElement (element, config, children)](#apidoc.element.react.ReactElement.cloneElement)
1.  [function <span class="apidocSignatureSpan">react.ReactElement.</span>createElement (type, config, children)](#apidoc.element.react.ReactElement.createElement)
1.  [function <span class="apidocSignatureSpan">react.ReactElement.</span>createFactory (type)](#apidoc.element.react.ReactElement.createFactory)
1.  [function <span class="apidocSignatureSpan">react.ReactElement.</span>isValidElement (object)](#apidoc.element.react.ReactElement.isValidElement)

#### [module react.ReactElementValidator](#apidoc.module.react.ReactElementValidator)
1.  [function <span class="apidocSignatureSpan">react.ReactElementValidator.</span>cloneElement (element, props, children)](#apidoc.element.react.ReactElementValidator.cloneElement)
1.  [function <span class="apidocSignatureSpan">react.ReactElementValidator.</span>createElement (type, props, children)](#apidoc.element.react.ReactElementValidator.createElement)
1.  [function <span class="apidocSignatureSpan">react.ReactElementValidator.</span>createFactory (type)](#apidoc.element.react.ReactElementValidator.createFactory)

#### [module react.ReactFragment](#apidoc.module.react.ReactFragment)
1.  [function <span class="apidocSignatureSpan">react.ReactFragment.</span>create (object)](#apidoc.element.react.ReactFragment.create)

#### [module react.ReactNoopUpdateQueue](#apidoc.module.react.ReactNoopUpdateQueue)
1.  [function <span class="apidocSignatureSpan">react.ReactNoopUpdateQueue.</span>enqueueCallback (publicInstance, callback)](#apidoc.element.react.ReactNoopUpdateQueue.enqueueCallback)
1.  [function <span class="apidocSignatureSpan">react.ReactNoopUpdateQueue.</span>enqueueForceUpdate (publicInstance)](#apidoc.element.react.ReactNoopUpdateQueue.enqueueForceUpdate)
1.  [function <span class="apidocSignatureSpan">react.ReactNoopUpdateQueue.</span>enqueueReplaceState (publicInstance, completeState)](#apidoc.element.react.ReactNoopUpdateQueue.enqueueReplaceState)
1.  [function <span class="apidocSignatureSpan">react.ReactNoopUpdateQueue.</span>enqueueSetState (publicInstance, partialState)](#apidoc.element.react.ReactNoopUpdateQueue.enqueueSetState)
1.  [function <span class="apidocSignatureSpan">react.ReactNoopUpdateQueue.</span>isMounted (publicInstance)](#apidoc.element.react.ReactNoopUpdateQueue.isMounted)

#### [module react.ReactStateSetters](#apidoc.module.react.ReactStateSetters)
1.  [function <span class="apidocSignatureSpan">react.ReactStateSetters.</span>createStateKeySetter (component, key)](#apidoc.element.react.ReactStateSetters.createStateKeySetter)
1.  [function <span class="apidocSignatureSpan">react.ReactStateSetters.</span>createStateSetter (component, funcReturningState)](#apidoc.element.react.ReactStateSetters.createStateSetter)
1.  object <span class="apidocSignatureSpan">react.ReactStateSetters.</span>Mixin

#### [module react.ReactTransitionChildMapping](#apidoc.module.react.ReactTransitionChildMapping)
1.  [function <span class="apidocSignatureSpan">react.ReactTransitionChildMapping.</span>getChildMapping (children, selfDebugID)](#apidoc.element.react.ReactTransitionChildMapping.getChildMapping)
1.  [function <span class="apidocSignatureSpan">react.ReactTransitionChildMapping.</span>mergeChildMappings (prev, next)](#apidoc.element.react.ReactTransitionChildMapping.mergeChildMappings)

#### [module react.ReactTransitionGroup](#apidoc.module.react.ReactTransitionGroup)
1.  [function <span class="apidocSignatureSpan">react.</span>ReactTransitionGroup ()](#apidoc.element.react.ReactTransitionGroup.ReactTransitionGroup)
1.  object <span class="apidocSignatureSpan">react.ReactTransitionGroup.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react.ReactTransitionGroup.</span>propTypes
1.  string <span class="apidocSignatureSpan">react.ReactTransitionGroup.</span>displayName

#### [module react.ReactTransitionGroup.prototype](#apidoc.module.react.ReactTransitionGroup.prototype)
1.  [function <span class="apidocSignatureSpan">react.ReactTransitionGroup.prototype.</span>componentDidMount ()](#apidoc.element.react.ReactTransitionGroup.prototype.componentDidMount)
1.  [function <span class="apidocSignatureSpan">react.ReactTransitionGroup.prototype.</span>componentDidUpdate ()](#apidoc.element.react.ReactTransitionGroup.prototype.componentDidUpdate)
1.  [function <span class="apidocSignatureSpan">react.ReactTransitionGroup.prototype.</span>componentWillMount ()](#apidoc.element.react.ReactTransitionGroup.prototype.componentWillMount)
1.  [function <span class="apidocSignatureSpan">react.ReactTransitionGroup.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.react.ReactTransitionGroup.prototype.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">react.ReactTransitionGroup.prototype.</span>render ()](#apidoc.element.react.ReactTransitionGroup.prototype.render)

#### [module react.ReactUMDEntry](#apidoc.module.react.ReactUMDEntry)
1.  [function <span class="apidocSignatureSpan">react.ReactUMDEntry.</span>Component (props, context, updater)](#apidoc.element.react.ReactUMDEntry.Component)
1.  [function <span class="apidocSignatureSpan">react.ReactUMDEntry.</span>PureComponent (props, context, updater)](#apidoc.element.react.ReactUMDEntry.PureComponent)
1.  [function <span class="apidocSignatureSpan">react.ReactUMDEntry.</span>__spread ()](#apidoc.element.react.ReactUMDEntry.__spread)
1.  [function <span class="apidocSignatureSpan">react.ReactUMDEntry.</span>cloneElement (element, props, children)](#apidoc.element.react.ReactUMDEntry.cloneElement)
1.  [function <span class="apidocSignatureSpan">react.ReactUMDEntry.</span>createClass (spec)](#apidoc.element.react.ReactUMDEntry.createClass)
1.  [function <span class="apidocSignatureSpan">react.ReactUMDEntry.</span>createElement (type, props, children)](#apidoc.element.react.ReactUMDEntry.createElement)
1.  [function <span class="apidocSignatureSpan">react.ReactUMDEntry.</span>createFactory (type)](#apidoc.element.react.ReactUMDEntry.createFactory)
1.  [function <span class="apidocSignatureSpan">react.ReactUMDEntry.</span>createMixin (mixin)](#apidoc.element.react.ReactUMDEntry.createMixin)
1.  [function <span class="apidocSignatureSpan">react.ReactUMDEntry.</span>isValidElement (object)](#apidoc.element.react.ReactUMDEntry.isValidElement)
1.  object <span class="apidocSignatureSpan">react.ReactUMDEntry.</span>Children
1.  object <span class="apidocSignatureSpan">react.ReactUMDEntry.</span>DOM
1.  object <span class="apidocSignatureSpan">react.ReactUMDEntry.</span>PropTypes
1.  object <span class="apidocSignatureSpan">react.ReactUMDEntry.</span>__SECRET_INTERNALS_DO_NOT_USE_OR_YOU_WILL_BE_FIRED
1.  string <span class="apidocSignatureSpan">react.ReactUMDEntry.</span>version



# <a name="apidoc.module.react"></a>[module react](#apidoc.module.react)

#### <a name="apidoc.element.react.Component"></a>[function <span class="apidocSignatureSpan">react.</span>Component (props, context, updater)](#apidoc.element.react.Component)
- description and source-code
```javascript
function ReactComponent(props, context, updater) {
  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  // We initialize the default updater but the real one gets injected by the
  // renderer.
  this.updater = updater || ReactNoopUpdateQueue;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.any"></a>[function <span class="apidocSignatureSpan">react.</span>PropTypes.any ()](#apidoc.element.react.PropTypes.any)
- description and source-code
```javascript
PropTypes.any = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.array"></a>[function <span class="apidocSignatureSpan">react.</span>PropTypes.array ()](#apidoc.element.react.PropTypes.array)
- description and source-code
```javascript
PropTypes.array = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.bool"></a>[function <span class="apidocSignatureSpan">react.</span>PropTypes.bool ()](#apidoc.element.react.PropTypes.bool)
- description and source-code
```javascript
PropTypes.bool = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.element"></a>[function <span class="apidocSignatureSpan">react.</span>PropTypes.element ()](#apidoc.element.react.PropTypes.element)
- description and source-code
```javascript
PropTypes.element = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.func"></a>[function <span class="apidocSignatureSpan">react.</span>PropTypes.func ()](#apidoc.element.react.PropTypes.func)
- description and source-code
```javascript
PropTypes.func = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.node"></a>[function <span class="apidocSignatureSpan">react.</span>PropTypes.node ()](#apidoc.element.react.PropTypes.node)
- description and source-code
```javascript
PropTypes.node = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.number"></a>[function <span class="apidocSignatureSpan">react.</span>PropTypes.number ()](#apidoc.element.react.PropTypes.number)
- description and source-code
```javascript
PropTypes.number = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.object"></a>[function <span class="apidocSignatureSpan">react.</span>PropTypes.object ()](#apidoc.element.react.PropTypes.object)
- description and source-code
```javascript
PropTypes.object = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.string"></a>[function <span class="apidocSignatureSpan">react.</span>PropTypes.string ()](#apidoc.element.react.PropTypes.string)
- description and source-code
```javascript
PropTypes.string = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.symbol"></a>[function <span class="apidocSignatureSpan">react.</span>PropTypes.symbol ()](#apidoc.element.react.PropTypes.symbol)
- description and source-code
```javascript
PropTypes.symbol = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PureComponent"></a>[function <span class="apidocSignatureSpan">react.</span>PureComponent (props, context, updater)](#apidoc.element.react.PureComponent)
- description and source-code
```javascript
function ReactPureComponent(props, context, updater) {
  // Duplicated from ReactComponent.
  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  // We initialize the default updater but the real one gets injected by the
  // renderer.
  this.updater = updater || ReactNoopUpdateQueue;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactElement"></a>[function <span class="apidocSignatureSpan">react.</span>ReactElement (type, key, ref, self, source, owner, props)](#apidoc.element.react.ReactElement)
- description and source-code
```javascript
ReactElement = function (type, key, ref, self, source, owner, props) {
  var element = {
    // This tag allow us to uniquely identify this as a React Element
    $$typeof: REACT_ELEMENT_TYPE,

    // Built-in properties that belong on the element
    type: type,
    key: key,
    ref: ref,
    props: props,

    // Record the component responsible for creating this element.
    _owner: owner
  };

  if (process.env.NODE_ENV !== 'production') {
    // The validation flag is currently mutative. We put it on
    // an external backing store so that we can freeze the whole object.
    // This can be replaced with a WeakMap once they are implemented in
    // commonly used development environments.
    element._store = {};

    // To make comparing ReactElements easier for testing purposes, we make
    // the validation flag non-enumerable (where possible, which should
    // include every environment we run tests in), so the test framework
    // ignores it.
    if (canDefineProperty) {
      Object.defineProperty(element._store, 'validated', {
        configurable: false,
        enumerable: false,
        writable: true,
        value: false
      });
      // self and source are DEV only properties.
      Object.defineProperty(element, '_self', {
        configurable: false,
        enumerable: false,
        writable: false,
        value: self
      });
      // Two elements created in two different places should be considered
      // equal for testing purposes and therefore we hide it from enumeration.
      Object.defineProperty(element, '_source', {
        configurable: false,
        enumerable: false,
        writable: false,
        value: source
      });
    } else {
      element._store.validated = false;
      element._self = self;
      element._source = source;
    }
    if (Object.freeze) {
      Object.freeze(element.props);
      Object.freeze(element);
    }
  }

  return element;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactTransitionGroup"></a>[function <span class="apidocSignatureSpan">react.</span>ReactTransitionGroup ()](#apidoc.element.react.ReactTransitionGroup)
- description and source-code
```javascript
function ReactTransitionGroup() {
  var _temp, _this, _ret;

  _classCallCheck(this, ReactTransitionGroup);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = _possibleConstructorReturn(this, _React$Component.call.apply(_React$Component, [this].concat(args
))), _this), _this.state = {
    // TODO: can we get useful debug information to show at this point?
    children: ReactTransitionChildMapping.getChildMapping(_this.props.children)
  }, _this.performAppear = function (key) {
    _this.currentlyTransitioningKeys[key] = true;

    var component = _this.refs[key];

    if (component.componentWillAppear) {
      component.componentWillAppear(_this._handleDoneAppearing.bind(_this, key));
    } else {
      _this._handleDoneAppearing(key);
    }
  }, _this._handleDoneAppearing = function (key) {
    var component = _this.refs[key];
    if (component.componentDidAppear) {
      component.componentDidAppear();
    }

    delete _this.currentlyTransitioningKeys[key];

    var currentChildMapping = ReactTransitionChildMapping.getChildMapping(_this.props.children);

    if (!currentChildMapping || !currentChildMapping.hasOwnProperty(key)) {
      // This was removed before it had fully appeared. Remove it.
      _this.performLeave(key);
    }
  }, _this.performEnter = function (key) {
    _this.currentlyTransitioningKeys[key] = true;

    var component = _this.refs[key];

    if (component.componentWillEnter) {
      component.componentWillEnter(_this._handleDoneEntering.bind(_this, key));
    } else {
      _this._handleDoneEntering(key);
    }
  }, _this._handleDoneEntering = function (key) {
    var component = _this.refs[key];
    if (component.componentDidEnter) {
      component.componentDidEnter();
    }

    delete _this.currentlyTransitioningKeys[key];

    var currentChildMapping = ReactTransitionChildMapping.getChildMapping(_this.props.children);

    if (!currentChildMapping || !currentChildMapping.hasOwnProperty(key)) {
      // This was removed before it had fully entered. Remove it.
      _this.performLeave(key);
    }
  }, _this.performLeave = function (key) {
    _this.currentlyTransitioningKeys[key] = true;

    var component = _this.refs[key];
    if (component.componentWillLeave) {
      component.componentWillLeave(_this._handleDoneLeaving.bind(_this, key));
    } else {
      // Note that this is somewhat dangerous b/c it calls setState()
      // again, effectively mutating the component before all the work
      // is done.
      _this._handleDoneLeaving(key);
    }
  }, _this._handleDoneLeaving = function (key) {
    var component = _this.refs[key];

    if (component.componentDidLeave) {
      component.componentDidLeave();
    }

    delete _this.currentlyTransitioningKeys[key];

    var currentChildMapping = ReactTransitionChildMapping.getChildMapping(_this.props.children);

    if (currentChildMapping && currentChildMapping.hasOwnProperty(key)) {
      // This entered again before it fully left. Add it again.
      _this.performEnter(key);
    } else {
      _this.setState(function (state) {
        var newChildren = _assign({}, state.children);
        delete newChildren[key];
        return { children: newChildren };
      });
    }
  }, _temp), _possibleConstructorReturn(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.__spread"></a>[function <span class="apidocSignatureSpan">react.</span>__spread ()](#apidoc.element.react.__spread)
- description and source-code
```javascript
__spread = function () {
  process.env.NODE_ENV !== 'production' ? warning(warned, 'React.__spread is deprecated and should not be used. Use ' + 'Object.
assign directly or another helper function with similar ' + 'semantics. You may be seeing this warning due to your compiler. ' + '
See https://fb.me/react-spread-deprecation for more details.') : void 0;
  warned = true;
  return _assign.apply(null, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.cloneElement"></a>[function <span class="apidocSignatureSpan">react.</span>cloneElement (element, props, children)](#apidoc.element.react.cloneElement)
- description and source-code
```javascript
cloneElement = function (element, props, children) {
  var newElement = ReactElement.cloneElement.apply(this, arguments);
  for (var i = 2; i < arguments.length; i++) {
    validateChildKeys(arguments[i], newElement.type);
  }
  validatePropTypes(newElement);
  return newElement;
}
```
- example usage
```shell
...
  var child = this.state.children[key];
  if (child) {
    // You may need to apply reactive updates to a child as it is leaving.
    // The normal React way to do it won't work since the child will have
    // already been removed. In case you need this behavior you can provide
    // a childFactory function to wrap every child, even the ones that are
    // leaving.
    childrenToRender.push(React.cloneElement(this.props.childFactory(child), { ref: key, key: key }));
  }
}

// Do not forward ReactTransitionGroup props to primitive DOM nodes
var props = _assign({}, this.props);
delete props.transitionLeave;
delete props.transitionName;
...
```

#### <a name="apidoc.element.react.createClass"></a>[function <span class="apidocSignatureSpan">react.</span>createClass (spec)](#apidoc.element.react.createClass)
- description and source-code
```javascript
createClass = function (spec) {
  // To keep our warnings more understandable, we'll use a little hack here to
  // ensure that Constructor.name !== 'Constructor'. This makes sure we don't
  // unnecessarily identify a class without displayName as 'Constructor'.
  var Constructor = identity(function (props, context, updater) {
    // This constructor gets overridden by mocks. The argument is used
    // by mocks to assert on what gets mounted.

    if (process.env.NODE_ENV !== 'production') {
      process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : void 0;
    }

    // Wire up auto-binding
    if (this.__reactAutoBindPairs.length) {
      bindAutoBindMethods(this);
    }

    this.props = props;
    this.context = context;
    this.refs = emptyObject;
    this.updater = updater || ReactNoopUpdateQueue;

    this.state = null;

    // ReactClasses doesn't have constructors. Instead, they use the
    // getInitialState and componentWillMount methods for initialization.

    var initialState = this.getInitialState ? this.getInitialState() : null;
    if (process.env.NODE_ENV !== 'production') {
      // We allow auto-mocks to proceed as if they're returning null.
      if (initialState === undefined && this.getInitialState._isMockFunction) {
        // This is probably bad practice. Consider warning here and
        // deprecating this convenience.
        initialState = null;
      }
    }
    !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false
, '%s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : _prodInvariant('
82', Constructor.displayName || 'ReactCompositeComponent') : void 0;

    this.state = initialState;
  });
  Constructor.prototype = new ReactClassComponent();
  Constructor.prototype.constructor = Constructor;
  Constructor.prototype.__reactAutoBindPairs = [];

  injectedMixins.forEach(mixSpecIntoComponent.bind(null, Constructor));

  mixSpecIntoComponent(Constructor, spec);

  // Initialize the defaultProps property after all mixins have been merged.
  if (Constructor.getDefaultProps) {
    Constructor.defaultProps = Constructor.getDefaultProps();
  }

  if (process.env.NODE_ENV !== 'production') {
    // This is a tag to indicate that the use of these method names is ok,
    // since it's used with createClass. If it's not, then it's likely a
    // mistake so we'll warn you to use the static property, property
    // initializer or constructor respectively.
    if (Constructor.getDefaultProps) {
      Constructor.getDefaultProps.isReactClassApproved = {};
    }
    if (Constructor.prototype.getInitialState) {
      Constructor.prototype.getInitialState.isReactClassApproved = {};
    }
  }

  !Constructor.prototype.render ? process.env.NODE_ENV !== 'production' ? invariant(false, 'createClass(...): Class specification
 must implement a 'render' method.') : _prodInvariant('83') : void 0;

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(!Constructor.prototype.componentShouldUpdate, '%s has a method called ' + 'componentShouldUpdate
(). Did you mean shouldComponentUpdate()? ' + 'The name is phrased as a question because the function is ' + 'expected to return
 a value.', spec.displayName || 'A component') : void 0;
    process.env.NODE_ENV !== 'production' ? warning(!Constructor.prototype.componentWillRecieveProps, '%s has a method called ' + '
componentWillRecieveProps(). Did you mean componentWillReceiveProps()?', spec.displayName || 'A component') : void 0;
  }

  // Reduce time spent doing lookups by setting these on the prototype.
  for (var methodName in ReactClassInterface) {
    if (!Constructor.prototype[methodName]) {
      Constructor.prototype[methodName] = null;
    }
  }

  return Constructor;
}
```
- example usage
```shell
...
* Composite components are higher-level components that compose other composite
* or host components.
*
* To create a new type of 'ReactClass', pass a specification of
* your new class to 'React.createClass'. The only requirement of your class
* specification is that you implement a 'render' method.
*
*   var MyComponent = React.createClass({
*     render: function() {
*       return <div>Hello World</div>;
*     }
*   });
*
* The class specification supports a specific protocol of methods that have
* special meaning (e.g. 'render'). See 'ReactClassInterface' for
...
```

#### <a name="apidoc.element.react.createElement"></a>[function <span class="apidocSignatureSpan">react.</span>createElement (type, props, children)](#apidoc.element.react.createElement)
- description and source-code
```javascript
createElement = function (type, props, children) {
  var validType = typeof type === 'string' || typeof type === 'function';
  // We warn in this case but don't throw. We expect the element creation to
  // succeed and there will likely be errors in render.
  if (!validType) {
    if (typeof type !== 'function' && typeof type !== 'string') {
      var info = '';
      if (type === undefined || typeof type === 'object' && type !== null && Object.keys(type).length === 0) {
        info += ' You likely forgot to export your component from the file ' + 'it\'s defined in.';
      }
      info += getDeclarationErrorAddendum();
      process.env.NODE_ENV !== 'production' ? warning(false, 'React.createElement: type is invalid -- expected a string (for ' + '
built-in components) or a class/function (for composite ' + 'components) but got: %s.%s', type == null ? type : typeof type, info
) : void 0;
    }
  }

  var element = ReactElement.createElement.apply(this, arguments);

  // The result can be nullish if a mock or a custom function is used.
  // TODO: Drop this when these are no longer allowed as the type argument.
  if (element == null) {
    return element;
  }

  // Skip key warning if the type isn't valid since our key validation logic
  // doesn't expect a non-string/function type and can throw confusing errors.
  // We don't want exception behavior to differ between dev and prod.
  // (Rendering will throw with a helpful message and as soon as the type is
  // fixed, the key warnings will appear.)
  if (validType) {
    for (var i = 2; i < arguments.length; i++) {
      validateChildKeys(arguments[i], type);
    }
  }

  validatePropTypes(element);

  return element;
}
```
- example usage
```shell
...
    delete props.transitionEnter;
    delete props.childFactory;
    delete props.transitionLeaveTimeout;
    delete props.transitionEnterTimeout;
    delete props.transitionAppearTimeout;
    delete props.component;

    return React.createElement(this.props.component, props, childrenToRender);
  };

  return ReactTransitionGroup;
}(React.Component);

ReactTransitionGroup.displayName = 'ReactTransitionGroup';
ReactTransitionGroup.propTypes = {
...
```

#### <a name="apidoc.element.react.createFactory"></a>[function <span class="apidocSignatureSpan">react.</span>createFactory (type)](#apidoc.element.react.createFactory)
- description and source-code
```javascript
createFactory = function (type) {
  var validatedFactory = ReactElementValidator.createElement.bind(null, type);
  // Legacy hook TODO: Warn if this is accessed
  validatedFactory.type = type;

  if (process.env.NODE_ENV !== 'production') {
    if (canDefineProperty) {
      Object.defineProperty(validatedFactory, 'type', {
        enumerable: false,
        get: function () {
          process.env.NODE_ENV !== 'production' ? warning(false, 'Factory.type is deprecated. Access the class directly ' + 'before
 passing it to createFactory.') : void 0;
          Object.defineProperty(this, 'type', {
            value: type
          });
          return type;
        }
      });
    }
  }

  return validatedFactory;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.createMixin"></a>[function <span class="apidocSignatureSpan">react.</span>createMixin (mixin)](#apidoc.element.react.createMixin)
- description and source-code
```javascript
createMixin = function (mixin) {
  // Currently a noop. Will be used to validate and trace mixins.
  return mixin;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.isValidElement"></a>[function <span class="apidocSignatureSpan">react.</span>isValidElement (object)](#apidoc.element.react.isValidElement)
- description and source-code
```javascript
isValidElement = function (object) {
  return typeof object === 'object' && object !== null && object.$$typeof === REACT_ELEMENT_TYPE;
}
```
- example usage
```shell
...
    context = bookKeeping.context;


var mappedChild = func.call(context, child, bookKeeping.count++);
if (Array.isArray(mappedChild)) {
  mapIntoWithKeyPrefixInternal(mappedChild, result, childKey, emptyFunction.thatReturnsArgument);
} else if (mappedChild != null) {
  if (ReactElement.isValidElement(mappedChild)) {
    mappedChild = ReactElement.cloneAndReplaceKey(mappedChild,
    // Keep both the (mapped) and old keys if they differ, just as
    // traverseAllChildren used to do for objects as children
    keyPrefix + (mappedChild.key && (!child || child.key !== mappedChild.key) ? escapeUserProvidedKey(mappedChild.key) + '/' : '') +
childKey);
  }
  result.push(mappedChild);
}
...
```



# <a name="apidoc.module.react.Children"></a>[module react.Children](#apidoc.module.react.Children)

#### <a name="apidoc.element.react.Children.count"></a>[function <span class="apidocSignatureSpan">react.Children.</span>count (children, context)](#apidoc.element.react.Children.count)
- description and source-code
```javascript
function countChildren(children, context) {
  return traverseAllChildren(children, forEachSingleChildDummy, null);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.Children.forEach"></a>[function <span class="apidocSignatureSpan">react.Children.</span>forEach (children, forEachFunc, forEachContext)](#apidoc.element.react.Children.forEach)
- description and source-code
```javascript
function forEachChildren(children, forEachFunc, forEachContext) {
  if (children == null) {
    return children;
  }
  var traverseContext = ForEachBookKeeping.getPooled(forEachFunc, forEachContext);
  traverseAllChildren(children, forEachSingleChild, traverseContext);
  ForEachBookKeeping.release(traverseContext);
}
```
- example usage
```shell
...

  this.state = initialState;
});
Constructor.prototype = new ReactClassComponent();
Constructor.prototype.constructor = Constructor;
Constructor.prototype.__reactAutoBindPairs = [];

injectedMixins.forEach(mixSpecIntoComponent.bind(null, Constructor));

mixSpecIntoComponent(Constructor, spec);

// Initialize the defaultProps property after all mixins have been merged.
if (Constructor.getDefaultProps) {
  Constructor.defaultProps = Constructor.getDefaultProps();
}
...
```

#### <a name="apidoc.element.react.Children.map"></a>[function <span class="apidocSignatureSpan">react.Children.</span>map (children, func, context)](#apidoc.element.react.Children.map)
- description and source-code
```javascript
function mapChildren(children, func, context) {
  if (children == null) {
    return children;
  }
  var result = [];
  mapIntoWithKeyPrefixInternal(children, result, null, func, context);
  return result;
}
```
- example usage
```shell
...
  return itemByKey[key];
};
removeItem = function (id) {
  var key = getKeyFromID(id);
  delete itemByKey[key];
};
getItemIDs = function () {
  return Object.keys(itemByKey).map(getIDFromKey);
};

addRoot = function (id) {
  var key = getKeyFromID(id);
  rootByKey[key] = true;
};
removeRoot = function (id) {
...
```

#### <a name="apidoc.element.react.Children.only"></a>[function <span class="apidocSignatureSpan">react.Children.</span>only (children)](#apidoc.element.react.Children.only)
- description and source-code
```javascript
function onlyChild(children) {
  !ReactElement.isValidElement(children) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'React.Children.only expected
 to receive a single React element child.') : _prodInvariant('143') : void 0;
  return children;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.Children.toArray"></a>[function <span class="apidocSignatureSpan">react.Children.</span>toArray (children)](#apidoc.element.react.Children.toArray)
- description and source-code
```javascript
function toArray(children) {
  var result = [];
  mapIntoWithKeyPrefixInternal(children, result, null, emptyFunction.thatReturnsArgument);
  return result;
}
```
- example usage
```shell
...
 * @return {object} mirrored array with mapped children
 */
function sliceChildren(children, start, end) {
  if (children == null) {
    return children;
  }

  var array = ReactChildren.toArray(children);
  return array.slice(start, end);
}

module.exports = sliceChildren;
...
```



# <a name="apidoc.module.react.Component"></a>[module react.Component](#apidoc.module.react.Component)

#### <a name="apidoc.element.react.Component.Component"></a>[function <span class="apidocSignatureSpan">react.</span>Component (props, context, updater)](#apidoc.element.react.Component.Component)
- description and source-code
```javascript
function ReactComponent(props, context, updater) {
  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  // We initialize the default updater but the real one gets injected by the
  // renderer.
  this.updater = updater || ReactNoopUpdateQueue;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react.Component.prototype"></a>[module react.Component.prototype](#apidoc.module.react.Component.prototype)

#### <a name="apidoc.element.react.Component.prototype.forceUpdate"></a>[function <span class="apidocSignatureSpan">react.Component.prototype.</span>forceUpdate (callback)](#apidoc.element.react.Component.prototype.forceUpdate)
- description and source-code
```javascript
forceUpdate = function (callback) {
  this.updater.enqueueForceUpdate(this);
  if (callback) {
    this.updater.enqueueCallback(this, callback, 'forceUpdate');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.Component.prototype.setState"></a>[function <span class="apidocSignatureSpan">react.Component.prototype.</span>setState (partialState, callback)](#apidoc.element.react.Component.prototype.setState)
- description and source-code
```javascript
setState = function (partialState, callback) {
  !(typeof partialState === 'object' || typeof partialState === 'function' || partialState == null) ? process.env.NODE_ENV !== '
production' ? invariant(false, 'setState(...): takes an object of state variables to update or a function which returns an object
 of state variables.') : _prodInvariant('85') : void 0;
  this.updater.enqueueSetState(this, partialState);
  if (callback) {
    this.updater.enqueueCallback(this, callback, 'setState');
  }
}
```
- example usage
```shell
...
  /**
* Invoked before the component receives new props.
*
* Use this as an opportunity to react to a prop transition by updating the
* state using 'this.setState'. Current props are accessed via 'this.props'.
*
*   componentWillReceiveProps: function(nextProps, nextContext) {
*     this.setState({
*       likesIncreasing: nextProps.likeCount > this.props.likeCount
*     });
*   }
*
* NOTE: There is no equivalent 'componentWillReceiveState'. An incoming prop
* transition may cause a state change, but the opposite is not true. If you
* need it, you are probably looking for 'componentWillUpdate'.
...
```



# <a name="apidoc.module.react.DOM"></a>[module react.DOM](#apidoc.module.react.DOM)

#### <a name="apidoc.element.react.DOM.a"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>a ()](#apidoc.element.react.DOM.a)
- description and source-code
```javascript
a = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.abbr"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>abbr ()](#apidoc.element.react.DOM.abbr)
- description and source-code
```javascript
abbr = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.address"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>address ()](#apidoc.element.react.DOM.address)
- description and source-code
```javascript
address = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.area"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>area ()](#apidoc.element.react.DOM.area)
- description and source-code
```javascript
area = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.article"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>article ()](#apidoc.element.react.DOM.article)
- description and source-code
```javascript
article = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.aside"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>aside ()](#apidoc.element.react.DOM.aside)
- description and source-code
```javascript
aside = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.audio"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>audio ()](#apidoc.element.react.DOM.audio)
- description and source-code
```javascript
audio = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.b"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>b ()](#apidoc.element.react.DOM.b)
- description and source-code
```javascript
b = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.base"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>base ()](#apidoc.element.react.DOM.base)
- description and source-code
```javascript
base = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.bdi"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>bdi ()](#apidoc.element.react.DOM.bdi)
- description and source-code
```javascript
bdi = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.bdo"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>bdo ()](#apidoc.element.react.DOM.bdo)
- description and source-code
```javascript
bdo = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.big"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>big ()](#apidoc.element.react.DOM.big)
- description and source-code
```javascript
big = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.blockquote"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>blockquote ()](#apidoc.element.react.DOM.blockquote)
- description and source-code
```javascript
blockquote = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.body"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>body ()](#apidoc.element.react.DOM.body)
- description and source-code
```javascript
body = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.br"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>br ()](#apidoc.element.react.DOM.br)
- description and source-code
```javascript
br = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.button"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>button ()](#apidoc.element.react.DOM.button)
- description and source-code
```javascript
button = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.canvas"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>canvas ()](#apidoc.element.react.DOM.canvas)
- description and source-code
```javascript
canvas = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.caption"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>caption ()](#apidoc.element.react.DOM.caption)
- description and source-code
```javascript
caption = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.circle"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>circle ()](#apidoc.element.react.DOM.circle)
- description and source-code
```javascript
circle = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.cite"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>cite ()](#apidoc.element.react.DOM.cite)
- description and source-code
```javascript
cite = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.clipPath"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>clipPath ()](#apidoc.element.react.DOM.clipPath)
- description and source-code
```javascript
clipPath = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.code"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>code ()](#apidoc.element.react.DOM.code)
- description and source-code
```javascript
code = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.col"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>col ()](#apidoc.element.react.DOM.col)
- description and source-code
```javascript
col = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.colgroup"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>colgroup ()](#apidoc.element.react.DOM.colgroup)
- description and source-code
```javascript
colgroup = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.data"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>data ()](#apidoc.element.react.DOM.data)
- description and source-code
```javascript
data = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.datalist"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>datalist ()](#apidoc.element.react.DOM.datalist)
- description and source-code
```javascript
datalist = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.dd"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>dd ()](#apidoc.element.react.DOM.dd)
- description and source-code
```javascript
dd = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.defs"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>defs ()](#apidoc.element.react.DOM.defs)
- description and source-code
```javascript
defs = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.del"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>del ()](#apidoc.element.react.DOM.del)
- description and source-code
```javascript
del = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.details"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>details ()](#apidoc.element.react.DOM.details)
- description and source-code
```javascript
details = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.dfn"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>dfn ()](#apidoc.element.react.DOM.dfn)
- description and source-code
```javascript
dfn = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.dialog"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>dialog ()](#apidoc.element.react.DOM.dialog)
- description and source-code
```javascript
dialog = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.div"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>div ()](#apidoc.element.react.DOM.div)
- description and source-code
```javascript
div = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.dl"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>dl ()](#apidoc.element.react.DOM.dl)
- description and source-code
```javascript
dl = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.dt"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>dt ()](#apidoc.element.react.DOM.dt)
- description and source-code
```javascript
dt = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.ellipse"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>ellipse ()](#apidoc.element.react.DOM.ellipse)
- description and source-code
```javascript
ellipse = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.em"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>em ()](#apidoc.element.react.DOM.em)
- description and source-code
```javascript
em = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.embed"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>embed ()](#apidoc.element.react.DOM.embed)
- description and source-code
```javascript
embed = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.fieldset"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>fieldset ()](#apidoc.element.react.DOM.fieldset)
- description and source-code
```javascript
fieldset = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.figcaption"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>figcaption ()](#apidoc.element.react.DOM.figcaption)
- description and source-code
```javascript
figcaption = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.figure"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>figure ()](#apidoc.element.react.DOM.figure)
- description and source-code
```javascript
figure = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.footer"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>footer ()](#apidoc.element.react.DOM.footer)
- description and source-code
```javascript
footer = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.form"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>form ()](#apidoc.element.react.DOM.form)
- description and source-code
```javascript
form = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.g"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>g ()](#apidoc.element.react.DOM.g)
- description and source-code
```javascript
g = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.h1"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>h1 ()](#apidoc.element.react.DOM.h1)
- description and source-code
```javascript
h1 = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.h2"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>h2 ()](#apidoc.element.react.DOM.h2)
- description and source-code
```javascript
h2 = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.h3"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>h3 ()](#apidoc.element.react.DOM.h3)
- description and source-code
```javascript
h3 = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.h4"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>h4 ()](#apidoc.element.react.DOM.h4)
- description and source-code
```javascript
h4 = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.h5"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>h5 ()](#apidoc.element.react.DOM.h5)
- description and source-code
```javascript
h5 = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.h6"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>h6 ()](#apidoc.element.react.DOM.h6)
- description and source-code
```javascript
h6 = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.head"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>head ()](#apidoc.element.react.DOM.head)
- description and source-code
```javascript
head = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.header"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>header ()](#apidoc.element.react.DOM.header)
- description and source-code
```javascript
header = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.hgroup"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>hgroup ()](#apidoc.element.react.DOM.hgroup)
- description and source-code
```javascript
hgroup = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.hr"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>hr ()](#apidoc.element.react.DOM.hr)
- description and source-code
```javascript
hr = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.html"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>html ()](#apidoc.element.react.DOM.html)
- description and source-code
```javascript
html = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.i"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>i ()](#apidoc.element.react.DOM.i)
- description and source-code
```javascript
i = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.iframe"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>iframe ()](#apidoc.element.react.DOM.iframe)
- description and source-code
```javascript
iframe = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.image"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>image ()](#apidoc.element.react.DOM.image)
- description and source-code
```javascript
image = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.img"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>img ()](#apidoc.element.react.DOM.img)
- description and source-code
```javascript
img = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.input"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>input ()](#apidoc.element.react.DOM.input)
- description and source-code
```javascript
input = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.ins"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>ins ()](#apidoc.element.react.DOM.ins)
- description and source-code
```javascript
ins = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.kbd"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>kbd ()](#apidoc.element.react.DOM.kbd)
- description and source-code
```javascript
kbd = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.keygen"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>keygen ()](#apidoc.element.react.DOM.keygen)
- description and source-code
```javascript
keygen = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.label"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>label ()](#apidoc.element.react.DOM.label)
- description and source-code
```javascript
label = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.legend"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>legend ()](#apidoc.element.react.DOM.legend)
- description and source-code
```javascript
legend = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.li"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>li ()](#apidoc.element.react.DOM.li)
- description and source-code
```javascript
li = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.line"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>line ()](#apidoc.element.react.DOM.line)
- description and source-code
```javascript
line = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.linearGradient"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>linearGradient ()](#apidoc.element.react.DOM.linearGradient)
- description and source-code
```javascript
linearGradient = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.link"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>link ()](#apidoc.element.react.DOM.link)
- description and source-code
```javascript
link = function () { [native code] }
```
- example usage
```shell
...
}

/**
 * Creates a PropType that enforces the ReactLink API and optionally checks the
 * type of the value being passed inside the link. Example:
 *
 * MyComponent.propTypes = {
 *   tabIndexLink: ReactLink.PropTypes.link(React.PropTypes.number)
 * }
 */
function createLinkTypeChecker(linkType) {
var shapes = {
  value: linkType === undefined ? React.PropTypes.any.isRequired : linkType.isRequired,
  requestChange: React.PropTypes.func.isRequired
};
...
```

#### <a name="apidoc.element.react.DOM.main"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>main ()](#apidoc.element.react.DOM.main)
- description and source-code
```javascript
main = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.map"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>map ()](#apidoc.element.react.DOM.map)
- description and source-code
```javascript
map = function () { [native code] }
```
- example usage
```shell
...
  return itemByKey[key];
};
removeItem = function (id) {
  var key = getKeyFromID(id);
  delete itemByKey[key];
};
getItemIDs = function () {
  return Object.keys(itemByKey).map(getIDFromKey);
};

addRoot = function (id) {
  var key = getKeyFromID(id);
  rootByKey[key] = true;
};
removeRoot = function (id) {
...
```

#### <a name="apidoc.element.react.DOM.mark"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>mark ()](#apidoc.element.react.DOM.mark)
- description and source-code
```javascript
mark = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.mask"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>mask ()](#apidoc.element.react.DOM.mask)
- description and source-code
```javascript
mask = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.menu"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>menu ()](#apidoc.element.react.DOM.menu)
- description and source-code
```javascript
menu = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.menuitem"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>menuitem ()](#apidoc.element.react.DOM.menuitem)
- description and source-code
```javascript
menuitem = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.meta"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>meta ()](#apidoc.element.react.DOM.meta)
- description and source-code
```javascript
meta = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.meter"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>meter ()](#apidoc.element.react.DOM.meter)
- description and source-code
```javascript
meter = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.nav"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>nav ()](#apidoc.element.react.DOM.nav)
- description and source-code
```javascript
nav = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.noscript"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>noscript ()](#apidoc.element.react.DOM.noscript)
- description and source-code
```javascript
noscript = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.object"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>object ()](#apidoc.element.react.DOM.object)
- description and source-code
```javascript
object = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.ol"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>ol ()](#apidoc.element.react.DOM.ol)
- description and source-code
```javascript
ol = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.optgroup"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>optgroup ()](#apidoc.element.react.DOM.optgroup)
- description and source-code
```javascript
optgroup = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.option"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>option ()](#apidoc.element.react.DOM.option)
- description and source-code
```javascript
option = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.output"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>output ()](#apidoc.element.react.DOM.output)
- description and source-code
```javascript
output = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.p"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>p ()](#apidoc.element.react.DOM.p)
- description and source-code
```javascript
p = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.param"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>param ()](#apidoc.element.react.DOM.param)
- description and source-code
```javascript
param = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.path"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>path ()](#apidoc.element.react.DOM.path)
- description and source-code
```javascript
path = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.pattern"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>pattern ()](#apidoc.element.react.DOM.pattern)
- description and source-code
```javascript
pattern = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.picture"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>picture ()](#apidoc.element.react.DOM.picture)
- description and source-code
```javascript
picture = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.polygon"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>polygon ()](#apidoc.element.react.DOM.polygon)
- description and source-code
```javascript
polygon = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.polyline"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>polyline ()](#apidoc.element.react.DOM.polyline)
- description and source-code
```javascript
polyline = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.pre"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>pre ()](#apidoc.element.react.DOM.pre)
- description and source-code
```javascript
pre = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.progress"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>progress ()](#apidoc.element.react.DOM.progress)
- description and source-code
```javascript
progress = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.q"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>q ()](#apidoc.element.react.DOM.q)
- description and source-code
```javascript
q = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.radialGradient"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>radialGradient ()](#apidoc.element.react.DOM.radialGradient)
- description and source-code
```javascript
radialGradient = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.rect"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>rect ()](#apidoc.element.react.DOM.rect)
- description and source-code
```javascript
rect = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.rp"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>rp ()](#apidoc.element.react.DOM.rp)
- description and source-code
```javascript
rp = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.rt"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>rt ()](#apidoc.element.react.DOM.rt)
- description and source-code
```javascript
rt = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.ruby"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>ruby ()](#apidoc.element.react.DOM.ruby)
- description and source-code
```javascript
ruby = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.s"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>s ()](#apidoc.element.react.DOM.s)
- description and source-code
```javascript
s = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.samp"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>samp ()](#apidoc.element.react.DOM.samp)
- description and source-code
```javascript
samp = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.script"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>script ()](#apidoc.element.react.DOM.script)
- description and source-code
```javascript
script = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.section"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>section ()](#apidoc.element.react.DOM.section)
- description and source-code
```javascript
section = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.select"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>select ()](#apidoc.element.react.DOM.select)
- description and source-code
```javascript
select = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.small"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>small ()](#apidoc.element.react.DOM.small)
- description and source-code
```javascript
small = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.source"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>source ()](#apidoc.element.react.DOM.source)
- description and source-code
```javascript
source = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.span"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>span ()](#apidoc.element.react.DOM.span)
- description and source-code
```javascript
span = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.stop"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>stop ()](#apidoc.element.react.DOM.stop)
- description and source-code
```javascript
stop = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.strong"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>strong ()](#apidoc.element.react.DOM.strong)
- description and source-code
```javascript
strong = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.style"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>style ()](#apidoc.element.react.DOM.style)
- description and source-code
```javascript
style = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.sub"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>sub ()](#apidoc.element.react.DOM.sub)
- description and source-code
```javascript
sub = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.summary"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>summary ()](#apidoc.element.react.DOM.summary)
- description and source-code
```javascript
summary = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.sup"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>sup ()](#apidoc.element.react.DOM.sup)
- description and source-code
```javascript
sup = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.svg"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>svg ()](#apidoc.element.react.DOM.svg)
- description and source-code
```javascript
svg = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.table"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>table ()](#apidoc.element.react.DOM.table)
- description and source-code
```javascript
table = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.tbody"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>tbody ()](#apidoc.element.react.DOM.tbody)
- description and source-code
```javascript
tbody = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.td"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>td ()](#apidoc.element.react.DOM.td)
- description and source-code
```javascript
td = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.text"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>text ()](#apidoc.element.react.DOM.text)
- description and source-code
```javascript
text = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.textarea"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>textarea ()](#apidoc.element.react.DOM.textarea)
- description and source-code
```javascript
textarea = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.tfoot"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>tfoot ()](#apidoc.element.react.DOM.tfoot)
- description and source-code
```javascript
tfoot = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.th"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>th ()](#apidoc.element.react.DOM.th)
- description and source-code
```javascript
th = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.thead"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>thead ()](#apidoc.element.react.DOM.thead)
- description and source-code
```javascript
thead = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.time"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>time ()](#apidoc.element.react.DOM.time)
- description and source-code
```javascript
time = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.title"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>title ()](#apidoc.element.react.DOM.title)
- description and source-code
```javascript
title = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.tr"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>tr ()](#apidoc.element.react.DOM.tr)
- description and source-code
```javascript
tr = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.track"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>track ()](#apidoc.element.react.DOM.track)
- description and source-code
```javascript
track = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.tspan"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>tspan ()](#apidoc.element.react.DOM.tspan)
- description and source-code
```javascript
tspan = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.u"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>u ()](#apidoc.element.react.DOM.u)
- description and source-code
```javascript
u = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.ul"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>ul ()](#apidoc.element.react.DOM.ul)
- description and source-code
```javascript
ul = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.var"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>var ()](#apidoc.element.react.DOM.var)
- description and source-code
```javascript
var = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.video"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>video ()](#apidoc.element.react.DOM.video)
- description and source-code
```javascript
video = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.DOM.wbr"></a>[function <span class="apidocSignatureSpan">react.DOM.</span>wbr ()](#apidoc.element.react.DOM.wbr)
- description and source-code
```javascript
wbr = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react.KeyEscapeUtils"></a>[module react.KeyEscapeUtils](#apidoc.module.react.KeyEscapeUtils)

#### <a name="apidoc.element.react.KeyEscapeUtils.escape"></a>[function <span class="apidocSignatureSpan">react.KeyEscapeUtils.</span>escape (key)](#apidoc.element.react.KeyEscapeUtils.escape)
- description and source-code
```javascript
function escape(key) {
  var escapeRegex = /[=:]/g;
  var escaperLookup = {
    '=': '=0',
    ':': '=2'
  };
  var escapedString = ('' + key).replace(escapeRegex, function (match) {
    return escaperLookup[match];
  });

  return '$' + escapedString;
}
```
- example usage
```shell
...
* @return {string}
*/
function getComponentKey(component, index) {
 // Do some typechecking here since we call this blindly. We want to ensure
 // that we don't block potential future ES APIs.
 if (component && typeof component === 'object' && component.key != null) {
   // Explicit key
   return KeyEscapeUtils.escape(component.key);
 }
 // Implicit key determined by the index in the set
 return index.toString(36);
}

/**
* @param {?*} children Children tree container.
...
```

#### <a name="apidoc.element.react.KeyEscapeUtils.unescape"></a>[function <span class="apidocSignatureSpan">react.KeyEscapeUtils.</span>unescape (key)](#apidoc.element.react.KeyEscapeUtils.unescape)
- description and source-code
```javascript
function unescape(key) {
  var unescapeRegex = /(=0|=2)/g;
  var unescaperLookup = {
    '=0': '=',
    '=2': ':'
  };
  var keySubstring = key[0] === '.' && key[1] === '$' ? key.substring(2) : key.substring(1);

  return ('' + keySubstring).replace(unescapeRegex, function (match) {
    return unescaperLookup[match];
  });
}
```
- example usage
```shell
...
    var result = traverseContext;
    var keyUnique = result[name] === undefined;
    if (process.env.NODE_ENV !== 'production') {
      if (!ReactComponentTreeHook) {
        ReactComponentTreeHook = require('./ReactComponentTreeHook');
      }
      if (!keyUnique) {
        process.env.NODE_ENV !== 'production' ? warning(false, 'flattenChildren(...): Encountered two children with the same key
, ' + ''%s'. Child keys must be unique; when two children share a key, only ' + 'the first child will be used.%s', KeyEscapeUtils
.unescape(name), ReactComponentTreeHook.getStackAddendumByID(selfDebugID)) : void 0;
      }
    }
    if (keyUnique && child != null) {
      result[name] = child;
    }
  }
}
...
```



# <a name="apidoc.module.react.LinkedStateMixin"></a>[module react.LinkedStateMixin](#apidoc.module.react.LinkedStateMixin)

#### <a name="apidoc.element.react.LinkedStateMixin.linkState"></a>[function <span class="apidocSignatureSpan">react.LinkedStateMixin.</span>linkState (key)](#apidoc.element.react.LinkedStateMixin.linkState)
- description and source-code
```javascript
linkState = function (key) {
  return new ReactLink(this.state[key], ReactStateSetters.createStateKeySetter(this, key));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react.PooledClass"></a>[module react.PooledClass](#apidoc.module.react.PooledClass)

#### <a name="apidoc.element.react.PooledClass.addPoolingTo"></a>[function <span class="apidocSignatureSpan">react.PooledClass.</span>addPoolingTo (CopyConstructor, pooler)](#apidoc.element.react.PooledClass.addPoolingTo)
- description and source-code
```javascript
addPoolingTo = function (CopyConstructor, pooler) {
  // Casting as any so that flow ignores the actual implementation and trusts
  // it to match the type we declared
  var NewKlass = CopyConstructor;
  NewKlass.instancePool = [];
  NewKlass.getPooled = pooler || DEFAULT_POOLER;
  if (!NewKlass.poolSize) {
    NewKlass.poolSize = DEFAULT_POOL_SIZE;
  }
  NewKlass.release = standardReleaser;
  return NewKlass;
}
```
- example usage
```shell
...
  this.count = 0;
}
ForEachBookKeeping.prototype.destructor = function () {
  this.func = null;
  this.context = null;
  this.count = 0;
};
PooledClass.addPoolingTo(ForEachBookKeeping, twoArgumentPooler);

function forEachSingleChild(bookKeeping, child, name) {
  var func = bookKeeping.func,
      context = bookKeeping.context;

  func.call(context, child, bookKeeping.count++);
}
...
```

#### <a name="apidoc.element.react.PooledClass.fourArgumentPooler"></a>[function <span class="apidocSignatureSpan">react.PooledClass.</span>fourArgumentPooler (a1, a2, a3, a4)](#apidoc.element.react.PooledClass.fourArgumentPooler)
- description and source-code
```javascript
fourArgumentPooler = function (a1, a2, a3, a4) {
  var Klass = this;
  if (Klass.instancePool.length) {
    var instance = Klass.instancePool.pop();
    Klass.call(instance, a1, a2, a3, a4);
    return instance;
  } else {
    return new Klass(a1, a2, a3, a4);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PooledClass.oneArgumentPooler"></a>[function <span class="apidocSignatureSpan">react.PooledClass.</span>oneArgumentPooler (copyFieldsFrom)](#apidoc.element.react.PooledClass.oneArgumentPooler)
- description and source-code
```javascript
oneArgumentPooler = function (copyFieldsFrom) {
  var Klass = this;
  if (Klass.instancePool.length) {
    var instance = Klass.instancePool.pop();
    Klass.call(instance, copyFieldsFrom);
    return instance;
  } else {
    return new Klass(copyFieldsFrom);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PooledClass.threeArgumentPooler"></a>[function <span class="apidocSignatureSpan">react.PooledClass.</span>threeArgumentPooler (a1, a2, a3)](#apidoc.element.react.PooledClass.threeArgumentPooler)
- description and source-code
```javascript
threeArgumentPooler = function (a1, a2, a3) {
  var Klass = this;
  if (Klass.instancePool.length) {
    var instance = Klass.instancePool.pop();
    Klass.call(instance, a1, a2, a3);
    return instance;
  } else {
    return new Klass(a1, a2, a3);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PooledClass.twoArgumentPooler"></a>[function <span class="apidocSignatureSpan">react.PooledClass.</span>twoArgumentPooler (a1, a2)](#apidoc.element.react.PooledClass.twoArgumentPooler)
- description and source-code
```javascript
twoArgumentPooler = function (a1, a2) {
  var Klass = this;
  if (Klass.instancePool.length) {
    var instance = Klass.instancePool.pop();
    Klass.call(instance, a1, a2);
    return instance;
  } else {
    return new Klass(a1, a2);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react.PropTypes"></a>[module react.PropTypes](#apidoc.module.react.PropTypes)

#### <a name="apidoc.element.react.PropTypes.any"></a>[function <span class="apidocSignatureSpan">react.PropTypes.</span>any ()](#apidoc.element.react.PropTypes.any)
- description and source-code
```javascript
any = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.array"></a>[function <span class="apidocSignatureSpan">react.PropTypes.</span>array ()](#apidoc.element.react.PropTypes.array)
- description and source-code
```javascript
array = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.arrayOf"></a>[function <span class="apidocSignatureSpan">react.PropTypes.</span>arrayOf (typeChecker)](#apidoc.element.react.PropTypes.arrayOf)
- description and source-code
```javascript
function createArrayOfTypeChecker(typeChecker) {
  function validate(props, propName, componentName, location, propFullName) {
    if (typeof typeChecker !== 'function') {
      return new PropTypeError('Property '' + propFullName + '' of component '' + componentName + '' has invalid PropType notation
 inside arrayOf.');
    }
    var propValue = props[propName];
    if (!Array.isArray(propValue)) {
      var locationName = ReactPropTypeLocationNames[location];
      var propType = getPropType(propValue);
      return new PropTypeError('Invalid ' + locationName + ' '' + propFullName + '' of type ' + (''' + propType + '' supplied to
 '' + componentName + '', expected an array.'));
    }
    for (var i = 0; i < propValue.length; i++) {
      var error = typeChecker(propValue, i, componentName, location, propFullName + '[' + i + ']', ReactPropTypesSecret);
      if (error instanceof Error) {
        return error;
      }
    }
    return null;
  }
  return createChainableTypeChecker(validate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.bool"></a>[function <span class="apidocSignatureSpan">react.PropTypes.</span>bool ()](#apidoc.element.react.PropTypes.bool)
- description and source-code
```javascript
bool = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.element"></a>[function <span class="apidocSignatureSpan">react.PropTypes.</span>element ()](#apidoc.element.react.PropTypes.element)
- description and source-code
```javascript
element = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.func"></a>[function <span class="apidocSignatureSpan">react.PropTypes.</span>func ()](#apidoc.element.react.PropTypes.func)
- description and source-code
```javascript
func = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.instanceOf"></a>[function <span class="apidocSignatureSpan">react.PropTypes.</span>instanceOf (expectedClass)](#apidoc.element.react.PropTypes.instanceOf)
- description and source-code
```javascript
function createInstanceTypeChecker(expectedClass) {
  function validate(props, propName, componentName, location, propFullName) {
    if (!(props[propName] instanceof expectedClass)) {
      var locationName = ReactPropTypeLocationNames[location];
      var expectedClassName = expectedClass.name || ANONYMOUS;
      var actualClassName = getClassName(props[propName]);
      return new PropTypeError('Invalid ' + locationName + ' '' + propFullName + '' of type ' + (''' + actualClassName + '' supplied
 to '' + componentName + '', expected ') + ('instance of '' + expectedClassName + ''.'));
    }
    return null;
  }
  return createChainableTypeChecker(validate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.node"></a>[function <span class="apidocSignatureSpan">react.PropTypes.</span>node ()](#apidoc.element.react.PropTypes.node)
- description and source-code
```javascript
node = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.number"></a>[function <span class="apidocSignatureSpan">react.PropTypes.</span>number ()](#apidoc.element.react.PropTypes.number)
- description and source-code
```javascript
number = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.object"></a>[function <span class="apidocSignatureSpan">react.PropTypes.</span>object ()](#apidoc.element.react.PropTypes.object)
- description and source-code
```javascript
object = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.objectOf"></a>[function <span class="apidocSignatureSpan">react.PropTypes.</span>objectOf (typeChecker)](#apidoc.element.react.PropTypes.objectOf)
- description and source-code
```javascript
function createObjectOfTypeChecker(typeChecker) {
  function validate(props, propName, componentName, location, propFullName) {
    if (typeof typeChecker !== 'function') {
      return new PropTypeError('Property '' + propFullName + '' of component '' + componentName + '' has invalid PropType notation
 inside objectOf.');
    }
    var propValue = props[propName];
    var propType = getPropType(propValue);
    if (propType !== 'object') {
      var locationName = ReactPropTypeLocationNames[location];
      return new PropTypeError('Invalid ' + locationName + ' '' + propFullName + '' of type ' + (''' + propType + '' supplied to
 '' + componentName + '', expected an object.'));
    }
    for (var key in propValue) {
      if (propValue.hasOwnProperty(key)) {
        var error = typeChecker(propValue, key, componentName, location, propFullName + '.' + key, ReactPropTypesSecret);
        if (error instanceof Error) {
          return error;
        }
      }
    }
    return null;
  }
  return createChainableTypeChecker(validate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.oneOf"></a>[function <span class="apidocSignatureSpan">react.PropTypes.</span>oneOf (expectedValues)](#apidoc.element.react.PropTypes.oneOf)
- description and source-code
```javascript
function createEnumTypeChecker(expectedValues) {
  if (!Array.isArray(expectedValues)) {
    process.env.NODE_ENV !== 'production' ? warning(false, 'Invalid argument supplied to oneOf, expected an instance of array.') :
void 0;
    return emptyFunction.thatReturnsNull;
  }

  function validate(props, propName, componentName, location, propFullName) {
    var propValue = props[propName];
    for (var i = 0; i < expectedValues.length; i++) {
      if (is(propValue, expectedValues[i])) {
        return null;
      }
    }

    var locationName = ReactPropTypeLocationNames[location];
    var valuesString = JSON.stringify(expectedValues);
    return new PropTypeError('Invalid ' + locationName + ' '' + propFullName + '' of value '' + propValue + '' ' + ('supplied to
 '' + componentName + '', expected one of ' + valuesString + '.'));
  }
  return createChainableTypeChecker(validate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.oneOfType"></a>[function <span class="apidocSignatureSpan">react.PropTypes.</span>oneOfType (arrayOfTypeCheckers)](#apidoc.element.react.PropTypes.oneOfType)
- description and source-code
```javascript
function createUnionTypeChecker(arrayOfTypeCheckers) {
  if (!Array.isArray(arrayOfTypeCheckers)) {
    process.env.NODE_ENV !== 'production' ? warning(false, 'Invalid argument supplied to oneOfType, expected an instance of array
.') : void 0;
    return emptyFunction.thatReturnsNull;
  }

  function validate(props, propName, componentName, location, propFullName) {
    for (var i = 0; i < arrayOfTypeCheckers.length; i++) {
      var checker = arrayOfTypeCheckers[i];
      if (checker(props, propName, componentName, location, propFullName, ReactPropTypesSecret) == null) {
        return null;
      }
    }

    var locationName = ReactPropTypeLocationNames[location];
    return new PropTypeError('Invalid ' + locationName + ' '' + propFullName + '' supplied to ' + (''' + componentName + ''.'));
  }
  return createChainableTypeChecker(validate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.shape"></a>[function <span class="apidocSignatureSpan">react.PropTypes.</span>shape (shapeTypes)](#apidoc.element.react.PropTypes.shape)
- description and source-code
```javascript
function createShapeTypeChecker(shapeTypes) {
  function validate(props, propName, componentName, location, propFullName) {
    var propValue = props[propName];
    var propType = getPropType(propValue);
    if (propType !== 'object') {
      var locationName = ReactPropTypeLocationNames[location];
      return new PropTypeError('Invalid ' + locationName + ' '' + propFullName + '' of type '' + propType + '' ' + ('supplied to
 '' + componentName + '', expected 'object'.'));
    }
    for (var key in shapeTypes) {
      var checker = shapeTypes[key];
      if (!checker) {
        continue;
      }
      var error = checker(propValue, key, componentName, location, propFullName + '.' + key, ReactPropTypesSecret);
      if (error) {
        return error;
      }
    }
    return null;
  }
  return createChainableTypeChecker(validate);
}
```
- example usage
```shell
...
 * }
 */
function createLinkTypeChecker(linkType) {
  var shapes = {
    value: linkType === undefined ? React.PropTypes.any.isRequired : linkType.isRequired,
    requestChange: React.PropTypes.func.isRequired
  };
  return React.PropTypes.shape(shapes);
}

ReactLink.PropTypes = {
  link: createLinkTypeChecker
};

module.exports = ReactLink;
...
```

#### <a name="apidoc.element.react.PropTypes.string"></a>[function <span class="apidocSignatureSpan">react.PropTypes.</span>string ()](#apidoc.element.react.PropTypes.string)
- description and source-code
```javascript
string = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.symbol"></a>[function <span class="apidocSignatureSpan">react.PropTypes.</span>symbol ()](#apidoc.element.react.PropTypes.symbol)
- description and source-code
```javascript
symbol = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react.PropTypes.any"></a>[module react.PropTypes.any](#apidoc.module.react.PropTypes.any)

#### <a name="apidoc.element.react.PropTypes.any.any"></a>[function <span class="apidocSignatureSpan">react.PropTypes.</span>any ()](#apidoc.element.react.PropTypes.any.any)
- description and source-code
```javascript
any = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.any.isRequired"></a>[function <span class="apidocSignatureSpan">react.PropTypes.any.</span>isRequired ()](#apidoc.element.react.PropTypes.any.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react.PropTypes.array"></a>[module react.PropTypes.array](#apidoc.module.react.PropTypes.array)

#### <a name="apidoc.element.react.PropTypes.array.array"></a>[function <span class="apidocSignatureSpan">react.PropTypes.</span>array ()](#apidoc.element.react.PropTypes.array.array)
- description and source-code
```javascript
array = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.array.isRequired"></a>[function <span class="apidocSignatureSpan">react.PropTypes.array.</span>isRequired ()](#apidoc.element.react.PropTypes.array.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react.PropTypes.bool"></a>[module react.PropTypes.bool](#apidoc.module.react.PropTypes.bool)

#### <a name="apidoc.element.react.PropTypes.bool.bool"></a>[function <span class="apidocSignatureSpan">react.PropTypes.</span>bool ()](#apidoc.element.react.PropTypes.bool.bool)
- description and source-code
```javascript
bool = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.bool.isRequired"></a>[function <span class="apidocSignatureSpan">react.PropTypes.bool.</span>isRequired ()](#apidoc.element.react.PropTypes.bool.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react.PropTypes.element"></a>[module react.PropTypes.element](#apidoc.module.react.PropTypes.element)

#### <a name="apidoc.element.react.PropTypes.element.element"></a>[function <span class="apidocSignatureSpan">react.PropTypes.</span>element ()](#apidoc.element.react.PropTypes.element.element)
- description and source-code
```javascript
element = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.element.isRequired"></a>[function <span class="apidocSignatureSpan">react.PropTypes.element.</span>isRequired ()](#apidoc.element.react.PropTypes.element.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react.PropTypes.func"></a>[module react.PropTypes.func](#apidoc.module.react.PropTypes.func)

#### <a name="apidoc.element.react.PropTypes.func.func"></a>[function <span class="apidocSignatureSpan">react.PropTypes.</span>func ()](#apidoc.element.react.PropTypes.func.func)
- description and source-code
```javascript
func = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.func.isRequired"></a>[function <span class="apidocSignatureSpan">react.PropTypes.func.</span>isRequired ()](#apidoc.element.react.PropTypes.func.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react.PropTypes.node"></a>[module react.PropTypes.node](#apidoc.module.react.PropTypes.node)

#### <a name="apidoc.element.react.PropTypes.node.node"></a>[function <span class="apidocSignatureSpan">react.PropTypes.</span>node ()](#apidoc.element.react.PropTypes.node.node)
- description and source-code
```javascript
node = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.node.isRequired"></a>[function <span class="apidocSignatureSpan">react.PropTypes.node.</span>isRequired ()](#apidoc.element.react.PropTypes.node.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react.PropTypes.number"></a>[module react.PropTypes.number](#apidoc.module.react.PropTypes.number)

#### <a name="apidoc.element.react.PropTypes.number.number"></a>[function <span class="apidocSignatureSpan">react.PropTypes.</span>number ()](#apidoc.element.react.PropTypes.number.number)
- description and source-code
```javascript
number = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.number.isRequired"></a>[function <span class="apidocSignatureSpan">react.PropTypes.number.</span>isRequired ()](#apidoc.element.react.PropTypes.number.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react.PropTypes.object"></a>[module react.PropTypes.object](#apidoc.module.react.PropTypes.object)

#### <a name="apidoc.element.react.PropTypes.object.object"></a>[function <span class="apidocSignatureSpan">react.PropTypes.</span>object ()](#apidoc.element.react.PropTypes.object.object)
- description and source-code
```javascript
object = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.object.isRequired"></a>[function <span class="apidocSignatureSpan">react.PropTypes.object.</span>isRequired ()](#apidoc.element.react.PropTypes.object.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react.PropTypes.string"></a>[module react.PropTypes.string](#apidoc.module.react.PropTypes.string)

#### <a name="apidoc.element.react.PropTypes.string.string"></a>[function <span class="apidocSignatureSpan">react.PropTypes.</span>string ()](#apidoc.element.react.PropTypes.string.string)
- description and source-code
```javascript
string = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.string.isRequired"></a>[function <span class="apidocSignatureSpan">react.PropTypes.string.</span>isRequired ()](#apidoc.element.react.PropTypes.string.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react.PropTypes.symbol"></a>[module react.PropTypes.symbol](#apidoc.module.react.PropTypes.symbol)

#### <a name="apidoc.element.react.PropTypes.symbol.symbol"></a>[function <span class="apidocSignatureSpan">react.PropTypes.</span>symbol ()](#apidoc.element.react.PropTypes.symbol.symbol)
- description and source-code
```javascript
symbol = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PropTypes.symbol.isRequired"></a>[function <span class="apidocSignatureSpan">react.PropTypes.symbol.</span>isRequired ()](#apidoc.element.react.PropTypes.symbol.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react.PureComponent"></a>[module react.PureComponent](#apidoc.module.react.PureComponent)

#### <a name="apidoc.element.react.PureComponent.PureComponent"></a>[function <span class="apidocSignatureSpan">react.</span>PureComponent (props, context, updater)](#apidoc.element.react.PureComponent.PureComponent)
- description and source-code
```javascript
function ReactPureComponent(props, context, updater) {
  // Duplicated from ReactComponent.
  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  // We initialize the default updater but the real one gets injected by the
  // renderer.
  this.updater = updater || ReactNoopUpdateQueue;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react.PureComponent.prototype"></a>[module react.PureComponent.prototype](#apidoc.module.react.PureComponent.prototype)

#### <a name="apidoc.element.react.PureComponent.prototype.constructor"></a>[function <span class="apidocSignatureSpan">react.PureComponent.prototype.</span>constructor (props, context, updater)](#apidoc.element.react.PureComponent.prototype.constructor)
- description and source-code
```javascript
function ReactPureComponent(props, context, updater) {
  // Duplicated from ReactComponent.
  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  // We initialize the default updater but the real one gets injected by the
  // renderer.
  this.updater = updater || ReactNoopUpdateQueue;
}
```
- example usage
```shell
...
var invariant = require('fbjs/lib/invariant');
var hasOwnProperty = {}.hasOwnProperty;

function shallowCopy(x) {
  if (Array.isArray(x)) {
    return x.concat();
  } else if (x && typeof x === 'object') {
    return _assign(new x.constructor(), x);
  } else {
    return x;
  }
}

var COMMAND_PUSH = '$push';
var COMMAND_UNSHIFT = '$unshift';
...
```

#### <a name="apidoc.element.react.PureComponent.prototype.forceUpdate"></a>[function <span class="apidocSignatureSpan">react.PureComponent.prototype.</span>forceUpdate (callback)](#apidoc.element.react.PureComponent.prototype.forceUpdate)
- description and source-code
```javascript
forceUpdate = function (callback) {
  this.updater.enqueueForceUpdate(this);
  if (callback) {
    this.updater.enqueueCallback(this, callback, 'forceUpdate');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.PureComponent.prototype.setState"></a>[function <span class="apidocSignatureSpan">react.PureComponent.prototype.</span>setState (partialState, callback)](#apidoc.element.react.PureComponent.prototype.setState)
- description and source-code
```javascript
setState = function (partialState, callback) {
  !(typeof partialState === 'object' || typeof partialState === 'function' || partialState == null) ? process.env.NODE_ENV !== '
production' ? invariant(false, 'setState(...): takes an object of state variables to update or a function which returns an object
 of state variables.') : _prodInvariant('85') : void 0;
  this.updater.enqueueSetState(this, partialState);
  if (callback) {
    this.updater.enqueueCallback(this, callback, 'setState');
  }
}
```
- example usage
```shell
...
  /**
* Invoked before the component receives new props.
*
* Use this as an opportunity to react to a prop transition by updating the
* state using 'this.setState'. Current props are accessed via 'this.props'.
*
*   componentWillReceiveProps: function(nextProps, nextContext) {
*     this.setState({
*       likesIncreasing: nextProps.likeCount > this.props.likeCount
*     });
*   }
*
* NOTE: There is no equivalent 'componentWillReceiveState'. An incoming prop
* transition may cause a state change, but the opposite is not true. If you
* need it, you are probably looking for 'componentWillUpdate'.
...
```



# <a name="apidoc.module.react.ReactAddonsDOMDependenciesUMDShim"></a>[module react.ReactAddonsDOMDependenciesUMDShim](#apidoc.module.react.ReactAddonsDOMDependenciesUMDShim)

#### <a name="apidoc.element.react.ReactAddonsDOMDependenciesUMDShim.getReactDOM"></a>[function <span class="apidocSignatureSpan">react.ReactAddonsDOMDependenciesUMDShim.</span>getReactDOM ()](#apidoc.element.react.ReactAddonsDOMDependenciesUMDShim.getReactDOM)
- description and source-code
```javascript
function getReactDOM() {
  if (!ReactDOM) {
    // This is safe to use because current module only exists in the addons build:
    var ReactWithAddonsUMDEntry = require('./ReactWithAddonsUMDEntry');
    // This is injected by the ReactDOM UMD build:
    ReactDOM = ReactWithAddonsUMDEntry.__SECRET_INJECTED_REACT_DOM_DO_NOT_USE_OR_YOU_WILL_BE_FIRED;
  }
  return ReactDOM;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactAddonsDOMDependenciesUMDShim.getReactPerf"></a>[function <span class="apidocSignatureSpan">react.ReactAddonsDOMDependenciesUMDShim.</span>getReactPerf ()](#apidoc.element.react.ReactAddonsDOMDependenciesUMDShim.getReactPerf)
- description and source-code
```javascript
getReactPerf = function () {
  return getReactDOM().__SECRET_INTERNALS_DO_NOT_USE_OR_YOU_WILL_BE_FIRED.ReactPerf;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactAddonsDOMDependenciesUMDShim.getReactTestUtils"></a>[function <span class="apidocSignatureSpan">react.ReactAddonsDOMDependenciesUMDShim.</span>getReactTestUtils ()](#apidoc.element.react.ReactAddonsDOMDependenciesUMDShim.getReactTestUtils)
- description and source-code
```javascript
getReactTestUtils = function () {
  return getReactDOM().__SECRET_INTERNALS_DO_NOT_USE_OR_YOU_WILL_BE_FIRED.ReactTestUtils;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react.ReactChildren"></a>[module react.ReactChildren](#apidoc.module.react.ReactChildren)

#### <a name="apidoc.element.react.ReactChildren.count"></a>[function <span class="apidocSignatureSpan">react.ReactChildren.</span>count (children, context)](#apidoc.element.react.ReactChildren.count)
- description and source-code
```javascript
function countChildren(children, context) {
  return traverseAllChildren(children, forEachSingleChildDummy, null);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactChildren.forEach"></a>[function <span class="apidocSignatureSpan">react.ReactChildren.</span>forEach (children, forEachFunc, forEachContext)](#apidoc.element.react.ReactChildren.forEach)
- description and source-code
```javascript
function forEachChildren(children, forEachFunc, forEachContext) {
  if (children == null) {
    return children;
  }
  var traverseContext = ForEachBookKeeping.getPooled(forEachFunc, forEachContext);
  traverseAllChildren(children, forEachSingleChild, traverseContext);
  ForEachBookKeeping.release(traverseContext);
}
```
- example usage
```shell
...

  this.state = initialState;
});
Constructor.prototype = new ReactClassComponent();
Constructor.prototype.constructor = Constructor;
Constructor.prototype.__reactAutoBindPairs = [];

injectedMixins.forEach(mixSpecIntoComponent.bind(null, Constructor));

mixSpecIntoComponent(Constructor, spec);

// Initialize the defaultProps property after all mixins have been merged.
if (Constructor.getDefaultProps) {
  Constructor.defaultProps = Constructor.getDefaultProps();
}
...
```

#### <a name="apidoc.element.react.ReactChildren.map"></a>[function <span class="apidocSignatureSpan">react.ReactChildren.</span>map (children, func, context)](#apidoc.element.react.ReactChildren.map)
- description and source-code
```javascript
function mapChildren(children, func, context) {
  if (children == null) {
    return children;
  }
  var result = [];
  mapIntoWithKeyPrefixInternal(children, result, null, func, context);
  return result;
}
```
- example usage
```shell
...
  return itemByKey[key];
};
removeItem = function (id) {
  var key = getKeyFromID(id);
  delete itemByKey[key];
};
getItemIDs = function () {
  return Object.keys(itemByKey).map(getIDFromKey);
};

addRoot = function (id) {
  var key = getKeyFromID(id);
  rootByKey[key] = true;
};
removeRoot = function (id) {
...
```

#### <a name="apidoc.element.react.ReactChildren.mapIntoWithKeyPrefixInternal"></a>[function <span class="apidocSignatureSpan">react.ReactChildren.</span>mapIntoWithKeyPrefixInternal (children, array, prefix, func, context)](#apidoc.element.react.ReactChildren.mapIntoWithKeyPrefixInternal)
- description and source-code
```javascript
function mapIntoWithKeyPrefixInternal(children, array, prefix, func, context) {
  var escapedPrefix = '';
  if (prefix != null) {
    escapedPrefix = escapeUserProvidedKey(prefix) + '/';
  }
  var traverseContext = MapBookKeeping.getPooled(array, escapedPrefix, func, context);
  traverseAllChildren(children, mapSingleChildIntoContext, traverseContext);
  MapBookKeeping.release(traverseContext);
}
```
- example usage
```shell
...
    for (var key in object) {
      if (process.env.NODE_ENV !== 'production') {
        if (!warnedAboutNumeric && numericPropertyRegex.test(key)) {
          process.env.NODE_ENV !== 'production' ? warning(false, 'React.addons.createFragment(...): Child objects should have ' + '
non-numeric keys so ordering is preserved.') : void 0;
          warnedAboutNumeric = true;
        }
      }
      ReactChildren.mapIntoWithKeyPrefixInternal(object[key], result, key, emptyFunction.thatReturnsArgument);
    }

    return result;
  }
};

module.exports = ReactFragment;
...
```

#### <a name="apidoc.element.react.ReactChildren.toArray"></a>[function <span class="apidocSignatureSpan">react.ReactChildren.</span>toArray (children)](#apidoc.element.react.ReactChildren.toArray)
- description and source-code
```javascript
function toArray(children) {
  var result = [];
  mapIntoWithKeyPrefixInternal(children, result, null, emptyFunction.thatReturnsArgument);
  return result;
}
```
- example usage
```shell
...
 * @return {object} mirrored array with mapped children
 */
function sliceChildren(children, start, end) {
  if (children == null) {
    return children;
  }

  var array = ReactChildren.toArray(children);
  return array.slice(start, end);
}

module.exports = sliceChildren;
...
```



# <a name="apidoc.module.react.ReactClass"></a>[module react.ReactClass](#apidoc.module.react.ReactClass)

#### <a name="apidoc.element.react.ReactClass.createClass"></a>[function <span class="apidocSignatureSpan">react.ReactClass.</span>createClass (spec)](#apidoc.element.react.ReactClass.createClass)
- description and source-code
```javascript
createClass = function (spec) {
  // To keep our warnings more understandable, we'll use a little hack here to
  // ensure that Constructor.name !== 'Constructor'. This makes sure we don't
  // unnecessarily identify a class without displayName as 'Constructor'.
  var Constructor = identity(function (props, context, updater) {
    // This constructor gets overridden by mocks. The argument is used
    // by mocks to assert on what gets mounted.

    if (process.env.NODE_ENV !== 'production') {
      process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : void 0;
    }

    // Wire up auto-binding
    if (this.__reactAutoBindPairs.length) {
      bindAutoBindMethods(this);
    }

    this.props = props;
    this.context = context;
    this.refs = emptyObject;
    this.updater = updater || ReactNoopUpdateQueue;

    this.state = null;

    // ReactClasses doesn't have constructors. Instead, they use the
    // getInitialState and componentWillMount methods for initialization.

    var initialState = this.getInitialState ? this.getInitialState() : null;
    if (process.env.NODE_ENV !== 'production') {
      // We allow auto-mocks to proceed as if they're returning null.
      if (initialState === undefined && this.getInitialState._isMockFunction) {
        // This is probably bad practice. Consider warning here and
        // deprecating this convenience.
        initialState = null;
      }
    }
    !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false
, '%s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : _prodInvariant('
82', Constructor.displayName || 'ReactCompositeComponent') : void 0;

    this.state = initialState;
  });
  Constructor.prototype = new ReactClassComponent();
  Constructor.prototype.constructor = Constructor;
  Constructor.prototype.__reactAutoBindPairs = [];

  injectedMixins.forEach(mixSpecIntoComponent.bind(null, Constructor));

  mixSpecIntoComponent(Constructor, spec);

  // Initialize the defaultProps property after all mixins have been merged.
  if (Constructor.getDefaultProps) {
    Constructor.defaultProps = Constructor.getDefaultProps();
  }

  if (process.env.NODE_ENV !== 'production') {
    // This is a tag to indicate that the use of these method names is ok,
    // since it's used with createClass. If it's not, then it's likely a
    // mistake so we'll warn you to use the static property, property
    // initializer or constructor respectively.
    if (Constructor.getDefaultProps) {
      Constructor.getDefaultProps.isReactClassApproved = {};
    }
    if (Constructor.prototype.getInitialState) {
      Constructor.prototype.getInitialState.isReactClassApproved = {};
    }
  }

  !Constructor.prototype.render ? process.env.NODE_ENV !== 'production' ? invariant(false, 'createClass(...): Class specification
 must implement a 'render' method.') : _prodInvariant('83') : void 0;

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(!Constructor.prototype.componentShouldUpdate, '%s has a method called ' + 'componentShouldUpdate
(). Did you mean shouldComponentUpdate()? ' + 'The name is phrased as a question because the function is ' + 'expected to return
 a value.', spec.displayName || 'A component') : void 0;
    process.env.NODE_ENV !== 'production' ? warning(!Constructor.prototype.componentWillRecieveProps, '%s has a method called ' + '
componentWillRecieveProps(). Did you mean componentWillReceiveProps()?', spec.displayName || 'A component') : void 0;
  }

  // Reduce time spent doing lookups by setting these on the prototype.
  for (var methodName in ReactClassInterface) {
    if (!Constructor.prototype[methodName]) {
      Constructor.prototype[methodName] = null;
    }
  }

  return Constructor;
}
```
- example usage
```shell
...
* Composite components are higher-level components that compose other composite
* or host components.
*
* To create a new type of 'ReactClass', pass a specification of
* your new class to 'React.createClass'. The only requirement of your class
* specification is that you implement a 'render' method.
*
*   var MyComponent = React.createClass({
*     render: function() {
*       return <div>Hello World</div>;
*     }
*   });
*
* The class specification supports a specific protocol of methods that have
* special meaning (e.g. 'render'). See 'ReactClassInterface' for
...
```



# <a name="apidoc.module.react.ReactComponentTreeDevtool"></a>[module react.ReactComponentTreeDevtool](#apidoc.module.react.ReactComponentTreeDevtool)

#### <a name="apidoc.element.react.ReactComponentTreeDevtool.getChildIDs"></a>[function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>getChildIDs (id)](#apidoc.element.react.ReactComponentTreeDevtool.getChildIDs)
- description and source-code
```javascript
getChildIDs = function (id) {
  var item = getItem(id);
  return item ? item.childIDs : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactComponentTreeDevtool.getCurrentStackAddendum"></a>[function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>getCurrentStackAddendum (topElement)](#apidoc.element.react.ReactComponentTreeDevtool.getCurrentStackAddendum)
- description and source-code
```javascript
getCurrentStackAddendum = function (topElement) {
  var info = '';
  if (topElement) {
    var name = getDisplayName(topElement);
    var owner = topElement._owner;
    info += describeComponentFrame(name, topElement._source, owner && owner.getName());
  }

  var currentOwner = ReactCurrentOwner.current;
  var id = currentOwner && currentOwner._debugID;

  info += ReactComponentTreeHook.getStackAddendumByID(id);
  return info;
}
```
- example usage
```shell
...
 // assigning it a key.
 var childOwner = '';
 if (element && element._owner && element._owner !== ReactCurrentOwner.current) {
   // Give the component that originally created this child.
   childOwner = ' It was passed a child from ' + element._owner.getName() + '.';
 }

 process.env.NODE_ENV !== 'production' ? warning(false, 'Each child in an array or iterator should have a unique "key" prop.' + '%
s%s See https://fb.me/react-warning-keys for more information.%s', currentComponentErrorInfo, childOwner, ReactComponentTreeHook
.getCurrentStackAddendum(element)) : void 0;
}

/**
* Ensure that every element either is passed in a static location, in an
* array with an explicit keys property defined, or in an object literal
* with valid key property.
*
...
```

#### <a name="apidoc.element.react.ReactComponentTreeDevtool.getDisplayName"></a>[function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>getDisplayName (id)](#apidoc.element.react.ReactComponentTreeDevtool.getDisplayName)
- description and source-code
```javascript
getDisplayName = function (id) {
  var element = ReactComponentTreeHook.getElement(id);
  if (!element) {
    return null;
  }
  return getDisplayName(element);
}
```
- example usage
```shell
...
  return element.type;
} else {
  return element.type.displayName || element.type.name || 'Unknown';
}
}

function describeID(id) {
var name = ReactComponentTreeHook.getDisplayName(id);
var element = ReactComponentTreeHook.getElement(id);
var ownerID = ReactComponentTreeHook.getOwnerID(id);
var ownerName;
if (ownerID) {
  ownerName = ReactComponentTreeHook.getDisplayName(ownerID);
}
process.env.NODE_ENV !== 'production' ? warning(element, 'ReactComponentTreeHook: Missing React element for debugID %s when ' + '
building stack', id) : void 0;
...
```

#### <a name="apidoc.element.react.ReactComponentTreeDevtool.getElement"></a>[function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>getElement (id)](#apidoc.element.react.ReactComponentTreeDevtool.getElement)
- description and source-code
```javascript
getElement = function (id) {
  var item = getItem(id);
  return item ? item.element : null;
}
```
- example usage
```shell
...
} else {
  return element.type.displayName || element.type.name || 'Unknown';
}
}

function describeID(id) {
var name = ReactComponentTreeHook.getDisplayName(id);
var element = ReactComponentTreeHook.getElement(id);
var ownerID = ReactComponentTreeHook.getOwnerID(id);
var ownerName;
if (ownerID) {
  ownerName = ReactComponentTreeHook.getDisplayName(ownerID);
}
process.env.NODE_ENV !== 'production' ? warning(element, 'ReactComponentTreeHook: Missing React element for debugID %s when ' + '
building stack', id) : void 0;
return describeComponentFrame(name, element && element._source, ownerName);
...
```

#### <a name="apidoc.element.react.ReactComponentTreeDevtool.getOwnerID"></a>[function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>getOwnerID (id)](#apidoc.element.react.ReactComponentTreeDevtool.getOwnerID)
- description and source-code
```javascript
getOwnerID = function (id) {
  var element = ReactComponentTreeHook.getElement(id);
  if (!element || !element._owner) {
    return null;
  }
  return element._owner._debugID;
}
```
- example usage
```shell
...
    return element.type.displayName || element.type.name || 'Unknown';
  }
}

function describeID(id) {
  var name = ReactComponentTreeHook.getDisplayName(id);
  var element = ReactComponentTreeHook.getElement(id);
  var ownerID = ReactComponentTreeHook.getOwnerID(id);
  var ownerName;
  if (ownerID) {
    ownerName = ReactComponentTreeHook.getDisplayName(ownerID);
  }
  process.env.NODE_ENV !== 'production' ? warning(element, 'ReactComponentTreeHook: Missing React element for debugID %s when ' + '
building stack', id) : void 0;
  return describeComponentFrame(name, element && element._source, ownerName);
}
...
```

#### <a name="apidoc.element.react.ReactComponentTreeDevtool.getParentID"></a>[function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>getParentID (id)](#apidoc.element.react.ReactComponentTreeDevtool.getParentID)
- description and source-code
```javascript
getParentID = function (id) {
  var item = getItem(id);
  return item ? item.parentID : null;
}
```
- example usage
```shell
...
  info += ReactComponentTreeHook.getStackAddendumByID(id);
  return info;
},
getStackAddendumByID: function (id) {
  var info = '';
  while (id) {
    info += describeID(id);
    id = ReactComponentTreeHook.getParentID(id);
  }
  return info;
},
getChildIDs: function (id) {
  var item = getItem(id);
  return item ? item.childIDs : [];
},
...
```

#### <a name="apidoc.element.react.ReactComponentTreeDevtool.getRegisteredIDs"></a>[function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>getRegisteredIDs ()](#apidoc.element.react.ReactComponentTreeDevtool.getRegisteredIDs)
- description and source-code
```javascript
getRegisteredIDs = function () {
  return Array.from(itemMap.keys());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactComponentTreeDevtool.getRootIDs"></a>[function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>getRootIDs ()](#apidoc.element.react.ReactComponentTreeDevtool.getRootIDs)
- description and source-code
```javascript
getRootIDs = function () {
  return Array.from(rootIDSet.keys());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactComponentTreeDevtool.getSource"></a>[function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>getSource (id)](#apidoc.element.react.ReactComponentTreeDevtool.getSource)
- description and source-code
```javascript
getSource = function (id) {
  var item = getItem(id);
  var element = item ? item.element : null;
  var source = element != null ? element._source : null;
  return source;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactComponentTreeDevtool.getStackAddendumByID"></a>[function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>getStackAddendumByID (id)](#apidoc.element.react.ReactComponentTreeDevtool.getStackAddendumByID)
- description and source-code
```javascript
getStackAddendumByID = function (id) {
  var info = '';
  while (id) {
    info += describeID(id);
    id = ReactComponentTreeHook.getParentID(id);
  }
  return info;
}
```
- example usage
```shell
...
    var owner = topElement._owner;
    info += describeComponentFrame(name, topElement._source, owner && owner.getName());
  }

  var currentOwner = ReactCurrentOwner.current;
  var id = currentOwner && currentOwner._debugID;

  info += ReactComponentTreeHook.getStackAddendumByID(id);
  return info;
},
getStackAddendumByID: function (id) {
  var info = '';
  while (id) {
    info += describeID(id);
    id = ReactComponentTreeHook.getParentID(id);
...
```

#### <a name="apidoc.element.react.ReactComponentTreeDevtool.getText"></a>[function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>getText (id)](#apidoc.element.react.ReactComponentTreeDevtool.getText)
- description and source-code
```javascript
getText = function (id) {
  var element = ReactComponentTreeHook.getElement(id);
  if (typeof element === 'string') {
    return element;
  } else if (typeof element === 'number') {
    return '' + element;
  } else {
    return null;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactComponentTreeDevtool.getUpdateCount"></a>[function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>getUpdateCount (id)](#apidoc.element.react.ReactComponentTreeDevtool.getUpdateCount)
- description and source-code
```javascript
getUpdateCount = function (id) {
  var item = getItem(id);
  return item ? item.updateCount : 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactComponentTreeDevtool.isMounted"></a>[function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>isMounted (id)](#apidoc.element.react.ReactComponentTreeDevtool.isMounted)
- description and source-code
```javascript
isMounted = function (id) {
  var item = getItem(id);
  return item ? item.isMounted : false;
}
```
- example usage
```shell
...
  /**
   * Checks whether or not this composite component is mounted.
   * @return {boolean} True if mounted, false otherwise.
   * @protected
   * @final
   */
  isMounted: function () {
    return this.updater.isMounted(this);
  }
};

var ReactClassComponent = function () {};
_assign(ReactClassComponent.prototype, ReactComponent.prototype, ReactClassMixin);

/**
...
```

#### <a name="apidoc.element.react.ReactComponentTreeDevtool.onBeforeMountComponent"></a>[function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>onBeforeMountComponent (id, element, parentID)](#apidoc.element.react.ReactComponentTreeDevtool.onBeforeMountComponent)
- description and source-code
```javascript
onBeforeMountComponent = function (id, element, parentID) {
  var item = {
    element: element,
    parentID: parentID,
    text: null,
    childIDs: [],
    isMounted: false,
    updateCount: 0
  };
  setItem(id, item);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactComponentTreeDevtool.onBeforeUpdateComponent"></a>[function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>onBeforeUpdateComponent (id, element)](#apidoc.element.react.ReactComponentTreeDevtool.onBeforeUpdateComponent)
- description and source-code
```javascript
onBeforeUpdateComponent = function (id, element) {
  var item = getItem(id);
  if (!item || !item.isMounted) {
    // We may end up here as a result of setState() in componentWillUnmount().
    // In this case, ignore the element.
    return;
  }
  item.element = element;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactComponentTreeDevtool.onMountComponent"></a>[function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>onMountComponent (id)](#apidoc.element.react.ReactComponentTreeDevtool.onMountComponent)
- description and source-code
```javascript
onMountComponent = function (id) {
  var item = getItem(id);
  !item ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Item must have been set') : _prodInvariant('144') : void 0;
  item.isMounted = true;
  var isRoot = item.parentID === 0;
  if (isRoot) {
    addRoot(id);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactComponentTreeDevtool.onSetChildren"></a>[function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>onSetChildren (id, nextChildIDs)](#apidoc.element.react.ReactComponentTreeDevtool.onSetChildren)
- description and source-code
```javascript
onSetChildren = function (id, nextChildIDs) {
  var item = getItem(id);
  !item ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Item must have been set') : _prodInvariant('144') : void 0;
  item.childIDs = nextChildIDs;

  for (var i = 0; i < nextChildIDs.length; i++) {
    var nextChildID = nextChildIDs[i];
    var nextChild = getItem(nextChildID);
    !nextChild ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Expected hook events to fire for the child before its
 parent includes it in onSetChildren().') : _prodInvariant('140') : void 0;
    !(nextChild.childIDs != null || typeof nextChild.element !== 'object' || nextChild.element == null) ? process.env.NODE_ENV !== '
production' ? invariant(false, 'Expected onSetChildren() to fire for a container child before its parent includes it in onSetChildren
().') : _prodInvariant('141') : void 0;
    !nextChild.isMounted ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Expected onMountComponent() to fire for the
 child before its parent includes it in onSetChildren().') : _prodInvariant('71') : void 0;
    if (nextChild.parentID == null) {
      nextChild.parentID = id;
      // TODO: This shouldn't be necessary but mounting a new root during in
      // componentWillMount currently causes not-yet-mounted components to
      // be purged from our tree data so their parent id is missing.
    }
    !(nextChild.parentID === id) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Expected onBeforeMountComponent() parent
 and onSetChildren() to be consistent (%s has parents %s and %s).', nextChildID, nextChild.parentID, id) : _prodInvariant('142',
nextChildID, nextChild.parentID, id) : void 0;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactComponentTreeDevtool.onUnmountComponent"></a>[function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>onUnmountComponent (id)](#apidoc.element.react.ReactComponentTreeDevtool.onUnmountComponent)
- description and source-code
```javascript
onUnmountComponent = function (id) {
  var item = getItem(id);
  if (item) {
    // We need to check if it exists.
    // 'item' might not exist if it is inside an error boundary, and a sibling
    // error boundary child threw while mounting. Then this instance never
    // got a chance to mount, but it still gets an unmounting event during
    // the error boundary cleanup.
    item.isMounted = false;
    var isRoot = item.parentID === 0;
    if (isRoot) {
      removeRoot(id);
    }
  }
  unmountedIDs.push(id);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactComponentTreeDevtool.onUpdateComponent"></a>[function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>onUpdateComponent (id)](#apidoc.element.react.ReactComponentTreeDevtool.onUpdateComponent)
- description and source-code
```javascript
onUpdateComponent = function (id) {
  var item = getItem(id);
  if (!item || !item.isMounted) {
    // We may end up here as a result of setState() in componentWillUnmount().
    // In this case, ignore the element.
    return;
  }
  item.updateCount++;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactComponentTreeDevtool.purgeUnmountedComponents"></a>[function <span class="apidocSignatureSpan">react.ReactComponentTreeDevtool.</span>purgeUnmountedComponents ()](#apidoc.element.react.ReactComponentTreeDevtool.purgeUnmountedComponents)
- description and source-code
```javascript
purgeUnmountedComponents = function () {
  if (ReactComponentTreeHook._preventPurging) {
    // Should only be used for testing.
    return;
  }

  for (var i = 0; i < unmountedIDs.length; i++) {
    var id = unmountedIDs[i];
    purgeDeep(id);
  }
  unmountedIDs.length = 0;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react.ReactComponentWithPureRenderMixin"></a>[module react.ReactComponentWithPureRenderMixin](#apidoc.module.react.ReactComponentWithPureRenderMixin)

#### <a name="apidoc.element.react.ReactComponentWithPureRenderMixin.shouldComponentUpdate"></a>[function <span class="apidocSignatureSpan">react.ReactComponentWithPureRenderMixin.</span>shouldComponentUpdate (nextProps, nextState)](#apidoc.element.react.ReactComponentWithPureRenderMixin.shouldComponentUpdate)
- description and source-code
```javascript
shouldComponentUpdate = function (nextProps, nextState) {
  return shallowCompare(this, nextProps, nextState);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react.ReactElement"></a>[module react.ReactElement](#apidoc.module.react.ReactElement)

#### <a name="apidoc.element.react.ReactElement.ReactElement"></a>[function <span class="apidocSignatureSpan">react.</span>ReactElement (type, key, ref, self, source, owner, props)](#apidoc.element.react.ReactElement.ReactElement)
- description and source-code
```javascript
ReactElement = function (type, key, ref, self, source, owner, props) {
  var element = {
    // This tag allow us to uniquely identify this as a React Element
    $$typeof: REACT_ELEMENT_TYPE,

    // Built-in properties that belong on the element
    type: type,
    key: key,
    ref: ref,
    props: props,

    // Record the component responsible for creating this element.
    _owner: owner
  };

  if (process.env.NODE_ENV !== 'production') {
    // The validation flag is currently mutative. We put it on
    // an external backing store so that we can freeze the whole object.
    // This can be replaced with a WeakMap once they are implemented in
    // commonly used development environments.
    element._store = {};

    // To make comparing ReactElements easier for testing purposes, we make
    // the validation flag non-enumerable (where possible, which should
    // include every environment we run tests in), so the test framework
    // ignores it.
    if (canDefineProperty) {
      Object.defineProperty(element._store, 'validated', {
        configurable: false,
        enumerable: false,
        writable: true,
        value: false
      });
      // self and source are DEV only properties.
      Object.defineProperty(element, '_self', {
        configurable: false,
        enumerable: false,
        writable: false,
        value: self
      });
      // Two elements created in two different places should be considered
      // equal for testing purposes and therefore we hide it from enumeration.
      Object.defineProperty(element, '_source', {
        configurable: false,
        enumerable: false,
        writable: false,
        value: source
      });
    } else {
      element._store.validated = false;
      element._self = self;
      element._source = source;
    }
    if (Object.freeze) {
      Object.freeze(element.props);
      Object.freeze(element);
    }
  }

  return element;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactElement.cloneAndReplaceKey"></a>[function <span class="apidocSignatureSpan">react.ReactElement.</span>cloneAndReplaceKey (oldElement, newKey)](#apidoc.element.react.ReactElement.cloneAndReplaceKey)
- description and source-code
```javascript
cloneAndReplaceKey = function (oldElement, newKey) {
  var newElement = ReactElement(oldElement.type, newKey, oldElement.ref, oldElement._self, oldElement._source, oldElement._owner
, oldElement.props);

  return newElement;
}
```
- example usage
```shell
...


  var mappedChild = func.call(context, child, bookKeeping.count++);
  if (Array.isArray(mappedChild)) {
    mapIntoWithKeyPrefixInternal(mappedChild, result, childKey, emptyFunction.thatReturnsArgument);
  } else if (mappedChild != null) {
    if (ReactElement.isValidElement(mappedChild)) {
      mappedChild = ReactElement.cloneAndReplaceKey(mappedChild,
      // Keep both the (mapped) and old keys if they differ, just as
      // traverseAllChildren used to do for objects as children
      keyPrefix + (mappedChild.key && (!child || child.key !== mappedChild.key) ? escapeUserProvidedKey(mappedChild.key) + '/' : '') +
childKey);
    }
    result.push(mappedChild);
  }
}
...
```

#### <a name="apidoc.element.react.ReactElement.cloneElement"></a>[function <span class="apidocSignatureSpan">react.ReactElement.</span>cloneElement (element, config, children)](#apidoc.element.react.ReactElement.cloneElement)
- description and source-code
```javascript
cloneElement = function (element, config, children) {
  var propName;

  // Original props are copied
  var props = _assign({}, element.props);

  // Reserved names are extracted
  var key = element.key;
  var ref = element.ref;
  // Self is preserved since the owner is preserved.
  var self = element._self;
  // Source is preserved since cloneElement is unlikely to be targeted by a
  // transpiler, and the original source is probably a better indicator of the
  // true owner.
  var source = element._source;

  // Owner will be preserved, unless ref is overridden
  var owner = element._owner;

  if (config != null) {
    if (hasValidRef(config)) {
      // Silently steal the ref from the parent.
      ref = config.ref;
      owner = ReactCurrentOwner.current;
    }
    if (hasValidKey(config)) {
      key = '' + config.key;
    }

    // Remaining properties override existing props
    var defaultProps;
    if (element.type && element.type.defaultProps) {
      defaultProps = element.type.defaultProps;
    }
    for (propName in config) {
      if (hasOwnProperty.call(config, propName) && !RESERVED_PROPS.hasOwnProperty(propName)) {
        if (config[propName] === undefined && defaultProps !== undefined) {
          // Resolve default props
          props[propName] = defaultProps[propName];
        } else {
          props[propName] = config[propName];
        }
      }
    }
  }

  // Children can be more than one argument, and those are transferred onto
  // the newly allocated props object.
  var childrenLength = arguments.length - 2;
  if (childrenLength === 1) {
    props.children = children;
  } else if (childrenLength > 1) {
    var childArray = Array(childrenLength);
    for (var i = 0; i < childrenLength; i++) {
      childArray[i] = arguments[i + 2];
    }
    props.children = childArray;
  }

  return ReactElement(element.type, key, ref, self, source, owner, props);
}
```
- example usage
```shell
...
  var child = this.state.children[key];
  if (child) {
    // You may need to apply reactive updates to a child as it is leaving.
    // The normal React way to do it won't work since the child will have
    // already been removed. In case you need this behavior you can provide
    // a childFactory function to wrap every child, even the ones that are
    // leaving.
    childrenToRender.push(React.cloneElement(this.props.childFactory(child), { ref: key, key: key }));
  }
}

// Do not forward ReactTransitionGroup props to primitive DOM nodes
var props = _assign({}, this.props);
delete props.transitionLeave;
delete props.transitionName;
...
```

#### <a name="apidoc.element.react.ReactElement.createElement"></a>[function <span class="apidocSignatureSpan">react.ReactElement.</span>createElement (type, config, children)](#apidoc.element.react.ReactElement.createElement)
- description and source-code
```javascript
createElement = function (type, config, children) {
  var propName;

  // Reserved names are extracted
  var props = {};

  var key = null;
  var ref = null;
  var self = null;
  var source = null;

  if (config != null) {
    if (hasValidRef(config)) {
      ref = config.ref;
    }
    if (hasValidKey(config)) {
      key = '' + config.key;
    }

    self = config.__self === undefined ? null : config.__self;
    source = config.__source === undefined ? null : config.__source;
    // Remaining properties are added to a new props object
    for (propName in config) {
      if (hasOwnProperty.call(config, propName) && !RESERVED_PROPS.hasOwnProperty(propName)) {
        props[propName] = config[propName];
      }
    }
  }

  // Children can be more than one argument, and those are transferred onto
  // the newly allocated props object.
  var childrenLength = arguments.length - 2;
  if (childrenLength === 1) {
    props.children = children;
  } else if (childrenLength > 1) {
    var childArray = Array(childrenLength);
    for (var i = 0; i < childrenLength; i++) {
      childArray[i] = arguments[i + 2];
    }
    if (process.env.NODE_ENV !== 'production') {
      if (Object.freeze) {
        Object.freeze(childArray);
      }
    }
    props.children = childArray;
  }

  // Resolve default props
  if (type && type.defaultProps) {
    var defaultProps = type.defaultProps;
    for (propName in defaultProps) {
      if (props[propName] === undefined) {
        props[propName] = defaultProps[propName];
      }
    }
  }
  if (process.env.NODE_ENV !== 'production') {
    if (key || ref) {
      if (typeof props.$$typeof === 'undefined' || props.$$typeof !== REACT_ELEMENT_TYPE) {
        var displayName = typeof type === 'function' ? type.displayName || type.name || 'Unknown' : type;
        if (key) {
          defineKeyPropWarningGetter(props, displayName);
        }
        if (ref) {
          defineRefPropWarningGetter(props, displayName);
        }
      }
    }
  }
  return ReactElement(type, key, ref, self, source, ReactCurrentOwner.current, props);
}
```
- example usage
```shell
...
    delete props.transitionEnter;
    delete props.childFactory;
    delete props.transitionLeaveTimeout;
    delete props.transitionEnterTimeout;
    delete props.transitionAppearTimeout;
    delete props.component;

    return React.createElement(this.props.component, props, childrenToRender);
  };

  return ReactTransitionGroup;
}(React.Component);

ReactTransitionGroup.displayName = 'ReactTransitionGroup';
ReactTransitionGroup.propTypes = {
...
```

#### <a name="apidoc.element.react.ReactElement.createFactory"></a>[function <span class="apidocSignatureSpan">react.ReactElement.</span>createFactory (type)](#apidoc.element.react.ReactElement.createFactory)
- description and source-code
```javascript
createFactory = function (type) {
  var factory = ReactElement.createElement.bind(null, type);
  // Expose the type on the factory and the prototype so that it can be
  // easily accessed on elements. E.g. '<Foo />.type === Foo'.
  // This should not be named 'constructor' since this may not be the function
  // that created the element, and it may not even be a constructor.
  // Legacy hook TODO: Warn if this is accessed
  factory.type = type;
  return factory;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactElement.isValidElement"></a>[function <span class="apidocSignatureSpan">react.ReactElement.</span>isValidElement (object)](#apidoc.element.react.ReactElement.isValidElement)
- description and source-code
```javascript
isValidElement = function (object) {
  return typeof object === 'object' && object !== null && object.$$typeof === REACT_ELEMENT_TYPE;
}
```
- example usage
```shell
...
    context = bookKeeping.context;


var mappedChild = func.call(context, child, bookKeeping.count++);
if (Array.isArray(mappedChild)) {
  mapIntoWithKeyPrefixInternal(mappedChild, result, childKey, emptyFunction.thatReturnsArgument);
} else if (mappedChild != null) {
  if (ReactElement.isValidElement(mappedChild)) {
    mappedChild = ReactElement.cloneAndReplaceKey(mappedChild,
    // Keep both the (mapped) and old keys if they differ, just as
    // traverseAllChildren used to do for objects as children
    keyPrefix + (mappedChild.key && (!child || child.key !== mappedChild.key) ? escapeUserProvidedKey(mappedChild.key) + '/' : '') +
childKey);
  }
  result.push(mappedChild);
}
...
```



# <a name="apidoc.module.react.ReactElementValidator"></a>[module react.ReactElementValidator](#apidoc.module.react.ReactElementValidator)

#### <a name="apidoc.element.react.ReactElementValidator.cloneElement"></a>[function <span class="apidocSignatureSpan">react.ReactElementValidator.</span>cloneElement (element, props, children)](#apidoc.element.react.ReactElementValidator.cloneElement)
- description and source-code
```javascript
cloneElement = function (element, props, children) {
  var newElement = ReactElement.cloneElement.apply(this, arguments);
  for (var i = 2; i < arguments.length; i++) {
    validateChildKeys(arguments[i], newElement.type);
  }
  validatePropTypes(newElement);
  return newElement;
}
```
- example usage
```shell
...
  var child = this.state.children[key];
  if (child) {
    // You may need to apply reactive updates to a child as it is leaving.
    // The normal React way to do it won't work since the child will have
    // already been removed. In case you need this behavior you can provide
    // a childFactory function to wrap every child, even the ones that are
    // leaving.
    childrenToRender.push(React.cloneElement(this.props.childFactory(child), { ref: key, key: key }));
  }
}

// Do not forward ReactTransitionGroup props to primitive DOM nodes
var props = _assign({}, this.props);
delete props.transitionLeave;
delete props.transitionName;
...
```

#### <a name="apidoc.element.react.ReactElementValidator.createElement"></a>[function <span class="apidocSignatureSpan">react.ReactElementValidator.</span>createElement (type, props, children)](#apidoc.element.react.ReactElementValidator.createElement)
- description and source-code
```javascript
createElement = function (type, props, children) {
  var validType = typeof type === 'string' || typeof type === 'function';
  // We warn in this case but don't throw. We expect the element creation to
  // succeed and there will likely be errors in render.
  if (!validType) {
    if (typeof type !== 'function' && typeof type !== 'string') {
      var info = '';
      if (type === undefined || typeof type === 'object' && type !== null && Object.keys(type).length === 0) {
        info += ' You likely forgot to export your component from the file ' + 'it\'s defined in.';
      }
      info += getDeclarationErrorAddendum();
      process.env.NODE_ENV !== 'production' ? warning(false, 'React.createElement: type is invalid -- expected a string (for ' + '
built-in components) or a class/function (for composite ' + 'components) but got: %s.%s', type == null ? type : typeof type, info
) : void 0;
    }
  }

  var element = ReactElement.createElement.apply(this, arguments);

  // The result can be nullish if a mock or a custom function is used.
  // TODO: Drop this when these are no longer allowed as the type argument.
  if (element == null) {
    return element;
  }

  // Skip key warning if the type isn't valid since our key validation logic
  // doesn't expect a non-string/function type and can throw confusing errors.
  // We don't want exception behavior to differ between dev and prod.
  // (Rendering will throw with a helpful message and as soon as the type is
  // fixed, the key warnings will appear.)
  if (validType) {
    for (var i = 2; i < arguments.length; i++) {
      validateChildKeys(arguments[i], type);
    }
  }

  validatePropTypes(element);

  return element;
}
```
- example usage
```shell
...
    delete props.transitionEnter;
    delete props.childFactory;
    delete props.transitionLeaveTimeout;
    delete props.transitionEnterTimeout;
    delete props.transitionAppearTimeout;
    delete props.component;

    return React.createElement(this.props.component, props, childrenToRender);
  };

  return ReactTransitionGroup;
}(React.Component);

ReactTransitionGroup.displayName = 'ReactTransitionGroup';
ReactTransitionGroup.propTypes = {
...
```

#### <a name="apidoc.element.react.ReactElementValidator.createFactory"></a>[function <span class="apidocSignatureSpan">react.ReactElementValidator.</span>createFactory (type)](#apidoc.element.react.ReactElementValidator.createFactory)
- description and source-code
```javascript
createFactory = function (type) {
  var validatedFactory = ReactElementValidator.createElement.bind(null, type);
  // Legacy hook TODO: Warn if this is accessed
  validatedFactory.type = type;

  if (process.env.NODE_ENV !== 'production') {
    if (canDefineProperty) {
      Object.defineProperty(validatedFactory, 'type', {
        enumerable: false,
        get: function () {
          process.env.NODE_ENV !== 'production' ? warning(false, 'Factory.type is deprecated. Access the class directly ' + 'before
 passing it to createFactory.') : void 0;
          Object.defineProperty(this, 'type', {
            value: type
          });
          return type;
        }
      });
    }
  }

  return validatedFactory;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react.ReactFragment"></a>[module react.ReactFragment](#apidoc.module.react.ReactFragment)

#### <a name="apidoc.element.react.ReactFragment.create"></a>[function <span class="apidocSignatureSpan">react.ReactFragment.</span>create (object)](#apidoc.element.react.ReactFragment.create)
- description and source-code
```javascript
create = function (object) {
  if (typeof object !== 'object' || !object || Array.isArray(object)) {
    process.env.NODE_ENV !== 'production' ? warning(false, 'React.addons.createFragment only accepts a single object. Got: %s',
object) : void 0;
    return object;
  }
  if (ReactElement.isValidElement(object)) {
    process.env.NODE_ENV !== 'production' ? warning(false, 'React.addons.createFragment does not accept a ReactElement ' + 'without
 a wrapper object.') : void 0;
    return object;
  }

  !(object.nodeType !== 1) ? process.env.NODE_ENV !== 'production' ? invariant(false, 'React.addons.createFragment(...): Encountered
 an invalid child; DOM elements are not valid children of React components.') : _prodInvariant('0') : void 0;

  var result = [];

  for (var key in object) {
    if (process.env.NODE_ENV !== 'production') {
      if (!warnedAboutNumeric && numericPropertyRegex.test(key)) {
        process.env.NODE_ENV !== 'production' ? warning(false, 'React.addons.createFragment(...): Child objects should have ' + '
non-numeric keys so ordering is preserved.') : void 0;
        warnedAboutNumeric = true;
      }
    }
    ReactChildren.mapIntoWithKeyPrefixInternal(object[key], result, key, emptyFunction.thatReturnsArgument);
  }

  return result;
}
```
- example usage
```shell
...

var _assign = require('object-assign');

function _classCallCheck(instance, Constructor) { if (!(instance instanceof Constructor)) { throw new TypeError("Cannot call a class
 as a function"); } }

function _possibleConstructorReturn(self, call) { if (!self) { throw new ReferenceError("this hasn't been initialised - super()
hasn't been called"); } return call && (typeof call === "object" || typeof call === "function") ? call : self; }

function _inherits(subClass, superClass) { if (typeof superClass !== "function" && superClass !== null) { throw new TypeError("Super
 expression must either be null or a function, not " + typeof superClass); } subClass.prototype = Object.create(superClass && superClass
.prototype, { constructor: { value: subClass, enumerable: false, writable: true, configurable: true } }); if (superClass) Object
.setPrototypeOf ? Object.setPrototypeOf(subClass, superClass) : subClass.__proto__ = superClass; }

var React = require('./React');
var ReactTransitionChildMapping = require('./ReactTransitionChildMapping');

var emptyFunction = require('fbjs/lib/emptyFunction');

/**
...
```



# <a name="apidoc.module.react.ReactNoopUpdateQueue"></a>[module react.ReactNoopUpdateQueue](#apidoc.module.react.ReactNoopUpdateQueue)

#### <a name="apidoc.element.react.ReactNoopUpdateQueue.enqueueCallback"></a>[function <span class="apidocSignatureSpan">react.ReactNoopUpdateQueue.</span>enqueueCallback (publicInstance, callback)](#apidoc.element.react.ReactNoopUpdateQueue.enqueueCallback)
- description and source-code
```javascript
enqueueCallback = function (publicInstance, callback) {}
```
- example usage
```shell
...
/**
 * TODO: This will be deprecated because state should always keep a consistent
 * type signature and the only use case for this, is to avoid that.
 */
replaceState: function (newState, callback) {
  this.updater.enqueueReplaceState(this, newState);
  if (callback) {
    this.updater.enqueueCallback(this, callback, 'replaceState');
  }
},

/**
 * Checks whether or not this composite component is mounted.
 * @return {boolean} True if mounted, false otherwise.
 * @protected
...
```

#### <a name="apidoc.element.react.ReactNoopUpdateQueue.enqueueForceUpdate"></a>[function <span class="apidocSignatureSpan">react.ReactNoopUpdateQueue.</span>enqueueForceUpdate (publicInstance)](#apidoc.element.react.ReactNoopUpdateQueue.enqueueForceUpdate)
- description and source-code
```javascript
enqueueForceUpdate = function (publicInstance) {
  warnNoop(publicInstance, 'forceUpdate');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactNoopUpdateQueue.enqueueReplaceState"></a>[function <span class="apidocSignatureSpan">react.ReactNoopUpdateQueue.</span>enqueueReplaceState (publicInstance, completeState)](#apidoc.element.react.ReactNoopUpdateQueue.enqueueReplaceState)
- description and source-code
```javascript
enqueueReplaceState = function (publicInstance, completeState) {
  warnNoop(publicInstance, 'replaceState');
}
```
- example usage
```shell
...
var ReactClassMixin = {

/**
 * TODO: This will be deprecated because state should always keep a consistent
 * type signature and the only use case for this, is to avoid that.
 */
replaceState: function (newState, callback) {
  this.updater.enqueueReplaceState(this, newState);
  if (callback) {
    this.updater.enqueueCallback(this, callback, 'replaceState');
  }
},

/**
 * Checks whether or not this composite component is mounted.
...
```

#### <a name="apidoc.element.react.ReactNoopUpdateQueue.enqueueSetState"></a>[function <span class="apidocSignatureSpan">react.ReactNoopUpdateQueue.</span>enqueueSetState (publicInstance, partialState)](#apidoc.element.react.ReactNoopUpdateQueue.enqueueSetState)
- description and source-code
```javascript
enqueueSetState = function (publicInstance, partialState) {
  warnNoop(publicInstance, 'setState');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactNoopUpdateQueue.isMounted"></a>[function <span class="apidocSignatureSpan">react.ReactNoopUpdateQueue.</span>isMounted (publicInstance)](#apidoc.element.react.ReactNoopUpdateQueue.isMounted)
- description and source-code
```javascript
isMounted = function (publicInstance) {
  return false;
}
```
- example usage
```shell
...
  /**
   * Checks whether or not this composite component is mounted.
   * @return {boolean} True if mounted, false otherwise.
   * @protected
   * @final
   */
  isMounted: function () {
    return this.updater.isMounted(this);
  }
};

var ReactClassComponent = function () {};
_assign(ReactClassComponent.prototype, ReactComponent.prototype, ReactClassMixin);

/**
...
```



# <a name="apidoc.module.react.ReactStateSetters"></a>[module react.ReactStateSetters](#apidoc.module.react.ReactStateSetters)

#### <a name="apidoc.element.react.ReactStateSetters.createStateKeySetter"></a>[function <span class="apidocSignatureSpan">react.ReactStateSetters.</span>createStateKeySetter (component, key)](#apidoc.element.react.ReactStateSetters.createStateKeySetter)
- description and source-code
```javascript
createStateKeySetter = function (component, key) {
  // Memoize the setters.
  var cache = component.__keySetters || (component.__keySetters = {});
  return cache[key] || (cache[key] = createStateKeySetter(component, key));
}
```
- example usage
```shell
...
   * ReactLink will have the current value of this.state[key] and will call
   * setState() when a change is requested.
   *
   * @param {string} key state key to update.
   * @return {ReactLink} ReactLink instance linking to the state.
   */
  linkState: function (key) {
    return new ReactLink(this.state[key], ReactStateSetters.createStateKeySetter(this, key));
  }
};

module.exports = LinkedStateMixin;
...
```

#### <a name="apidoc.element.react.ReactStateSetters.createStateSetter"></a>[function <span class="apidocSignatureSpan">react.ReactStateSetters.</span>createStateSetter (component, funcReturningState)](#apidoc.element.react.ReactStateSetters.createStateSetter)
- description and source-code
```javascript
createStateSetter = function (component, funcReturningState) {
  return function (a, b, c, d, e, f) {
    var partialState = funcReturningState.call(component, a, b, c, d, e, f);
    if (partialState) {
      component.setState(partialState);
    }
  };
}
```
- example usage
```shell
...
  /**
* Returns a function that calls the provided function, and uses the result
* of that to set the component's state.
*
* For example, these statements are equivalent:
*
*   this.setState({x: 1});
*   this.createStateSetter(function(xValue) {
*     return {x: xValue};
*   })(1);
*
* @param {function} funcReturningState Returned callback uses this to
*                                      determine how to update state.
* @return {function} callback that when invoked uses funcReturningState to
*                    determined the object literal to setState.
...
```



# <a name="apidoc.module.react.ReactTransitionChildMapping"></a>[module react.ReactTransitionChildMapping](#apidoc.module.react.ReactTransitionChildMapping)

#### <a name="apidoc.element.react.ReactTransitionChildMapping.getChildMapping"></a>[function <span class="apidocSignatureSpan">react.ReactTransitionChildMapping.</span>getChildMapping (children, selfDebugID)](#apidoc.element.react.ReactTransitionChildMapping.getChildMapping)
- description and source-code
```javascript
getChildMapping = function (children, selfDebugID) {
  if (!children) {
    return children;
  }

  if (process.env.NODE_ENV !== 'production') {
    return flattenChildren(children, selfDebugID);
  }

  return flattenChildren(children);
}
```
- example usage
```shell
...
 * and a new set of keys and merges them with its best guess of the correct
 * ordering. In the future we may expose some of the utilities in
 * ReactMultiChild to make this easy, but for now React itself does not
 * directly have this concept of the union of prevChildren and nextChildren
 * so we implement it here.
 *
 * @param {object} prev prev children as returned from
 * 'ReactTransitionChildMapping.getChildMapping()'.
 * @param {object} next next children as returned from
 * 'ReactTransitionChildMapping.getChildMapping()'.
 * @return {object} a key set that contains all keys in 'prev' and all keys
 * in 'next' in a reasonable order.
 */
mergeChildMappings: function (prev, next) {
  prev = prev || {};
...
```

#### <a name="apidoc.element.react.ReactTransitionChildMapping.mergeChildMappings"></a>[function <span class="apidocSignatureSpan">react.ReactTransitionChildMapping.</span>mergeChildMappings (prev, next)](#apidoc.element.react.ReactTransitionChildMapping.mergeChildMappings)
- description and source-code
```javascript
mergeChildMappings = function (prev, next) {
  prev = prev || {};
  next = next || {};

  function getValueForKey(key) {
    if (next.hasOwnProperty(key)) {
      return next[key];
    } else {
      return prev[key];
    }
  }

  // For each key of 'next', the list of keys to insert before that key in
  // the combined list
  var nextKeysPending = {};

  var pendingKeys = [];
  for (var prevKey in prev) {
    if (next.hasOwnProperty(prevKey)) {
      if (pendingKeys.length) {
        nextKeysPending[prevKey] = pendingKeys;
        pendingKeys = [];
      }
    } else {
      pendingKeys.push(prevKey);
    }
  }

  var i;
  var childMapping = {};
  for (var nextKey in next) {
    if (nextKeysPending.hasOwnProperty(nextKey)) {
      for (i = 0; i < nextKeysPending[nextKey].length; i++) {
        var pendingNextKey = nextKeysPending[nextKey][i];
        childMapping[nextKeysPending[nextKey][i]] = getValueForKey(pendingNextKey);
      }
    }
    childMapping[nextKey] = getValueForKey(nextKey);
  }

  // Finally, add the keys which didn't appear before any key in 'next'
  for (i = 0; i < pendingKeys.length; i++) {
    childMapping[pendingKeys[i]] = getValueForKey(pendingKeys[i]);
  }

  return childMapping;
}
```
- example usage
```shell
...
  };

  ReactTransitionGroup.prototype.componentWillReceiveProps = function componentWillReceiveProps(nextProps) {
var nextChildMapping = ReactTransitionChildMapping.getChildMapping(nextProps.children);
var prevChildMapping = this.state.children;

this.setState({
  children: ReactTransitionChildMapping.mergeChildMappings(prevChildMapping, nextChildMapping)
});

var key;

for (key in nextChildMapping) {
  var hasPrev = prevChildMapping && prevChildMapping.hasOwnProperty(key);
  if (nextChildMapping[key] && !hasPrev && !this.currentlyTransitioningKeys[key]) {
...
```



# <a name="apidoc.module.react.ReactTransitionGroup"></a>[module react.ReactTransitionGroup](#apidoc.module.react.ReactTransitionGroup)

#### <a name="apidoc.element.react.ReactTransitionGroup.ReactTransitionGroup"></a>[function <span class="apidocSignatureSpan">react.</span>ReactTransitionGroup ()](#apidoc.element.react.ReactTransitionGroup.ReactTransitionGroup)
- description and source-code
```javascript
function ReactTransitionGroup() {
  var _temp, _this, _ret;

  _classCallCheck(this, ReactTransitionGroup);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = _possibleConstructorReturn(this, _React$Component.call.apply(_React$Component, [this].concat(args
))), _this), _this.state = {
    // TODO: can we get useful debug information to show at this point?
    children: ReactTransitionChildMapping.getChildMapping(_this.props.children)
  }, _this.performAppear = function (key) {
    _this.currentlyTransitioningKeys[key] = true;

    var component = _this.refs[key];

    if (component.componentWillAppear) {
      component.componentWillAppear(_this._handleDoneAppearing.bind(_this, key));
    } else {
      _this._handleDoneAppearing(key);
    }
  }, _this._handleDoneAppearing = function (key) {
    var component = _this.refs[key];
    if (component.componentDidAppear) {
      component.componentDidAppear();
    }

    delete _this.currentlyTransitioningKeys[key];

    var currentChildMapping = ReactTransitionChildMapping.getChildMapping(_this.props.children);

    if (!currentChildMapping || !currentChildMapping.hasOwnProperty(key)) {
      // This was removed before it had fully appeared. Remove it.
      _this.performLeave(key);
    }
  }, _this.performEnter = function (key) {
    _this.currentlyTransitioningKeys[key] = true;

    var component = _this.refs[key];

    if (component.componentWillEnter) {
      component.componentWillEnter(_this._handleDoneEntering.bind(_this, key));
    } else {
      _this._handleDoneEntering(key);
    }
  }, _this._handleDoneEntering = function (key) {
    var component = _this.refs[key];
    if (component.componentDidEnter) {
      component.componentDidEnter();
    }

    delete _this.currentlyTransitioningKeys[key];

    var currentChildMapping = ReactTransitionChildMapping.getChildMapping(_this.props.children);

    if (!currentChildMapping || !currentChildMapping.hasOwnProperty(key)) {
      // This was removed before it had fully entered. Remove it.
      _this.performLeave(key);
    }
  }, _this.performLeave = function (key) {
    _this.currentlyTransitioningKeys[key] = true;

    var component = _this.refs[key];
    if (component.componentWillLeave) {
      component.componentWillLeave(_this._handleDoneLeaving.bind(_this, key));
    } else {
      // Note that this is somewhat dangerous b/c it calls setState()
      // again, effectively mutating the component before all the work
      // is done.
      _this._handleDoneLeaving(key);
    }
  }, _this._handleDoneLeaving = function (key) {
    var component = _this.refs[key];

    if (component.componentDidLeave) {
      component.componentDidLeave();
    }

    delete _this.currentlyTransitioningKeys[key];

    var currentChildMapping = ReactTransitionChildMapping.getChildMapping(_this.props.children);

    if (currentChildMapping && currentChildMapping.hasOwnProperty(key)) {
      // This entered again before it fully left. Add it again.
      _this.performEnter(key);
    } else {
      _this.setState(function (state) {
        var newChildren = _assign({}, state.children);
        delete newChildren[key];
        return { children: newChildren };
      });
    }
  }, _temp), _possibleConstructorReturn(_this, _ret);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react.ReactTransitionGroup.prototype"></a>[module react.ReactTransitionGroup.prototype](#apidoc.module.react.ReactTransitionGroup.prototype)

#### <a name="apidoc.element.react.ReactTransitionGroup.prototype.componentDidMount"></a>[function <span class="apidocSignatureSpan">react.ReactTransitionGroup.prototype.</span>componentDidMount ()](#apidoc.element.react.ReactTransitionGroup.prototype.componentDidMount)
- description and source-code
```javascript
function componentDidMount() {
  var initialChildMapping = this.state.children;
  for (var key in initialChildMapping) {
    if (initialChildMapping[key]) {
      this.performAppear(key);
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactTransitionGroup.prototype.componentDidUpdate"></a>[function <span class="apidocSignatureSpan">react.ReactTransitionGroup.prototype.</span>componentDidUpdate ()](#apidoc.element.react.ReactTransitionGroup.prototype.componentDidUpdate)
- description and source-code
```javascript
function componentDidUpdate() {
  var keysToEnter = this.keysToEnter;
  this.keysToEnter = [];
  keysToEnter.forEach(this.performEnter);

  var keysToLeave = this.keysToLeave;
  this.keysToLeave = [];
  keysToLeave.forEach(this.performLeave);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactTransitionGroup.prototype.componentWillMount"></a>[function <span class="apidocSignatureSpan">react.ReactTransitionGroup.prototype.</span>componentWillMount ()](#apidoc.element.react.ReactTransitionGroup.prototype.componentWillMount)
- description and source-code
```javascript
function componentWillMount() {
  this.currentlyTransitioningKeys = {};
  this.keysToEnter = [];
  this.keysToLeave = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactTransitionGroup.prototype.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">react.ReactTransitionGroup.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.react.ReactTransitionGroup.prototype.componentWillReceiveProps)
- description and source-code
```javascript
function componentWillReceiveProps(nextProps) {
  var nextChildMapping = ReactTransitionChildMapping.getChildMapping(nextProps.children);
  var prevChildMapping = this.state.children;

  this.setState({
    children: ReactTransitionChildMapping.mergeChildMappings(prevChildMapping, nextChildMapping)
  });

  var key;

  for (key in nextChildMapping) {
    var hasPrev = prevChildMapping && prevChildMapping.hasOwnProperty(key);
    if (nextChildMapping[key] && !hasPrev && !this.currentlyTransitioningKeys[key]) {
      this.keysToEnter.push(key);
    }
  }

  for (key in prevChildMapping) {
    var hasNext = nextChildMapping && nextChildMapping.hasOwnProperty(key);
    if (prevChildMapping[key] && !hasNext && !this.currentlyTransitioningKeys[key]) {
      this.keysToLeave.push(key);
    }
  }

  // If we want to someday check for reordering, we could do it here.
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactTransitionGroup.prototype.render"></a>[function <span class="apidocSignatureSpan">react.ReactTransitionGroup.prototype.</span>render ()](#apidoc.element.react.ReactTransitionGroup.prototype.render)
- description and source-code
```javascript
function render() {
  // TODO: we could get rid of the need for the wrapper node
  // by cloning a single child
  var childrenToRender = [];
  for (var key in this.state.children) {
    var child = this.state.children[key];
    if (child) {
      // You may need to apply reactive updates to a child as it is leaving.
      // The normal React way to do it won't work since the child will have
      // already been removed. In case you need this behavior you can provide
      // a childFactory function to wrap every child, even the ones that are
      // leaving.
      childrenToRender.push(React.cloneElement(this.props.childFactory(child), { ref: key, key: key }));
    }
  }

  // Do not forward ReactTransitionGroup props to primitive DOM nodes
  var props = _assign({}, this.props);
  delete props.transitionLeave;
  delete props.transitionName;
  delete props.transitionAppear;
  delete props.transitionEnter;
  delete props.childFactory;
  delete props.transitionLeaveTimeout;
  delete props.transitionEnterTimeout;
  delete props.transitionAppearTimeout;
  delete props.component;

  return React.createElement(this.props.component, props, childrenToRender);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react.ReactUMDEntry"></a>[module react.ReactUMDEntry](#apidoc.module.react.ReactUMDEntry)

#### <a name="apidoc.element.react.ReactUMDEntry.Component"></a>[function <span class="apidocSignatureSpan">react.ReactUMDEntry.</span>Component (props, context, updater)](#apidoc.element.react.ReactUMDEntry.Component)
- description and source-code
```javascript
function ReactComponent(props, context, updater) {
  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  // We initialize the default updater but the real one gets injected by the
  // renderer.
  this.updater = updater || ReactNoopUpdateQueue;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactUMDEntry.PureComponent"></a>[function <span class="apidocSignatureSpan">react.ReactUMDEntry.</span>PureComponent (props, context, updater)](#apidoc.element.react.ReactUMDEntry.PureComponent)
- description and source-code
```javascript
function ReactPureComponent(props, context, updater) {
  // Duplicated from ReactComponent.
  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  // We initialize the default updater but the real one gets injected by the
  // renderer.
  this.updater = updater || ReactNoopUpdateQueue;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactUMDEntry.__spread"></a>[function <span class="apidocSignatureSpan">react.ReactUMDEntry.</span>__spread ()](#apidoc.element.react.ReactUMDEntry.__spread)
- description and source-code
```javascript
__spread = function () {
  process.env.NODE_ENV !== 'production' ? warning(warned, 'React.__spread is deprecated and should not be used. Use ' + 'Object.
assign directly or another helper function with similar ' + 'semantics. You may be seeing this warning due to your compiler. ' + '
See https://fb.me/react-spread-deprecation for more details.') : void 0;
  warned = true;
  return _assign.apply(null, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactUMDEntry.cloneElement"></a>[function <span class="apidocSignatureSpan">react.ReactUMDEntry.</span>cloneElement (element, props, children)](#apidoc.element.react.ReactUMDEntry.cloneElement)
- description and source-code
```javascript
cloneElement = function (element, props, children) {
  var newElement = ReactElement.cloneElement.apply(this, arguments);
  for (var i = 2; i < arguments.length; i++) {
    validateChildKeys(arguments[i], newElement.type);
  }
  validatePropTypes(newElement);
  return newElement;
}
```
- example usage
```shell
...
  var child = this.state.children[key];
  if (child) {
    // You may need to apply reactive updates to a child as it is leaving.
    // The normal React way to do it won't work since the child will have
    // already been removed. In case you need this behavior you can provide
    // a childFactory function to wrap every child, even the ones that are
    // leaving.
    childrenToRender.push(React.cloneElement(this.props.childFactory(child), { ref: key, key: key }));
  }
}

// Do not forward ReactTransitionGroup props to primitive DOM nodes
var props = _assign({}, this.props);
delete props.transitionLeave;
delete props.transitionName;
...
```

#### <a name="apidoc.element.react.ReactUMDEntry.createClass"></a>[function <span class="apidocSignatureSpan">react.ReactUMDEntry.</span>createClass (spec)](#apidoc.element.react.ReactUMDEntry.createClass)
- description and source-code
```javascript
createClass = function (spec) {
  // To keep our warnings more understandable, we'll use a little hack here to
  // ensure that Constructor.name !== 'Constructor'. This makes sure we don't
  // unnecessarily identify a class without displayName as 'Constructor'.
  var Constructor = identity(function (props, context, updater) {
    // This constructor gets overridden by mocks. The argument is used
    // by mocks to assert on what gets mounted.

    if (process.env.NODE_ENV !== 'production') {
      process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : void 0;
    }

    // Wire up auto-binding
    if (this.__reactAutoBindPairs.length) {
      bindAutoBindMethods(this);
    }

    this.props = props;
    this.context = context;
    this.refs = emptyObject;
    this.updater = updater || ReactNoopUpdateQueue;

    this.state = null;

    // ReactClasses doesn't have constructors. Instead, they use the
    // getInitialState and componentWillMount methods for initialization.

    var initialState = this.getInitialState ? this.getInitialState() : null;
    if (process.env.NODE_ENV !== 'production') {
      // We allow auto-mocks to proceed as if they're returning null.
      if (initialState === undefined && this.getInitialState._isMockFunction) {
        // This is probably bad practice. Consider warning here and
        // deprecating this convenience.
        initialState = null;
      }
    }
    !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false
, '%s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : _prodInvariant('
82', Constructor.displayName || 'ReactCompositeComponent') : void 0;

    this.state = initialState;
  });
  Constructor.prototype = new ReactClassComponent();
  Constructor.prototype.constructor = Constructor;
  Constructor.prototype.__reactAutoBindPairs = [];

  injectedMixins.forEach(mixSpecIntoComponent.bind(null, Constructor));

  mixSpecIntoComponent(Constructor, spec);

  // Initialize the defaultProps property after all mixins have been merged.
  if (Constructor.getDefaultProps) {
    Constructor.defaultProps = Constructor.getDefaultProps();
  }

  if (process.env.NODE_ENV !== 'production') {
    // This is a tag to indicate that the use of these method names is ok,
    // since it's used with createClass. If it's not, then it's likely a
    // mistake so we'll warn you to use the static property, property
    // initializer or constructor respectively.
    if (Constructor.getDefaultProps) {
      Constructor.getDefaultProps.isReactClassApproved = {};
    }
    if (Constructor.prototype.getInitialState) {
      Constructor.prototype.getInitialState.isReactClassApproved = {};
    }
  }

  !Constructor.prototype.render ? process.env.NODE_ENV !== 'production' ? invariant(false, 'createClass(...): Class specification
 must implement a 'render' method.') : _prodInvariant('83') : void 0;

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(!Constructor.prototype.componentShouldUpdate, '%s has a method called ' + 'componentShouldUpdate
(). Did you mean shouldComponentUpdate()? ' + 'The name is phrased as a question because the function is ' + 'expected to return
 a value.', spec.displayName || 'A component') : void 0;
    process.env.NODE_ENV !== 'production' ? warning(!Constructor.prototype.componentWillRecieveProps, '%s has a method called ' + '
componentWillRecieveProps(). Did you mean componentWillReceiveProps()?', spec.displayName || 'A component') : void 0;
  }

  // Reduce time spent doing lookups by setting these on the prototype.
  for (var methodName in ReactClassInterface) {
    if (!Constructor.prototype[methodName]) {
      Constructor.prototype[methodName] = null;
    }
  }

  return Constructor;
}
```
- example usage
```shell
...
* Composite components are higher-level components that compose other composite
* or host components.
*
* To create a new type of 'ReactClass', pass a specification of
* your new class to 'React.createClass'. The only requirement of your class
* specification is that you implement a 'render' method.
*
*   var MyComponent = React.createClass({
*     render: function() {
*       return <div>Hello World</div>;
*     }
*   });
*
* The class specification supports a specific protocol of methods that have
* special meaning (e.g. 'render'). See 'ReactClassInterface' for
...
```

#### <a name="apidoc.element.react.ReactUMDEntry.createElement"></a>[function <span class="apidocSignatureSpan">react.ReactUMDEntry.</span>createElement (type, props, children)](#apidoc.element.react.ReactUMDEntry.createElement)
- description and source-code
```javascript
createElement = function (type, props, children) {
  var validType = typeof type === 'string' || typeof type === 'function';
  // We warn in this case but don't throw. We expect the element creation to
  // succeed and there will likely be errors in render.
  if (!validType) {
    if (typeof type !== 'function' && typeof type !== 'string') {
      var info = '';
      if (type === undefined || typeof type === 'object' && type !== null && Object.keys(type).length === 0) {
        info += ' You likely forgot to export your component from the file ' + 'it\'s defined in.';
      }
      info += getDeclarationErrorAddendum();
      process.env.NODE_ENV !== 'production' ? warning(false, 'React.createElement: type is invalid -- expected a string (for ' + '
built-in components) or a class/function (for composite ' + 'components) but got: %s.%s', type == null ? type : typeof type, info
) : void 0;
    }
  }

  var element = ReactElement.createElement.apply(this, arguments);

  // The result can be nullish if a mock or a custom function is used.
  // TODO: Drop this when these are no longer allowed as the type argument.
  if (element == null) {
    return element;
  }

  // Skip key warning if the type isn't valid since our key validation logic
  // doesn't expect a non-string/function type and can throw confusing errors.
  // We don't want exception behavior to differ between dev and prod.
  // (Rendering will throw with a helpful message and as soon as the type is
  // fixed, the key warnings will appear.)
  if (validType) {
    for (var i = 2; i < arguments.length; i++) {
      validateChildKeys(arguments[i], type);
    }
  }

  validatePropTypes(element);

  return element;
}
```
- example usage
```shell
...
    delete props.transitionEnter;
    delete props.childFactory;
    delete props.transitionLeaveTimeout;
    delete props.transitionEnterTimeout;
    delete props.transitionAppearTimeout;
    delete props.component;

    return React.createElement(this.props.component, props, childrenToRender);
  };

  return ReactTransitionGroup;
}(React.Component);

ReactTransitionGroup.displayName = 'ReactTransitionGroup';
ReactTransitionGroup.propTypes = {
...
```

#### <a name="apidoc.element.react.ReactUMDEntry.createFactory"></a>[function <span class="apidocSignatureSpan">react.ReactUMDEntry.</span>createFactory (type)](#apidoc.element.react.ReactUMDEntry.createFactory)
- description and source-code
```javascript
createFactory = function (type) {
  var validatedFactory = ReactElementValidator.createElement.bind(null, type);
  // Legacy hook TODO: Warn if this is accessed
  validatedFactory.type = type;

  if (process.env.NODE_ENV !== 'production') {
    if (canDefineProperty) {
      Object.defineProperty(validatedFactory, 'type', {
        enumerable: false,
        get: function () {
          process.env.NODE_ENV !== 'production' ? warning(false, 'Factory.type is deprecated. Access the class directly ' + 'before
 passing it to createFactory.') : void 0;
          Object.defineProperty(this, 'type', {
            value: type
          });
          return type;
        }
      });
    }
  }

  return validatedFactory;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactUMDEntry.createMixin"></a>[function <span class="apidocSignatureSpan">react.ReactUMDEntry.</span>createMixin (mixin)](#apidoc.element.react.ReactUMDEntry.createMixin)
- description and source-code
```javascript
createMixin = function (mixin) {
  // Currently a noop. Will be used to validate and trace mixins.
  return mixin;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react.ReactUMDEntry.isValidElement"></a>[function <span class="apidocSignatureSpan">react.ReactUMDEntry.</span>isValidElement (object)](#apidoc.element.react.ReactUMDEntry.isValidElement)
- description and source-code
```javascript
isValidElement = function (object) {
  return typeof object === 'object' && object !== null && object.$$typeof === REACT_ELEMENT_TYPE;
}
```
- example usage
```shell
...
    context = bookKeeping.context;


var mappedChild = func.call(context, child, bookKeeping.count++);
if (Array.isArray(mappedChild)) {
  mapIntoWithKeyPrefixInternal(mappedChild, result, childKey, emptyFunction.thatReturnsArgument);
} else if (mappedChild != null) {
  if (ReactElement.isValidElement(mappedChild)) {
    mappedChild = ReactElement.cloneAndReplaceKey(mappedChild,
    // Keep both the (mapped) and old keys if they differ, just as
    // traverseAllChildren used to do for objects as children
    keyPrefix + (mappedChild.key && (!child || child.key !== mappedChild.key) ? escapeUserProvidedKey(mappedChild.key) + '/' : '') +
childKey);
  }
  result.push(mappedChild);
}
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
