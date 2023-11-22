# npm-cli-6856

## npm@10

```sh
$ npm -v
10.2.4
$ npm ls --all
npm ERR! code ELSPROBLEMS
npm ERR! invalid: react@18.2.0 /home/koooge/go/src/github.com/koooge/npm-cli-6856/node_modules/react
npm ERR! invalid: react-dom@18.2.0 /home/koooge/go/src/github.com/koooge/npm-cli-6856/node_modules/react-dom
npm-cli-6856@1.0.0 /home/koooge/go/src/github.com/koooge/npm-cli-6856
├─┬ react-dom@18.2.0 overridden
│ ├─┬ loose-envify@1.4.0
│ │ └── js-tokens@4.0.0
│ ├── react@18.2.0 deduped
│ └─┬ scheduler@0.23.0
│   └── loose-envify@1.4.0 deduped
├─┬ react-vis@1.12.1 overridden
│ ├─┬ d3-array@3.2.4
│ │ └── internmap@2.0.3
│ ├── d3-collection@1.0.7
│ ├── d3-color@3.1.0
│ ├─┬ d3-contour@4.0.2
│ │ └── d3-array@3.2.4 deduped
│ ├── d3-format@3.1.0
│ ├─┬ d3-geo@3.1.0
│ │ └── d3-array@3.2.4 deduped
│ ├── d3-hexbin@0.2.2
│ ├── d3-hierarchy@3.1.2
│ ├─┬ d3-interpolate@3.0.1
│ │ └── d3-color@3.1.0 deduped
│ ├─┬ d3-sankey@0.12.3
│ │ ├─┬ d3-array@2.12.1
│ │ │ └── internmap@1.0.1
│ │ └─┬ d3-shape@1.3.7
│ │   └── d3-path@1.0.9
│ ├─┬ d3-scale@4.0.2
│ │ ├── d3-array@3.2.4 deduped
│ │ ├── d3-format@3.1.0 deduped
│ │ ├── d3-interpolate@3.0.1 deduped
│ │ ├─┬ d3-time-format@4.1.0
│ │ │ └── d3-time@3.1.0 deduped
│ │ └─┬ d3-time@3.1.0
│ │   └── d3-array@3.2.4 deduped
│ ├─┬ d3-shape@3.2.0
│ │ └── d3-path@3.1.0
│ ├── d3-voronoi@1.1.4
│ ├─┬ deep-equal@1.1.2
│ │ ├─┬ is-arguments@1.1.1
│ │ │ ├─┬ call-bind@1.0.5
│ │ │ │ ├── function-bind@1.1.2
│ │ │ │ ├─┬ get-intrinsic@1.2.2
│ │ │ │ │ ├── function-bind@1.1.2 deduped
│ │ │ │ │ ├── has-proto@1.0.1
│ │ │ │ │ ├── has-symbols@1.0.3 deduped
│ │ │ │ │ └─┬ hasown@2.0.0
│ │ │ │ │   └── function-bind@1.1.2 deduped
│ │ │ │ └─┬ set-function-length@1.1.1
│ │ │ │   ├── define-data-property@1.1.1 deduped
│ │ │ │   ├── get-intrinsic@1.2.2 deduped
│ │ │ │   ├─┬ gopd@1.0.1
│ │ │ │   │ └── get-intrinsic@1.2.2 deduped
│ │ │ │   └── has-property-descriptors@1.0.1 deduped
│ │ │ └─┬ has-tostringtag@1.0.0
│ │ │   └── has-symbols@1.0.3
│ │ ├─┬ is-date-object@1.0.5
│ │ │ └── has-tostringtag@1.0.0 deduped
│ │ ├─┬ is-regex@1.1.4
│ │ │ ├── call-bind@1.0.5 deduped
│ │ │ └── has-tostringtag@1.0.0 deduped
│ │ ├─┬ object-is@1.1.5
│ │ │ ├── call-bind@1.0.5 deduped
│ │ │ └─┬ define-properties@1.2.1
│ │ │   ├─┬ define-data-property@1.1.1
│ │ │   │ ├── get-intrinsic@1.2.2 deduped
│ │ │   │ ├── gopd@1.0.1 deduped
│ │ │   │ └── has-property-descriptors@1.0.1 deduped
│ │ │   ├─┬ has-property-descriptors@1.0.1
│ │ │   │ └── get-intrinsic@1.2.2 deduped
│ │ │   └── object-keys@1.1.1 deduped
│ │ ├── object-keys@1.1.1
│ │ └─┬ regexp.prototype.flags@1.5.1
│ │   ├── call-bind@1.0.5 deduped
│ │   ├── define-properties@1.2.1 deduped
│ │   └─┬ set-function-name@2.0.1
│ │     ├── define-data-property@1.1.1 deduped
│ │     ├── functions-have-names@1.2.3
│ │     └── has-property-descriptors@1.0.1 deduped
│ ├─┬ global@4.4.0
│ │ ├─┬ min-document@2.19.0
│ │ │ └── dom-walk@0.1.2
│ │ └── process@0.11.10
│ ├─┬ prop-types@15.8.1
│ │ ├── loose-envify@1.4.0 deduped
│ │ ├── object-assign@4.1.1
│ │ └── react-is@16.13.1
│ ├── react-dom@18.2.0 deduped invalid: "^16.8.3" from node_modules/react-vis
│ ├─┬ react-motion@0.5.2 overridden
│ │ ├── performance-now@0.2.0
│ │ ├── prop-types@15.8.1 deduped
│ │ ├─┬ raf@3.4.1
│ │ │ └── performance-now@2.1.0
│ │ └── react@18.2.0 deduped invalid: "^16.8.3" from node_modules/react-vis, "^0.14.9 || ^15.3.0 || ^16.0.0" from node_modules/react-motion
│ └── react@18.2.0 deduped invalid: "^16.8.3" from node_modules/react-vis
└─┬ react@18.2.0 invalid: "^16.8.3" from node_modules/react-vis overridden
  └── loose-envify@1.4.0 deduped


npm ERR! A complete log of this run can be found in: /home/koooge/.npm/_logs/2023-11-22T20_36_35_650Z-debug-0.log
```


