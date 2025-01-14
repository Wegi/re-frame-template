## Unreleased

## 1.0.16 (2019-10-15)

#### Changed

- Upgrade re-frame-10x to 0.4.4

## 1.0.15 (2019-10-11)

#### Changed

- Upgrade shadow-cljs to 2.8.62

## 1.0.14 (2019-10-09)

#### Changed

- Upgrade shadow-cljs to 2.8.61

## 1.0.13 (2019-09-27)

#### Changed

- Upgrade shadow-cljs to 2.8.59

## 1.0.12 (2019-09-25)

#### Changed

- Upgrade shadow-cljs to 2.8.58

## 1.0.11 (2019-09-25)

#### Changed

- Upgrade shadow-cljs to 2.8.57

## 1.0.10 (2019-09-24)

#### Changed

- Upgrade shadow-cljs to 2.8.56

## 1.0.9 (2019-09-22)

#### Changed

- Upgrade shadow-cljs to 2.8.55

## 1.0.8 (2019-09-20)

#### Changed

- Upgrade shadow-cljs to 2.8.53
- Upgrade re-com to 2.6.0
- Upgrade re-pressed to 0.3.1

## 1.0.7 (2019-09-11)

#### Changed

- Upgrade re-frame-10x to 0.4.3
- Upgrade lein-garden to 0.3.0

#### Removed

- Empty generated `core.clj` [#93](https://github.com/day8/re-frame-template/pull/93) 
  thanks to @thheller

## 1.0.6 (2019-08-28)

#### Changed

- Upgrade shadow-cljs to 2.8.52
- Upgrade re-frame to 0.10.9
- Upgrade karma to 4.3.0

## 1.0.5 (2019-08-24)

#### Fixed

- 1.0.4 introduced a regression whereby if the +10x profile was not used an
  extra bracket in `shadow-cljs.edn` would cause the build to fail. This is
  fixed in 1.0.5. See [#92](https://github.com/day8/re-frame-template/issues/92).

## 1.0.4 (2019-08-21)

#### Changed

- Greatly simplified shadow-cljs config thanks to @thheller
- Upgrade react-flip-move to 3.0.3. Fixes warning of depedency conflict with re-frame-10x.
- Upgrade karma-chrome-launcher to 3.1.0
- Upgrade to shadow-cljs 2.8.51

#### Fixed

- +cider profile adds -Xmx1G :jvm-opts as a workaround for Emacs cider-jack-in-cljs failure
  thanks to investigation and report by @Quezion

## 1.0.3 (2019-08-18)

#### Fixed

- Don't use unsafe version ranges in package.json

## 1.0.2 (2019-08-16)

#### Changed

- Upgrade shadow-cljs to 2.8.48

## 1.0.1 (2019-08-12)

#### Changed

- Upgrade shadow-cljs to 2.8.45

#### Removed

- Remove +gadfly profile

## 1.0.0 (2019-08-06)

#### Changed

- Migrate to shadow-cljs

## 0.3.23 (2019-07-15)

#### Changed

- Upgrade re-frame to 0.10.8

## 0.3.22 (2019-06-08)

#### Changed

- Upgrade compojure to 1.6.1
- Upgrade garden to 1.3.9
- Upgrade Clojure to 1.10.1
- Upgrade re-com to 2.5.0
- Upgrade re-pressed to 0.3.0
- Upgrade re-frame-10x to 0.4.0
- Upgrade ns-tracker to 0.4.0
- Upgrade re-frisk to 0.5.4.1
- Upgrade ring to 1.7.1
- Upgrade yogthos/config 1.1.2
- Upgrade figwheel-sidecar to 0.5.18
- Upgrade cider/piggieback to 0.4.1

## 0.3.20 (2019-03-12)

#### Fixed

- Ensure that .gitignore is created

## 0.3.19 (2019-03-11)

#### Changed

- Upgrade re-com to 2.4.0

#### Removed

- Transitive dependencies on cljs-time and core.async

## 0.3.18 (2019-03-11)

#### Changed

- Upgrade Clojure to 1.10.0
- Upgrade ClojureScript to 1.10.520
- Upgrade reagent to 0.8.1
- Upgrade re-frame to 0.10.6
