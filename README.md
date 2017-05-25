# javascript-study-guide

## Useful sites
1. https://theintern.github.io
2. SBG developer guide 

## react
1. just a view layer, it is a view linker, it is the tree component
2. virtual DOM (document object model)
3. uses flux (pattern, uni-directional data flow, MVC but better)
4. uni-directional means that: actions -> dispatcher -> store -> view then view go back to actions

## useful react things
1. mount ->fully render tree
2. shallow ->only render one level of the tree(preferred for testing)
3. you can return html without strings in javascript
4. props: parameters= props
class shoppingList{
<h1> list for {this.props.name}}</h1>
}

5. render() returns description
6. below are same thing:
<div className="Shopping">...</div>
is equal to
React.createElement('div',{className:'Shopping'});
7. .slice() copies to new variable--ex. thing=thing2.slice()


## relay
1. relay is a evolution of flux
2. needs to be used with react but react does not need relay

## other things
1. what is grunt?
2. GUI gallery->get UI components, harmony
3. CDN: content delivery network -> allows regional things
4. backend (BE)- it is a service layer which talks to oracle db and rest APIS, consists of plugin manager + page controller
5. SASS+CSS- the style of html document
6. metadata-info about plugin/where it is on CDN
7. enzyme- to use react and test, made by airbnb
8. docker- half VM
9. SPA- single page app->do not refresh page, only refresh plugin


## Tests
1. smokes-long+slow
2. bats -very fast tests

## how to link SCSS
1. first put it all in .scss file
2. import in homepage ui
3. in homepage.jsx
4. huge import ././sass

## QuickBase
1. build your own web app
2. sold it
3. now our test case management

## Node module
1. JS environemnt
2. does bindings for you
3. makes it faster
4. helps with dependencies

## web pack
1. able to zip
2. able to concatebate 
3. able to get chrome to load 1 smal concatenated file instead of 30 huge files

## great acronyms
1. FTU-first time users
2. TLA-three letter acronym 
3. VOC-voice of customer
4. DNL: profits and loss
5. MVP -min viable product
6. FAB- irst accounting benefits ->things like adding transactions to QBO as customer 
7. XD: experience design

## git tutorial
1. git merge 
3. git checkout
4. git status
5. git add
6. git commit
7. git push