## npm@8

```sh
$ npm -v
8.19.4
$ npm ls --all
npm-cli-6856@1.0.0 /home/koooge/go/src/github.com/koooge/npm-cli-6856
├─┬ react-dom@18.2.0 overridden
│ ├─┬ loose-envify@1.4.0
│ │ └── js-tokens@4.0.0
│ ├── react@18.2.0 deduped
│ └─┬ scheduler@0.23.0
│   └── loose-envify@1.4.0 deduped
├─┬ react-vis@1.12.1
│ ├─┬ d3-array@3.2.4
│ │ └── internmap@2.0.3
│ ├── d3-collection@1.0.7
│ ├── d3-color@3.1.0
│ ├─┬ d3-contour@4.0.2
│ │ └── d3-array@3.2.4 deduped
│ ├── d3-format@3.1.0
│ ├─┬ d3-geo@3.1.0
│ │ └── d3-array@3.2.4 deduped
│ ├── d3-hexbin@0.2.2
│ ├── d3-hierarchy@3.1.2
│ ├─┬ d3-interpolate@3.0.1
│ │ └── d3-color@3.1.0 deduped
│ ├─┬ d3-sankey@0.12.3
│ │ ├─┬ d3-array@2.12.1
│ │ │ └── internmap@1.0.1
│ │ └─┬ d3-shape@1.3.7
│ │   └── d3-path@1.0.9
│ ├─┬ d3-scale@4.0.2
│ │ ├── d3-array@3.2.4 deduped
│ │ ├── d3-format@3.1.0 deduped
│ │ ├── d3-interpolate@3.0.1 deduped
│ │ ├─┬ d3-time-format@4.1.0
│ │ │ └── d3-time@3.1.0 deduped
│ │ └─┬ d3-time@3.1.0
│ │   └── d3-array@3.2.4 deduped
│ ├─┬ d3-shape@3.2.0
│ │ └── d3-path@3.1.0
│ ├── d3-voronoi@1.1.4
│ ├─┬ deep-equal@1.1.2
│ │ ├─┬ is-arguments@1.1.1
│ │ │ ├─┬ call-bind@1.0.5
│ │ │ │ ├── function-bind@1.1.2
│ │ │ │ ├─┬ get-intrinsic@1.2.2
│ │ │ │ │ ├── function-bind@1.1.2 deduped
│ │ │ │ │ ├── has-proto@1.0.1
│ │ │ │ │ ├── has-symbols@1.0.3 deduped
│ │ │ │ │ └─┬ hasown@2.0.0
│ │ │ │ │   └── function-bind@1.1.2 deduped
│ │ │ │ └─┬ set-function-length@1.1.1
│ │ │ │   ├── define-data-property@1.1.1 deduped
│ │ │ │   ├── get-intrinsic@1.2.2 deduped
│ │ │ │   ├─┬ gopd@1.0.1
│ │ │ │   │ └── get-intrinsic@1.2.2 deduped
│ │ │ │   └── has-property-descriptors@1.0.1 deduped
│ │ │ └─┬ has-tostringtag@1.0.0
│ │ │   └── has-symbols@1.0.3
│ │ ├─┬ is-date-object@1.0.5
│ │ │ └── has-tostringtag@1.0.0 deduped
│ │ ├─┬ is-regex@1.1.4
│ │ │ ├── call-bind@1.0.5 deduped
│ │ │ └── has-tostringtag@1.0.0 deduped
│ │ ├─┬ object-is@1.1.5
│ │ │ ├── call-bind@1.0.5 deduped
│ │ │ └─┬ define-properties@1.2.1
│ │ │   ├─┬ define-data-property@1.1.1
│ │ │   │ ├── get-intrinsic@1.2.2 deduped
│ │ │   │ ├── gopd@1.0.1 deduped
│ │ │   │ └── has-property-descriptors@1.0.1 deduped
│ │ │   ├─┬ has-property-descriptors@1.0.1
│ │ │   │ └── get-intrinsic@1.2.2 deduped
│ │ │   └── object-keys@1.1.1 deduped
│ │ ├── object-keys@1.1.1
│ │ └─┬ regexp.prototype.flags@1.5.1
│ │   ├── call-bind@1.0.5 deduped
│ │   ├── define-properties@1.2.1 deduped
│ │   └─┬ set-function-name@2.0.1
│ │     ├── define-data-property@1.1.1 deduped
│ │     ├── functions-have-names@1.2.3
│ │     └── has-property-descriptors@1.0.1 deduped
│ ├─┬ global@4.4.0
│ │ ├─┬ min-document@2.19.0
│ │ │ └── dom-walk@0.1.2
│ │ └── process@0.11.10
│ ├─┬ prop-types@15.8.1
│ │ ├── loose-envify@1.4.0 deduped
│ │ ├── object-assign@4.1.1
│ │ └── react-is@16.13.1
│ ├── react-dom@18.2.0 deduped
│ ├─┬ react-motion@0.5.2
│ │ ├── performance-now@0.2.0
│ │ ├── prop-types@15.8.1 deduped
│ │ ├─┬ raf@3.4.1
│ │ │ └── performance-now@2.1.0
│ │ └── react@18.2.0 deduped
│ └── react@18.2.0 deduped
└─┬ react@18.2.0 overridden
  └── loose-envify@1.4.0 deduped
```
