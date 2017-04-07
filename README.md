# api documentation for  [material-ui (v0.17.1)](http://material-ui.com/)  [![npm package](https://img.shields.io/npm/v/npmdoc-material-ui.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-material-ui) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-material-ui.svg)](https://travis-ci.org/npmdoc/node-npmdoc-material-ui)
#### React Components that Implement Google's Material Design.

[![NPM](https://nodei.co/npm/material-ui.png?downloads=true)](https://www.npmjs.com/package/material-ui)

[![apidoc](https://npmdoc.github.io/node-npmdoc-material-ui/build/screenCapture.buildNpmdoc.browser.%2Fhome%2Ftravis%2Fbuild%2Fnpmdoc%2Fnode-npmdoc-material-ui%2Ftmp%2Fbuild%2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-material-ui/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-material-ui/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-material-ui/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Material-UI Team"
    },
    "bugs": {
        "url": "https://github.com/callemall/material-ui/issues"
    },
    "dependencies": {
        "babel-runtime": "^6.18.0",
        "inline-style-prefixer": "^2.0.1",
        "keycode": "^2.1.1",
        "lodash.merge": "^4.6.0",
        "lodash.throttle": "^4.1.1",
        "react-addons-create-fragment": "^15.0.0",
        "react-addons-transition-group": "^15.0.0",
        "react-event-listener": "^0.4.0",
        "recompose": "^0.22.0",
        "simple-assign": "^0.1.0",
        "warning": "^3.0.0"
    },
    "description": "React Components that Implement Google's Material Design.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "37f9b9c073afa1603b8fb900d620b41699663176",
        "tarball": "https://registry.npmjs.org/material-ui/-/material-ui-0.17.1.tgz"
    },
    "homepage": "http://material-ui.com/",
    "jsnext:main": "./index.es.js",
    "keywords": [
        "react",
        "react-component",
        "material design",
        "material-ui"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "cea-admin",
            "email": "engineering@call-em-all.com"
        },
        {
            "name": "hai-cea",
            "email": "hai@call-em-all.com"
        },
        {
            "name": "jtollerene",
            "email": "jtollerene@gmail.com"
        },
        {
            "name": "nmarks",
            "email": "info@nathanmarks.io"
        },
        {
            "name": "oliviertassinari",
            "email": "olivier.tassinari@gmail.com"
        }
    ],
    "module": "./index.es.js",
    "name": "material-ui",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^15.4.0",
        "react-dom": "^15.4.0",
        "react-tap-event-plugin": "^2.0.1"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/callemall/material-ui.git"
    },
    "scripts": {},
    "version": "0.17.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module material-ui](#apidoc.module.material-ui)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>AppBar ()](#apidoc.element.material-ui.AppBar)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>AutoComplete ()](#apidoc.element.material-ui.AutoComplete)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>Avatar ()](#apidoc.element.material-ui.Avatar)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>Badge ()](#apidoc.element.material-ui.Badge)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>BottomNavigation (props, context)](#apidoc.element.material-ui.BottomNavigation)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>BottomNavigationItem (props, context)](#apidoc.element.material-ui.BottomNavigationItem)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>Card ()](#apidoc.element.material-ui.Card)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>CardActions ()](#apidoc.element.material-ui.CardActions)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>CardHeader ()](#apidoc.element.material-ui.CardHeader)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>CardMedia ()](#apidoc.element.material-ui.CardMedia)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>CardText ()](#apidoc.element.material-ui.CardText)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>CardTitle ()](#apidoc.element.material-ui.CardTitle)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>Checkbox ()](#apidoc.element.material-ui.Checkbox)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>Chip ()](#apidoc.element.material-ui.Chip)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>CircularProgress ()](#apidoc.element.material-ui.CircularProgress)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>DatePicker ()](#apidoc.element.material-ui.DatePicker)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>Dialog ()](#apidoc.element.material-ui.Dialog)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>Divider (props, context)](#apidoc.element.material-ui.Divider)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>Drawer ()](#apidoc.element.material-ui.Drawer)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>DropDownMenu ()](#apidoc.element.material-ui.DropDownMenu)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>FlatButton ()](#apidoc.element.material-ui.FlatButton)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>FloatingActionButton ()](#apidoc.element.material-ui.FloatingActionButton)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>FontIcon ()](#apidoc.element.material-ui.FontIcon)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>GridList ()](#apidoc.element.material-ui.GridList)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>GridTile ()](#apidoc.element.material-ui.GridTile)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>IconButton ()](#apidoc.element.material-ui.IconButton)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>IconMenu ()](#apidoc.element.material-ui.IconMenu)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>LinearProgress ()](#apidoc.element.material-ui.LinearProgress)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>List ()](#apidoc.element.material-ui.List)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>ListItem ()](#apidoc.element.material-ui.ListItem)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>Menu (props, context)](#apidoc.element.material-ui.Menu)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>MenuItem ()](#apidoc.element.material-ui.MenuItem)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>MuiThemeProvider ()](#apidoc.element.material-ui.MuiThemeProvider)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>Paper ()](#apidoc.element.material-ui.Paper)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>Popover (props, context)](#apidoc.element.material-ui.Popover)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>RadioButton ()](#apidoc.element.material-ui.RadioButton)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>RadioButtonGroup ()](#apidoc.element.material-ui.RadioButtonGroup)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>RaisedButton ()](#apidoc.element.material-ui.RaisedButton)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>RefreshIndicator ()](#apidoc.element.material-ui.RefreshIndicator)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>SelectField ()](#apidoc.element.material-ui.SelectField)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>Slider ()](#apidoc.element.material-ui.Slider)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>Snackbar ()](#apidoc.element.material-ui.Snackbar)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>Step ()](#apidoc.element.material-ui.Step)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>StepButton ()](#apidoc.element.material-ui.StepButton)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>StepContent ()](#apidoc.element.material-ui.StepContent)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>StepLabel (props, context)](#apidoc.element.material-ui.StepLabel)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>Stepper ()](#apidoc.element.material-ui.Stepper)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>Subheader (props, context)](#apidoc.element.material-ui.Subheader)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>SvgIcon ()](#apidoc.element.material-ui.SvgIcon)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>Tab ()](#apidoc.element.material-ui.Tab)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>Table ()](#apidoc.element.material-ui.Table)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>TableBody ()](#apidoc.element.material-ui.TableBody)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>TableFooter ()](#apidoc.element.material-ui.TableFooter)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>TableHeader ()](#apidoc.element.material-ui.TableHeader)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>TableHeaderColumn ()](#apidoc.element.material-ui.TableHeaderColumn)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>TableRow ()](#apidoc.element.material-ui.TableRow)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>TableRowColumn ()](#apidoc.element.material-ui.TableRowColumn)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>Tabs ()](#apidoc.element.material-ui.Tabs)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>TextField ()](#apidoc.element.material-ui.TextField)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>TimePicker ()](#apidoc.element.material-ui.TimePicker)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>Toggle ()](#apidoc.element.material-ui.Toggle)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>Toolbar ()](#apidoc.element.material-ui.Toolbar)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>ToolbarGroup ()](#apidoc.element.material-ui.ToolbarGroup)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>ToolbarSeparator ()](#apidoc.element.material-ui.ToolbarSeparator)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>ToolbarTitle ()](#apidoc.element.material-ui.ToolbarTitle)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>makeSelectable (MyComponent)](#apidoc.element.material-ui.makeSelectable)
1.  object <span class="apidocSignatureSpan">material-ui.</span>AppCanvas
1.  object <span class="apidocSignatureSpan">material-ui.</span>AutoComplete.contextTypes
1.  object <span class="apidocSignatureSpan">material-ui.</span>AutoComplete.defaultProps
1.  object <span class="apidocSignatureSpan">material-ui.</span>AutoComplete.propTypes
1.  object <span class="apidocSignatureSpan">material-ui.</span>AutoLockScrolling
1.  object <span class="apidocSignatureSpan">material-ui.</span>BeforeAfterWrapper
1.  object <span class="apidocSignatureSpan">material-ui.</span>Calendar
1.  object <span class="apidocSignatureSpan">material-ui.</span>CalendarActionButtons
1.  object <span class="apidocSignatureSpan">material-ui.</span>CalendarMonth
1.  object <span class="apidocSignatureSpan">material-ui.</span>CalendarToolbar
1.  object <span class="apidocSignatureSpan">material-ui.</span>CalendarYear
1.  object <span class="apidocSignatureSpan">material-ui.</span>CardExpandable
1.  object <span class="apidocSignatureSpan">material-ui.</span>CircleRipple
1.  object <span class="apidocSignatureSpan">material-ui.</span>ClearFix
1.  object <span class="apidocSignatureSpan">material-ui.</span>ClickAwayListener
1.  object <span class="apidocSignatureSpan">material-ui.</span>Clock
1.  object <span class="apidocSignatureSpan">material-ui.</span>ClockHours
1.  object <span class="apidocSignatureSpan">material-ui.</span>ClockMinutes
1.  object <span class="apidocSignatureSpan">material-ui.</span>ClockNumber
1.  object <span class="apidocSignatureSpan">material-ui.</span>ClockPointer
1.  object <span class="apidocSignatureSpan">material-ui.</span>DateDisplay
1.  object <span class="apidocSignatureSpan">material-ui.</span>DatePickerDialog
1.  object <span class="apidocSignatureSpan">material-ui.</span>DayButton
1.  object <span class="apidocSignatureSpan">material-ui.</span>EnhancedButton
1.  object <span class="apidocSignatureSpan">material-ui.</span>EnhancedSwitch
1.  object <span class="apidocSignatureSpan">material-ui.</span>EnhancedTextarea
1.  object <span class="apidocSignatureSpan">material-ui.</span>ExpandTransition
1.  object <span class="apidocSignatureSpan">material-ui.</span>ExpandTransitionChild
1.  object <span class="apidocSignatureSpan">material-ui.</span>FlatButtonLabel
1.  object <span class="apidocSignatureSpan">material-ui.</span>FocusRipple
1.  object <span class="apidocSignatureSpan">material-ui.</span>InkBar
1.  object <span class="apidocSignatureSpan">material-ui.</span>NestedList
1.  object <span class="apidocSignatureSpan">material-ui.</span>Overlay
1.  object <span class="apidocSignatureSpan">material-ui.</span>PopoverAnimationDefault
1.  object <span class="apidocSignatureSpan">material-ui.</span>PopoverAnimationVertical
1.  object <span class="apidocSignatureSpan">material-ui.</span>RenderToLayer
1.  object <span class="apidocSignatureSpan">material-ui.</span>ScaleIn
1.  object <span class="apidocSignatureSpan">material-ui.</span>ScaleInChild
1.  object <span class="apidocSignatureSpan">material-ui.</span>SlideIn
1.  object <span class="apidocSignatureSpan">material-ui.</span>SlideInChild
1.  object <span class="apidocSignatureSpan">material-ui.</span>SnackbarBody
1.  object <span class="apidocSignatureSpan">material-ui.</span>StepConnector
1.  object <span class="apidocSignatureSpan">material-ui.</span>TabTemplate
1.  object <span class="apidocSignatureSpan">material-ui.</span>TextFieldHint
1.  object <span class="apidocSignatureSpan">material-ui.</span>TextFieldLabel
1.  object <span class="apidocSignatureSpan">material-ui.</span>TextFieldUnderline
1.  object <span class="apidocSignatureSpan">material-ui.</span>TimeDisplay
1.  object <span class="apidocSignatureSpan">material-ui.</span>TimePickerDialog
1.  object <span class="apidocSignatureSpan">material-ui.</span>Tooltip
1.  object <span class="apidocSignatureSpan">material-ui.</span>TouchRipple
1.  object <span class="apidocSignatureSpan">material-ui.</span>YearButton
1.  object <span class="apidocSignatureSpan">material-ui.</span>autoprefixer
1.  object <span class="apidocSignatureSpan">material-ui.</span>callOnce
1.  object <span class="apidocSignatureSpan">material-ui.</span>childUtils
1.  object <span class="apidocSignatureSpan">material-ui.</span>colorManipulator
1.  object <span class="apidocSignatureSpan">material-ui.</span>dateUtils
1.  object <span class="apidocSignatureSpan">material-ui.</span>deprecatedExport
1.  object <span class="apidocSignatureSpan">material-ui.</span>deprecatedPropType
1.  object <span class="apidocSignatureSpan">material-ui.</span>getMuiTheme
1.  object <span class="apidocSignatureSpan">material-ui.</span>iOSHelpers
1.  object <span class="apidocSignatureSpan">material-ui.</span>menuUtils
1.  object <span class="apidocSignatureSpan">material-ui.</span>muiThemeable
1.  object <span class="apidocSignatureSpan">material-ui.</span>navigation_arrow_drop_right
1.  object <span class="apidocSignatureSpan">material-ui.</span>rtl
1.  object <span class="apidocSignatureSpan">material-ui.</span>timeUtils
1.  object <span class="apidocSignatureSpan">material-ui.</span>withWidth

#### [module material-ui.AppBar](#apidoc.module.material-ui.AppBar)
1.  [function <span class="apidocSignatureSpan">material-ui.AppBar.</span>default ()](#apidoc.element.material-ui.AppBar.default)
1.  [function <span class="apidocSignatureSpan">material-ui.AppBar.</span>getStyles (props, context)](#apidoc.element.material-ui.AppBar.getStyles)

#### [module material-ui.AppCanvas](#apidoc.module.material-ui.AppCanvas)
1.  [function <span class="apidocSignatureSpan">material-ui.AppCanvas.</span>default ()](#apidoc.element.material-ui.AppCanvas.default)

#### [module material-ui.AutoComplete](#apidoc.module.material-ui.AutoComplete)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>AutoComplete ()](#apidoc.element.material-ui.AutoComplete.AutoComplete)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.</span>Divider (props, context)](#apidoc.element.material-ui.AutoComplete.Divider)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.</span>Item ()](#apidoc.element.material-ui.AutoComplete.Item)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.</span>caseInsensitiveFilter (searchText, key)](#apidoc.element.material-ui.AutoComplete.caseInsensitiveFilter)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.</span>caseSensitiveFilter (searchText, key)](#apidoc.element.material-ui.AutoComplete.caseSensitiveFilter)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.</span>defaultFilter (searchText, key)](#apidoc.element.material-ui.AutoComplete.defaultFilter)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.</span>fuzzyFilter (searchText, key)](#apidoc.element.material-ui.AutoComplete.fuzzyFilter)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.</span>levenshteinDistance (searchText, key)](#apidoc.element.material-ui.AutoComplete.levenshteinDistance)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.</span>levenshteinDistanceFilter (distanceLessThan)](#apidoc.element.material-ui.AutoComplete.levenshteinDistanceFilter)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.</span>noFilter ()](#apidoc.element.material-ui.AutoComplete.noFilter)
1.  object <span class="apidocSignatureSpan">material-ui.AutoComplete.</span>contextTypes
1.  object <span class="apidocSignatureSpan">material-ui.AutoComplete.</span>defaultProps
1.  object <span class="apidocSignatureSpan">material-ui.AutoComplete.</span>propTypes

#### [module material-ui.AutoComplete.contextTypes](#apidoc.module.material-ui.AutoComplete.contextTypes)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.contextTypes.</span>muiTheme ()](#apidoc.element.material-ui.AutoComplete.contextTypes.muiTheme)

#### [module material-ui.AutoComplete.defaultProps](#apidoc.module.material-ui.AutoComplete.defaultProps)
1.  boolean <span class="apidocSignatureSpan">material-ui.AutoComplete.defaultProps.</span>animated
1.  boolean <span class="apidocSignatureSpan">material-ui.AutoComplete.defaultProps.</span>disableFocusRipple
1.  boolean <span class="apidocSignatureSpan">material-ui.AutoComplete.defaultProps.</span>fullWidth
1.  boolean <span class="apidocSignatureSpan">material-ui.AutoComplete.defaultProps.</span>open
1.  boolean <span class="apidocSignatureSpan">material-ui.AutoComplete.defaultProps.</span>openOnFocus
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.defaultProps.</span>filter (searchText, key)](#apidoc.element.material-ui.AutoComplete.defaultProps.filter)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.defaultProps.</span>onNewRequest ()](#apidoc.element.material-ui.AutoComplete.defaultProps.onNewRequest)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.defaultProps.</span>onUpdateInput ()](#apidoc.element.material-ui.AutoComplete.defaultProps.onUpdateInput)
1.  number <span class="apidocSignatureSpan">material-ui.AutoComplete.defaultProps.</span>menuCloseDelay
1.  object <span class="apidocSignatureSpan">material-ui.AutoComplete.defaultProps.</span>anchorOrigin
1.  object <span class="apidocSignatureSpan">material-ui.AutoComplete.defaultProps.</span>dataSourceConfig
1.  object <span class="apidocSignatureSpan">material-ui.AutoComplete.defaultProps.</span>targetOrigin
1.  string <span class="apidocSignatureSpan">material-ui.AutoComplete.defaultProps.</span>searchText

#### [module material-ui.AutoComplete.propTypes](#apidoc.module.material-ui.AutoComplete.propTypes)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>anchorOrigin ()](#apidoc.element.material-ui.AutoComplete.propTypes.anchorOrigin)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>animated ()](#apidoc.element.material-ui.AutoComplete.propTypes.animated)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>animation ()](#apidoc.element.material-ui.AutoComplete.propTypes.animation)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>dataSource ()](#apidoc.element.material-ui.AutoComplete.propTypes.dataSource)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>dataSourceConfig ()](#apidoc.element.material-ui.AutoComplete.propTypes.dataSourceConfig)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>disableFocusRipple ()](#apidoc.element.material-ui.AutoComplete.propTypes.disableFocusRipple)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>errorStyle ()](#apidoc.element.material-ui.AutoComplete.propTypes.errorStyle)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>errorText ()](#apidoc.element.material-ui.AutoComplete.propTypes.errorText)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>filter ()](#apidoc.element.material-ui.AutoComplete.propTypes.filter)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>floatingLabelText ()](#apidoc.element.material-ui.AutoComplete.propTypes.floatingLabelText)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>fullWidth ()](#apidoc.element.material-ui.AutoComplete.propTypes.fullWidth)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>hintText ()](#apidoc.element.material-ui.AutoComplete.propTypes.hintText)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>listStyle ()](#apidoc.element.material-ui.AutoComplete.propTypes.listStyle)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>maxSearchResults ()](#apidoc.element.material-ui.AutoComplete.propTypes.maxSearchResults)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>menuCloseDelay ()](#apidoc.element.material-ui.AutoComplete.propTypes.menuCloseDelay)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>menuProps ()](#apidoc.element.material-ui.AutoComplete.propTypes.menuProps)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>menuStyle ()](#apidoc.element.material-ui.AutoComplete.propTypes.menuStyle)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>onBlur ()](#apidoc.element.material-ui.AutoComplete.propTypes.onBlur)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>onClose ()](#apidoc.element.material-ui.AutoComplete.propTypes.onClose)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>onFocus ()](#apidoc.element.material-ui.AutoComplete.propTypes.onFocus)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>onKeyDown ()](#apidoc.element.material-ui.AutoComplete.propTypes.onKeyDown)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>onNewRequest ()](#apidoc.element.material-ui.AutoComplete.propTypes.onNewRequest)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>onUpdateInput ()](#apidoc.element.material-ui.AutoComplete.propTypes.onUpdateInput)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>open ()](#apidoc.element.material-ui.AutoComplete.propTypes.open)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>openOnFocus ()](#apidoc.element.material-ui.AutoComplete.propTypes.openOnFocus)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>popoverProps ()](#apidoc.element.material-ui.AutoComplete.propTypes.popoverProps)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>searchText ()](#apidoc.element.material-ui.AutoComplete.propTypes.searchText)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>style ()](#apidoc.element.material-ui.AutoComplete.propTypes.style)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>targetOrigin ()](#apidoc.element.material-ui.AutoComplete.propTypes.targetOrigin)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>textFieldStyle ()](#apidoc.element.material-ui.AutoComplete.propTypes.textFieldStyle)

#### [module material-ui.AutoLockScrolling](#apidoc.module.material-ui.AutoLockScrolling)
1.  [function <span class="apidocSignatureSpan">material-ui.AutoLockScrolling.</span>default ()](#apidoc.element.material-ui.AutoLockScrolling.default)

#### [module material-ui.Avatar](#apidoc.module.material-ui.Avatar)
1.  [function <span class="apidocSignatureSpan">material-ui.Avatar.</span>default ()](#apidoc.element.material-ui.Avatar.default)

#### [module material-ui.Badge](#apidoc.module.material-ui.Badge)
1.  [function <span class="apidocSignatureSpan">material-ui.Badge.</span>default ()](#apidoc.element.material-ui.Badge.default)

#### [module material-ui.BeforeAfterWrapper](#apidoc.module.material-ui.BeforeAfterWrapper)
1.  [function <span class="apidocSignatureSpan">material-ui.BeforeAfterWrapper.</span>default ()](#apidoc.element.material-ui.BeforeAfterWrapper.default)

#### [module material-ui.BottomNavigation](#apidoc.module.material-ui.BottomNavigation)
1.  [function <span class="apidocSignatureSpan">material-ui.BottomNavigation.</span>default (props, context)](#apidoc.element.material-ui.BottomNavigation.default)

#### [module material-ui.BottomNavigationItem](#apidoc.module.material-ui.BottomNavigationItem)
1.  [function <span class="apidocSignatureSpan">material-ui.BottomNavigationItem.</span>default (props, context)](#apidoc.element.material-ui.BottomNavigationItem.default)

#### [module material-ui.Calendar](#apidoc.module.material-ui.Calendar)
1.  [function <span class="apidocSignatureSpan">material-ui.Calendar.</span>default ()](#apidoc.element.material-ui.Calendar.default)

#### [module material-ui.CalendarActionButtons](#apidoc.module.material-ui.CalendarActionButtons)
1.  [function <span class="apidocSignatureSpan">material-ui.CalendarActionButtons.</span>default ()](#apidoc.element.material-ui.CalendarActionButtons.default)

#### [module material-ui.CalendarMonth](#apidoc.module.material-ui.CalendarMonth)
1.  [function <span class="apidocSignatureSpan">material-ui.CalendarMonth.</span>default ()](#apidoc.element.material-ui.CalendarMonth.default)

#### [module material-ui.CalendarToolbar](#apidoc.module.material-ui.CalendarToolbar)
1.  [function <span class="apidocSignatureSpan">material-ui.CalendarToolbar.</span>default ()](#apidoc.element.material-ui.CalendarToolbar.default)

#### [module material-ui.CalendarYear](#apidoc.module.material-ui.CalendarYear)
1.  [function <span class="apidocSignatureSpan">material-ui.CalendarYear.</span>default ()](#apidoc.element.material-ui.CalendarYear.default)

#### [module material-ui.Card](#apidoc.module.material-ui.Card)
1.  [function <span class="apidocSignatureSpan">material-ui.Card.</span>default ()](#apidoc.element.material-ui.Card.default)

#### [module material-ui.CardActions](#apidoc.module.material-ui.CardActions)
1.  [function <span class="apidocSignatureSpan">material-ui.CardActions.</span>default ()](#apidoc.element.material-ui.CardActions.default)

#### [module material-ui.CardExpandable](#apidoc.module.material-ui.CardExpandable)
1.  [function <span class="apidocSignatureSpan">material-ui.CardExpandable.</span>default ()](#apidoc.element.material-ui.CardExpandable.default)

#### [module material-ui.CardHeader](#apidoc.module.material-ui.CardHeader)
1.  [function <span class="apidocSignatureSpan">material-ui.CardHeader.</span>default ()](#apidoc.element.material-ui.CardHeader.default)

#### [module material-ui.CardMedia](#apidoc.module.material-ui.CardMedia)
1.  [function <span class="apidocSignatureSpan">material-ui.CardMedia.</span>default ()](#apidoc.element.material-ui.CardMedia.default)

#### [module material-ui.CardText](#apidoc.module.material-ui.CardText)
1.  [function <span class="apidocSignatureSpan">material-ui.CardText.</span>default ()](#apidoc.element.material-ui.CardText.default)

#### [module material-ui.CardTitle](#apidoc.module.material-ui.CardTitle)
1.  [function <span class="apidocSignatureSpan">material-ui.CardTitle.</span>default ()](#apidoc.element.material-ui.CardTitle.default)

#### [module material-ui.Checkbox](#apidoc.module.material-ui.Checkbox)
1.  [function <span class="apidocSignatureSpan">material-ui.Checkbox.</span>default ()](#apidoc.element.material-ui.Checkbox.default)

#### [module material-ui.Chip](#apidoc.module.material-ui.Chip)
1.  [function <span class="apidocSignatureSpan">material-ui.Chip.</span>default ()](#apidoc.element.material-ui.Chip.default)

#### [module material-ui.CircleRipple](#apidoc.module.material-ui.CircleRipple)
1.  [function <span class="apidocSignatureSpan">material-ui.CircleRipple.</span>default ()](#apidoc.element.material-ui.CircleRipple.default)

#### [module material-ui.CircularProgress](#apidoc.module.material-ui.CircularProgress)
1.  [function <span class="apidocSignatureSpan">material-ui.CircularProgress.</span>default ()](#apidoc.element.material-ui.CircularProgress.default)

#### [module material-ui.ClearFix](#apidoc.module.material-ui.ClearFix)
1.  [function <span class="apidocSignatureSpan">material-ui.ClearFix.</span>default (_ref)](#apidoc.element.material-ui.ClearFix.default)

#### [module material-ui.ClickAwayListener](#apidoc.module.material-ui.ClickAwayListener)
1.  [function <span class="apidocSignatureSpan">material-ui.ClickAwayListener.</span>default ()](#apidoc.element.material-ui.ClickAwayListener.default)

#### [module material-ui.Clock](#apidoc.module.material-ui.Clock)
1.  [function <span class="apidocSignatureSpan">material-ui.Clock.</span>default ()](#apidoc.element.material-ui.Clock.default)

#### [module material-ui.ClockHours](#apidoc.module.material-ui.ClockHours)
1.  [function <span class="apidocSignatureSpan">material-ui.ClockHours.</span>default ()](#apidoc.element.material-ui.ClockHours.default)

#### [module material-ui.ClockMinutes](#apidoc.module.material-ui.ClockMinutes)
1.  [function <span class="apidocSignatureSpan">material-ui.ClockMinutes.</span>default ()](#apidoc.element.material-ui.ClockMinutes.default)

#### [module material-ui.ClockNumber](#apidoc.module.material-ui.ClockNumber)
1.  [function <span class="apidocSignatureSpan">material-ui.ClockNumber.</span>default ()](#apidoc.element.material-ui.ClockNumber.default)

#### [module material-ui.ClockPointer](#apidoc.module.material-ui.ClockPointer)
1.  [function <span class="apidocSignatureSpan">material-ui.ClockPointer.</span>default ()](#apidoc.element.material-ui.ClockPointer.default)

#### [module material-ui.DateDisplay](#apidoc.module.material-ui.DateDisplay)
1.  [function <span class="apidocSignatureSpan">material-ui.DateDisplay.</span>default ()](#apidoc.element.material-ui.DateDisplay.default)

#### [module material-ui.DatePicker](#apidoc.module.material-ui.DatePicker)
1.  [function <span class="apidocSignatureSpan">material-ui.DatePicker.</span>default ()](#apidoc.element.material-ui.DatePicker.default)

#### [module material-ui.DatePickerDialog](#apidoc.module.material-ui.DatePickerDialog)
1.  [function <span class="apidocSignatureSpan">material-ui.DatePickerDialog.</span>default ()](#apidoc.element.material-ui.DatePickerDialog.default)

#### [module material-ui.DayButton](#apidoc.module.material-ui.DayButton)
1.  [function <span class="apidocSignatureSpan">material-ui.DayButton.</span>default ()](#apidoc.element.material-ui.DayButton.default)

#### [module material-ui.Dialog](#apidoc.module.material-ui.Dialog)
1.  [function <span class="apidocSignatureSpan">material-ui.Dialog.</span>default ()](#apidoc.element.material-ui.Dialog.default)

#### [module material-ui.Divider](#apidoc.module.material-ui.Divider)
1.  [function <span class="apidocSignatureSpan">material-ui.Divider.</span>default (props, context)](#apidoc.element.material-ui.Divider.default)

#### [module material-ui.Drawer](#apidoc.module.material-ui.Drawer)
1.  [function <span class="apidocSignatureSpan">material-ui.Drawer.</span>default ()](#apidoc.element.material-ui.Drawer.default)

#### [module material-ui.DropDownMenu](#apidoc.module.material-ui.DropDownMenu)
1.  [function <span class="apidocSignatureSpan">material-ui.DropDownMenu.</span>default ()](#apidoc.element.material-ui.DropDownMenu.default)

#### [module material-ui.EnhancedButton](#apidoc.module.material-ui.EnhancedButton)
1.  [function <span class="apidocSignatureSpan">material-ui.EnhancedButton.</span>default ()](#apidoc.element.material-ui.EnhancedButton.default)

#### [module material-ui.EnhancedSwitch](#apidoc.module.material-ui.EnhancedSwitch)
1.  [function <span class="apidocSignatureSpan">material-ui.EnhancedSwitch.</span>default ()](#apidoc.element.material-ui.EnhancedSwitch.default)

#### [module material-ui.EnhancedTextarea](#apidoc.module.material-ui.EnhancedTextarea)
1.  [function <span class="apidocSignatureSpan">material-ui.EnhancedTextarea.</span>default ()](#apidoc.element.material-ui.EnhancedTextarea.default)

#### [module material-ui.ExpandTransition](#apidoc.module.material-ui.ExpandTransition)
1.  [function <span class="apidocSignatureSpan">material-ui.ExpandTransition.</span>default ()](#apidoc.element.material-ui.ExpandTransition.default)

#### [module material-ui.ExpandTransitionChild](#apidoc.module.material-ui.ExpandTransitionChild)
1.  [function <span class="apidocSignatureSpan">material-ui.ExpandTransitionChild.</span>default ()](#apidoc.element.material-ui.ExpandTransitionChild.default)

#### [module material-ui.FlatButton](#apidoc.module.material-ui.FlatButton)
1.  [function <span class="apidocSignatureSpan">material-ui.FlatButton.</span>default ()](#apidoc.element.material-ui.FlatButton.default)

#### [module material-ui.FlatButtonLabel](#apidoc.module.material-ui.FlatButtonLabel)
1.  [function <span class="apidocSignatureSpan">material-ui.FlatButtonLabel.</span>default ()](#apidoc.element.material-ui.FlatButtonLabel.default)

#### [module material-ui.FloatingActionButton](#apidoc.module.material-ui.FloatingActionButton)
1.  [function <span class="apidocSignatureSpan">material-ui.FloatingActionButton.</span>default ()](#apidoc.element.material-ui.FloatingActionButton.default)

#### [module material-ui.FocusRipple](#apidoc.module.material-ui.FocusRipple)
1.  [function <span class="apidocSignatureSpan">material-ui.FocusRipple.</span>default ()](#apidoc.element.material-ui.FocusRipple.default)

#### [module material-ui.FontIcon](#apidoc.module.material-ui.FontIcon)
1.  [function <span class="apidocSignatureSpan">material-ui.FontIcon.</span>default ()](#apidoc.element.material-ui.FontIcon.default)

#### [module material-ui.GridList](#apidoc.module.material-ui.GridList)
1.  [function <span class="apidocSignatureSpan">material-ui.GridList.</span>default ()](#apidoc.element.material-ui.GridList.default)

#### [module material-ui.GridTile](#apidoc.module.material-ui.GridTile)
1.  [function <span class="apidocSignatureSpan">material-ui.GridTile.</span>default ()](#apidoc.element.material-ui.GridTile.default)

#### [module material-ui.IconButton](#apidoc.module.material-ui.IconButton)
1.  [function <span class="apidocSignatureSpan">material-ui.IconButton.</span>default ()](#apidoc.element.material-ui.IconButton.default)

#### [module material-ui.IconMenu](#apidoc.module.material-ui.IconMenu)
1.  [function <span class="apidocSignatureSpan">material-ui.IconMenu.</span>default ()](#apidoc.element.material-ui.IconMenu.default)

#### [module material-ui.InkBar](#apidoc.module.material-ui.InkBar)
1.  [function <span class="apidocSignatureSpan">material-ui.InkBar.</span>default ()](#apidoc.element.material-ui.InkBar.default)

#### [module material-ui.LinearProgress](#apidoc.module.material-ui.LinearProgress)
1.  [function <span class="apidocSignatureSpan">material-ui.LinearProgress.</span>default ()](#apidoc.element.material-ui.LinearProgress.default)

#### [module material-ui.List](#apidoc.module.material-ui.List)
1.  [function <span class="apidocSignatureSpan">material-ui.List.</span>default ()](#apidoc.element.material-ui.List.default)

#### [module material-ui.ListItem](#apidoc.module.material-ui.ListItem)
1.  [function <span class="apidocSignatureSpan">material-ui.ListItem.</span>default ()](#apidoc.element.material-ui.ListItem.default)

#### [module material-ui.Menu](#apidoc.module.material-ui.Menu)
1.  [function <span class="apidocSignatureSpan">material-ui.Menu.</span>default (props, context)](#apidoc.element.material-ui.Menu.default)

#### [module material-ui.MenuItem](#apidoc.module.material-ui.MenuItem)
1.  [function <span class="apidocSignatureSpan">material-ui.MenuItem.</span>default ()](#apidoc.element.material-ui.MenuItem.default)

#### [module material-ui.MuiThemeProvider](#apidoc.module.material-ui.MuiThemeProvider)
1.  [function <span class="apidocSignatureSpan">material-ui.MuiThemeProvider.</span>default ()](#apidoc.element.material-ui.MuiThemeProvider.default)

#### [module material-ui.NestedList](#apidoc.module.material-ui.NestedList)
1.  [function <span class="apidocSignatureSpan">material-ui.NestedList.</span>default (props)](#apidoc.element.material-ui.NestedList.default)

#### [module material-ui.Overlay](#apidoc.module.material-ui.Overlay)
1.  [function <span class="apidocSignatureSpan">material-ui.Overlay.</span>default ()](#apidoc.element.material-ui.Overlay.default)

#### [module material-ui.Paper](#apidoc.module.material-ui.Paper)
1.  [function <span class="apidocSignatureSpan">material-ui.Paper.</span>default ()](#apidoc.element.material-ui.Paper.default)

#### [module material-ui.Popover](#apidoc.module.material-ui.Popover)
1.  [function <span class="apidocSignatureSpan">material-ui.Popover.</span>default (props, context)](#apidoc.element.material-ui.Popover.default)

#### [module material-ui.PopoverAnimationDefault](#apidoc.module.material-ui.PopoverAnimationDefault)
1.  [function <span class="apidocSignatureSpan">material-ui.PopoverAnimationDefault.</span>default ()](#apidoc.element.material-ui.PopoverAnimationDefault.default)

#### [module material-ui.PopoverAnimationVertical](#apidoc.module.material-ui.PopoverAnimationVertical)
1.  [function <span class="apidocSignatureSpan">material-ui.PopoverAnimationVertical.</span>default ()](#apidoc.element.material-ui.PopoverAnimationVertical.default)

#### [module material-ui.RadioButton](#apidoc.module.material-ui.RadioButton)
1.  [function <span class="apidocSignatureSpan">material-ui.RadioButton.</span>default ()](#apidoc.element.material-ui.RadioButton.default)

#### [module material-ui.RadioButtonGroup](#apidoc.module.material-ui.RadioButtonGroup)
1.  [function <span class="apidocSignatureSpan">material-ui.RadioButtonGroup.</span>default ()](#apidoc.element.material-ui.RadioButtonGroup.default)

#### [module material-ui.RaisedButton](#apidoc.module.material-ui.RaisedButton)
1.  [function <span class="apidocSignatureSpan">material-ui.RaisedButton.</span>default ()](#apidoc.element.material-ui.RaisedButton.default)

#### [module material-ui.RefreshIndicator](#apidoc.module.material-ui.RefreshIndicator)
1.  [function <span class="apidocSignatureSpan">material-ui.RefreshIndicator.</span>default ()](#apidoc.element.material-ui.RefreshIndicator.default)

#### [module material-ui.RenderToLayer](#apidoc.module.material-ui.RenderToLayer)
1.  [function <span class="apidocSignatureSpan">material-ui.RenderToLayer.</span>default ()](#apidoc.element.material-ui.RenderToLayer.default)

#### [module material-ui.ScaleIn](#apidoc.module.material-ui.ScaleIn)
1.  [function <span class="apidocSignatureSpan">material-ui.ScaleIn.</span>default ()](#apidoc.element.material-ui.ScaleIn.default)

#### [module material-ui.ScaleInChild](#apidoc.module.material-ui.ScaleInChild)
1.  [function <span class="apidocSignatureSpan">material-ui.ScaleInChild.</span>default ()](#apidoc.element.material-ui.ScaleInChild.default)

#### [module material-ui.SelectField](#apidoc.module.material-ui.SelectField)
1.  [function <span class="apidocSignatureSpan">material-ui.SelectField.</span>default ()](#apidoc.element.material-ui.SelectField.default)

#### [module material-ui.SlideIn](#apidoc.module.material-ui.SlideIn)
1.  [function <span class="apidocSignatureSpan">material-ui.SlideIn.</span>default ()](#apidoc.element.material-ui.SlideIn.default)

#### [module material-ui.SlideInChild](#apidoc.module.material-ui.SlideInChild)
1.  [function <span class="apidocSignatureSpan">material-ui.SlideInChild.</span>default ()](#apidoc.element.material-ui.SlideInChild.default)

#### [module material-ui.Slider](#apidoc.module.material-ui.Slider)
1.  [function <span class="apidocSignatureSpan">material-ui.Slider.</span>default ()](#apidoc.element.material-ui.Slider.default)

#### [module material-ui.Snackbar](#apidoc.module.material-ui.Snackbar)
1.  [function <span class="apidocSignatureSpan">material-ui.Snackbar.</span>default ()](#apidoc.element.material-ui.Snackbar.default)

#### [module material-ui.SnackbarBody](#apidoc.module.material-ui.SnackbarBody)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>SnackbarBody (props, context)](#apidoc.element.material-ui.SnackbarBody.SnackbarBody)
1.  [function <span class="apidocSignatureSpan">material-ui.SnackbarBody.</span>default ()](#apidoc.element.material-ui.SnackbarBody.default)

#### [module material-ui.Step](#apidoc.module.material-ui.Step)
1.  [function <span class="apidocSignatureSpan">material-ui.Step.</span>default ()](#apidoc.element.material-ui.Step.default)

#### [module material-ui.StepButton](#apidoc.module.material-ui.StepButton)
1.  [function <span class="apidocSignatureSpan">material-ui.StepButton.</span>default ()](#apidoc.element.material-ui.StepButton.default)

#### [module material-ui.StepConnector](#apidoc.module.material-ui.StepConnector)
1.  [function <span class="apidocSignatureSpan">material-ui.StepConnector.</span>PlainStepConnector (props, context)](#apidoc.element.material-ui.StepConnector.PlainStepConnector)
1.  [function <span class="apidocSignatureSpan">material-ui.StepConnector.</span>default ()](#apidoc.element.material-ui.StepConnector.default)

#### [module material-ui.StepContent](#apidoc.module.material-ui.StepContent)
1.  [function <span class="apidocSignatureSpan">material-ui.StepContent.</span>default ()](#apidoc.element.material-ui.StepContent.default)

#### [module material-ui.StepLabel](#apidoc.module.material-ui.StepLabel)
1.  [function <span class="apidocSignatureSpan">material-ui.StepLabel.</span>default (props, context)](#apidoc.element.material-ui.StepLabel.default)

#### [module material-ui.Stepper](#apidoc.module.material-ui.Stepper)
1.  [function <span class="apidocSignatureSpan">material-ui.Stepper.</span>default ()](#apidoc.element.material-ui.Stepper.default)

#### [module material-ui.Subheader](#apidoc.module.material-ui.Subheader)
1.  [function <span class="apidocSignatureSpan">material-ui.Subheader.</span>default (props, context)](#apidoc.element.material-ui.Subheader.default)

#### [module material-ui.SvgIcon](#apidoc.module.material-ui.SvgIcon)
1.  [function <span class="apidocSignatureSpan">material-ui.SvgIcon.</span>default ()](#apidoc.element.material-ui.SvgIcon.default)

#### [module material-ui.Tab](#apidoc.module.material-ui.Tab)
1.  [function <span class="apidocSignatureSpan">material-ui.Tab.</span>default ()](#apidoc.element.material-ui.Tab.default)

#### [module material-ui.TabTemplate](#apidoc.module.material-ui.TabTemplate)
1.  [function <span class="apidocSignatureSpan">material-ui.TabTemplate.</span>default (_ref)](#apidoc.element.material-ui.TabTemplate.default)

#### [module material-ui.Table](#apidoc.module.material-ui.Table)
1.  [function <span class="apidocSignatureSpan">material-ui.Table.</span>default ()](#apidoc.element.material-ui.Table.default)

#### [module material-ui.TableBody](#apidoc.module.material-ui.TableBody)
1.  [function <span class="apidocSignatureSpan">material-ui.TableBody.</span>default ()](#apidoc.element.material-ui.TableBody.default)

#### [module material-ui.TableFooter](#apidoc.module.material-ui.TableFooter)
1.  [function <span class="apidocSignatureSpan">material-ui.TableFooter.</span>default ()](#apidoc.element.material-ui.TableFooter.default)

#### [module material-ui.TableHeader](#apidoc.module.material-ui.TableHeader)
1.  [function <span class="apidocSignatureSpan">material-ui.TableHeader.</span>default ()](#apidoc.element.material-ui.TableHeader.default)

#### [module material-ui.TableHeaderColumn](#apidoc.module.material-ui.TableHeaderColumn)
1.  [function <span class="apidocSignatureSpan">material-ui.TableHeaderColumn.</span>default ()](#apidoc.element.material-ui.TableHeaderColumn.default)

#### [module material-ui.TableRow](#apidoc.module.material-ui.TableRow)
1.  [function <span class="apidocSignatureSpan">material-ui.TableRow.</span>default ()](#apidoc.element.material-ui.TableRow.default)

#### [module material-ui.TableRowColumn](#apidoc.module.material-ui.TableRowColumn)
1.  [function <span class="apidocSignatureSpan">material-ui.TableRowColumn.</span>default ()](#apidoc.element.material-ui.TableRowColumn.default)

#### [module material-ui.Tabs](#apidoc.module.material-ui.Tabs)
1.  [function <span class="apidocSignatureSpan">material-ui.Tabs.</span>default ()](#apidoc.element.material-ui.Tabs.default)

#### [module material-ui.TextField](#apidoc.module.material-ui.TextField)
1.  [function <span class="apidocSignatureSpan">material-ui.TextField.</span>default ()](#apidoc.element.material-ui.TextField.default)

#### [module material-ui.TextFieldHint](#apidoc.module.material-ui.TextFieldHint)
1.  [function <span class="apidocSignatureSpan">material-ui.TextFieldHint.</span>default (props)](#apidoc.element.material-ui.TextFieldHint.default)

#### [module material-ui.TextFieldLabel](#apidoc.module.material-ui.TextFieldLabel)
1.  [function <span class="apidocSignatureSpan">material-ui.TextFieldLabel.</span>default (props)](#apidoc.element.material-ui.TextFieldLabel.default)

#### [module material-ui.TextFieldUnderline](#apidoc.module.material-ui.TextFieldUnderline)
1.  [function <span class="apidocSignatureSpan">material-ui.TextFieldUnderline.</span>default (props)](#apidoc.element.material-ui.TextFieldUnderline.default)

#### [module material-ui.TimeDisplay](#apidoc.module.material-ui.TimeDisplay)
1.  [function <span class="apidocSignatureSpan">material-ui.TimeDisplay.</span>default ()](#apidoc.element.material-ui.TimeDisplay.default)

#### [module material-ui.TimePicker](#apidoc.module.material-ui.TimePicker)
1.  [function <span class="apidocSignatureSpan">material-ui.TimePicker.</span>default ()](#apidoc.element.material-ui.TimePicker.default)

#### [module material-ui.TimePickerDialog](#apidoc.module.material-ui.TimePickerDialog)
1.  [function <span class="apidocSignatureSpan">material-ui.TimePickerDialog.</span>default ()](#apidoc.element.material-ui.TimePickerDialog.default)

#### [module material-ui.Toggle](#apidoc.module.material-ui.Toggle)
1.  [function <span class="apidocSignatureSpan">material-ui.Toggle.</span>default ()](#apidoc.element.material-ui.Toggle.default)

#### [module material-ui.Toolbar](#apidoc.module.material-ui.Toolbar)
1.  [function <span class="apidocSignatureSpan">material-ui.Toolbar.</span>default ()](#apidoc.element.material-ui.Toolbar.default)

#### [module material-ui.ToolbarGroup](#apidoc.module.material-ui.ToolbarGroup)
1.  [function <span class="apidocSignatureSpan">material-ui.ToolbarGroup.</span>default ()](#apidoc.element.material-ui.ToolbarGroup.default)

#### [module material-ui.ToolbarSeparator](#apidoc.module.material-ui.ToolbarSeparator)
1.  [function <span class="apidocSignatureSpan">material-ui.ToolbarSeparator.</span>default ()](#apidoc.element.material-ui.ToolbarSeparator.default)

#### [module material-ui.ToolbarTitle](#apidoc.module.material-ui.ToolbarTitle)
1.  [function <span class="apidocSignatureSpan">material-ui.ToolbarTitle.</span>default ()](#apidoc.element.material-ui.ToolbarTitle.default)

#### [module material-ui.Tooltip](#apidoc.module.material-ui.Tooltip)
1.  [function <span class="apidocSignatureSpan">material-ui.Tooltip.</span>default ()](#apidoc.element.material-ui.Tooltip.default)

#### [module material-ui.TouchRipple](#apidoc.module.material-ui.TouchRipple)
1.  [function <span class="apidocSignatureSpan">material-ui.TouchRipple.</span>default (props, context)](#apidoc.element.material-ui.TouchRipple.default)

#### [module material-ui.YearButton](#apidoc.module.material-ui.YearButton)
1.  [function <span class="apidocSignatureSpan">material-ui.YearButton.</span>default ()](#apidoc.element.material-ui.YearButton.default)

#### [module material-ui.autoprefixer](#apidoc.module.material-ui.autoprefixer)
1.  [function <span class="apidocSignatureSpan">material-ui.autoprefixer.</span>default (muiTheme)](#apidoc.element.material-ui.autoprefixer.default)

#### [module material-ui.callOnce](#apidoc.module.material-ui.callOnce)
1.  [function <span class="apidocSignatureSpan">material-ui.callOnce.</span>default ()](#apidoc.element.material-ui.callOnce.default)

#### [module material-ui.childUtils](#apidoc.module.material-ui.childUtils)
1.  [function <span class="apidocSignatureSpan">material-ui.childUtils.</span>createChildFragment (fragments)](#apidoc.element.material-ui.childUtils.createChildFragment)
1.  [function <span class="apidocSignatureSpan">material-ui.childUtils.</span>extendChildren (children, extendedProps, extendedChildren)](#apidoc.element.material-ui.childUtils.extendChildren)

#### [module material-ui.colorManipulator](#apidoc.module.material-ui.colorManipulator)
1.  [function <span class="apidocSignatureSpan">material-ui.colorManipulator.</span>convertColorToString (color)](#apidoc.element.material-ui.colorManipulator.convertColorToString)
1.  [function <span class="apidocSignatureSpan">material-ui.colorManipulator.</span>convertHexToRGB (color)](#apidoc.element.material-ui.colorManipulator.convertHexToRGB)
1.  [function <span class="apidocSignatureSpan">material-ui.colorManipulator.</span>darken (color, coefficient)](#apidoc.element.material-ui.colorManipulator.darken)
1.  [function <span class="apidocSignatureSpan">material-ui.colorManipulator.</span>decomposeColor (color)](#apidoc.element.material-ui.colorManipulator.decomposeColor)
1.  [function <span class="apidocSignatureSpan">material-ui.colorManipulator.</span>emphasize (color)](#apidoc.element.material-ui.colorManipulator.emphasize)
1.  [function <span class="apidocSignatureSpan">material-ui.colorManipulator.</span>fade (color, value)](#apidoc.element.material-ui.colorManipulator.fade)
1.  [function <span class="apidocSignatureSpan">material-ui.colorManipulator.</span>getContrastRatio (foreground, background)](#apidoc.element.material-ui.colorManipulator.getContrastRatio)
1.  [function <span class="apidocSignatureSpan">material-ui.colorManipulator.</span>getLuminance (color)](#apidoc.element.material-ui.colorManipulator.getLuminance)
1.  [function <span class="apidocSignatureSpan">material-ui.colorManipulator.</span>lighten (color, coefficient)](#apidoc.element.material-ui.colorManipulator.lighten)

#### [module material-ui.dateUtils](#apidoc.module.material-ui.dateUtils)
1.  [function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>addDays (d, days)](#apidoc.element.material-ui.dateUtils.addDays)
1.  [function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>addMonths (d, months)](#apidoc.element.material-ui.dateUtils.addMonths)
1.  [function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>addYears (d, years)](#apidoc.element.material-ui.dateUtils.addYears)
1.  [function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>cloneAsDate (d)](#apidoc.element.material-ui.dateUtils.cloneAsDate)
1.  [function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>cloneDate (d)](#apidoc.element.material-ui.dateUtils.cloneDate)
1.  [function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>dateTimeFormat (locale, options)](#apidoc.element.material-ui.dateUtils.dateTimeFormat)
1.  [function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>formatIso (date)](#apidoc.element.material-ui.dateUtils.formatIso)
1.  [function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>getDaysInMonth (d)](#apidoc.element.material-ui.dateUtils.getDaysInMonth)
1.  [function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>getFirstDayOfMonth (d)](#apidoc.element.material-ui.dateUtils.getFirstDayOfMonth)
1.  [function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>getFirstDayOfWeek ()](#apidoc.element.material-ui.dateUtils.getFirstDayOfWeek)
1.  [function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>getWeekArray (d, firstDayOfWeek)](#apidoc.element.material-ui.dateUtils.getWeekArray)
1.  [function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>isAfterDate (d1, d2)](#apidoc.element.material-ui.dateUtils.isAfterDate)
1.  [function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>isBeforeDate (d1, d2)](#apidoc.element.material-ui.dateUtils.isBeforeDate)
1.  [function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>isBetweenDates (dateToCheck, startDate, endDate)](#apidoc.element.material-ui.dateUtils.isBetweenDates)
1.  [function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>isEqualDate (d1, d2)](#apidoc.element.material-ui.dateUtils.isEqualDate)
1.  [function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>localizedWeekday (DateTimeFormat, locale, day, firstDayOfWeek)](#apidoc.element.material-ui.dateUtils.localizedWeekday)
1.  [function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>monthDiff (d1, d2)](#apidoc.element.material-ui.dateUtils.monthDiff)
1.  [function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>yearDiff (d1, d2)](#apidoc.element.material-ui.dateUtils.yearDiff)

#### [module material-ui.deprecatedExport](#apidoc.module.material-ui.deprecatedExport)
1.  [function <span class="apidocSignatureSpan">material-ui.deprecatedExport.</span>default (object, deprecatedPath, supportedPath)](#apidoc.element.material-ui.deprecatedExport.default)

#### [module material-ui.deprecatedPropType](#apidoc.module.material-ui.deprecatedPropType)
1.  [function <span class="apidocSignatureSpan">material-ui.deprecatedPropType.</span>default (validator, reason)](#apidoc.element.material-ui.deprecatedPropType.default)

#### [module material-ui.getMuiTheme](#apidoc.module.material-ui.getMuiTheme)
1.  [function <span class="apidocSignatureSpan">material-ui.getMuiTheme.</span>default (muiTheme)](#apidoc.element.material-ui.getMuiTheme.default)

#### [module material-ui.iOSHelpers](#apidoc.module.material-ui.iOSHelpers)
1.  [function <span class="apidocSignatureSpan">material-ui.iOSHelpers.</span>getOffsetTop (elem)](#apidoc.element.material-ui.iOSHelpers.getOffsetTop)
1.  [function <span class="apidocSignatureSpan">material-ui.iOSHelpers.</span>isIOS ()](#apidoc.element.material-ui.iOSHelpers.isIOS)

#### [module material-ui.makeSelectable](#apidoc.module.material-ui.makeSelectable)
1.  [function <span class="apidocSignatureSpan">material-ui.</span>makeSelectable (MyComponent)](#apidoc.element.material-ui.makeSelectable.makeSelectable)
1.  [function <span class="apidocSignatureSpan">material-ui.makeSelectable.</span>default (MyComponent)](#apidoc.element.material-ui.makeSelectable.default)

#### [module material-ui.menuUtils](#apidoc.module.material-ui.menuUtils)
1.  [function <span class="apidocSignatureSpan">material-ui.menuUtils.</span>HotKeyHolder ()](#apidoc.element.material-ui.menuUtils.HotKeyHolder)

#### [module material-ui.muiThemeable](#apidoc.module.material-ui.muiThemeable)
1.  [function <span class="apidocSignatureSpan">material-ui.muiThemeable.</span>default ()](#apidoc.element.material-ui.muiThemeable.default)

#### [module material-ui.navigation_arrow_drop_right](#apidoc.module.material-ui.navigation_arrow_drop_right)
1.  [function <span class="apidocSignatureSpan">material-ui.navigation_arrow_drop_right.</span>default ()](#apidoc.element.material-ui.navigation_arrow_drop_right.default)

#### [module material-ui.rtl](#apidoc.module.material-ui.rtl)
1.  [function <span class="apidocSignatureSpan">material-ui.rtl.</span>default (muiTheme)](#apidoc.element.material-ui.rtl.default)

#### [module material-ui.timeUtils](#apidoc.module.material-ui.timeUtils)
1.  [function <span class="apidocSignatureSpan">material-ui.timeUtils.</span>addHours (d, hours)](#apidoc.element.material-ui.timeUtils.addHours)
1.  [function <span class="apidocSignatureSpan">material-ui.timeUtils.</span>addMinutes (d, minutes)](#apidoc.element.material-ui.timeUtils.addMinutes)
1.  [function <span class="apidocSignatureSpan">material-ui.timeUtils.</span>addSeconds (d, seconds)](#apidoc.element.material-ui.timeUtils.addSeconds)
1.  [function <span class="apidocSignatureSpan">material-ui.timeUtils.</span>formatTime (date)](#apidoc.element.material-ui.timeUtils.formatTime)
1.  [function <span class="apidocSignatureSpan">material-ui.timeUtils.</span>getTouchEventOffsetValues (event)](#apidoc.element.material-ui.timeUtils.getTouchEventOffsetValues)
1.  [function <span class="apidocSignatureSpan">material-ui.timeUtils.</span>isInner (props)](#apidoc.element.material-ui.timeUtils.isInner)
1.  [function <span class="apidocSignatureSpan">material-ui.timeUtils.</span>rad2deg (rad)](#apidoc.element.material-ui.timeUtils.rad2deg)

#### [module material-ui.withWidth](#apidoc.module.material-ui.withWidth)
1.  [function <span class="apidocSignatureSpan">material-ui.withWidth.</span>default ()](#apidoc.element.material-ui.withWidth.default)
1.  number <span class="apidocSignatureSpan">material-ui.withWidth.</span>LARGE
1.  number <span class="apidocSignatureSpan">material-ui.withWidth.</span>MEDIUM
1.  number <span class="apidocSignatureSpan">material-ui.withWidth.</span>SMALL



# <a name="apidoc.module.material-ui"></a>[module material-ui](#apidoc.module.material-ui)

#### <a name="apidoc.element.material-ui.AppBar"></a>[function <span class="apidocSignatureSpan">material-ui.</span>AppBar ()](#apidoc.element.material-ui.AppBar)
- description and source-code
```javascript
function AppBar() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, AppBar);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = AppBar.__proto__ || (0, _getPrototypeOf2
.default)(AppBar)).call.apply(_ref, [this].concat(args))), _this), _this.handleTouchTapLeftIconButton = function (event) {
    if (_this.props.onLeftIconButtonTouchTap) {
      _this.props.onLeftIconButtonTouchTap(event);
    }
  }, _this.handleTouchTapRightIconButton = function (event) {
    if (_this.props.onRightIconButtonTouchTap) {
      _this.props.onRightIconButtonTouchTap(event);
    }
  }, _this.handleTitleTouchTap = function (event) {
    if (_this.props.onTitleTouchTap) {
      _this.props.onTitleTouchTap(event);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete"></a>[function <span class="apidocSignatureSpan">material-ui.</span>AutoComplete ()](#apidoc.element.material-ui.AutoComplete)
- description and source-code
```javascript
function AutoComplete() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, AutoComplete);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = AutoComplete.__proto__ || (0, _getPrototypeOf2
.default)(AutoComplete)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    anchorEl: null,
    focusTextField: true,
    open: false,
    searchText: undefined
  }, _this.handleRequestClose = function () {
    // Only take into account the Popover clickAway when we are
    // not focusing the TextField.
    if (!_this.state.focusTextField) {
      _this.close();
    }
  }, _this.handleMouseDown = function (event) {
    // Keep the TextField focused
    event.preventDefault();
  }, _this.handleItemTouchTap = function (event, child) {
    var dataSource = _this.props.dataSource;

    var index = parseInt(child.key, 10);
    var chosenRequest = dataSource[index];
    var searchText = _this.chosenRequestText(chosenRequest);

    _this.setState({
      searchText: searchText
    }, function () {
      _this.props.onUpdateInput(searchText, _this.props.dataSource, {
        source: 'touchTap'
      });

      _this.timerTouchTapCloseId = setTimeout(function () {
        _this.timerTouchTapCloseId = null;
        _this.close();
        _this.props.onNewRequest(chosenRequest, index);
      }, _this.props.menuCloseDelay);
    });
  }, _this.chosenRequestText = function (chosenRequest) {
    if (typeof chosenRequest === 'string') {
      return chosenRequest;
    } else {
      return chosenRequest[_this.props.dataSourceConfig.text];
    }
  }, _this.handleEscKeyDown = function () {
    _this.close();
  }, _this.handleKeyDown = function (event) {
    if (_this.props.onKeyDown) _this.props.onKeyDown(event);

    switch ((0, _keycode2.default)(event)) {
      case 'enter':
        _this.close();
        var searchText = _this.state.searchText;
        if (searchText !== '') {
          _this.props.onNewRequest(searchText, -1);
        }
        break;

      case 'esc':
        _this.close();
        break;

      case 'down':
        event.preventDefault();
        _this.setState({
          open: true,
          focusTextField: false,
          anchorEl: _reactDom2.default.findDOMNode(_this.refs.searchTextField)
        });
        break;

      default:
        break;
    }
  }, _this.handleChange = function (event) {
    var searchText = event.target.value;

    // Make sure that we have a new searchText.
    // Fix an issue with a Cordova Webview
    if (searchText === _this.state.searchText) {
      return;
    }

    _this.setState({
      searchText: searchText,
      open: true,
      anchorEl: _reactDom2.default.findDOMNode(_this.refs.searchTextField)
    }, function () {
      _this.props.onUpdateInput(searchText, _this.props.dataSource, {
        source: 'change'
      });
    });
  }, _this.handleBlur = function (event) {
    if (_this.state.focusTextField && _this.timerTouchTapCloseId === null) {
      _this.timerBlurClose = setTimeout(function () {
        _this.close();
      }, 0);
    }

    if (_this.props.onBlur) {
      _this.props.onBlur(event);
    }
  }, _this.handleFocus = function (event) {
    if (!_this.state.open && _this.props.openOnFocus) {
      _this.setState({
        open: true,
        anchorEl: _reactDom2.default.findDOMNode(_this.refs.searchTextField)
      });
    }

    _this.setState({
      focusTextField: true
    });

    if (_this.props.onFocus) {
      _this.props.onFocus(event);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.Avatar"></a>[function <span class="apidocSignatureSpan">material-ui.</span>Avatar ()](#apidoc.element.material-ui.Avatar)
- description and source-code
```javascript
function Avatar() {
  (0, _classCallCheck3.default)(this, Avatar);
  return (0, _possibleConstructorReturn3.default)(this, (Avatar.__proto__ || (0, _getPrototypeOf2.default)(Avatar)).apply(this,
arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.Badge"></a>[function <span class="apidocSignatureSpan">material-ui.</span>Badge ()](#apidoc.element.material-ui.Badge)
- description and source-code
```javascript
function Badge() {
  (0, _classCallCheck3.default)(this, Badge);
  return (0, _possibleConstructorReturn3.default)(this, (Badge.__proto__ || (0, _getPrototypeOf2.default)(Badge)).apply(this, arguments
));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.BottomNavigation"></a>[function <span class="apidocSignatureSpan">material-ui.</span>BottomNavigation (props, context)](#apidoc.element.material-ui.BottomNavigation)
- description and source-code
```javascript
function BottomNavigation(props, context) {
  var children = props.children,
      style = props.style,
      selectedIndex = props.selectedIndex,
      other = (0, _objectWithoutProperties3.default)(props, ['children', 'style', 'selectedIndex']);
  var prepareStyles = context.muiTheme.prepareStyles;

  var styles = getStyles(props, context);

  var preparedChildren = _react.Children.map(children, function (child, index) {
    return (0, _react.cloneElement)(child, {
      style: (0, _simpleAssign2.default)({}, styles.item, child.props.style),
      selected: index === selectedIndex
    });
  });

  return _react2.default.createElement(
    'div',
    (0, _extends3.default)({}, other, { style: prepareStyles((0, _simpleAssign2.default)({}, styles.root, style)) }),
    preparedChildren
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.BottomNavigationItem"></a>[function <span class="apidocSignatureSpan">material-ui.</span>BottomNavigationItem (props, context)](#apidoc.element.material-ui.BottomNavigationItem)
- description and source-code
```javascript
function BottomNavigationItem(props, context) {
  var label = props.label,
      icon = props.icon,
      style = props.style,
      other = (0, _objectWithoutProperties3.default)(props, ['label', 'icon', 'style']);
  var prepareStyles = context.muiTheme.prepareStyles;

  var styles = getStyles(props, context);

  var styledIcon = (0, _react.cloneElement)(icon, {
    style: (0, _simpleAssign2.default)({}, styles.icon, icon.props.style),
    color: icon.props.color || styles.iconColor
  });

  return _react2.default.createElement(
    _EnhancedButton2.default,
    (0, _extends3.default)({}, other, { style: (0, _simpleAssign2.default)({}, styles.root, style) }),
    styledIcon,
    _react2.default.createElement(
      'div',
      { style: prepareStyles(styles.label) },
      label
    )
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.Card"></a>[function <span class="apidocSignatureSpan">material-ui.</span>Card ()](#apidoc.element.material-ui.Card)
- description and source-code
```javascript
function Card() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, Card);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = Card.__proto__ || (0, _getPrototypeOf2.
default)(Card)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    expanded: null
  }, _this.handleExpanding = function (event) {
    event.preventDefault();
    var newExpandedState = !_this.state.expanded;
    // no automatic state update when the component is controlled
    if (_this.props.expanded === null) {
      _this.setState({ expanded: newExpandedState });
    }
    if (_this.props.onExpandChange) {
      _this.props.onExpandChange(newExpandedState);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.CardActions"></a>[function <span class="apidocSignatureSpan">material-ui.</span>CardActions ()](#apidoc.element.material-ui.CardActions)
- description and source-code
```javascript
function CardActions() {
  (0, _classCallCheck3.default)(this, CardActions);
  return (0, _possibleConstructorReturn3.default)(this, (CardActions.__proto__ || (0, _getPrototypeOf2.default)(CardActions)).apply
(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.CardHeader"></a>[function <span class="apidocSignatureSpan">material-ui.</span>CardHeader ()](#apidoc.element.material-ui.CardHeader)
- description and source-code
```javascript
function CardHeader() {
  (0, _classCallCheck3.default)(this, CardHeader);
  return (0, _possibleConstructorReturn3.default)(this, (CardHeader.__proto__ || (0, _getPrototypeOf2.default)(CardHeader)).apply
(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.CardMedia"></a>[function <span class="apidocSignatureSpan">material-ui.</span>CardMedia ()](#apidoc.element.material-ui.CardMedia)
- description and source-code
```javascript
function CardMedia() {
  (0, _classCallCheck3.default)(this, CardMedia);
  return (0, _possibleConstructorReturn3.default)(this, (CardMedia.__proto__ || (0, _getPrototypeOf2.default)(CardMedia)).apply(
this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.CardText"></a>[function <span class="apidocSignatureSpan">material-ui.</span>CardText ()](#apidoc.element.material-ui.CardText)
- description and source-code
```javascript
function CardText() {
  (0, _classCallCheck3.default)(this, CardText);
  return (0, _possibleConstructorReturn3.default)(this, (CardText.__proto__ || (0, _getPrototypeOf2.default)(CardText)).apply(this
, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.CardTitle"></a>[function <span class="apidocSignatureSpan">material-ui.</span>CardTitle ()](#apidoc.element.material-ui.CardTitle)
- description and source-code
```javascript
function CardTitle() {
  (0, _classCallCheck3.default)(this, CardTitle);
  return (0, _possibleConstructorReturn3.default)(this, (CardTitle.__proto__ || (0, _getPrototypeOf2.default)(CardTitle)).apply(
this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.Checkbox"></a>[function <span class="apidocSignatureSpan">material-ui.</span>Checkbox ()](#apidoc.element.material-ui.Checkbox)
- description and source-code
```javascript
function Checkbox() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, Checkbox);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = Checkbox.__proto__ || (0, _getPrototypeOf2
.default)(Checkbox)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    switched: false
  }, _this.handleStateChange = function (newSwitched) {
    _this.setState({
      switched: newSwitched
    });
  }, _this.handleCheck = function (event, isInputChecked) {
    if (_this.props.onCheck) {
      _this.props.onCheck(event, isInputChecked);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.Chip"></a>[function <span class="apidocSignatureSpan">material-ui.</span>Chip ()](#apidoc.element.material-ui.Chip)
- description and source-code
```javascript
function Chip() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, Chip);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = Chip.__proto__ || (0, _getPrototypeOf2.
default)(Chip)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    clicked: false,
    deleteHovered: false,
    focused: false,
    hovered: false
  }, _this.handleBlur = function (event) {
    _this.setState({ clicked: false, focused: false });
    _this.props.onBlur(event);
  }, _this.handleFocus = function (event) {
    if (_this.props.onTouchTap || _this.props.onRequestDelete) {
      _this.setState({ focused: true });
    }
    _this.props.onFocus(event);
  }, _this.handleKeyboardFocus = function (event, keyboardFocused) {
    if (keyboardFocused) {
      _this.handleFocus();
      _this.props.onFocus(event);
    } else {
      _this.handleBlur();
    }

    _this.props.onKeyboardFocus(event, keyboardFocused);
  }, _this.handleKeyDown = function (event) {
    if ((0, _keycode2.default)(event) === 'backspace') {
      event.preventDefault();
      if (_this.props.onRequestDelete) {
        _this.props.onRequestDelete(event);
      }
    }
    _this.props.onKeyDown(event);
  }, _this.handleMouseDown = function (event) {
    // Only listen to left clicks
    if (event.button === 0) {
      event.stopPropagation();
      if (_this.props.onTouchTap) {
        _this.setState({ clicked: true });
      }
    }
    _this.props.onMouseDown(event);
  }, _this.handleMouseEnter = function (event) {
    if (_this.props.onTouchTap) {
      _this.setState({ hovered: true });
    }
    _this.props.onMouseEnter(event);
  }, _this.handleMouseEnterDeleteIcon = function () {
    _this.setState({ deleteHovered: true });
  }, _this.handleMouseLeave = function (event) {
    _this.setState({
      clicked: false,
      hovered: false
    });
    _this.props.onMouseLeave(event);
  }, _this.handleMouseLeaveDeleteIcon = function () {
    _this.setState({ deleteHovered: false });
  }, _this.handleMouseUp = function (event) {
    _this.setState({ clicked: false });
    _this.props.onMouseUp(event);
  }, _this.handleTouchTapDeleteIcon = function (event) {
    // Stop the event from bubbling up to the 'Chip'
    event.stopPropagation();
    _this.props.onRequestDelete(event);
  }, _this.handleTouchEnd = function (event) {
    _this.setState({ clicked: false });
    _this.props.onTouchEnd(event);
  }, _this.handleTouchStart = function (event) {
    event.stopPropagation();
    if (_this.props.onTouchTap) {
      _this.setState({ clicked: true });
    }
    _this.props.onTouchStart(event);
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.CircularProgress"></a>[function <span class="apidocSignatureSpan">material-ui.</span>CircularProgress ()](#apidoc.element.material-ui.CircularProgress)
- description and source-code
```javascript
function CircularProgress() {
  (0, _classCallCheck3.default)(this, CircularProgress);
  return (0, _possibleConstructorReturn3.default)(this, (CircularProgress.__proto__ || (0, _getPrototypeOf2.default)(CircularProgress
)).apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.DatePicker"></a>[function <span class="apidocSignatureSpan">material-ui.</span>DatePicker ()](#apidoc.element.material-ui.DatePicker)
- description and source-code
```javascript
function DatePicker() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, DatePicker);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = DatePicker.__proto__ || (0, _getPrototypeOf2
.default)(DatePicker)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    date: undefined
  }, _this.handleAccept = function (date) {
    if (!_this.isControlled()) {
      _this.setState({
        date: date
      });
    }
    if (_this.props.onChange) {
      _this.props.onChange(null, date);
    }
  }, _this.handleFocus = function (event) {
    event.target.blur();
    if (_this.props.onFocus) {
      _this.props.onFocus(event);
    }
  }, _this.handleTouchTap = function (event) {
    if (_this.props.onTouchTap) {
      _this.props.onTouchTap(event);
    }

    if (!_this.props.disabled) {
      setTimeout(function () {
        _this.openDialog();
      }, 0);
    }
  }, _this.formatDate = function (date) {
    if (_this.props.locale) {
      var DateTimeFormat = _this.props.DateTimeFormat || _dateUtils.dateTimeFormat;
      return new DateTimeFormat(_this.props.locale, {
        day: 'numeric',
        month: 'numeric',
        year: 'numeric'
      }).format(date);
    } else {
      return (0, _dateUtils.formatIso)(date);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.Dialog"></a>[function <span class="apidocSignatureSpan">material-ui.</span>Dialog ()](#apidoc.element.material-ui.Dialog)
- description and source-code
```javascript
function Dialog() {
  var _ref3;

  var _temp3, _this3, _ret3;

  (0, _classCallCheck3.default)(this, Dialog);

  for (var _len3 = arguments.length, args = Array(_len3), _key3 = 0; _key3 < _len3; _key3++) {
    args[_key3] = arguments[_key3];
  }

  return _ret3 = (_temp3 = (_this3 = (0, _possibleConstructorReturn3.default)(this, (_ref3 = Dialog.__proto__ || (0, _getPrototypeOf2
.default)(Dialog)).call.apply(_ref3, [this].concat(args))), _this3), _this3.renderLayer = function () {
    return _react2.default.createElement(DialogInline, _this3.props);
  }, _temp3), (0, _possibleConstructorReturn3.default)(_this3, _ret3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.Divider"></a>[function <span class="apidocSignatureSpan">material-ui.</span>Divider (props, context)](#apidoc.element.material-ui.Divider)
- description and source-code
```javascript
function Divider(props, context) {
  var inset = props.inset,
      style = props.style,
      other = (0, _objectWithoutProperties3.default)(props, ['inset', 'style']);
  var _context$muiTheme = context.muiTheme,
      baseTheme = _context$muiTheme.baseTheme,
      prepareStyles = _context$muiTheme.prepareStyles;


  var styles = {
    root: {
      margin: 0,
      marginTop: -1,
      marginLeft: inset ? 72 : 0,
      height: 1,
      border: 'none',
      backgroundColor: baseTheme.palette.borderColor
    }
  };

  return _react2.default.createElement('hr', (0, _extends3.default)({}, other, { style: prepareStyles((0, _simpleAssign2.default
)(styles.root, style)) }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.Drawer"></a>[function <span class="apidocSignatureSpan">material-ui.</span>Drawer ()](#apidoc.element.material-ui.Drawer)
- description and source-code
```javascript
function Drawer() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, Drawer);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = Drawer.__proto__ || (0, _getPrototypeOf2
.default)(Drawer)).call.apply(_ref, [this].concat(args))), _this), _this.handleTouchTapOverlay = function (event) {
    event.preventDefault();
    _this.close('clickaway');
  }, _this.handleKeyUp = function (event) {
    if (_this.state.open && !_this.props.docked && (0, _keycode2.default)(event) === 'esc') {
      _this.close('escape');
    }
  }, _this.onBodyTouchStart = function (event) {
    var swipeAreaWidth = _this.props.swipeAreaWidth;

    var touchStartX = event.touches[0].pageX;
    var touchStartY = event.touches[0].pageY;

    // Open only if swiping from far left (or right) while closed
    if (swipeAreaWidth !== null && !_this.state.open) {
      if (_this.props.openSecondary) {
        // If openSecondary is true calculate from the far right
        if (touchStartX < document.body.offsetWidth - swipeAreaWidth) return;
      } else {
        // If openSecondary is false calculate from the far left
        if (touchStartX > swipeAreaWidth) return;
      }
    }

    if (!_this.state.open && (openNavEventHandler !== _this.onBodyTouchStart || _this.props.disableSwipeToOpen)) {
      return;
    }

    _this.maybeSwiping = true;
    _this.touchStartX = touchStartX;
    _this.touchStartY = touchStartY;

    document.body.addEventListener('touchmove', _this.onBodyTouchMove);
    document.body.addEventListener('touchend', _this.onBodyTouchEnd);
    document.body.addEventListener('touchcancel', _this.onBodyTouchEnd);
  }, _this.onBodyTouchMove = function (event) {
    var currentX = event.touches[0].pageX;
    var currentY = event.touches[0].pageY;

    if (_this.state.swiping) {
      event.preventDefault();
      _this.setPosition(_this.getTranslateX(currentX));
    } else if (_this.maybeSwiping) {
      var dXAbs = Math.abs(currentX - _this.touchStartX);
      var dYAbs = Math.abs(currentY - _this.touchStartY);
      // If the user has moved his thumb ten pixels in either direction,
      // we can safely make an assumption about whether he was intending
      // to swipe or scroll.
      var threshold = 10;

      if (dXAbs > threshold && dYAbs <= threshold) {
        _this.swipeStartX = currentX;
        _this.setState({
          swiping: _this.state.open ? 'closing' : 'opening'
        });
        _this.setPosition(_this.getTranslateX(currentX));
      } else if (dXAbs <= threshold && dYAbs > threshold) {
        _this.onBodyTouchEnd();
      }
    }
  }, _this.onBodyTouchEnd = function (event) {
    if (_this.state.swiping) {
      var currentX = event.changedTouches[0].pageX;
      var translateRatio = _this.getTranslateX(currentX) / _this.getMaxTranslateX();

      _this.maybeSwiping = false;
      var swiping = _this.state.swiping;
      _this.setState({
        swiping: null
      });

      // We have to open or close after setting swiping to null,
      // because only then CSS transition is enabled.
      if (translateRatio > 0.5) {
        if (swiping === 'opening') {
          _this.setPosition(_this.getMaxTranslateX());
        } else {
          _this.close('swipe');
        }
      } else {
        if (swiping === 'opening') {
          _this.open('swipe');
        } else {
          _this.setPosition(0);
        }
      }
    } else {
      _this.maybeSwiping = false;
    }

    document.body.removeEventListener('touchmove', _this.onBodyTouchMove);
    document.body.removeEventListener('touchend', _this.onBodyTouchEnd);
    document.body.removeEventListener('touchcancel', _this.onBodyTouchEnd);
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.DropDownMenu"></a>[function <span class="apidocSignatureSpan">material-ui.</span>DropDownMenu ()](#apidoc.element.material-ui.DropDownMenu)
- description and source-code
```javascript
function DropDownMenu() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, DropDownMenu);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = DropDownMenu.__proto__ || (0, _getPrototypeOf2
.default)(DropDownMenu)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    open: false
  }, _this.rootNode = undefined, _this.arrowNode = undefined, _this.handleTouchTapControl = function (event) {
    event.preventDefault();
    if (!_this.props.disabled) {
      _this.setState({
        open: !_this.state.open,
        anchorEl: _this.rootNode
      });
    }
  }, _this.handleRequestCloseMenu = function () {
    _this.close(false);
  }, _this.handleEscKeyDownMenu = function () {
    _this.close(true);
  }, _this.handleKeyDown = function (event) {
    switch ((0, _keycode2.default)(event)) {
      case 'up':
      case 'down':
      case 'space':
      case 'enter':
        event.preventDefault();
        _this.setState({
          open: true,
          anchorEl: _this.rootNode
        });
        break;
    }
  }, _this.handleItemTouchTap = function (event, child, index) {
    if (_this.props.multiple) {
      if (!_this.state.open) {
        _this.setState({ open: true });
      }
    } else {
      event.persist();
      _this.setState({
        open: false
      }, function () {
        if (_this.props.onChange) {
          _this.props.onChange(event, index, child.props.value);
        }

        _this.close(_events2.default.isKeyboard(event));
      });
    }
  }, _this.handleChange = function (event, value) {
    if (_this.props.multiple && _this.props.onChange) {
      _this.props.onChange(event, undefined, value);
    }
  }, _this.close = function (isKeyboard) {
    _this.setState({
      open: false
    }, function () {
      if (_this.props.onClose) {
        _this.props.onClose();
      }

      if (isKeyboard) {
        var dropArrow = _this.arrowNode;
        var dropNode = _reactDom2.default.findDOMNode(dropArrow);
        dropNode.focus();
        dropArrow.setKeyboardFocus(true);
      }
    });
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.FlatButton"></a>[function <span class="apidocSignatureSpan">material-ui.</span>FlatButton ()](#apidoc.element.material-ui.FlatButton)
- description and source-code
```javascript
function FlatButton() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, FlatButton);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = FlatButton.__proto__ || (0, _getPrototypeOf2
.default)(FlatButton)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    hovered: false,
    isKeyboardFocused: false,
    touch: false
  }, _this.handleKeyboardFocus = function (event, isKeyboardFocused) {
    _this.setState({ isKeyboardFocused: isKeyboardFocused });
    _this.props.onKeyboardFocus(event, isKeyboardFocused);
  }, _this.handleMouseEnter = function (event) {
    // Cancel hover styles for touch devices
    if (!_this.state.touch) _this.setState({ hovered: true });
    _this.props.onMouseEnter(event);
  }, _this.handleMouseLeave = function (event) {
    _this.setState({ hovered: false });
    _this.props.onMouseLeave(event);
  }, _this.handleTouchStart = function (event) {
    _this.setState({ touch: true });
    _this.props.onTouchStart(event);
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.FloatingActionButton"></a>[function <span class="apidocSignatureSpan">material-ui.</span>FloatingActionButton ()](#apidoc.element.material-ui.FloatingActionButton)
- description and source-code
```javascript
function FloatingActionButton() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, FloatingActionButton);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = FloatingActionButton.__proto__ || (0, _getPrototypeOf2
.default)(FloatingActionButton)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    hovered: false,
    touch: false,
    zDepth: undefined
  }, _this.handleMouseDown = function (event) {
    // only listen to left clicks
    if (event.button === 0) {
      _this.setState({ zDepth: _this.props.zDepth + 1 });
    }
    if (_this.props.onMouseDown) _this.props.onMouseDown(event);
  }, _this.handleMouseUp = function (event) {
    _this.setState({ zDepth: _this.props.zDepth });
    if (_this.props.onMouseUp) {
      _this.props.onMouseUp(event);
    }
  }, _this.handleMouseLeave = function (event) {
    if (!_this.refs.container.isKeyboardFocused()) {
      _this.setState({ zDepth: _this.props.zDepth, hovered: false });
    }
    if (_this.props.onMouseLeave) {
      _this.props.onMouseLeave(event);
    }
  }, _this.handleMouseEnter = function (event) {
    if (!_this.refs.container.isKeyboardFocused() && !_this.state.touch) {
      _this.setState({ hovered: true });
    }
    if (_this.props.onMouseEnter) {
      _this.props.onMouseEnter(event);
    }
  }, _this.handleTouchStart = function (event) {
    _this.setState({
      touch: true,
      zDepth: _this.props.zDepth + 1
    });
    if (_this.props.onTouchStart) {
      _this.props.onTouchStart(event);
    }
  }, _this.handleTouchEnd = function (event) {
    _this.setState({
      touch: true,
      zDepth: _this.props.zDepth
    });
    if (_this.props.onTouchEnd) {
      _this.props.onTouchEnd(event);
    }
  }, _this.handleKeyboardFocus = function (event, keyboardFocused) {
    if (keyboardFocused && !_this.props.disabled) {
      _this.setState({ zDepth: _this.props.zDepth + 1 });
      _this.refs.overlay.style.backgroundColor = (0, _colorManipulator.fade)(getStyles(_this.props, _this.context).icon.color, 0
.4);
    } else if (!_this.state.hovered) {
      _this.setState({ zDepth: _this.props.zDepth });
      _this.refs.overlay.style.backgroundColor = 'transparent';
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.FontIcon"></a>[function <span class="apidocSignatureSpan">material-ui.</span>FontIcon ()](#apidoc.element.material-ui.FontIcon)
- description and source-code
```javascript
function FontIcon() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, FontIcon);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = FontIcon.__proto__ || (0, _getPrototypeOf2
.default)(FontIcon)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    hovered: false
  }, _this.handleMouseLeave = function (event) {
    // hover is needed only when a hoverColor is defined
    if (_this.props.hoverColor !== undefined) {
      _this.setState({ hovered: false });
    }
    if (_this.props.onMouseLeave) {
      _this.props.onMouseLeave(event);
    }
  }, _this.handleMouseEnter = function (event) {
    // hover is needed only when a hoverColor is defined
    if (_this.props.hoverColor !== undefined) {
      _this.setState({ hovered: true });
    }
    if (_this.props.onMouseEnter) {
      _this.props.onMouseEnter(event);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.GridList"></a>[function <span class="apidocSignatureSpan">material-ui.</span>GridList ()](#apidoc.element.material-ui.GridList)
- description and source-code
```javascript
function GridList() {
  (0, _classCallCheck3.default)(this, GridList);
  return (0, _possibleConstructorReturn3.default)(this, (GridList.__proto__ || (0, _getPrototypeOf2.default)(GridList)).apply(this
, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.GridTile"></a>[function <span class="apidocSignatureSpan">material-ui.</span>GridTile ()](#apidoc.element.material-ui.GridTile)
- description and source-code
```javascript
function GridTile() {
  (0, _classCallCheck3.default)(this, GridTile);
  return (0, _possibleConstructorReturn3.default)(this, (GridTile.__proto__ || (0, _getPrototypeOf2.default)(GridTile)).apply(this
, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.IconButton"></a>[function <span class="apidocSignatureSpan">material-ui.</span>IconButton ()](#apidoc.element.material-ui.IconButton)
- description and source-code
```javascript
function IconButton() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, IconButton);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = IconButton.__proto__ || (0, _getPrototypeOf2
.default)(IconButton)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    hovered: false,
    isKeyboardFocused: false,
    // Not to be confonded with the touch property.
    // This state is to determined if it's a mobile device.
    touch: false,
    tooltipShown: false
  }, _this.handleBlur = function (event) {
    _this.hideTooltip();
    if (_this.props.onBlur) {
      _this.props.onBlur(event);
    }
  }, _this.handleFocus = function (event) {
    _this.showTooltip();
    if (_this.props.onFocus) {
      _this.props.onFocus(event);
    }
  }, _this.handleMouseLeave = function (event) {
    if (!_this.button.isKeyboardFocused()) {
      _this.hideTooltip();
    }
    _this.setState({ hovered: false });
    if (_this.props.onMouseLeave) {
      _this.props.onMouseLeave(event);
    }
  }, _this.handleMouseOut = function (event) {
    if (_this.props.disabled) _this.hideTooltip();
    if (_this.props.onMouseOut) _this.props.onMouseOut(event);
  }, _this.handleMouseEnter = function (event) {
    _this.showTooltip();

    // Cancel hover styles for touch devices
    if (!_this.state.touch) {
      _this.setState({ hovered: true });
    }
    if (_this.props.onMouseEnter) {
      _this.props.onMouseEnter(event);
    }
  }, _this.handleTouchStart = function (event) {
    _this.setState({ touch: true });

    if (_this.props.onTouchStart) {
      _this.props.onTouchStart(event);
    }
  }, _this.handleKeyboardFocus = function (event, isKeyboardFocused) {
    var _this$props = _this.props,
        disabled = _this$props.disabled,
        onFocus = _this$props.onFocus,
        onBlur = _this$props.onBlur,
        onKeyboardFocus = _this$props.onKeyboardFocus;

    if (isKeyboardFocused && !disabled) {
      _this.showTooltip();
      if (onFocus) {
        onFocus(event);
      }
    } else {
      _this.hideTooltip();
      if (onBlur) {
        onBlur(event);
      }
    }

    _this.setState({ isKeyboardFocused: isKeyboardFocused });
    if (onKeyboardFocus) {
      onKeyboardFocus(event, isKeyboardFocused);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.IconMenu"></a>[function <span class="apidocSignatureSpan">material-ui.</span>IconMenu ()](#apidoc.element.material-ui.IconMenu)
- description and source-code
```javascript
function IconMenu() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, IconMenu);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = IconMenu.__proto__ || (0, _getPrototypeOf2
.default)(IconMenu)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    menuInitiallyKeyboardFocused: false,
    open: false
  }, _this.handleItemTouchTap = function (event, child) {
    if (_this.props.touchTapCloseDelay !== 0 && !child.props.hasOwnProperty('menuItems')) {
      (function () {
        var isKeyboard = _events2.default.isKeyboard(event);
        _this.timerCloseId = setTimeout(function () {
          _this.close(isKeyboard ? 'enter' : 'itemTap', isKeyboard);
        }, _this.props.touchTapCloseDelay);
      })();
    }

    _this.props.onItemTouchTap(event, child);
  }, _this.handleRequestClose = function (reason) {
    _this.close(reason);
  }, _this.handleEscKeyDownMenu = function (event) {
    _this.close('escape', event);
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.LinearProgress"></a>[function <span class="apidocSignatureSpan">material-ui.</span>LinearProgress ()](#apidoc.element.material-ui.LinearProgress)
- description and source-code
```javascript
function LinearProgress() {
  (0, _classCallCheck3.default)(this, LinearProgress);
  return (0, _possibleConstructorReturn3.default)(this, (LinearProgress.__proto__ || (0, _getPrototypeOf2.default)(LinearProgress
)).apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.List"></a>[function <span class="apidocSignatureSpan">material-ui.</span>List ()](#apidoc.element.material-ui.List)
- description and source-code
```javascript
function List() {
  (0, _classCallCheck3.default)(this, List);
  return (0, _possibleConstructorReturn3.default)(this, (List.__proto__ || (0, _getPrototypeOf2.default)(List)).apply(this, arguments
));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.ListItem"></a>[function <span class="apidocSignatureSpan">material-ui.</span>ListItem ()](#apidoc.element.material-ui.ListItem)
- description and source-code
```javascript
function ListItem() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, ListItem);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = ListItem.__proto__ || (0, _getPrototypeOf2
.default)(ListItem)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    hovered: false,
    isKeyboardFocused: false,
    open: false,
    rightIconButtonHovered: false,
    rightIconButtonKeyboardFocused: false,
    touch: false
  }, _this.handleKeyboardFocus = function (event, isKeyboardFocused) {
    _this.setState({ isKeyboardFocused: isKeyboardFocused });
    _this.props.onKeyboardFocus(event, isKeyboardFocused);
  }, _this.handleMouseEnter = function (event) {
    if (!_this.state.touch) _this.setState({ hovered: true });
    _this.props.onMouseEnter(event);
  }, _this.handleMouseLeave = function (event) {
    _this.setState({ hovered: false });
    _this.props.onMouseLeave(event);
  }, _this.handleNestedListToggle = function (event) {
    event.stopPropagation();

    if (_this.props.open === null) {
      _this.setState({ open: !_this.state.open }, function () {
        _this.props.onNestedListToggle(_this);
      });
    } else {
      // Exposing 'this' in the callback is quite a bad API.
      // I'm doing a one level deep clone to expose a fake state.open.
      _this.props.onNestedListToggle((0, _extends3.default)({}, _this, {
        state: {
          open: !_this.state.open
        }
      }));
    }
  }, _this.handleRightIconButtonKeyboardFocus = function (event, isKeyboardFocused) {
    if (isKeyboardFocused) {
      _this.setState({
        isKeyboardFocused: false,
        rightIconButtonKeyboardFocused: isKeyboardFocused
      });
    }

    var iconButton = _this.props.rightIconButton;

    if (iconButton && iconButton.props.onKeyboardFocus) iconButton.props.onKeyboardFocus(event, isKeyboardFocused);
  }, _this.handleRightIconButtonMouseLeave = function (event) {
    var iconButton = _this.props.rightIconButton;
    _this.setState({ rightIconButtonHovered: false });
    if (iconButton && iconButton.props.onMouseLeave) iconButton.props.onMouseLeave(event);
  }, _this.handleRightIconButtonMouseEnter = function (event) {
    var iconButton = _this.props.rightIconButton;
    _this.setState({ rightIconButtonHovered: true });
    if (iconButton && iconButton.props.onMouseEnter) iconButton.props.onMouseEnter(event);
  }, _this.handleRightIconButtonMouseUp = function (event) {
    var iconButton = _this.props.rightIconButton;
    event.stopPropagation();
    if (iconButton && iconButton.props.onMouseUp) iconButton.props.onMouseUp(event);
  }, _this.handleRightIconButtonTouchTap = function (event) {
    var iconButton = _this.props.rightIconButton;

    // Stop the event from bubbling up to the list-item
    event.stopPropagation();
    if (iconButton && iconButton.props.onTouchTap) iconButton.props.onTouchTap(event);
  }, _this.handleTouchStart = function (event) {
    _this.setState({ touch: true });
    _this.props.onTouchStart(event);
  }, _this.handleTouchEnd = function (event) {
    _this.setState({ touch: true });
    _this.props.onTouchEnd(event);
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.Menu"></a>[function <span class="apidocSignatureSpan">material-ui.</span>Menu (props, context)](#apidoc.element.material-ui.Menu)
- description and source-code
```javascript
function Menu(props, context) {
  (0, _classCallCheck3.default)(this, Menu);

  var _this = (0, _possibleConstructorReturn3.default)(this, (Menu.__proto__ || (0, _getPrototypeOf2.default)(Menu)).call(this,
props, context));

  _initialiseProps.call(_this);

  var filteredChildren = _this.getFilteredChildren(props.children);
  var selectedIndex = _this.getSelectedIndex(props, filteredChildren);

  var newFocusIndex = props.disableAutoFocus ? -1 : selectedIndex >= 0 ? selectedIndex : 0;
  if (newFocusIndex !== -1 && props.onMenuItemFocusChange) {
    props.onMenuItemFocusChange(null, newFocusIndex);
  }
  _this.state = {
    focusIndex: newFocusIndex,
    isKeyboardFocused: props.initiallyKeyboardFocused,
    keyWidth: props.desktop ? 64 : 56
  };

  _this.hotKeyHolder = new _menuUtils.HotKeyHolder();
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.MenuItem"></a>[function <span class="apidocSignatureSpan">material-ui.</span>MenuItem ()](#apidoc.element.material-ui.MenuItem)
- description and source-code
```javascript
function MenuItem() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, MenuItem);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = MenuItem.__proto__ || (0, _getPrototypeOf2
.default)(MenuItem)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    open: false
  }, _this.cloneMenuItem = function (item) {
    return _react2.default.cloneElement(item, {
      onTouchTap: function onTouchTap(event) {
        if (!item.props.menuItems) {
          _this.handleRequestClose();
        }

        if (item.props.onTouchTap) {
          item.props.onTouchTap(event);
        }
      }
    });
  }, _this.handleTouchTap = function (event) {
    event.preventDefault();

    _this.setState({
      open: true,
      anchorEl: _reactDom2.default.findDOMNode(_this)
    });

    if (_this.props.onTouchTap) {
      _this.props.onTouchTap(event);
    }
  }, _this.handleRequestClose = function () {
    _this.setState({
      open: false,
      anchorEl: null
    });
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.MuiThemeProvider"></a>[function <span class="apidocSignatureSpan">material-ui.</span>MuiThemeProvider ()](#apidoc.element.material-ui.MuiThemeProvider)
- description and source-code
```javascript
function MuiThemeProvider() {
  (0, _classCallCheck3.default)(this, MuiThemeProvider);
  return (0, _possibleConstructorReturn3.default)(this, (MuiThemeProvider.__proto__ || (0, _getPrototypeOf2.default)(MuiThemeProvider
)).apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.Paper"></a>[function <span class="apidocSignatureSpan">material-ui.</span>Paper ()](#apidoc.element.material-ui.Paper)
- description and source-code
```javascript
function Paper() {
  (0, _classCallCheck3.default)(this, Paper);
  return (0, _possibleConstructorReturn3.default)(this, (Paper.__proto__ || (0, _getPrototypeOf2.default)(Paper)).apply(this, arguments
));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.Popover"></a>[function <span class="apidocSignatureSpan">material-ui.</span>Popover (props, context)](#apidoc.element.material-ui.Popover)
- description and source-code
```javascript
function Popover(props, context) {
  (0, _classCallCheck3.default)(this, Popover);

  var _this = (0, _possibleConstructorReturn3.default)(this, (Popover.__proto__ || (0, _getPrototypeOf2.default)(Popover)).call(
this, props, context));

  _this.timeout = null;

  _this.renderLayer = function () {
    var _this$props = _this.props,
        animated = _this$props.animated,
        animation = _this$props.animation,
        anchorEl = _this$props.anchorEl,
        anchorOrigin = _this$props.anchorOrigin,
        autoCloseWhenOffScreen = _this$props.autoCloseWhenOffScreen,
        canAutoPosition = _this$props.canAutoPosition,
        children = _this$props.children,
        onRequestClose = _this$props.onRequestClose,
        style = _this$props.style,
        targetOrigin = _this$props.targetOrigin,
        useLayerForClickAway = _this$props.useLayerForClickAway,
        other = (0, _objectWithoutProperties3.default)(_this$props, ['animated', 'animation', 'anchorEl', 'anchorOrigin', 'autoCloseWhenOffScreen
', 'canAutoPosition', 'children', 'onRequestClose', 'style', 'targetOrigin', 'useLayerForClickAway']);


    var styleRoot = style;

    if (!animated) {
      styleRoot = {
        position: 'fixed',
        zIndex: _this.context.muiTheme.zIndex.popover
      };

      if (!_this.state.open) {
        return null;
      }

      return _react2.default.createElement(
        _Paper2.default,
        (0, _extends3.default)({ style: (0, _simpleAssign2.default)(styleRoot, style) }, other),
        children
      );
    }

    var Animation = animation || _PopoverAnimationDefault2.default;

    return _react2.default.createElement(
      Animation,
      (0, _extends3.default)({
        targetOrigin: targetOrigin,
        style: styleRoot
      }, other, {
        open: _this.state.open && !_this.state.closing
      }),
      children
    );
  };

  _this.componentClickAway = function (event) {
    event.preventDefault();
    _this.requestClose('clickAway');
  };

  _this.setPlacement = function (scrolling) {
    if (!_this.state.open) {
      return;
    }

    if (!_this.refs.layer.getLayer()) {
      return;
    }

    var targetEl = _this.refs.layer.getLayer().children[0];
    if (!targetEl) {
      return;
    }

    var _this$props2 = _this.props,
        targetOrigin = _this$props2.targetOrigin,
        anchorOrigin = _this$props2.anchorOrigin;

    var anchorEl = _this.props.anchorEl || _this.anchorEl;

    var anchor = _this.getAnchorPosition(anchorEl);
    var target = _this.getTargetPosition(targetEl);

    var targetPosition = {
      top: anchor[anchorOrigin.vertical] - target[targetOrigin.vertical],
      left: anchor[anchorOrigin.horizontal] - target[targetOrigin.horizontal]
    };

    if (scrolling && _this.props.autoCloseWhenOffScreen) {
      _this.autoCloseWhenOffScreen(anchor);
    }

    if (_this.props.canAutoPosition) {
      target = _this.getTargetPosition(targetEl); // update as height may have changed
      targetPosition = _this.applyAutoPositionIfNeeded(anchor, target, targetOrigin, anchorOrigin, targetPosition);
    }

    targetEl.style.top = Math.max(0, targetPosition.top) + 'px';
    targetEl.style.left = Math.max(0, targetPosition.left) + 'px';
    targetEl.style.maxHeight = window.innerHeight + 'px';
  };

  _this.handleResize = (0, _lodash2.default)(_this.setPlacement, 100);
  _this.handleScroll = (0, _lodash2.default)(_this.setPlacement.bind(_this, true), 50);

  _this.state = {
    open: props.open,
    closing: false
  };
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.RadioButton"></a>[function <span class="apidocSignatureSpan">material-ui.</span>RadioButton ()](#apidoc.element.material-ui.RadioButton)
- description and source-code
```javascript
function RadioButton() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, RadioButton);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = RadioButton.__proto__ || (0, _getPrototypeOf2
.default)(RadioButton)).call.apply(_ref, [this].concat(args))), _this), _this.handleSwitch = function (event) {
    if (_this.props.onCheck) {
      _this.props.onCheck(event, _this.props.value);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.RadioButtonGroup"></a>[function <span class="apidocSignatureSpan">material-ui.</span>RadioButtonGroup ()](#apidoc.element.material-ui.RadioButtonGroup)
- description and source-code
```javascript
function RadioButtonGroup() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, RadioButtonGroup);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = RadioButtonGroup.__proto__ || (0, _getPrototypeOf2
.default)(RadioButtonGroup)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    numberCheckedRadioButtons: 0,
    selected: ''
  }, _this.handleChange = function (event, newSelection) {
    _this.updateRadioButtons(newSelection);

    // Successful update
    if (_this.state.numberCheckedRadioButtons === 0) {
      if (_this.props.onChange) _this.props.onChange(event, newSelection);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.RaisedButton"></a>[function <span class="apidocSignatureSpan">material-ui.</span>RaisedButton ()](#apidoc.element.material-ui.RaisedButton)
- description and source-code
```javascript
function RaisedButton() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, RaisedButton);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = RaisedButton.__proto__ || (0, _getPrototypeOf2
.default)(RaisedButton)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    hovered: false,
    keyboardFocused: false,
    touched: false,
    initialZDepth: 0,
    zDepth: 0
  }, _this.handleMouseDown = function (event) {
    // only listen to left clicks
    if (event.button === 0) {
      _this.setState({
        zDepth: _this.state.initialZDepth + 1
      });
    }
    if (_this.props.onMouseDown) {
      _this.props.onMouseDown(event);
    }
  }, _this.handleMouseUp = function (event) {
    _this.setState({
      zDepth: _this.state.initialZDepth
    });
    if (_this.props.onMouseUp) {
      _this.props.onMouseUp(event);
    }
  }, _this.handleMouseLeave = function (event) {
    if (!_this.state.keyboardFocused) {
      _this.setState({
        zDepth: _this.state.initialZDepth,
        hovered: false
      });
    }
    if (_this.props.onMouseLeave) {
      _this.props.onMouseLeave(event);
    }
  }, _this.handleMouseEnter = function (event) {
    if (!_this.state.keyboardFocused && !_this.state.touched) {
      _this.setState({
        hovered: true
      });
    }
    if (_this.props.onMouseEnter) {
      _this.props.onMouseEnter(event);
    }
  }, _this.handleTouchStart = function (event) {
    _this.setState({
      touched: true,
      zDepth: _this.state.initialZDepth + 1
    });

    if (_this.props.onTouchStart) {
      _this.props.onTouchStart(event);
    }
  }, _this.handleTouchEnd = function (event) {
    _this.setState({
      touched: true,
      zDepth: _this.state.initialZDepth
    });

    if (_this.props.onTouchEnd) {
      _this.props.onTouchEnd(event);
    }
  }, _this.handleKeyboardFocus = function (event, keyboardFocused) {
    var zDepth = keyboardFocused && !_this.props.disabled ? _this.state.initialZDepth + 1 : _this.state.initialZDepth;

    _this.setState({
      zDepth: zDepth,
      keyboardFocused: keyboardFocused
    });
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.RefreshIndicator"></a>[function <span class="apidocSignatureSpan">material-ui.</span>RefreshIndicator ()](#apidoc.element.material-ui.RefreshIndicator)
- description and source-code
```javascript
function RefreshIndicator() {
  (0, _classCallCheck3.default)(this, RefreshIndicator);
  return (0, _possibleConstructorReturn3.default)(this, (RefreshIndicator.__proto__ || (0, _getPrototypeOf2.default)(RefreshIndicator
)).apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.SelectField"></a>[function <span class="apidocSignatureSpan">material-ui.</span>SelectField ()](#apidoc.element.material-ui.SelectField)
- description and source-code
```javascript
function SelectField() {
  (0, _classCallCheck3.default)(this, SelectField);
  return (0, _possibleConstructorReturn3.default)(this, (SelectField.__proto__ || (0, _getPrototypeOf2.default)(SelectField)).apply
(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.Slider"></a>[function <span class="apidocSignatureSpan">material-ui.</span>Slider ()](#apidoc.element.material-ui.Slider)
- description and source-code
```javascript
function Slider() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, Slider);

  for (var _len3 = arguments.length, args = Array(_len3), _key3 = 0; _key3 < _len3; _key3++) {
    args[_key3] = arguments[_key3];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = Slider.__proto__ || (0, _getPrototypeOf2
.default)(Slider)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    active: false,
    dragging: false,
    focused: false,
    hovered: false,
    value: 0
  }, _this.track = null, _this.handle = null, _this.handleKeyDown = function (event) {
    var _this$props = _this.props,
        axis = _this$props.axis,
        min = _this$props.min,
        max = _this$props.max,
        step = _this$props.step;


    var action = void 0;

    switch ((0, _keycode2.default)(event)) {
      case 'page down':
      case 'down':
        if (axis === 'y-reverse') {
          action = 'increase';
        } else {
          action = 'decrease';
        }
        break;
      case 'left':
        if (axis === 'x-reverse') {
          action = 'increase';
        } else {
          action = 'decrease';
        }
        break;
      case 'page up':
      case 'up':
        if (axis === 'y-reverse') {
          action = 'decrease';
        } else {
          action = 'increase';
        }
        break;
      case 'right':
        if (axis === 'x-reverse') {
          action = 'decrease';
        } else {
          action = 'increase';
        }
        break;
      case 'home':
        action = 'min';
        break;
      case 'end':
        action = 'max';
        break;
    }

    if (action) {
      var newValue = void 0;

      // Cancel scroll
      event.preventDefault();

      switch (action) {
        case 'decrease':
          newValue = _this.state.value - step;
          break;
        case 'increase':
          newValue = _this.state.value + step;
          break;
        case 'min':
          newValue = min;
          break;
        case 'max':
          newValue = max;
          break;
      }

      // We need to use toFixed() because of float point errors.
      // For example, 0.01 + 0.06 = 0.06999999999999999
      newValue = parseFloat(newValue.toFixed(5));

      if (newValue > max) {
        newValue = max;
      } else if (newValue < min) {
        newValue = min;
      }

      if (_this.state.value !== newValue) {
        _this.setState({
          value: newValue
        });

        if (_this.props.onChange) {
          _this.props.onChange(event, newValue);
        }
      }
    }
  }, _this.handleDragMouseMove = function (event) {
    _this.onDragUpdate(event, 'mouse');
  }, _this.handleTouchMove = function (event) {
    _this.onDragUpdate(event, 'touch');
  }, _this.handleMouseEnd = function (event) {
    document.removeEventListener('mousemove', _this.handleDragMouseMove);
    document.removeEventListener('mouseup', _this.handleMouseEnd);

    _this.onDragStop(event);
  }, _this.handleTouchEnd = function (event) {
    document.removeEventListener('touchmove', _this.handleTouchMove);
    document.removeEventListener('touchup', _this.handleTouchEnd);
    document.removeEventListener('touchend', _this.handleTouchEnd);
    document.removeEventListener('touchcancel', _this.handleTouchEnd);

    _this.onDragStop(event);
  }, _this.handleTouchStart = function (event) {
    if (_this.props.disabled) {
      return;
    }

    var position = void 0;
    if (isMouseControlInverted(_this.props.axis)) {
      position = _this.getTrackOffset() - event.touches[0][mainAxisClientOffsetProperty[_this.props.axis]];
    } else {
      position = event.touches[0][mainAxisClientOffsetProperty[_this.props.axis]] - _this.getTrackOffset();
    }
    _this.setValueFromPosition(event, position);

    document.addEventListener('touchmove', _this.handleTouchMove);
    document.addEventListener('touchup', _this.handleTouchEnd);
    document.addEventListener('touchend', _this.handleTouchEnd);
    document.addEventListener('touchcancel', _this.handleTo ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.Snackbar"></a>[function <span class="apidocSignatureSpan">material-ui.</span>Snackbar ()](#apidoc.element.material-ui.Snackbar)
- description and source-code
```javascript
function Snackbar() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, Snackbar);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = Snackbar.__proto__ || (0, _getPrototypeOf2
.default)(Snackbar)).call.apply(_ref, [this].concat(args))), _this), _this.componentClickAway = function () {
    if (_this.timerTransitionId) {
      // If transitioning, don't close the snackbar.
      return;
    }

    if (_this.props.open !== null && _this.props.onRequestClose) {
      _this.props.onRequestClose('clickaway');
    } else {
      _this.setState({ open: false });
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.Step"></a>[function <span class="apidocSignatureSpan">material-ui.</span>Step ()](#apidoc.element.material-ui.Step)
- description and source-code
```javascript
function Step() {
  var _ref3;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, Step);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref3 = Step.__proto__ || (0, _getPrototypeOf2
.default)(Step)).call.apply(_ref3, [this].concat(args))), _this), _this.renderChild = function (child) {
    var _this$props = _this.props,
        active = _this$props.active,
        completed = _this$props.completed,
        disabled = _this$props.disabled,
        index = _this$props.index,
        last = _this$props.last;


    var icon = index + 1;

    return _react2.default.cloneElement(child, (0, _simpleAssign2.default)({ active: active, completed: completed, disabled: disabled
, icon: icon, last: last }, child.props));
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.StepButton"></a>[function <span class="apidocSignatureSpan">material-ui.</span>StepButton ()](#apidoc.element.material-ui.StepButton)
- description and source-code
```javascript
function StepButton() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, StepButton);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = StepButton.__proto__ || (0, _getPrototypeOf2
.default)(StepButton)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    hovered: false,
    touched: false
  }, _this.handleMouseEnter = function (event) {
    var onMouseEnter = _this.props.onMouseEnter;
    // Cancel hover styles for touch devices

    if (!_this.state.touched) {
      _this.setState({ hovered: true });
    }
    if (typeof onMouseEnter === 'function') {
      onMouseEnter(event);
    }
  }, _this.handleMouseLeave = function (event) {
    var onMouseLeave = _this.props.onMouseLeave;

    _this.setState({ hovered: false });
    if (typeof onMouseLeave === 'function') {
      onMouseLeave(event);
    }
  }, _this.handleTouchStart = function (event) {
    var onTouchStart = _this.props.onTouchStart;

    if (!_this.state.touched) {
      _this.setState({ touched: true });
    }
    if (typeof onTouchStart === 'function') {
      onTouchStart(event);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.StepContent"></a>[function <span class="apidocSignatureSpan">material-ui.</span>StepContent ()](#apidoc.element.material-ui.StepContent)
- description and source-code
```javascript
function StepContent() {
  (0, _classCallCheck3.default)(this, StepContent);
  return (0, _possibleConstructorReturn3.default)(this, (StepContent.__proto__ || (0, _getPrototypeOf2.default)(StepContent)).apply
(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.StepLabel"></a>[function <span class="apidocSignatureSpan">material-ui.</span>StepLabel (props, context)](#apidoc.element.material-ui.StepLabel)
- description and source-code
```javascript
function StepLabel(props, context) {
  var active = props.active,
      children = props.children,
      completed = props.completed,
      userIcon = props.icon,
      iconContainerStyle = props.iconContainerStyle,
      last = props.last,
      style = props.style,
      other = (0, _objectWithoutProperties3.default)(props, ['active', 'children', 'completed', 'icon', 'iconContainerStyle', 'last
', 'style']);
  var prepareStyles = context.muiTheme.prepareStyles;

  var styles = getStyles(props, context);
  var icon = renderIcon(completed, userIcon, styles);

  return _react2.default.createElement(
    'span',
    (0, _extends3.default)({ style: prepareStyles((0, _simpleAssign2.default)(styles.root, style)) }, other),
    icon && _react2.default.createElement(
      'span',
      { style: prepareStyles((0, _simpleAssign2.default)(styles.iconContainer, iconContainerStyle)) },
      icon
    ),
    children
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.Stepper"></a>[function <span class="apidocSignatureSpan">material-ui.</span>Stepper ()](#apidoc.element.material-ui.Stepper)
- description and source-code
```javascript
function Stepper() {
  (0, _classCallCheck3.default)(this, Stepper);
  return (0, _possibleConstructorReturn3.default)(this, (Stepper.__proto__ || (0, _getPrototypeOf2.default)(Stepper)).apply(this
, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.Subheader"></a>[function <span class="apidocSignatureSpan">material-ui.</span>Subheader (props, context)](#apidoc.element.material-ui.Subheader)
- description and source-code
```javascript
function Subheader(props, context) {
  var children = props.children,
      inset = props.inset,
      style = props.style,
      other = (0, _objectWithoutProperties3.default)(props, ['children', 'inset', 'style']);
  var _context$muiTheme = context.muiTheme,
      prepareStyles = _context$muiTheme.prepareStyles,
      subheader = _context$muiTheme.subheader;


  var styles = {
    root: {
      boxSizing: 'border-box',
      color: subheader.color,
      fontSize: 14,
      fontWeight: subheader.fontWeight,
      lineHeight: '48px',
      paddingLeft: inset ? 72 : 16,
      width: '100%'
    }
  };

  return _react2.default.createElement(
    'div',
    (0, _extends3.default)({}, other, { style: prepareStyles((0, _simpleAssign2.default)(styles.root, style)) }),
    children
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.SvgIcon"></a>[function <span class="apidocSignatureSpan">material-ui.</span>SvgIcon ()](#apidoc.element.material-ui.SvgIcon)
- description and source-code
```javascript
function SvgIcon() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, SvgIcon);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = SvgIcon.__proto__ || (0, _getPrototypeOf2
.default)(SvgIcon)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    hovered: false
  }, _this.handleMouseLeave = function (event) {
    _this.setState({ hovered: false });
    _this.props.onMouseLeave(event);
  }, _this.handleMouseEnter = function (event) {
    _this.setState({ hovered: true });
    _this.props.onMouseEnter(event);
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.Tab"></a>[function <span class="apidocSignatureSpan">material-ui.</span>Tab ()](#apidoc.element.material-ui.Tab)
- description and source-code
```javascript
function Tab() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, Tab);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = Tab.__proto__ || (0, _getPrototypeOf2.default
)(Tab)).call.apply(_ref, [this].concat(args))), _this), _this.handleTouchTap = function (event) {
    if (_this.props.onTouchTap) {
      _this.props.onTouchTap(_this.props.value, event, _this);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.Table"></a>[function <span class="apidocSignatureSpan">material-ui.</span>Table ()](#apidoc.element.material-ui.Table)
- description and source-code
```javascript
function Table() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, Table);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = Table.__proto__ || (0, _getPrototypeOf2
.default)(Table)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    allRowsSelected: false
  }, _this.onCellClick = function (rowNumber, columnNumber, event) {
    if (_this.props.onCellClick) _this.props.onCellClick(rowNumber, columnNumber, event);
  }, _this.onCellHover = function (rowNumber, columnNumber, event) {
    if (_this.props.onCellHover) _this.props.onCellHover(rowNumber, columnNumber, event);
  }, _this.onCellHoverExit = function (rowNumber, columnNumber, event) {
    if (_this.props.onCellHoverExit) _this.props.onCellHoverExit(rowNumber, columnNumber, event);
  }, _this.onRowHover = function (rowNumber) {
    if (_this.props.onRowHover) _this.props.onRowHover(rowNumber);
  }, _this.onRowHoverExit = function (rowNumber) {
    if (_this.props.onRowHoverExit) _this.props.onRowHoverExit(rowNumber);
  }, _this.onRowSelection = function (selectedRows) {
    if (_this.state.allRowsSelected) _this.setState({ allRowsSelected: false });
    if (_this.props.onRowSelection) _this.props.onRowSelection(selectedRows);
  }, _this.onSelectAll = function () {
    if (_this.props.onRowSelection) {
      if (!_this.state.allRowsSelected) {
        _this.props.onRowSelection('all');
      } else {
        _this.props.onRowSelection('none');
      }
    }

    _this.setState({ allRowsSelected: !_this.state.allRowsSelected });
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.TableBody"></a>[function <span class="apidocSignatureSpan">material-ui.</span>TableBody ()](#apidoc.element.material-ui.TableBody)
- description and source-code
```javascript
function TableBody() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, TableBody);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = TableBody.__proto__ || (0, _getPrototypeOf2
.default)(TableBody)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    selectedRows: []
  }, _this.handleClickAway = function () {
    if (_this.props.deselectOnClickaway && _this.state.selectedRows.length) {
      _this.setState({
        selectedRows: []
      });
      if (_this.props.onRowSelection) {
        _this.props.onRowSelection([]);
      }
    }
  }, _this.onRowClick = function (event, rowNumber) {
    event.stopPropagation();

    if (_this.props.selectable) {
      // Prevent text selection while selecting rows.
      window.getSelection().removeAllRanges();
      _this.processRowSelection(event, rowNumber);
    }
  }, _this.onCellClick = function (event, rowNumber, columnNumber) {
    event.stopPropagation();
    if (_this.props.onCellClick) {
      _this.props.onCellClick(rowNumber, _this.getColumnId(columnNumber), event);
    }
  }, _this.onCellHover = function (event, rowNumber, columnNumber) {
    if (_this.props.onCellHover) {
      _this.props.onCellHover(rowNumber, _this.getColumnId(columnNumber), event);
    }
    _this.onRowHover(event, rowNumber);
  }, _this.onCellHoverExit = function (event, rowNumber, columnNumber) {
    if (_this.props.onCellHoverExit) {
      _this.props.onCellHoverExit(rowNumber, _this.getColumnId(columnNumber), event);
    }
    _this.onRowHoverExit(event, rowNumber);
  }, _this.onRowHover = function (event, rowNumber) {
    if (_this.props.onRowHover) {
      _this.props.onRowHover(rowNumber);
    }
  }, _this.onRowHoverExit = function (event, rowNumber) {
    if (_this.props.onRowHoverExit) {
      _this.props.onRowHoverExit(rowNumber);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.TableFooter"></a>[function <span class="apidocSignatureSpan">material-ui.</span>TableFooter ()](#apidoc.element.material-ui.TableFooter)
- description and source-code
```javascript
function TableFooter() {
  (0, _classCallCheck3.default)(this, TableFooter);
  return (0, _possibleConstructorReturn3.default)(this, (TableFooter.__proto__ || (0, _getPrototypeOf2.default)(TableFooter)).apply
(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.TableHeader"></a>[function <span class="apidocSignatureSpan">material-ui.</span>TableHeader ()](#apidoc.element.material-ui.TableHeader)
- description and source-code
```javascript
function TableHeader() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, TableHeader);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = TableHeader.__proto__ || (0, _getPrototypeOf2
.default)(TableHeader)).call.apply(_ref, [this].concat(args))), _this), _this.handleCheckAll = function (event, checked) {
    if (_this.props.onSelectAll) {
      _this.props.onSelectAll(checked);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.TableHeaderColumn"></a>[function <span class="apidocSignatureSpan">material-ui.</span>TableHeaderColumn ()](#apidoc.element.material-ui.TableHeaderColumn)
- description and source-code
```javascript
function TableHeaderColumn() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, TableHeaderColumn);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = TableHeaderColumn.__proto__ || (0, _getPrototypeOf2
.default)(TableHeaderColumn)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    hovered: false
  }, _this.onMouseEnter = function () {
    if (_this.props.tooltip !== undefined) {
      _this.setState({ hovered: true });
    }
  }, _this.onMouseLeave = function () {
    if (_this.props.tooltip !== undefined) {
      _this.setState({ hovered: false });
    }
  }, _this.onClick = function (event) {
    if (_this.props.onClick) {
      _this.props.onClick(event, _this.props.columnNumber);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.TableRow"></a>[function <span class="apidocSignatureSpan">material-ui.</span>TableRow ()](#apidoc.element.material-ui.TableRow)
- description and source-code
```javascript
function TableRow() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, TableRow);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = TableRow.__proto__ || (0, _getPrototypeOf2
.default)(TableRow)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    hovered: false
  }, _this.onCellClick = function (event, columnIndex) {
    if (_this.props.selectable && _this.props.onCellClick) {
      _this.props.onCellClick(event, _this.props.rowNumber, columnIndex);
    }
    event.ctrlKey = true;
    _this.onRowClick(event);
  }, _this.onCellHover = function (event, columnIndex) {
    if (_this.props.hoverable) {
      _this.setState({ hovered: true });
      if (_this.props.onCellHover) _this.props.onCellHover(event, _this.props.rowNumber, columnIndex);
      _this.onRowHover(event);
    }
  }, _this.onCellHoverExit = function (event, columnIndex) {
    if (_this.props.hoverable) {
      _this.setState({ hovered: false });
      if (_this.props.onCellHoverExit) _this.props.onCellHoverExit(event, _this.props.rowNumber, columnIndex);
      _this.onRowHoverExit(event);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.TableRowColumn"></a>[function <span class="apidocSignatureSpan">material-ui.</span>TableRowColumn ()](#apidoc.element.material-ui.TableRowColumn)
- description and source-code
```javascript
function TableRowColumn() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, TableRowColumn);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = TableRowColumn.__proto__ || (0, _getPrototypeOf2
.default)(TableRowColumn)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    hovered: false
  }, _this.onClick = function (event) {
    if (_this.props.onClick) {
      _this.props.onClick(event, _this.props.columnNumber);
    }
  }, _this.onMouseEnter = function (event) {
    if (_this.props.hoverable) {
      _this.setState({ hovered: true });
      if (_this.props.onHover) {
        _this.props.onHover(event, _this.props.columnNumber);
      }
    }
  }, _this.onMouseLeave = function (event) {
    if (_this.props.hoverable) {
      _this.setState({ hovered: false });
      if (_this.props.onHoverExit) {
        _this.props.onHoverExit(event, _this.props.columnNumber);
      }
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.Tabs"></a>[function <span class="apidocSignatureSpan">material-ui.</span>Tabs ()](#apidoc.element.material-ui.Tabs)
- description and source-code
```javascript
function Tabs() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, Tabs);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = Tabs.__proto__ || (0, _getPrototypeOf2.
default)(Tabs)).call.apply(_ref, [this].concat(args))), _this), _this.state = { selectedIndex: 0 }, _this.handleTabTouchTap = function
 (value, event, tab) {
    var valueLink = _this.getValueLink(_this.props);
    var index = tab.props.index;

    if (valueLink.value && valueLink.value !== value || _this.state.selectedIndex !== index) {
      valueLink.requestChange(value, event, tab);
    }

    _this.setState({ selectedIndex: index });

    if (tab.props.onActive) {
      tab.props.onActive(tab);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.TextField"></a>[function <span class="apidocSignatureSpan">material-ui.</span>TextField ()](#apidoc.element.material-ui.TextField)
- description and source-code
```javascript
function TextField() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, TextField);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = TextField.__proto__ || (0, _getPrototypeOf2
.default)(TextField)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    isFocused: false,
    errorText: undefined,
    hasValue: false
  }, _this.handleInputBlur = function (event) {
    _this.setState({ isFocused: false });
    if (_this.props.onBlur) {
      _this.props.onBlur(event);
    }
  }, _this.handleInputChange = function (event) {
    _this.setState({ hasValue: isValid(event.target.value) });
    if (_this.props.onChange) {
      _this.props.onChange(event, event.target.value);
    }
  }, _this.handleInputFocus = function (event) {
    if (_this.props.disabled) {
      return;
    }
    _this.setState({ isFocused: true });
    if (_this.props.onFocus) {
      _this.props.onFocus(event);
    }
  }, _this.handleHeightChange = function (event, height) {
    var newHeight = height + 24;
    if (_this.props.floatingLabelText) {
      newHeight += 24;
    }
    _reactDom2.default.findDOMNode(_this).style.height = newHeight + 'px';
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.TimePicker"></a>[function <span class="apidocSignatureSpan">material-ui.</span>TimePicker ()](#apidoc.element.material-ui.TimePicker)
- description and source-code
```javascript
function TimePicker() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, TimePicker);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = TimePicker.__proto__ || (0, _getPrototypeOf2
.default)(TimePicker)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    time: null,
    dialogTime: new Date()
  }, _this.handleAcceptDialog = function (time) {
    _this.setState({
      time: time
    });
    if (_this.props.onChange) _this.props.onChange(null, time);
  }, _this.handleFocusInput = function (event) {
    event.target.blur();
    if (_this.props.onFocus) {
      _this.props.onFocus(event);
    }
  }, _this.handleTouchTapInput = function (event) {
    event.preventDefault();

    if (!_this.props.disabled) {
      _this.openDialog();
    }

    if (_this.props.onTouchTap) {
      _this.props.onTouchTap(event);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.Toggle"></a>[function <span class="apidocSignatureSpan">material-ui.</span>Toggle ()](#apidoc.element.material-ui.Toggle)
- description and source-code
```javascript
function Toggle() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, Toggle);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = Toggle.__proto__ || (0, _getPrototypeOf2
.default)(Toggle)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    switched: false
  }, _this.handleStateChange = function (newSwitched) {
    _this.setState({
      switched: newSwitched
    });
  }, _this.handleToggle = function (event, isInputChecked) {
    if (_this.props.onToggle) {
      _this.props.onToggle(event, isInputChecked);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.Toolbar"></a>[function <span class="apidocSignatureSpan">material-ui.</span>Toolbar ()](#apidoc.element.material-ui.Toolbar)
- description and source-code
```javascript
function Toolbar() {
  (0, _classCallCheck3.default)(this, Toolbar);
  return (0, _possibleConstructorReturn3.default)(this, (Toolbar.__proto__ || (0, _getPrototypeOf2.default)(Toolbar)).apply(this
, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.ToolbarGroup"></a>[function <span class="apidocSignatureSpan">material-ui.</span>ToolbarGroup ()](#apidoc.element.material-ui.ToolbarGroup)
- description and source-code
```javascript
function ToolbarGroup() {
  (0, _classCallCheck3.default)(this, ToolbarGroup);
  return (0, _possibleConstructorReturn3.default)(this, (ToolbarGroup.__proto__ || (0, _getPrototypeOf2.default)(ToolbarGroup)).
apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.ToolbarSeparator"></a>[function <span class="apidocSignatureSpan">material-ui.</span>ToolbarSeparator ()](#apidoc.element.material-ui.ToolbarSeparator)
- description and source-code
```javascript
function ToolbarSeparator() {
  (0, _classCallCheck3.default)(this, ToolbarSeparator);
  return (0, _possibleConstructorReturn3.default)(this, (ToolbarSeparator.__proto__ || (0, _getPrototypeOf2.default)(ToolbarSeparator
)).apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.ToolbarTitle"></a>[function <span class="apidocSignatureSpan">material-ui.</span>ToolbarTitle ()](#apidoc.element.material-ui.ToolbarTitle)
- description and source-code
```javascript
function ToolbarTitle() {
  (0, _classCallCheck3.default)(this, ToolbarTitle);
  return (0, _possibleConstructorReturn3.default)(this, (ToolbarTitle.__proto__ || (0, _getPrototypeOf2.default)(ToolbarTitle)).
apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.makeSelectable"></a>[function <span class="apidocSignatureSpan">material-ui.</span>makeSelectable (MyComponent)](#apidoc.element.material-ui.makeSelectable)
- description and source-code
```javascript
function makeSelectable(MyComponent) {
  var _class, _temp2;

  return _temp2 = _class = function (_Component) {
    (0, _inherits3.default)(_class, _Component);

    function _class() {
      var _ref;

      var _temp, _this, _ret;

      (0, _classCallCheck3.default)(this, _class);

      for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
        args[_key] = arguments[_key];
      }

      return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = _class.__proto__ || (0, _getPrototypeOf2
.default)(_class)).call.apply(_ref, [this].concat(args))), _this), _this.hasSelectedDescendant = function (previousValue, child) {
        if (_react2.default.isValidElement(child) && child.props.nestedItems && child.props.nestedItems.length > 0) {
          return child.props.nestedItems.reduce(_this.hasSelectedDescendant, previousValue);
        }
        return previousValue || _this.isChildSelected(child, _this.props);
      }, _this.handleItemTouchTap = function (event, item) {
        var itemValue = item.props.value;

        if (itemValue !== _this.props.value) {
          if (_this.props.onChange) {
            _this.props.onChange(event, itemValue);
          }
        }
      }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
    }

    (0, _createClass3.default)(_class, [{
      key: 'extendChild',
      value: function extendChild(child, styles, selectedItemStyle) {
        var _this2 = this;

        if (child && child.type && child.type.muiName === 'ListItem') {
          var selected = this.isChildSelected(child, this.props);
          var selectedChildrenStyles = void 0;
          if (selected) {
            selectedChildrenStyles = (0, _simpleAssign2.default)({}, styles, selectedItemStyle);
          }

          var mergedChildrenStyles = (0, _simpleAssign2.default)({}, child.props.style, selectedChildrenStyles);

          this.keyIndex += 1;

          return _react2.default.cloneElement(child, {
            onTouchTap: function onTouchTap(event) {
              _this2.handleItemTouchTap(event, child);
              if (child.props.onTouchTap) {
                child.props.onTouchTap(event);
              }
            },
            key: this.keyIndex,
            style: mergedChildrenStyles,
            nestedItems: child.props.nestedItems.map(function (child) {
              return _this2.extendChild(child, styles, selectedItemStyle);
            }),
            initiallyOpen: this.isInitiallyOpen(child)
          });
        } else {
          return child;
        }
      }
    }, {
      key: 'isInitiallyOpen',
      value: function isInitiallyOpen(child) {
        if (child.props.initiallyOpen) {
          return child.props.initiallyOpen;
        }
        return this.hasSelectedDescendant(false, child);
      }
    }, {
      key: 'isChildSelected',
      value: function isChildSelected(child, props) {
        return props.value === child.props.value;
      }
    }, {
      key: 'render',
      value: function render() {
        var _this3 = this;

        var _props = this.props,
            children = _props.children,
            selectedItemStyle = _props.selectedItemStyle,
            other = (0, _objectWithoutProperties3.default)(_props, ['children', 'selectedItemStyle']);


        this.keyIndex = 0;
        var styles = {};

        if (!selectedItemStyle) {
          var textColor = this.context.muiTheme.baseTheme.palette.textColor;
          styles.backgroundColor = (0, _colorManipulator.fade)(textColor, 0.2);
        }

        return _react2.default.createElement(
          MyComponent,
          (0, _extends3.default)({}, other, this.state),
          _react.Children.map(children, function (child) {
            return _this3.extendChild(child, styles, selectedItemStyle);
          })
        );
      }
    }]);
    return _class;
  }(_react.Component), _class.propTypes = {
    children: _react.PropTypes.node,
    onChange: _react.PropTypes.func,
    selectedItemStyle: _react.PropTypes.object,
    value: _react.Prop ...
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.material-ui.AppBar"></a>[module material-ui.AppBar](#apidoc.module.material-ui.AppBar)

#### <a name="apidoc.element.material-ui.AppBar.default"></a>[function <span class="apidocSignatureSpan">material-ui.AppBar.</span>default ()](#apidoc.element.material-ui.AppBar.default)
- description and source-code
```javascript
function AppBar() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, AppBar);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = AppBar.__proto__ || (0, _getPrototypeOf2
.default)(AppBar)).call.apply(_ref, [this].concat(args))), _this), _this.handleTouchTapLeftIconButton = function (event) {
    if (_this.props.onLeftIconButtonTouchTap) {
      _this.props.onLeftIconButtonTouchTap(event);
    }
  }, _this.handleTouchTapRightIconButton = function (event) {
    if (_this.props.onRightIconButtonTouchTap) {
      _this.props.onRightIconButtonTouchTap(event);
    }
  }, _this.handleTitleTouchTap = function (event) {
    if (_this.props.onTitleTouchTap) {
      _this.props.onTitleTouchTap(event);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```

#### <a name="apidoc.element.material-ui.AppBar.getStyles"></a>[function <span class="apidocSignatureSpan">material-ui.AppBar.</span>getStyles (props, context)](#apidoc.element.material-ui.AppBar.getStyles)
- description and source-code
```javascript
function getStyles(props, context) {
  var _context$muiTheme = context.muiTheme,
      appBar = _context$muiTheme.appBar,
      iconButtonSize = _context$muiTheme.button.iconButtonSize,
      zIndex = _context$muiTheme.zIndex;


  var flatButtonSize = 36;

  var styles = {
    root: {
      position: 'relative',
      zIndex: zIndex.appBar,
      width: '100%',
      display: 'flex',
      backgroundColor: appBar.color,
      paddingLeft: appBar.padding,
      paddingRight: appBar.padding
    },
    title: {
      whiteSpace: 'nowrap',
      overflow: 'hidden',
      textOverflow: 'ellipsis',
      margin: 0,
      paddingTop: 0,
      letterSpacing: 0,
      fontSize: 24,
      fontWeight: appBar.titleFontWeight,
      color: appBar.textColor,
      height: appBar.height,
      lineHeight: appBar.height + 'px'
    },
    mainElement: {
      boxFlex: 1,
      flex: '1'
    },
    iconButtonStyle: {
      marginTop: (appBar.height - iconButtonSize) / 2,
      marginRight: 8,
      marginLeft: -16
    },
    iconButtonIconStyle: {
      fill: appBar.textColor,
      color: appBar.textColor
    },
    flatButton: {
      color: appBar.textColor,
      marginTop: (iconButtonSize - flatButtonSize) / 2 + 1
    }
  };

  return styles;
}
```
- example usage
```shell
...
    openSecondary = _props.openSecondary,
    overlayClassName = _props.overlayClassName,
    overlayStyle = _props.overlayStyle,
    style = _props.style,
    zDepth = _props.zDepth;


var styles = this.getStyles();

var overlay = void 0;
if (!docked) {
  overlay = _react2.default.createElement(_Overlay2.default, {
    ref: 'overlay',
    show: this.shouldShow(),
    className: overlayClassName,
...
```



# <a name="apidoc.module.material-ui.AppCanvas"></a>[module material-ui.AppCanvas](#apidoc.module.material-ui.AppCanvas)

#### <a name="apidoc.element.material-ui.AppCanvas.default"></a>[function <span class="apidocSignatureSpan">material-ui.AppCanvas.</span>default ()](#apidoc.element.material-ui.AppCanvas.default)
- description and source-code
```javascript
function AppCanvas() {
  (0, _classCallCheck3.default)(this, AppCanvas);
  return (0, _possibleConstructorReturn3.default)(this, (AppCanvas.__proto__ || (0, _getPrototypeOf2.default)(AppCanvas)).apply(
this, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.AutoComplete"></a>[module material-ui.AutoComplete](#apidoc.module.material-ui.AutoComplete)

#### <a name="apidoc.element.material-ui.AutoComplete.AutoComplete"></a>[function <span class="apidocSignatureSpan">material-ui.</span>AutoComplete ()](#apidoc.element.material-ui.AutoComplete.AutoComplete)
- description and source-code
```javascript
function AutoComplete() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, AutoComplete);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = AutoComplete.__proto__ || (0, _getPrototypeOf2
.default)(AutoComplete)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    anchorEl: null,
    focusTextField: true,
    open: false,
    searchText: undefined
  }, _this.handleRequestClose = function () {
    // Only take into account the Popover clickAway when we are
    // not focusing the TextField.
    if (!_this.state.focusTextField) {
      _this.close();
    }
  }, _this.handleMouseDown = function (event) {
    // Keep the TextField focused
    event.preventDefault();
  }, _this.handleItemTouchTap = function (event, child) {
    var dataSource = _this.props.dataSource;

    var index = parseInt(child.key, 10);
    var chosenRequest = dataSource[index];
    var searchText = _this.chosenRequestText(chosenRequest);

    _this.setState({
      searchText: searchText
    }, function () {
      _this.props.onUpdateInput(searchText, _this.props.dataSource, {
        source: 'touchTap'
      });

      _this.timerTouchTapCloseId = setTimeout(function () {
        _this.timerTouchTapCloseId = null;
        _this.close();
        _this.props.onNewRequest(chosenRequest, index);
      }, _this.props.menuCloseDelay);
    });
  }, _this.chosenRequestText = function (chosenRequest) {
    if (typeof chosenRequest === 'string') {
      return chosenRequest;
    } else {
      return chosenRequest[_this.props.dataSourceConfig.text];
    }
  }, _this.handleEscKeyDown = function () {
    _this.close();
  }, _this.handleKeyDown = function (event) {
    if (_this.props.onKeyDown) _this.props.onKeyDown(event);

    switch ((0, _keycode2.default)(event)) {
      case 'enter':
        _this.close();
        var searchText = _this.state.searchText;
        if (searchText !== '') {
          _this.props.onNewRequest(searchText, -1);
        }
        break;

      case 'esc':
        _this.close();
        break;

      case 'down':
        event.preventDefault();
        _this.setState({
          open: true,
          focusTextField: false,
          anchorEl: _reactDom2.default.findDOMNode(_this.refs.searchTextField)
        });
        break;

      default:
        break;
    }
  }, _this.handleChange = function (event) {
    var searchText = event.target.value;

    // Make sure that we have a new searchText.
    // Fix an issue with a Cordova Webview
    if (searchText === _this.state.searchText) {
      return;
    }

    _this.setState({
      searchText: searchText,
      open: true,
      anchorEl: _reactDom2.default.findDOMNode(_this.refs.searchTextField)
    }, function () {
      _this.props.onUpdateInput(searchText, _this.props.dataSource, {
        source: 'change'
      });
    });
  }, _this.handleBlur = function (event) {
    if (_this.state.focusTextField && _this.timerTouchTapCloseId === null) {
      _this.timerBlurClose = setTimeout(function () {
        _this.close();
      }, 0);
    }

    if (_this.props.onBlur) {
      _this.props.onBlur(event);
    }
  }, _this.handleFocus = function (event) {
    if (!_this.state.open && _this.props.openOnFocus) {
      _this.setState({
        open: true,
        anchorEl: _reactDom2.default.findDOMNode(_this.refs.searchTextField)
      });
    }

    _this.setState({
      focusTextField: true
    });

    if (_this.props.onFocus) {
      _this.props.onFocus(event);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.Divider"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.</span>Divider (props, context)](#apidoc.element.material-ui.AutoComplete.Divider)
- description and source-code
```javascript
function Divider(props, context) {
  var inset = props.inset,
      style = props.style,
      other = (0, _objectWithoutProperties3.default)(props, ['inset', 'style']);
  var _context$muiTheme = context.muiTheme,
      baseTheme = _context$muiTheme.baseTheme,
      prepareStyles = _context$muiTheme.prepareStyles;


  var styles = {
    root: {
      margin: 0,
      marginTop: -1,
      marginLeft: inset ? 72 : 0,
      height: 1,
      border: 'none',
      backgroundColor: baseTheme.palette.borderColor
    }
  };

  return _react2.default.createElement('hr', (0, _extends3.default)({}, other, { style: prepareStyles((0, _simpleAssign2.default
)(styles.root, style)) }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.Item"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.</span>Item ()](#apidoc.element.material-ui.AutoComplete.Item)
- description and source-code
```javascript
function MenuItem() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, MenuItem);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = MenuItem.__proto__ || (0, _getPrototypeOf2
.default)(MenuItem)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    open: false
  }, _this.cloneMenuItem = function (item) {
    return _react2.default.cloneElement(item, {
      onTouchTap: function onTouchTap(event) {
        if (!item.props.menuItems) {
          _this.handleRequestClose();
        }

        if (item.props.onTouchTap) {
          item.props.onTouchTap(event);
        }
      }
    });
  }, _this.handleTouchTap = function (event) {
    event.preventDefault();

    _this.setState({
      open: true,
      anchorEl: _reactDom2.default.findDOMNode(_this)
    });

    if (_this.props.onTouchTap) {
      _this.props.onTouchTap(event);
    }
  }, _this.handleRequestClose = function () {
    _this.setState({
      open: false,
      anchorEl: null
    });
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.caseInsensitiveFilter"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.</span>caseInsensitiveFilter (searchText, key)](#apidoc.element.material-ui.AutoComplete.caseInsensitiveFilter)
- description and source-code
```javascript
caseInsensitiveFilter = function (searchText, key) {
  return key.toLowerCase().indexOf(searchText.toLowerCase()) !== -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.caseSensitiveFilter"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.</span>caseSensitiveFilter (searchText, key)](#apidoc.element.material-ui.AutoComplete.caseSensitiveFilter)
- description and source-code
```javascript
caseSensitiveFilter = function (searchText, key) {
  return searchText !== '' && key.indexOf(searchText) !== -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.defaultFilter"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.</span>defaultFilter (searchText, key)](#apidoc.element.material-ui.AutoComplete.defaultFilter)
- description and source-code
```javascript
defaultFilter = function (searchText, key) {
  return searchText !== '' && key.indexOf(searchText) !== -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.fuzzyFilter"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.</span>fuzzyFilter (searchText, key)](#apidoc.element.material-ui.AutoComplete.fuzzyFilter)
- description and source-code
```javascript
fuzzyFilter = function (searchText, key) {
  var compareString = key.toLowerCase();
  searchText = searchText.toLowerCase();

  var searchTextIndex = 0;
  for (var index = 0; index < key.length; index++) {
    if (compareString[index] === searchText[searchTextIndex]) {
      searchTextIndex += 1;
    }
  }

  return searchTextIndex === searchText.length;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.levenshteinDistance"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.</span>levenshteinDistance (searchText, key)](#apidoc.element.material-ui.AutoComplete.levenshteinDistance)
- description and source-code
```javascript
levenshteinDistance = function (searchText, key) {
  var current = [];
  var prev = void 0;
  var value = void 0;

  for (var i = 0; i <= key.length; i++) {
    for (var j = 0; j <= searchText.length; j++) {
      if (i && j) {
        if (searchText.charAt(j - 1) === key.charAt(i - 1)) value = prev;else value = Math.min(current[j], current[j - 1], prev) +
1;
      } else {
        value = i + j;
      }
      prev = current[j];
      current[j] = value;
    }
  }
  return current.pop();
}
```
- example usage
```shell
...
if (distanceLessThan === undefined) {
  return AutoComplete.levenshteinDistance;
} else if (typeof distanceLessThan !== 'number') {
  throw 'Error: AutoComplete.levenshteinDistanceFilter is a filter generator, not a filter!';
}

return function (s, k) {
  return AutoComplete.levenshteinDistance(s, k) < distanceLessThan;
};
};

AutoComplete.fuzzyFilter = function (searchText, key) {
var compareString = key.toLowerCase();
searchText = searchText.toLowerCase();
...
```

#### <a name="apidoc.element.material-ui.AutoComplete.levenshteinDistanceFilter"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.</span>levenshteinDistanceFilter (distanceLessThan)](#apidoc.element.material-ui.AutoComplete.levenshteinDistanceFilter)
- description and source-code
```javascript
levenshteinDistanceFilter = function (distanceLessThan) {
  if (distanceLessThan === undefined) {
    return AutoComplete.levenshteinDistance;
  } else if (typeof distanceLessThan !== 'number') {
    throw 'Error: AutoComplete.levenshteinDistanceFilter is a filter generator, not a filter!';
  }

  return function (s, k) {
    return AutoComplete.levenshteinDistance(s, k) < distanceLessThan;
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.noFilter"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.</span>noFilter ()](#apidoc.element.material-ui.AutoComplete.noFilter)
- description and source-code
```javascript
noFilter = function () {
  return true;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.material-ui.AutoComplete.contextTypes"></a>[module material-ui.AutoComplete.contextTypes](#apidoc.module.material-ui.AutoComplete.contextTypes)

#### <a name="apidoc.element.material-ui.AutoComplete.contextTypes.muiTheme"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.contextTypes.</span>muiTheme ()](#apidoc.element.material-ui.AutoComplete.contextTypes.muiTheme)
- description and source-code
```javascript
muiTheme = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.material-ui.AutoComplete.defaultProps"></a>[module material-ui.AutoComplete.defaultProps](#apidoc.module.material-ui.AutoComplete.defaultProps)

#### <a name="apidoc.element.material-ui.AutoComplete.defaultProps.filter"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.defaultProps.</span>filter (searchText, key)](#apidoc.element.material-ui.AutoComplete.defaultProps.filter)
- description and source-code
```javascript
function filter(searchText, key) {
  return searchText !== '' && key.indexOf(searchText) !== -1;
}
```
- example usage
```shell
...
});
            }
            break;

          case 'object':
            if (item && typeof item[_this2.props.dataSourceConfig.text] === 'string') {
var itemText = item[_this2.props.dataSourceConfig.text];
if (!_this2.props.filter(searchText, itemText, item)) break;

var itemValue = item[_this2.props.dataSourceConfig.value];
if (itemValue.type && (itemValue.type.muiName === _MenuItem2.default.muiName || itemValue.type.muiName === _Divider2.default.muiName
)) {
  requestsList.push({
    text: itemText,
    value: _react2.default.cloneElement(itemValue, {
      key: index,
...
```

#### <a name="apidoc.element.material-ui.AutoComplete.defaultProps.onNewRequest"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.defaultProps.</span>onNewRequest ()](#apidoc.element.material-ui.AutoComplete.defaultProps.onNewRequest)
- description and source-code
```javascript
function onNewRequest() {}
```
- example usage
```shell
...
    _this.props.onUpdateInput(searchText, _this.props.dataSource, {
      source: 'touchTap'
    });

    _this.timerTouchTapCloseId = setTimeout(function () {
      _this.timerTouchTapCloseId = null;
      _this.close();
      _this.props.onNewRequest(chosenRequest, index);
    }, _this.props.menuCloseDelay);
  });
}, _this.chosenRequestText = function (chosenRequest) {
  if (typeof chosenRequest === 'string') {
    return chosenRequest;
  } else {
    return chosenRequest[_this.props.dataSourceConfig.text];
...
```

#### <a name="apidoc.element.material-ui.AutoComplete.defaultProps.onUpdateInput"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.defaultProps.</span>onUpdateInput ()](#apidoc.element.material-ui.AutoComplete.defaultProps.onUpdateInput)
- description and source-code
```javascript
function onUpdateInput() {}
```
- example usage
```shell
...
      var index = parseInt(child.key, 10);
      var chosenRequest = dataSource[index];
      var searchText = _this.chosenRequestText(chosenRequest);

      _this.setState({
searchText: searchText
      }, function () {
_this.props.onUpdateInput(searchText, _this.props.dataSource, {
  source: 'touchTap'
});

_this.timerTouchTapCloseId = setTimeout(function () {
  _this.timerTouchTapCloseId = null;
  _this.close();
  _this.props.onNewRequest(chosenRequest, index);
...
```



# <a name="apidoc.module.material-ui.AutoComplete.propTypes"></a>[module material-ui.AutoComplete.propTypes](#apidoc.module.material-ui.AutoComplete.propTypes)

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.anchorOrigin"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>anchorOrigin ()](#apidoc.element.material-ui.AutoComplete.propTypes.anchorOrigin)
- description and source-code
```javascript
anchorOrigin = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.animated"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>animated ()](#apidoc.element.material-ui.AutoComplete.propTypes.animated)
- description and source-code
```javascript
animated = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.animation"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>animation ()](#apidoc.element.material-ui.AutoComplete.propTypes.animation)
- description and source-code
```javascript
animation = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.dataSource"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>dataSource ()](#apidoc.element.material-ui.AutoComplete.propTypes.dataSource)
- description and source-code
```javascript
dataSource = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.dataSourceConfig"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>dataSourceConfig ()](#apidoc.element.material-ui.AutoComplete.propTypes.dataSourceConfig)
- description and source-code
```javascript
dataSourceConfig = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.disableFocusRipple"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>disableFocusRipple ()](#apidoc.element.material-ui.AutoComplete.propTypes.disableFocusRipple)
- description and source-code
```javascript
disableFocusRipple = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.errorStyle"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>errorStyle ()](#apidoc.element.material-ui.AutoComplete.propTypes.errorStyle)
- description and source-code
```javascript
errorStyle = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.errorText"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>errorText ()](#apidoc.element.material-ui.AutoComplete.propTypes.errorText)
- description and source-code
```javascript
errorText = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.filter"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>filter ()](#apidoc.element.material-ui.AutoComplete.propTypes.filter)
- description and source-code
```javascript
filter = function () { [native code] }
```
- example usage
```shell
...
});
            }
            break;

          case 'object':
            if (item && typeof item[_this2.props.dataSourceConfig.text] === 'string') {
var itemText = item[_this2.props.dataSourceConfig.text];
if (!_this2.props.filter(searchText, itemText, item)) break;

var itemValue = item[_this2.props.dataSourceConfig.value];
if (itemValue.type && (itemValue.type.muiName === _MenuItem2.default.muiName || itemValue.type.muiName === _Divider2.default.muiName
)) {
  requestsList.push({
    text: itemText,
    value: _react2.default.cloneElement(itemValue, {
      key: index,
...
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.floatingLabelText"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>floatingLabelText ()](#apidoc.element.material-ui.AutoComplete.propTypes.floatingLabelText)
- description and source-code
```javascript
floatingLabelText = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.fullWidth"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>fullWidth ()](#apidoc.element.material-ui.AutoComplete.propTypes.fullWidth)
- description and source-code
```javascript
fullWidth = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.hintText"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>hintText ()](#apidoc.element.material-ui.AutoComplete.propTypes.hintText)
- description and source-code
```javascript
hintText = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.listStyle"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>listStyle ()](#apidoc.element.material-ui.AutoComplete.propTypes.listStyle)
- description and source-code
```javascript
listStyle = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.maxSearchResults"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>maxSearchResults ()](#apidoc.element.material-ui.AutoComplete.propTypes.maxSearchResults)
- description and source-code
```javascript
maxSearchResults = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.menuCloseDelay"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>menuCloseDelay ()](#apidoc.element.material-ui.AutoComplete.propTypes.menuCloseDelay)
- description and source-code
```javascript
menuCloseDelay = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.menuProps"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>menuProps ()](#apidoc.element.material-ui.AutoComplete.propTypes.menuProps)
- description and source-code
```javascript
menuProps = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.menuStyle"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>menuStyle ()](#apidoc.element.material-ui.AutoComplete.propTypes.menuStyle)
- description and source-code
```javascript
menuStyle = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.onBlur"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>onBlur ()](#apidoc.element.material-ui.AutoComplete.propTypes.onBlur)
- description and source-code
```javascript
onBlur = function () { [native code] }
```
- example usage
```shell
...
  if (_this.state.focusTextField && _this.timerTouchTapCloseId === null) {
    _this.timerBlurClose = setTimeout(function () {
      _this.close();
    }, 0);
  }

  if (_this.props.onBlur) {
    _this.props.onBlur(event);
  }
}, _this.handleFocus = function (event) {
  if (!_this.state.open && _this.props.openOnFocus) {
    _this.setState({
      open: true,
      anchorEl: _reactDom2.default.findDOMNode(_this.refs.searchTextField)
    });
...
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.onClose"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>onClose ()](#apidoc.element.material-ui.AutoComplete.propTypes.onClose)
- description and source-code
```javascript
onClose = function () { [native code] }
```
- example usage
```shell
...
  value: function close() {
    this.setState({
      open: false,
      anchorEl: null
    });

    if (this.props.onClose) {
      this.props.onClose();
    }
  }
}, {
  key: 'blur',
  value: function blur() {
    this.refs.searchTextField.blur();
  }
...
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.onFocus"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>onFocus ()](#apidoc.element.material-ui.AutoComplete.propTypes.onFocus)
- description and source-code
```javascript
onFocus = function () { [native code] }
```
- example usage
```shell
...
    }

    _this.setState({
      focusTextField: true
    });

    if (_this.props.onFocus) {
      _this.props.onFocus(event);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}

(0, _createClass3.default)(AutoComplete, [{
  key: 'componentWillMount',
  value: function componentWillMount() {
...
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.onKeyDown"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>onKeyDown ()](#apidoc.element.material-ui.AutoComplete.propTypes.onKeyDown)
- description and source-code
```javascript
onKeyDown = function () { [native code] }
```
- example usage
```shell
...
  return chosenRequest;
} else {
  return chosenRequest[_this.props.dataSourceConfig.text];
}
    }, _this.handleEscKeyDown = function () {
_this.close();
    }, _this.handleKeyDown = function (event) {
if (_this.props.onKeyDown) _this.props.onKeyDown(event);

switch ((0, _keycode2.default)(event)) {
  case 'enter':
    _this.close();
    var searchText = _this.state.searchText;
    if (searchText !== '') {
      _this.props.onNewRequest(searchText, -1);
...
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.onNewRequest"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>onNewRequest ()](#apidoc.element.material-ui.AutoComplete.propTypes.onNewRequest)
- description and source-code
```javascript
onNewRequest = function () { [native code] }
```
- example usage
```shell
...
    _this.props.onUpdateInput(searchText, _this.props.dataSource, {
      source: 'touchTap'
    });

    _this.timerTouchTapCloseId = setTimeout(function () {
      _this.timerTouchTapCloseId = null;
      _this.close();
      _this.props.onNewRequest(chosenRequest, index);
    }, _this.props.menuCloseDelay);
  });
}, _this.chosenRequestText = function (chosenRequest) {
  if (typeof chosenRequest === 'string') {
    return chosenRequest;
  } else {
    return chosenRequest[_this.props.dataSourceConfig.text];
...
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.onUpdateInput"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>onUpdateInput ()](#apidoc.element.material-ui.AutoComplete.propTypes.onUpdateInput)
- description and source-code
```javascript
onUpdateInput = function () { [native code] }
```
- example usage
```shell
...
      var index = parseInt(child.key, 10);
      var chosenRequest = dataSource[index];
      var searchText = _this.chosenRequestText(chosenRequest);

      _this.setState({
searchText: searchText
      }, function () {
_this.props.onUpdateInput(searchText, _this.props.dataSource, {
  source: 'touchTap'
});

_this.timerTouchTapCloseId = setTimeout(function () {
  _this.timerTouchTapCloseId = null;
  _this.close();
  _this.props.onNewRequest(chosenRequest, index);
...
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.open"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>open ()](#apidoc.element.material-ui.AutoComplete.propTypes.open)
- description and source-code
```javascript
open = function () { [native code] }
```
- example usage
```shell
...
    if (swiping === 'opening') {
      _this.setPosition(_this.getMaxTranslateX());
    } else {
      _this.close('swipe');
    }
  } else {
    if (swiping === 'opening') {
      _this.open('swipe');
    } else {
      _this.setPosition(0);
    }
  }
} else {
  _this.maybeSwiping = false;
}
...
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.openOnFocus"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>openOnFocus ()](#apidoc.element.material-ui.AutoComplete.propTypes.openOnFocus)
- description and source-code
```javascript
openOnFocus = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.popoverProps"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>popoverProps ()](#apidoc.element.material-ui.AutoComplete.propTypes.popoverProps)
- description and source-code
```javascript
popoverProps = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.searchText"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>searchText ()](#apidoc.element.material-ui.AutoComplete.propTypes.searchText)
- description and source-code
```javascript
searchText = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.style"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>style ()](#apidoc.element.material-ui.AutoComplete.propTypes.style)
- description and source-code
```javascript
style = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.targetOrigin"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>targetOrigin ()](#apidoc.element.material-ui.AutoComplete.propTypes.targetOrigin)
- description and source-code
```javascript
targetOrigin = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.textFieldStyle"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>textFieldStyle ()](#apidoc.element.material-ui.AutoComplete.propTypes.textFieldStyle)
- description and source-code
```javascript
textFieldStyle = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.material-ui.AutoLockScrolling"></a>[module material-ui.AutoLockScrolling](#apidoc.module.material-ui.AutoLockScrolling)

#### <a name="apidoc.element.material-ui.AutoLockScrolling.default"></a>[function <span class="apidocSignatureSpan">material-ui.AutoLockScrolling.</span>default ()](#apidoc.element.material-ui.AutoLockScrolling.default)
- description and source-code
```javascript
function AutoLockScrolling() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, AutoLockScrolling);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = AutoLockScrolling.__proto__ || (0, _getPrototypeOf2
.default)(AutoLockScrolling)).call.apply(_ref, [this].concat(args))), _this), _this.locked = false, _temp), (0, _possibleConstructorReturn3
.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.Avatar"></a>[module material-ui.Avatar](#apidoc.module.material-ui.Avatar)

#### <a name="apidoc.element.material-ui.Avatar.default"></a>[function <span class="apidocSignatureSpan">material-ui.Avatar.</span>default ()](#apidoc.element.material-ui.Avatar.default)
- description and source-code
```javascript
function Avatar() {
  (0, _classCallCheck3.default)(this, Avatar);
  return (0, _possibleConstructorReturn3.default)(this, (Avatar.__proto__ || (0, _getPrototypeOf2.default)(Avatar)).apply(this,
arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.Badge"></a>[module material-ui.Badge](#apidoc.module.material-ui.Badge)

#### <a name="apidoc.element.material-ui.Badge.default"></a>[function <span class="apidocSignatureSpan">material-ui.Badge.</span>default ()](#apidoc.element.material-ui.Badge.default)
- description and source-code
```javascript
function Badge() {
  (0, _classCallCheck3.default)(this, Badge);
  return (0, _possibleConstructorReturn3.default)(this, (Badge.__proto__ || (0, _getPrototypeOf2.default)(Badge)).apply(this, arguments
));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.BeforeAfterWrapper"></a>[module material-ui.BeforeAfterWrapper](#apidoc.module.material-ui.BeforeAfterWrapper)

#### <a name="apidoc.element.material-ui.BeforeAfterWrapper.default"></a>[function <span class="apidocSignatureSpan">material-ui.BeforeAfterWrapper.</span>default ()](#apidoc.element.material-ui.BeforeAfterWrapper.default)
- description and source-code
```javascript
function BeforeAfterWrapper() {
  (0, _classCallCheck3.default)(this, BeforeAfterWrapper);
  return (0, _possibleConstructorReturn3.default)(this, (BeforeAfterWrapper.__proto__ || (0, _getPrototypeOf2.default)(BeforeAfterWrapper
)).apply(this, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.BottomNavigation"></a>[module material-ui.BottomNavigation](#apidoc.module.material-ui.BottomNavigation)

#### <a name="apidoc.element.material-ui.BottomNavigation.default"></a>[function <span class="apidocSignatureSpan">material-ui.BottomNavigation.</span>default (props, context)](#apidoc.element.material-ui.BottomNavigation.default)
- description and source-code
```javascript
function BottomNavigation(props, context) {
  var children = props.children,
      style = props.style,
      selectedIndex = props.selectedIndex,
      other = (0, _objectWithoutProperties3.default)(props, ['children', 'style', 'selectedIndex']);
  var prepareStyles = context.muiTheme.prepareStyles;

  var styles = getStyles(props, context);

  var preparedChildren = _react.Children.map(children, function (child, index) {
    return (0, _react.cloneElement)(child, {
      style: (0, _simpleAssign2.default)({}, styles.item, child.props.style),
      selected: index === selectedIndex
    });
  });

  return _react2.default.createElement(
    'div',
    (0, _extends3.default)({}, other, { style: prepareStyles((0, _simpleAssign2.default)({}, styles.root, style)) }),
    preparedChildren
  );
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.BottomNavigationItem"></a>[module material-ui.BottomNavigationItem](#apidoc.module.material-ui.BottomNavigationItem)

#### <a name="apidoc.element.material-ui.BottomNavigationItem.default"></a>[function <span class="apidocSignatureSpan">material-ui.BottomNavigationItem.</span>default (props, context)](#apidoc.element.material-ui.BottomNavigationItem.default)
- description and source-code
```javascript
function BottomNavigationItem(props, context) {
  var label = props.label,
      icon = props.icon,
      style = props.style,
      other = (0, _objectWithoutProperties3.default)(props, ['label', 'icon', 'style']);
  var prepareStyles = context.muiTheme.prepareStyles;

  var styles = getStyles(props, context);

  var styledIcon = (0, _react.cloneElement)(icon, {
    style: (0, _simpleAssign2.default)({}, styles.icon, icon.props.style),
    color: icon.props.color || styles.iconColor
  });

  return _react2.default.createElement(
    _EnhancedButton2.default,
    (0, _extends3.default)({}, other, { style: (0, _simpleAssign2.default)({}, styles.root, style) }),
    styledIcon,
    _react2.default.createElement(
      'div',
      { style: prepareStyles(styles.label) },
      label
    )
  );
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.Calendar"></a>[module material-ui.Calendar](#apidoc.module.material-ui.Calendar)

#### <a name="apidoc.element.material-ui.Calendar.default"></a>[function <span class="apidocSignatureSpan">material-ui.Calendar.</span>default ()](#apidoc.element.material-ui.Calendar.default)
- description and source-code
```javascript
function Calendar() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, Calendar);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = Calendar.__proto__ || (0, _getPrototypeOf2
.default)(Calendar)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    displayDate: undefined,
    displayMonthDay: true,
    selectedDate: undefined,
    transitionDirection: 'left',
    transitionEnter: true
  }, _this.handleTouchTapDay = function (event, date) {
    _this.setSelectedDate(date);
    if (_this.props.onTouchTapDay) _this.props.onTouchTapDay(event, date);
  }, _this.handleMonthChange = function (months) {
    _this.setState({
      transitionDirection: months >= 0 ? 'left' : 'right',
      displayDate: (0, _dateUtils.addMonths)(_this.state.displayDate, months)
    });
  }, _this.handleTouchTapYear = function (event, year) {
    var date = (0, _dateUtils.cloneDate)(_this.state.selectedDate);
    date.setFullYear(year);
    _this.setSelectedDate(date, event);
    _this.handleTouchTapDateDisplayMonthDay();
  }, _this.handleTouchTapDateDisplayMonthDay = function () {
    _this.setState({
      displayMonthDay: true
    });
  }, _this.handleTouchTapDateDisplayYear = function () {
    _this.setState({
      displayMonthDay: false
    });
  }, _this.handleWindowKeyDown = function (event) {
    if (_this.props.open) {
      switch ((0, _keycode2.default)(event)) {
        case 'up':
          if (event.altKey && event.shiftKey) {
            _this.addSelectedYears(-1);
          } else if (event.shiftKey) {
            _this.addSelectedMonths(-1);
          } else {
            _this.addSelectedDays(-7);
          }
          break;

        case 'down':
          if (event.altKey && event.shiftKey) {
            _this.addSelectedYears(1);
          } else if (event.shiftKey) {
            _this.addSelectedMonths(1);
          } else {
            _this.addSelectedDays(7);
          }
          break;

        case 'right':
          if (event.altKey && event.shiftKey) {
            _this.addSelectedYears(1);
          } else if (event.shiftKey) {
            _this.addSelectedMonths(1);
          } else {
            _this.addSelectedDays(1);
          }
          break;

        case 'left':
          if (event.altKey && event.shiftKey) {
            _this.addSelectedYears(-1);
          } else if (event.shiftKey) {
            _this.addSelectedMonths(-1);
          } else {
            _this.addSelectedDays(-1);
          }
          break;
      }
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.CalendarActionButtons"></a>[module material-ui.CalendarActionButtons](#apidoc.module.material-ui.CalendarActionButtons)

#### <a name="apidoc.element.material-ui.CalendarActionButtons.default"></a>[function <span class="apidocSignatureSpan">material-ui.CalendarActionButtons.</span>default ()](#apidoc.element.material-ui.CalendarActionButtons.default)
- description and source-code
```javascript
function CalendarActionButton() {
  (0, _classCallCheck3.default)(this, CalendarActionButton);
  return (0, _possibleConstructorReturn3.default)(this, (CalendarActionButton.__proto__ || (0, _getPrototypeOf2.default)(CalendarActionButton
)).apply(this, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.CalendarMonth"></a>[module material-ui.CalendarMonth](#apidoc.module.material-ui.CalendarMonth)

#### <a name="apidoc.element.material-ui.CalendarMonth.default"></a>[function <span class="apidocSignatureSpan">material-ui.CalendarMonth.</span>default ()](#apidoc.element.material-ui.CalendarMonth.default)
- description and source-code
```javascript
function CalendarMonth() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, CalendarMonth);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = CalendarMonth.__proto__ || (0, _getPrototypeOf2
.default)(CalendarMonth)).call.apply(_ref, [this].concat(args))), _this), _this.handleTouchTapDay = function (event, date) {
    if (_this.props.onTouchTapDay) {
      _this.props.onTouchTapDay(event, date);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.CalendarToolbar"></a>[module material-ui.CalendarToolbar](#apidoc.module.material-ui.CalendarToolbar)

#### <a name="apidoc.element.material-ui.CalendarToolbar.default"></a>[function <span class="apidocSignatureSpan">material-ui.CalendarToolbar.</span>default ()](#apidoc.element.material-ui.CalendarToolbar.default)
- description and source-code
```javascript
function CalendarToolbar() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, CalendarToolbar);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = CalendarToolbar.__proto__ || (0, _getPrototypeOf2
.default)(CalendarToolbar)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    transitionDirection: 'up'
  }, _this.handleTouchTapPrevMonth = function () {
    if (_this.props.onMonthChange) {
      _this.props.onMonthChange(-1);
    }
  }, _this.handleTouchTapNextMonth = function () {
    if (_this.props.onMonthChange) {
      _this.props.onMonthChange(1);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.CalendarYear"></a>[module material-ui.CalendarYear](#apidoc.module.material-ui.CalendarYear)

#### <a name="apidoc.element.material-ui.CalendarYear.default"></a>[function <span class="apidocSignatureSpan">material-ui.CalendarYear.</span>default ()](#apidoc.element.material-ui.CalendarYear.default)
- description and source-code
```javascript
function CalendarYear() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, CalendarYear);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = CalendarYear.__proto__ || (0, _getPrototypeOf2
.default)(CalendarYear)).call.apply(_ref, [this].concat(args))), _this), _this.handleTouchTapYear = function (event, year) {
    if (_this.props.onTouchTapYear) {
      _this.props.onTouchTapYear(event, year);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.Card"></a>[module material-ui.Card](#apidoc.module.material-ui.Card)

#### <a name="apidoc.element.material-ui.Card.default"></a>[function <span class="apidocSignatureSpan">material-ui.Card.</span>default ()](#apidoc.element.material-ui.Card.default)
- description and source-code
```javascript
function Card() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, Card);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = Card.__proto__ || (0, _getPrototypeOf2.
default)(Card)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    expanded: null
  }, _this.handleExpanding = function (event) {
    event.preventDefault();
    var newExpandedState = !_this.state.expanded;
    // no automatic state update when the component is controlled
    if (_this.props.expanded === null) {
      _this.setState({ expanded: newExpandedState });
    }
    if (_this.props.onExpandChange) {
      _this.props.onExpandChange(newExpandedState);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.CardActions"></a>[module material-ui.CardActions](#apidoc.module.material-ui.CardActions)

#### <a name="apidoc.element.material-ui.CardActions.default"></a>[function <span class="apidocSignatureSpan">material-ui.CardActions.</span>default ()](#apidoc.element.material-ui.CardActions.default)
- description and source-code
```javascript
function CardActions() {
  (0, _classCallCheck3.default)(this, CardActions);
  return (0, _possibleConstructorReturn3.default)(this, (CardActions.__proto__ || (0, _getPrototypeOf2.default)(CardActions)).apply
(this, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.CardExpandable"></a>[module material-ui.CardExpandable](#apidoc.module.material-ui.CardExpandable)

#### <a name="apidoc.element.material-ui.CardExpandable.default"></a>[function <span class="apidocSignatureSpan">material-ui.CardExpandable.</span>default ()](#apidoc.element.material-ui.CardExpandable.default)
- description and source-code
```javascript
function CardExpandable() {
  (0, _classCallCheck3.default)(this, CardExpandable);
  return (0, _possibleConstructorReturn3.default)(this, (CardExpandable.__proto__ || (0, _getPrototypeOf2.default)(CardExpandable
)).apply(this, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.CardHeader"></a>[module material-ui.CardHeader](#apidoc.module.material-ui.CardHeader)

#### <a name="apidoc.element.material-ui.CardHeader.default"></a>[function <span class="apidocSignatureSpan">material-ui.CardHeader.</span>default ()](#apidoc.element.material-ui.CardHeader.default)
- description and source-code
```javascript
function CardHeader() {
  (0, _classCallCheck3.default)(this, CardHeader);
  return (0, _possibleConstructorReturn3.default)(this, (CardHeader.__proto__ || (0, _getPrototypeOf2.default)(CardHeader)).apply
(this, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.CardMedia"></a>[module material-ui.CardMedia](#apidoc.module.material-ui.CardMedia)

#### <a name="apidoc.element.material-ui.CardMedia.default"></a>[function <span class="apidocSignatureSpan">material-ui.CardMedia.</span>default ()](#apidoc.element.material-ui.CardMedia.default)
- description and source-code
```javascript
function CardMedia() {
  (0, _classCallCheck3.default)(this, CardMedia);
  return (0, _possibleConstructorReturn3.default)(this, (CardMedia.__proto__ || (0, _getPrototypeOf2.default)(CardMedia)).apply(
this, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.CardText"></a>[module material-ui.CardText](#apidoc.module.material-ui.CardText)

#### <a name="apidoc.element.material-ui.CardText.default"></a>[function <span class="apidocSignatureSpan">material-ui.CardText.</span>default ()](#apidoc.element.material-ui.CardText.default)
- description and source-code
```javascript
function CardText() {
  (0, _classCallCheck3.default)(this, CardText);
  return (0, _possibleConstructorReturn3.default)(this, (CardText.__proto__ || (0, _getPrototypeOf2.default)(CardText)).apply(this
, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.CardTitle"></a>[module material-ui.CardTitle](#apidoc.module.material-ui.CardTitle)

#### <a name="apidoc.element.material-ui.CardTitle.default"></a>[function <span class="apidocSignatureSpan">material-ui.CardTitle.</span>default ()](#apidoc.element.material-ui.CardTitle.default)
- description and source-code
```javascript
function CardTitle() {
  (0, _classCallCheck3.default)(this, CardTitle);
  return (0, _possibleConstructorReturn3.default)(this, (CardTitle.__proto__ || (0, _getPrototypeOf2.default)(CardTitle)).apply(
this, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.Checkbox"></a>[module material-ui.Checkbox](#apidoc.module.material-ui.Checkbox)

#### <a name="apidoc.element.material-ui.Checkbox.default"></a>[function <span class="apidocSignatureSpan">material-ui.Checkbox.</span>default ()](#apidoc.element.material-ui.Checkbox.default)
- description and source-code
```javascript
function Checkbox() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, Checkbox);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = Checkbox.__proto__ || (0, _getPrototypeOf2
.default)(Checkbox)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    switched: false
  }, _this.handleStateChange = function (newSwitched) {
    _this.setState({
      switched: newSwitched
    });
  }, _this.handleCheck = function (event, isInputChecked) {
    if (_this.props.onCheck) {
      _this.props.onCheck(event, isInputChecked);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.Chip"></a>[module material-ui.Chip](#apidoc.module.material-ui.Chip)

#### <a name="apidoc.element.material-ui.Chip.default"></a>[function <span class="apidocSignatureSpan">material-ui.Chip.</span>default ()](#apidoc.element.material-ui.Chip.default)
- description and source-code
```javascript
function Chip() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, Chip);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = Chip.__proto__ || (0, _getPrototypeOf2.
default)(Chip)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    clicked: false,
    deleteHovered: false,
    focused: false,
    hovered: false
  }, _this.handleBlur = function (event) {
    _this.setState({ clicked: false, focused: false });
    _this.props.onBlur(event);
  }, _this.handleFocus = function (event) {
    if (_this.props.onTouchTap || _this.props.onRequestDelete) {
      _this.setState({ focused: true });
    }
    _this.props.onFocus(event);
  }, _this.handleKeyboardFocus = function (event, keyboardFocused) {
    if (keyboardFocused) {
      _this.handleFocus();
      _this.props.onFocus(event);
    } else {
      _this.handleBlur();
    }

    _this.props.onKeyboardFocus(event, keyboardFocused);
  }, _this.handleKeyDown = function (event) {
    if ((0, _keycode2.default)(event) === 'backspace') {
      event.preventDefault();
      if (_this.props.onRequestDelete) {
        _this.props.onRequestDelete(event);
      }
    }
    _this.props.onKeyDown(event);
  }, _this.handleMouseDown = function (event) {
    // Only listen to left clicks
    if (event.button === 0) {
      event.stopPropagation();
      if (_this.props.onTouchTap) {
        _this.setState({ clicked: true });
      }
    }
    _this.props.onMouseDown(event);
  }, _this.handleMouseEnter = function (event) {
    if (_this.props.onTouchTap) {
      _this.setState({ hovered: true });
    }
    _this.props.onMouseEnter(event);
  }, _this.handleMouseEnterDeleteIcon = function () {
    _this.setState({ deleteHovered: true });
  }, _this.handleMouseLeave = function (event) {
    _this.setState({
      clicked: false,
      hovered: false
    });
    _this.props.onMouseLeave(event);
  }, _this.handleMouseLeaveDeleteIcon = function () {
    _this.setState({ deleteHovered: false });
  }, _this.handleMouseUp = function (event) {
    _this.setState({ clicked: false });
    _this.props.onMouseUp(event);
  }, _this.handleTouchTapDeleteIcon = function (event) {
    // Stop the event from bubbling up to the 'Chip'
    event.stopPropagation();
    _this.props.onRequestDelete(event);
  }, _this.handleTouchEnd = function (event) {
    _this.setState({ clicked: false });
    _this.props.onTouchEnd(event);
  }, _this.handleTouchStart = function (event) {
    event.stopPropagation();
    if (_this.props.onTouchTap) {
      _this.setState({ clicked: true });
    }
    _this.props.onTouchStart(event);
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.CircleRipple"></a>[module material-ui.CircleRipple](#apidoc.module.material-ui.CircleRipple)

#### <a name="apidoc.element.material-ui.CircleRipple.default"></a>[function <span class="apidocSignatureSpan">material-ui.CircleRipple.</span>default ()](#apidoc.element.material-ui.CircleRipple.default)
- description and source-code
```javascript
function CircleRipple() {
  (0, _classCallCheck3.default)(this, CircleRipple);
  return (0, _possibleConstructorReturn3.default)(this, (CircleRipple.__proto__ || (0, _getPrototypeOf2.default)(CircleRipple)).
apply(this, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.CircularProgress"></a>[module material-ui.CircularProgress](#apidoc.module.material-ui.CircularProgress)

#### <a name="apidoc.element.material-ui.CircularProgress.default"></a>[function <span class="apidocSignatureSpan">material-ui.CircularProgress.</span>default ()](#apidoc.element.material-ui.CircularProgress.default)
- description and source-code
```javascript
function CircularProgress() {
  (0, _classCallCheck3.default)(this, CircularProgress);
  return (0, _possibleConstructorReturn3.default)(this, (CircularProgress.__proto__ || (0, _getPrototypeOf2.default)(CircularProgress
)).apply(this, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.ClearFix"></a>[module material-ui.ClearFix](#apidoc.module.material-ui.ClearFix)

#### <a name="apidoc.element.material-ui.ClearFix.default"></a>[function <span class="apidocSignatureSpan">material-ui.ClearFix.</span>default (_ref)](#apidoc.element.material-ui.ClearFix.default)
- description and source-code
```javascript
function ClearFix(_ref) {
  var style = _ref.style,
      children = _ref.children,
      other = (0, _objectWithoutProperties3.default)(_ref, ['style', 'children']);
  return _react2.default.createElement(
    _BeforeAfterWrapper2.default,
    (0, _extends3.default)({}, other, {
      beforeStyle: styles.before,
      afterStyle: styles.after,
      style: style
    }),
    children
  );
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.ClickAwayListener"></a>[module material-ui.ClickAwayListener](#apidoc.module.material-ui.ClickAwayListener)

#### <a name="apidoc.element.material-ui.ClickAwayListener.default"></a>[function <span class="apidocSignatureSpan">material-ui.ClickAwayListener.</span>default ()](#apidoc.element.material-ui.ClickAwayListener.default)
- description and source-code
```javascript
function ClickAwayListener() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, ClickAwayListener);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = ClickAwayListener.__proto__ || (0, _getPrototypeOf2
.default)(ClickAwayListener)).call.apply(_ref, [this].concat(args))), _this), _this.handleClickAway = function (event) {
    if (event.defaultPrevented) {
      return;
    }

    // IE11 support, which trigger the handleClickAway even after the unbind
    if (_this.isCurrentlyMounted) {
      var el = _reactDom2.default.findDOMNode(_this);

      if (document.documentElement.contains(event.target) && !isDescendant(el, event.target)) {
        _this.props.onClickAway(event);
      }
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.Clock"></a>[module material-ui.Clock](#apidoc.module.material-ui.Clock)

#### <a name="apidoc.element.material-ui.Clock.default"></a>[function <span class="apidocSignatureSpan">material-ui.Clock.</span>default ()](#apidoc.element.material-ui.Clock.default)
- description and source-code
```javascript
function Clock() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, Clock);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = Clock.__proto__ || (0, _getPrototypeOf2
.default)(Clock)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    selectedTime: null,
    mode: 'hour'
  }, _this.setMode = function (mode) {
    setTimeout(function () {
      _this.setState({
        mode: mode
      });
    }, 100);
  }, _this.handleSelectAffix = function (affix) {
    if (affix === _this.getAffix()) return;

    var hours = _this.state.selectedTime.getHours();

    if (affix === 'am') {
      _this.handleChangeHours(hours - 12, affix);
      return;
    }

    _this.handleChangeHours(hours + 12, affix);
  }, _this.handleChangeHours = function (hours, finished) {
    var time = new Date(_this.state.selectedTime);
    var affix = void 0;

    if (typeof finished === 'string') {
      affix = finished;
      finished = undefined;
    }
    if (!affix) {
      affix = _this.getAffix();
    }
    if (affix === 'pm' && hours < 12) {
      hours += 12;
    }

    time.setHours(hours);
    _this.setState({
      selectedTime: time
    });

    if (finished) {
      setTimeout(function () {
        _this.setState({
          mode: 'minute'
        });

        var onChangeHours = _this.props.onChangeHours;

        if (onChangeHours) {
          onChangeHours(time);
        }
      }, 100);
    }
  }, _this.handleChangeMinutes = function (minutes, finished) {
    var time = new Date(_this.state.selectedTime);
    time.setMinutes(minutes);
    _this.setState({
      selectedTime: time
    });

    var onChangeMinutes = _this.props.onChangeMinutes;

    if (onChangeMinutes && finished) {
      setTimeout(function () {
        onChangeMinutes(time);
      }, 0);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.ClockHours"></a>[module material-ui.ClockHours](#apidoc.module.material-ui.ClockHours)

#### <a name="apidoc.element.material-ui.ClockHours.default"></a>[function <span class="apidocSignatureSpan">material-ui.ClockHours.</span>default ()](#apidoc.element.material-ui.ClockHours.default)
- description and source-code
```javascript
function ClockHours() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, ClockHours);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = ClockHours.__proto__ || (0, _getPrototypeOf2
.default)(ClockHours)).call.apply(_ref, [this].concat(args))), _this), _this.handleUp = function (event) {
    event.preventDefault();
    _this.setClock(event.nativeEvent, true);
  }, _this.handleMove = function (event) {
    event.preventDefault();
    if (_this.isMousePressed(event) !== 1) return;
    _this.setClock(event.nativeEvent, false);
  }, _this.handleTouchMove = function (event) {
    event.preventDefault();
    _this.setClock(event.changedTouches[0], false);
  }, _this.handleTouchEnd = function (event) {
    event.preventDefault();
    _this.setClock(event.changedTouches[0], true);
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.ClockMinutes"></a>[module material-ui.ClockMinutes](#apidoc.module.material-ui.ClockMinutes)

#### <a name="apidoc.element.material-ui.ClockMinutes.default"></a>[function <span class="apidocSignatureSpan">material-ui.ClockMinutes.</span>default ()](#apidoc.element.material-ui.ClockMinutes.default)
- description and source-code
```javascript
function ClockMinutes() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, ClockMinutes);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = ClockMinutes.__proto__ || (0, _getPrototypeOf2
.default)(ClockMinutes)).call.apply(_ref, [this].concat(args))), _this), _this.handleUp = function (event) {
    event.preventDefault();
    _this.setClock(event.nativeEvent, true);
  }, _this.handleMove = function (event) {
    event.preventDefault();
    if (_this.isMousePressed(event) !== 1) {
      return;
    }
    _this.setClock(event.nativeEvent, false);
  }, _this.handleTouch = function (event) {
    event.preventDefault();
    _this.setClock(event.changedTouches[0], event.type === 'touchend');
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.ClockNumber"></a>[module material-ui.ClockNumber](#apidoc.module.material-ui.ClockNumber)

#### <a name="apidoc.element.material-ui.ClockNumber.default"></a>[function <span class="apidocSignatureSpan">material-ui.ClockNumber.</span>default ()](#apidoc.element.material-ui.ClockNumber.default)
- description and source-code
```javascript
function ClockNumber() {
  (0, _classCallCheck3.default)(this, ClockNumber);
  return (0, _possibleConstructorReturn3.default)(this, (ClockNumber.__proto__ || (0, _getPrototypeOf2.default)(ClockNumber)).apply
(this, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.ClockPointer"></a>[module material-ui.ClockPointer](#apidoc.module.material-ui.ClockPointer)

#### <a name="apidoc.element.material-ui.ClockPointer.default"></a>[function <span class="apidocSignatureSpan">material-ui.ClockPointer.</span>default ()](#apidoc.element.material-ui.ClockPointer.default)
- description and source-code
```javascript
function ClockPointer() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, ClockPointer);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = ClockPointer.__proto__ || (0, _getPrototypeOf2
.default)(ClockPointer)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    inner: false
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.DateDisplay"></a>[module material-ui.DateDisplay](#apidoc.module.material-ui.DateDisplay)

#### <a name="apidoc.element.material-ui.DateDisplay.default"></a>[function <span class="apidocSignatureSpan">material-ui.DateDisplay.</span>default ()](#apidoc.element.material-ui.DateDisplay.default)
- description and source-code
```javascript
function DateDisplay() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, DateDisplay);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = DateDisplay.__proto__ || (0, _getPrototypeOf2
.default)(DateDisplay)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    selectedYear: false,
    transitionDirection: 'up'
  }, _this.handleTouchTapMonthDay = function () {
    if (_this.props.onTouchTapMonthDay && _this.state.selectedYear) {
      _this.props.onTouchTapMonthDay();
    }

    _this.setState({ selectedYear: false });
  }, _this.handleTouchTapYear = function () {
    if (_this.props.onTouchTapYear && !_this.props.disableYearSelection && !_this.state.selectedYear) {
      _this.props.onTouchTapYear();
    }

    if (!_this.props.disableYearSelection) {
      _this.setState({ selectedYear: true });
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.DatePicker"></a>[module material-ui.DatePicker](#apidoc.module.material-ui.DatePicker)

#### <a name="apidoc.element.material-ui.DatePicker.default"></a>[function <span class="apidocSignatureSpan">material-ui.DatePicker.</span>default ()](#apidoc.element.material-ui.DatePicker.default)
- description and source-code
```javascript
function DatePicker() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, DatePicker);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = DatePicker.__proto__ || (0, _getPrototypeOf2
.default)(DatePicker)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    date: undefined
  }, _this.handleAccept = function (date) {
    if (!_this.isControlled()) {
      _this.setState({
        date: date
      });
    }
    if (_this.props.onChange) {
      _this.props.onChange(null, date);
    }
  }, _this.handleFocus = function (event) {
    event.target.blur();
    if (_this.props.onFocus) {
      _this.props.onFocus(event);
    }
  }, _this.handleTouchTap = function (event) {
    if (_this.props.onTouchTap) {
      _this.props.onTouchTap(event);
    }

    if (!_this.props.disabled) {
      setTimeout(function () {
        _this.openDialog();
      }, 0);
    }
  }, _this.formatDate = function (date) {
    if (_this.props.locale) {
      var DateTimeFormat = _this.props.DateTimeFormat || _dateUtils.dateTimeFormat;
      return new DateTimeFormat(_this.props.locale, {
        day: 'numeric',
        month: 'numeric',
        year: 'numeric'
      }).format(date);
    } else {
      return (0, _dateUtils.formatIso)(date);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.DatePickerDialog"></a>[module material-ui.DatePickerDialog](#apidoc.module.material-ui.DatePickerDialog)

#### <a name="apidoc.element.material-ui.DatePickerDialog.default"></a>[function <span class="apidocSignatureSpan">material-ui.DatePickerDialog.</span>default ()](#apidoc.element.material-ui.DatePickerDialog.default)
- description and source-code
```javascript
function DatePickerDialog() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, DatePickerDialog);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = DatePickerDialog.__proto__ || (0, _getPrototypeOf2
.default)(DatePickerDialog)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    open: false
  }, _this.show = function () {
    if (_this.props.onShow && !_this.state.open) {
      _this.props.onShow();
    }

    _this.setState({
      open: true
    });
  }, _this.dismiss = function () {
    if (_this.props.onDismiss && _this.state.open) {
      _this.props.onDismiss();
    }

    _this.setState({
      open: false
    });
  }, _this.handleTouchTapDay = function () {
    if (_this.props.autoOk) {
      setTimeout(_this.handleTouchTapOk, 300);
    }
  }, _this.handleTouchTapCancel = function () {
    _this.dismiss();
  }, _this.handleRequestClose = function () {
    _this.dismiss();
  }, _this.handleTouchTapOk = function () {
    if (_this.props.onAccept && !_this.refs.calendar.isSelectedDateDisabled()) {
      _this.props.onAccept(_this.refs.calendar.getSelectedDate());
    }

    _this.setState({
      open: false
    });
  }, _this.handleWindowKeyUp = function (event) {
    switch ((0, _keycode2.default)(event)) {
      case 'enter':
        _this.handleTouchTapOk();
        break;
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.DayButton"></a>[module material-ui.DayButton](#apidoc.module.material-ui.DayButton)

#### <a name="apidoc.element.material-ui.DayButton.default"></a>[function <span class="apidocSignatureSpan">material-ui.DayButton.</span>default ()](#apidoc.element.material-ui.DayButton.default)
- description and source-code
```javascript
function DayButton() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, DayButton);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = DayButton.__proto__ || (0, _getPrototypeOf2
.default)(DayButton)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    hover: false
  }, _this.handleMouseEnter = function () {
    if (!_this.props.disabled) {
      _this.setState({ hover: true });
    }
  }, _this.handleMouseLeave = function () {
    if (!_this.props.disabled) {
      _this.setState({ hover: false });
    }
  }, _this.handleTouchTap = function (event) {
    if (!_this.props.disabled && _this.props.onTouchTap) {
      _this.props.onTouchTap(event, _this.props.date);
    }
  }, _this.handleKeyboardFocus = function (event, keyboardFocused) {
    if (!_this.props.disabled && _this.props.onKeyboardFocus) {
      _this.props.onKeyboardFocus(event, keyboardFocused, _this.props.date);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.Dialog"></a>[module material-ui.Dialog](#apidoc.module.material-ui.Dialog)

#### <a name="apidoc.element.material-ui.Dialog.default"></a>[function <span class="apidocSignatureSpan">material-ui.Dialog.</span>default ()](#apidoc.element.material-ui.Dialog.default)
- description and source-code
```javascript
function Dialog() {
  var _ref3;

  var _temp3, _this3, _ret3;

  (0, _classCallCheck3.default)(this, Dialog);

  for (var _len3 = arguments.length, args = Array(_len3), _key3 = 0; _key3 < _len3; _key3++) {
    args[_key3] = arguments[_key3];
  }

  return _ret3 = (_temp3 = (_this3 = (0, _possibleConstructorReturn3.default)(this, (_ref3 = Dialog.__proto__ || (0, _getPrototypeOf2
.default)(Dialog)).call.apply(_ref3, [this].concat(args))), _this3), _this3.renderLayer = function () {
    return _react2.default.createElement(DialogInline, _this3.props);
  }, _temp3), (0, _possibleConstructorReturn3.default)(_this3, _ret3);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.Divider"></a>[module material-ui.Divider](#apidoc.module.material-ui.Divider)

#### <a name="apidoc.element.material-ui.Divider.default"></a>[function <span class="apidocSignatureSpan">material-ui.Divider.</span>default (props, context)](#apidoc.element.material-ui.Divider.default)
- description and source-code
```javascript
function Divider(props, context) {
  var inset = props.inset,
      style = props.style,
      other = (0, _objectWithoutProperties3.default)(props, ['inset', 'style']);
  var _context$muiTheme = context.muiTheme,
      baseTheme = _context$muiTheme.baseTheme,
      prepareStyles = _context$muiTheme.prepareStyles;


  var styles = {
    root: {
      margin: 0,
      marginTop: -1,
      marginLeft: inset ? 72 : 0,
      height: 1,
      border: 'none',
      backgroundColor: baseTheme.palette.borderColor
    }
  };

  return _react2.default.createElement('hr', (0, _extends3.default)({}, other, { style: prepareStyles((0, _simpleAssign2.default
)(styles.root, style)) }));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.Drawer"></a>[module material-ui.Drawer](#apidoc.module.material-ui.Drawer)

#### <a name="apidoc.element.material-ui.Drawer.default"></a>[function <span class="apidocSignatureSpan">material-ui.Drawer.</span>default ()](#apidoc.element.material-ui.Drawer.default)
- description and source-code
```javascript
function Drawer() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, Drawer);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = Drawer.__proto__ || (0, _getPrototypeOf2
.default)(Drawer)).call.apply(_ref, [this].concat(args))), _this), _this.handleTouchTapOverlay = function (event) {
    event.preventDefault();
    _this.close('clickaway');
  }, _this.handleKeyUp = function (event) {
    if (_this.state.open && !_this.props.docked && (0, _keycode2.default)(event) === 'esc') {
      _this.close('escape');
    }
  }, _this.onBodyTouchStart = function (event) {
    var swipeAreaWidth = _this.props.swipeAreaWidth;

    var touchStartX = event.touches[0].pageX;
    var touchStartY = event.touches[0].pageY;

    // Open only if swiping from far left (or right) while closed
    if (swipeAreaWidth !== null && !_this.state.open) {
      if (_this.props.openSecondary) {
        // If openSecondary is true calculate from the far right
        if (touchStartX < document.body.offsetWidth - swipeAreaWidth) return;
      } else {
        // If openSecondary is false calculate from the far left
        if (touchStartX > swipeAreaWidth) return;
      }
    }

    if (!_this.state.open && (openNavEventHandler !== _this.onBodyTouchStart || _this.props.disableSwipeToOpen)) {
      return;
    }

    _this.maybeSwiping = true;
    _this.touchStartX = touchStartX;
    _this.touchStartY = touchStartY;

    document.body.addEventListener('touchmove', _this.onBodyTouchMove);
    document.body.addEventListener('touchend', _this.onBodyTouchEnd);
    document.body.addEventListener('touchcancel', _this.onBodyTouchEnd);
  }, _this.onBodyTouchMove = function (event) {
    var currentX = event.touches[0].pageX;
    var currentY = event.touches[0].pageY;

    if (_this.state.swiping) {
      event.preventDefault();
      _this.setPosition(_this.getTranslateX(currentX));
    } else if (_this.maybeSwiping) {
      var dXAbs = Math.abs(currentX - _this.touchStartX);
      var dYAbs = Math.abs(currentY - _this.touchStartY);
      // If the user has moved his thumb ten pixels in either direction,
      // we can safely make an assumption about whether he was intending
      // to swipe or scroll.
      var threshold = 10;

      if (dXAbs > threshold && dYAbs <= threshold) {
        _this.swipeStartX = currentX;
        _this.setState({
          swiping: _this.state.open ? 'closing' : 'opening'
        });
        _this.setPosition(_this.getTranslateX(currentX));
      } else if (dXAbs <= threshold && dYAbs > threshold) {
        _this.onBodyTouchEnd();
      }
    }
  }, _this.onBodyTouchEnd = function (event) {
    if (_this.state.swiping) {
      var currentX = event.changedTouches[0].pageX;
      var translateRatio = _this.getTranslateX(currentX) / _this.getMaxTranslateX();

      _this.maybeSwiping = false;
      var swiping = _this.state.swiping;
      _this.setState({
        swiping: null
      });

      // We have to open or close after setting swiping to null,
      // because only then CSS transition is enabled.
      if (translateRatio > 0.5) {
        if (swiping === 'opening') {
          _this.setPosition(_this.getMaxTranslateX());
        } else {
          _this.close('swipe');
        }
      } else {
        if (swiping === 'opening') {
          _this.open('swipe');
        } else {
          _this.setPosition(0);
        }
      }
    } else {
      _this.maybeSwiping = false;
    }

    document.body.removeEventListener('touchmove', _this.onBodyTouchMove);
    document.body.removeEventListener('touchend', _this.onBodyTouchEnd);
    document.body.removeEventListener('touchcancel', _this.onBodyTouchEnd);
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.DropDownMenu"></a>[module material-ui.DropDownMenu](#apidoc.module.material-ui.DropDownMenu)

#### <a name="apidoc.element.material-ui.DropDownMenu.default"></a>[function <span class="apidocSignatureSpan">material-ui.DropDownMenu.</span>default ()](#apidoc.element.material-ui.DropDownMenu.default)
- description and source-code
```javascript
function DropDownMenu() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, DropDownMenu);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = DropDownMenu.__proto__ || (0, _getPrototypeOf2
.default)(DropDownMenu)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    open: false
  }, _this.rootNode = undefined, _this.arrowNode = undefined, _this.handleTouchTapControl = function (event) {
    event.preventDefault();
    if (!_this.props.disabled) {
      _this.setState({
        open: !_this.state.open,
        anchorEl: _this.rootNode
      });
    }
  }, _this.handleRequestCloseMenu = function () {
    _this.close(false);
  }, _this.handleEscKeyDownMenu = function () {
    _this.close(true);
  }, _this.handleKeyDown = function (event) {
    switch ((0, _keycode2.default)(event)) {
      case 'up':
      case 'down':
      case 'space':
      case 'enter':
        event.preventDefault();
        _this.setState({
          open: true,
          anchorEl: _this.rootNode
        });
        break;
    }
  }, _this.handleItemTouchTap = function (event, child, index) {
    if (_this.props.multiple) {
      if (!_this.state.open) {
        _this.setState({ open: true });
      }
    } else {
      event.persist();
      _this.setState({
        open: false
      }, function () {
        if (_this.props.onChange) {
          _this.props.onChange(event, index, child.props.value);
        }

        _this.close(_events2.default.isKeyboard(event));
      });
    }
  }, _this.handleChange = function (event, value) {
    if (_this.props.multiple && _this.props.onChange) {
      _this.props.onChange(event, undefined, value);
    }
  }, _this.close = function (isKeyboard) {
    _this.setState({
      open: false
    }, function () {
      if (_this.props.onClose) {
        _this.props.onClose();
      }

      if (isKeyboard) {
        var dropArrow = _this.arrowNode;
        var dropNode = _reactDom2.default.findDOMNode(dropArrow);
        dropNode.focus();
        dropArrow.setKeyboardFocus(true);
      }
    });
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.EnhancedButton"></a>[module material-ui.EnhancedButton](#apidoc.module.material-ui.EnhancedButton)

#### <a name="apidoc.element.material-ui.EnhancedButton.default"></a>[function <span class="apidocSignatureSpan">material-ui.EnhancedButton.</span>default ()](#apidoc.element.material-ui.EnhancedButton.default)
- description and source-code
```javascript
function EnhancedButton() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, EnhancedButton);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = EnhancedButton.__proto__ || (0, _getPrototypeOf2
.default)(EnhancedButton)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    isKeyboardFocused: false
  }, _this.handleKeyDown = function (event) {
    if (!_this.props.disabled && !_this.props.disableKeyboardFocus) {
      if ((0, _keycode2.default)(event) === 'enter' && _this.state.isKeyboardFocused) {
        _this.handleTouchTap(event);
      }
      if ((0, _keycode2.default)(event) === 'esc' && _this.state.isKeyboardFocused) {
        _this.removeKeyboardFocus(event);
      }
    }
    _this.props.onKeyDown(event);
  }, _this.handleKeyUp = function (event) {
    if (!_this.props.disabled && !_this.props.disableKeyboardFocus) {
      if ((0, _keycode2.default)(event) === 'space' && _this.state.isKeyboardFocused) {
        _this.handleTouchTap(event);
      }
    }
    _this.props.onKeyUp(event);
  }, _this.handleBlur = function (event) {
    _this.cancelFocusTimeout();
    _this.removeKeyboardFocus(event);
    _this.props.onBlur(event);
  }, _this.handleFocus = function (event) {
    if (event) event.persist();
    if (!_this.props.disabled && !_this.props.disableKeyboardFocus) {
      // setTimeout is needed because the focus event fires first
      // Wait so that we can capture if this was a keyboard focus
      // or touch focus
      _this.focusTimeout = setTimeout(function () {
        if (tabPressed) {
          _this.setKeyboardFocus(event);
          tabPressed = false;
        }
      }, 150);

      _this.props.onFocus(event);
    }
  }, _this.handleClick = function (event) {
    if (!_this.props.disabled) {
      tabPressed = false;
      _this.props.onClick(event);
    }
  }, _this.handleTouchTap = function (event) {
    _this.cancelFocusTimeout();
    if (!_this.props.disabled) {
      tabPressed = false;
      _this.removeKeyboardFocus(event);
      _this.props.onTouchTap(event);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.EnhancedSwitch"></a>[module material-ui.EnhancedSwitch](#apidoc.module.material-ui.EnhancedSwitch)

#### <a name="apidoc.element.material-ui.EnhancedSwitch.default"></a>[function <span class="apidocSignatureSpan">material-ui.EnhancedSwitch.</span>default ()](#apidoc.element.material-ui.EnhancedSwitch.default)
- description and source-code
```javascript
function EnhancedSwitch() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, EnhancedSwitch);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = EnhancedSwitch.__proto__ || (0, _getPrototypeOf2
.default)(EnhancedSwitch)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    isKeyboardFocused: false
  }, _this.handleChange = function (event) {
    _this.tabPressed = false;
    _this.setState({
      isKeyboardFocused: false
    });

    var isInputChecked = _this.refs.checkbox.checked;

    if (!_this.props.hasOwnProperty('checked') && _this.props.onParentShouldUpdate) {
      _this.props.onParentShouldUpdate(isInputChecked);
    }

    if (_this.props.onSwitch) {
      _this.props.onSwitch(event, isInputChecked);
    }
  }, _this.handleKeyDown = function (event) {
    var code = (0, _keycode2.default)(event);

    if (code === 'tab') {
      _this.tabPressed = true;
    }
    if (_this.state.isKeyboardFocused && code === 'space') {
      _this.handleChange(event);
    }
  }, _this.handleKeyUp = function (event) {
    if (_this.state.isKeyboardFocused && (0, _keycode2.default)(event) === 'space') {
      _this.handleChange(event);
    }
  }, _this.handleMouseDown = function (event) {
    // only listen to left clicks
    if (event.button === 0) {
      _this.refs.touchRipple.start(event);
    }
  }, _this.handleMouseUp = function () {
    _this.refs.touchRipple.end();
  }, _this.handleMouseLeave = function () {
    _this.refs.touchRipple.end();
  }, _this.handleTouchStart = function (event) {
    _this.refs.touchRipple.start(event);
  }, _this.handleTouchEnd = function () {
    _this.refs.touchRipple.end();
  }, _this.handleBlur = function (event) {
    _this.setState({
      isKeyboardFocused: false
    });

    if (_this.props.onBlur) {
      _this.props.onBlur(event);
    }
  }, _this.handleFocus = function (event) {
    // setTimeout is needed becuase the focus event fires first
    // Wait so that we can capture if this was a keyboard focus
    // or touch focus
    setTimeout(function () {
      if (_this.tabPressed) {
        _this.setState({
          isKeyboardFocused: true
        });
      }
    }, 150);

    if (_this.props.onFocus) {
      _this.props.onFocus(event);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.EnhancedTextarea"></a>[module material-ui.EnhancedTextarea](#apidoc.module.material-ui.EnhancedTextarea)

#### <a name="apidoc.element.material-ui.EnhancedTextarea.default"></a>[function <span class="apidocSignatureSpan">material-ui.EnhancedTextarea.</span>default ()](#apidoc.element.material-ui.EnhancedTextarea.default)
- description and source-code
```javascript
function EnhancedTextarea() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, EnhancedTextarea);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = EnhancedTextarea.__proto__ || (0, _getPrototypeOf2
.default)(EnhancedTextarea)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    height: null
  }, _this.handleResize = function (event) {
    _this.syncHeightWithShadow(undefined, event);
  }, _this.handleChange = function (event) {
    _this.syncHeightWithShadow(event.target.value);

    if (_this.props.hasOwnProperty('valueLink')) {
      _this.props.valueLink.requestChange(event.target.value);
    }

    if (_this.props.onChange) {
      _this.props.onChange(event);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.ExpandTransition"></a>[module material-ui.ExpandTransition](#apidoc.module.material-ui.ExpandTransition)

#### <a name="apidoc.element.material-ui.ExpandTransition.default"></a>[function <span class="apidocSignatureSpan">material-ui.ExpandTransition.</span>default ()](#apidoc.element.material-ui.ExpandTransition.default)
- description and source-code
```javascript
function ExpandTransition() {
  (0, _classCallCheck3.default)(this, ExpandTransition);
  return (0, _possibleConstructorReturn3.default)(this, (ExpandTransition.__proto__ || (0, _getPrototypeOf2.default)(ExpandTransition
)).apply(this, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.ExpandTransitionChild"></a>[module material-ui.ExpandTransitionChild](#apidoc.module.material-ui.ExpandTransitionChild)

#### <a name="apidoc.element.material-ui.ExpandTransitionChild.default"></a>[function <span class="apidocSignatureSpan">material-ui.ExpandTransitionChild.</span>default ()](#apidoc.element.material-ui.ExpandTransitionChild.default)
- description and source-code
```javascript
function ExpandTransitionChild() {
  (0, _classCallCheck3.default)(this, ExpandTransitionChild);
  return (0, _possibleConstructorReturn3.default)(this, (ExpandTransitionChild.__proto__ || (0, _getPrototypeOf2.default)(ExpandTransitionChild
)).apply(this, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.FlatButton"></a>[module material-ui.FlatButton](#apidoc.module.material-ui.FlatButton)

#### <a name="apidoc.element.material-ui.FlatButton.default"></a>[function <span class="apidocSignatureSpan">material-ui.FlatButton.</span>default ()](#apidoc.element.material-ui.FlatButton.default)
- description and source-code
```javascript
function FlatButton() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, FlatButton);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = FlatButton.__proto__ || (0, _getPrototypeOf2
.default)(FlatButton)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    hovered: false,
    isKeyboardFocused: false,
    touch: false
  }, _this.handleKeyboardFocus = function (event, isKeyboardFocused) {
    _this.setState({ isKeyboardFocused: isKeyboardFocused });
    _this.props.onKeyboardFocus(event, isKeyboardFocused);
  }, _this.handleMouseEnter = function (event) {
    // Cancel hover styles for touch devices
    if (!_this.state.touch) _this.setState({ hovered: true });
    _this.props.onMouseEnter(event);
  }, _this.handleMouseLeave = function (event) {
    _this.setState({ hovered: false });
    _this.props.onMouseLeave(event);
  }, _this.handleTouchStart = function (event) {
    _this.setState({ touch: true });
    _this.props.onTouchStart(event);
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.FlatButtonLabel"></a>[module material-ui.FlatButtonLabel](#apidoc.module.material-ui.FlatButtonLabel)

#### <a name="apidoc.element.material-ui.FlatButtonLabel.default"></a>[function <span class="apidocSignatureSpan">material-ui.FlatButtonLabel.</span>default ()](#apidoc.element.material-ui.FlatButtonLabel.default)
- description and source-code
```javascript
function FlatButtonLabel() {
  (0, _classCallCheck3.default)(this, FlatButtonLabel);
  return (0, _possibleConstructorReturn3.default)(this, (FlatButtonLabel.__proto__ || (0, _getPrototypeOf2.default)(FlatButtonLabel
)).apply(this, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.FloatingActionButton"></a>[module material-ui.FloatingActionButton](#apidoc.module.material-ui.FloatingActionButton)

#### <a name="apidoc.element.material-ui.FloatingActionButton.default"></a>[function <span class="apidocSignatureSpan">material-ui.FloatingActionButton.</span>default ()](#apidoc.element.material-ui.FloatingActionButton.default)
- description and source-code
```javascript
function FloatingActionButton() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, FloatingActionButton);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = FloatingActionButton.__proto__ || (0, _getPrototypeOf2
.default)(FloatingActionButton)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    hovered: false,
    touch: false,
    zDepth: undefined
  }, _this.handleMouseDown = function (event) {
    // only listen to left clicks
    if (event.button === 0) {
      _this.setState({ zDepth: _this.props.zDepth + 1 });
    }
    if (_this.props.onMouseDown) _this.props.onMouseDown(event);
  }, _this.handleMouseUp = function (event) {
    _this.setState({ zDepth: _this.props.zDepth });
    if (_this.props.onMouseUp) {
      _this.props.onMouseUp(event);
    }
  }, _this.handleMouseLeave = function (event) {
    if (!_this.refs.container.isKeyboardFocused()) {
      _this.setState({ zDepth: _this.props.zDepth, hovered: false });
    }
    if (_this.props.onMouseLeave) {
      _this.props.onMouseLeave(event);
    }
  }, _this.handleMouseEnter = function (event) {
    if (!_this.refs.container.isKeyboardFocused() && !_this.state.touch) {
      _this.setState({ hovered: true });
    }
    if (_this.props.onMouseEnter) {
      _this.props.onMouseEnter(event);
    }
  }, _this.handleTouchStart = function (event) {
    _this.setState({
      touch: true,
      zDepth: _this.props.zDepth + 1
    });
    if (_this.props.onTouchStart) {
      _this.props.onTouchStart(event);
    }
  }, _this.handleTouchEnd = function (event) {
    _this.setState({
      touch: true,
      zDepth: _this.props.zDepth
    });
    if (_this.props.onTouchEnd) {
      _this.props.onTouchEnd(event);
    }
  }, _this.handleKeyboardFocus = function (event, keyboardFocused) {
    if (keyboardFocused && !_this.props.disabled) {
      _this.setState({ zDepth: _this.props.zDepth + 1 });
      _this.refs.overlay.style.backgroundColor = (0, _colorManipulator.fade)(getStyles(_this.props, _this.context).icon.color, 0
.4);
    } else if (!_this.state.hovered) {
      _this.setState({ zDepth: _this.props.zDepth });
      _this.refs.overlay.style.backgroundColor = 'transparent';
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.FocusRipple"></a>[module material-ui.FocusRipple](#apidoc.module.material-ui.FocusRipple)

#### <a name="apidoc.element.material-ui.FocusRipple.default"></a>[function <span class="apidocSignatureSpan">material-ui.FocusRipple.</span>default ()](#apidoc.element.material-ui.FocusRipple.default)
- description and source-code
```javascript
function FocusRipple() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, FocusRipple);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = FocusRipple.__proto__ || (0, _getPrototypeOf2
.default)(FocusRipple)).call.apply(_ref, [this].concat(args))), _this), _this.pulsate = function () {
    var innerCircle = _reactDom2.default.findDOMNode(_this.refs.innerCircle);
    if (!innerCircle) return;

    var startScale = 'scale(1)';
    var endScale = 'scale(0.85)';
    var currentScale = innerCircle.style.transform || startScale;
    var nextScale = currentScale === startScale ? endScale : startScale;

    _autoPrefix2.default.set(innerCircle.style, 'transform', nextScale);
    _this.timeout = setTimeout(_this.pulsate, pulsateDuration);
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.FontIcon"></a>[module material-ui.FontIcon](#apidoc.module.material-ui.FontIcon)

#### <a name="apidoc.element.material-ui.FontIcon.default"></a>[function <span class="apidocSignatureSpan">material-ui.FontIcon.</span>default ()](#apidoc.element.material-ui.FontIcon.default)
- description and source-code
```javascript
function FontIcon() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, FontIcon);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = FontIcon.__proto__ || (0, _getPrototypeOf2
.default)(FontIcon)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    hovered: false
  }, _this.handleMouseLeave = function (event) {
    // hover is needed only when a hoverColor is defined
    if (_this.props.hoverColor !== undefined) {
      _this.setState({ hovered: false });
    }
    if (_this.props.onMouseLeave) {
      _this.props.onMouseLeave(event);
    }
  }, _this.handleMouseEnter = function (event) {
    // hover is needed only when a hoverColor is defined
    if (_this.props.hoverColor !== undefined) {
      _this.setState({ hovered: true });
    }
    if (_this.props.onMouseEnter) {
      _this.props.onMouseEnter(event);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.GridList"></a>[module material-ui.GridList](#apidoc.module.material-ui.GridList)

#### <a name="apidoc.element.material-ui.GridList.default"></a>[function <span class="apidocSignatureSpan">material-ui.GridList.</span>default ()](#apidoc.element.material-ui.GridList.default)
- description and source-code
```javascript
function GridList() {
  (0, _classCallCheck3.default)(this, GridList);
  return (0, _possibleConstructorReturn3.default)(this, (GridList.__proto__ || (0, _getPrototypeOf2.default)(GridList)).apply(this
, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.GridTile"></a>[module material-ui.GridTile](#apidoc.module.material-ui.GridTile)

#### <a name="apidoc.element.material-ui.GridTile.default"></a>[function <span class="apidocSignatureSpan">material-ui.GridTile.</span>default ()](#apidoc.element.material-ui.GridTile.default)
- description and source-code
```javascript
function GridTile() {
  (0, _classCallCheck3.default)(this, GridTile);
  return (0, _possibleConstructorReturn3.default)(this, (GridTile.__proto__ || (0, _getPrototypeOf2.default)(GridTile)).apply(this
, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.IconButton"></a>[module material-ui.IconButton](#apidoc.module.material-ui.IconButton)

#### <a name="apidoc.element.material-ui.IconButton.default"></a>[function <span class="apidocSignatureSpan">material-ui.IconButton.</span>default ()](#apidoc.element.material-ui.IconButton.default)
- description and source-code
```javascript
function IconButton() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, IconButton);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = IconButton.__proto__ || (0, _getPrototypeOf2
.default)(IconButton)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    hovered: false,
    isKeyboardFocused: false,
    // Not to be confonded with the touch property.
    // This state is to determined if it's a mobile device.
    touch: false,
    tooltipShown: false
  }, _this.handleBlur = function (event) {
    _this.hideTooltip();
    if (_this.props.onBlur) {
      _this.props.onBlur(event);
    }
  }, _this.handleFocus = function (event) {
    _this.showTooltip();
    if (_this.props.onFocus) {
      _this.props.onFocus(event);
    }
  }, _this.handleMouseLeave = function (event) {
    if (!_this.button.isKeyboardFocused()) {
      _this.hideTooltip();
    }
    _this.setState({ hovered: false });
    if (_this.props.onMouseLeave) {
      _this.props.onMouseLeave(event);
    }
  }, _this.handleMouseOut = function (event) {
    if (_this.props.disabled) _this.hideTooltip();
    if (_this.props.onMouseOut) _this.props.onMouseOut(event);
  }, _this.handleMouseEnter = function (event) {
    _this.showTooltip();

    // Cancel hover styles for touch devices
    if (!_this.state.touch) {
      _this.setState({ hovered: true });
    }
    if (_this.props.onMouseEnter) {
      _this.props.onMouseEnter(event);
    }
  }, _this.handleTouchStart = function (event) {
    _this.setState({ touch: true });

    if (_this.props.onTouchStart) {
      _this.props.onTouchStart(event);
    }
  }, _this.handleKeyboardFocus = function (event, isKeyboardFocused) {
    var _this$props = _this.props,
        disabled = _this$props.disabled,
        onFocus = _this$props.onFocus,
        onBlur = _this$props.onBlur,
        onKeyboardFocus = _this$props.onKeyboardFocus;

    if (isKeyboardFocused && !disabled) {
      _this.showTooltip();
      if (onFocus) {
        onFocus(event);
      }
    } else {
      _this.hideTooltip();
      if (onBlur) {
        onBlur(event);
      }
    }

    _this.setState({ isKeyboardFocused: isKeyboardFocused });
    if (onKeyboardFocus) {
      onKeyboardFocus(event, isKeyboardFocused);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.IconMenu"></a>[module material-ui.IconMenu](#apidoc.module.material-ui.IconMenu)

#### <a name="apidoc.element.material-ui.IconMenu.default"></a>[function <span class="apidocSignatureSpan">material-ui.IconMenu.</span>default ()](#apidoc.element.material-ui.IconMenu.default)
- description and source-code
```javascript
function IconMenu() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, IconMenu);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = IconMenu.__proto__ || (0, _getPrototypeOf2
.default)(IconMenu)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    menuInitiallyKeyboardFocused: false,
    open: false
  }, _this.handleItemTouchTap = function (event, child) {
    if (_this.props.touchTapCloseDelay !== 0 && !child.props.hasOwnProperty('menuItems')) {
      (function () {
        var isKeyboard = _events2.default.isKeyboard(event);
        _this.timerCloseId = setTimeout(function () {
          _this.close(isKeyboard ? 'enter' : 'itemTap', isKeyboard);
        }, _this.props.touchTapCloseDelay);
      })();
    }

    _this.props.onItemTouchTap(event, child);
  }, _this.handleRequestClose = function (reason) {
    _this.close(reason);
  }, _this.handleEscKeyDownMenu = function (event) {
    _this.close('escape', event);
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.InkBar"></a>[module material-ui.InkBar](#apidoc.module.material-ui.InkBar)

#### <a name="apidoc.element.material-ui.InkBar.default"></a>[function <span class="apidocSignatureSpan">material-ui.InkBar.</span>default ()](#apidoc.element.material-ui.InkBar.default)
- description and source-code
```javascript
function InkBar() {
  (0, _classCallCheck3.default)(this, InkBar);
  return (0, _possibleConstructorReturn3.default)(this, (InkBar.__proto__ || (0, _getPrototypeOf2.default)(InkBar)).apply(this,
arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.LinearProgress"></a>[module material-ui.LinearProgress](#apidoc.module.material-ui.LinearProgress)

#### <a name="apidoc.element.material-ui.LinearProgress.default"></a>[function <span class="apidocSignatureSpan">material-ui.LinearProgress.</span>default ()](#apidoc.element.material-ui.LinearProgress.default)
- description and source-code
```javascript
function LinearProgress() {
  (0, _classCallCheck3.default)(this, LinearProgress);
  return (0, _possibleConstructorReturn3.default)(this, (LinearProgress.__proto__ || (0, _getPrototypeOf2.default)(LinearProgress
)).apply(this, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.List"></a>[module material-ui.List](#apidoc.module.material-ui.List)

#### <a name="apidoc.element.material-ui.List.default"></a>[function <span class="apidocSignatureSpan">material-ui.List.</span>default ()](#apidoc.element.material-ui.List.default)
- description and source-code
```javascript
function List() {
  (0, _classCallCheck3.default)(this, List);
  return (0, _possibleConstructorReturn3.default)(this, (List.__proto__ || (0, _getPrototypeOf2.default)(List)).apply(this, arguments
));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.ListItem"></a>[module material-ui.ListItem](#apidoc.module.material-ui.ListItem)

#### <a name="apidoc.element.material-ui.ListItem.default"></a>[function <span class="apidocSignatureSpan">material-ui.ListItem.</span>default ()](#apidoc.element.material-ui.ListItem.default)
- description and source-code
```javascript
function ListItem() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, ListItem);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = ListItem.__proto__ || (0, _getPrototypeOf2
.default)(ListItem)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    hovered: false,
    isKeyboardFocused: false,
    open: false,
    rightIconButtonHovered: false,
    rightIconButtonKeyboardFocused: false,
    touch: false
  }, _this.handleKeyboardFocus = function (event, isKeyboardFocused) {
    _this.setState({ isKeyboardFocused: isKeyboardFocused });
    _this.props.onKeyboardFocus(event, isKeyboardFocused);
  }, _this.handleMouseEnter = function (event) {
    if (!_this.state.touch) _this.setState({ hovered: true });
    _this.props.onMouseEnter(event);
  }, _this.handleMouseLeave = function (event) {
    _this.setState({ hovered: false });
    _this.props.onMouseLeave(event);
  }, _this.handleNestedListToggle = function (event) {
    event.stopPropagation();

    if (_this.props.open === null) {
      _this.setState({ open: !_this.state.open }, function () {
        _this.props.onNestedListToggle(_this);
      });
    } else {
      // Exposing 'this' in the callback is quite a bad API.
      // I'm doing a one level deep clone to expose a fake state.open.
      _this.props.onNestedListToggle((0, _extends3.default)({}, _this, {
        state: {
          open: !_this.state.open
        }
      }));
    }
  }, _this.handleRightIconButtonKeyboardFocus = function (event, isKeyboardFocused) {
    if (isKeyboardFocused) {
      _this.setState({
        isKeyboardFocused: false,
        rightIconButtonKeyboardFocused: isKeyboardFocused
      });
    }

    var iconButton = _this.props.rightIconButton;

    if (iconButton && iconButton.props.onKeyboardFocus) iconButton.props.onKeyboardFocus(event, isKeyboardFocused);
  }, _this.handleRightIconButtonMouseLeave = function (event) {
    var iconButton = _this.props.rightIconButton;
    _this.setState({ rightIconButtonHovered: false });
    if (iconButton && iconButton.props.onMouseLeave) iconButton.props.onMouseLeave(event);
  }, _this.handleRightIconButtonMouseEnter = function (event) {
    var iconButton = _this.props.rightIconButton;
    _this.setState({ rightIconButtonHovered: true });
    if (iconButton && iconButton.props.onMouseEnter) iconButton.props.onMouseEnter(event);
  }, _this.handleRightIconButtonMouseUp = function (event) {
    var iconButton = _this.props.rightIconButton;
    event.stopPropagation();
    if (iconButton && iconButton.props.onMouseUp) iconButton.props.onMouseUp(event);
  }, _this.handleRightIconButtonTouchTap = function (event) {
    var iconButton = _this.props.rightIconButton;

    // Stop the event from bubbling up to the list-item
    event.stopPropagation();
    if (iconButton && iconButton.props.onTouchTap) iconButton.props.onTouchTap(event);
  }, _this.handleTouchStart = function (event) {
    _this.setState({ touch: true });
    _this.props.onTouchStart(event);
  }, _this.handleTouchEnd = function (event) {
    _this.setState({ touch: true });
    _this.props.onTouchEnd(event);
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.Menu"></a>[module material-ui.Menu](#apidoc.module.material-ui.Menu)

#### <a name="apidoc.element.material-ui.Menu.default"></a>[function <span class="apidocSignatureSpan">material-ui.Menu.</span>default (props, context)](#apidoc.element.material-ui.Menu.default)
- description and source-code
```javascript
function Menu(props, context) {
  (0, _classCallCheck3.default)(this, Menu);

  var _this = (0, _possibleConstructorReturn3.default)(this, (Menu.__proto__ || (0, _getPrototypeOf2.default)(Menu)).call(this,
props, context));

  _initialiseProps.call(_this);

  var filteredChildren = _this.getFilteredChildren(props.children);
  var selectedIndex = _this.getSelectedIndex(props, filteredChildren);

  var newFocusIndex = props.disableAutoFocus ? -1 : selectedIndex >= 0 ? selectedIndex : 0;
  if (newFocusIndex !== -1 && props.onMenuItemFocusChange) {
    props.onMenuItemFocusChange(null, newFocusIndex);
  }
  _this.state = {
    focusIndex: newFocusIndex,
    isKeyboardFocused: props.initiallyKeyboardFocused,
    keyWidth: props.desktop ? 64 : 56
  };

  _this.hotKeyHolder = new _menuUtils.HotKeyHolder();
  return _this;
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.MenuItem"></a>[module material-ui.MenuItem](#apidoc.module.material-ui.MenuItem)

#### <a name="apidoc.element.material-ui.MenuItem.default"></a>[function <span class="apidocSignatureSpan">material-ui.MenuItem.</span>default ()](#apidoc.element.material-ui.MenuItem.default)
- description and source-code
```javascript
function MenuItem() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, MenuItem);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = MenuItem.__proto__ || (0, _getPrototypeOf2
.default)(MenuItem)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    open: false
  }, _this.cloneMenuItem = function (item) {
    return _react2.default.cloneElement(item, {
      onTouchTap: function onTouchTap(event) {
        if (!item.props.menuItems) {
          _this.handleRequestClose();
        }

        if (item.props.onTouchTap) {
          item.props.onTouchTap(event);
        }
      }
    });
  }, _this.handleTouchTap = function (event) {
    event.preventDefault();

    _this.setState({
      open: true,
      anchorEl: _reactDom2.default.findDOMNode(_this)
    });

    if (_this.props.onTouchTap) {
      _this.props.onTouchTap(event);
    }
  }, _this.handleRequestClose = function () {
    _this.setState({
      open: false,
      anchorEl: null
    });
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.MuiThemeProvider"></a>[module material-ui.MuiThemeProvider](#apidoc.module.material-ui.MuiThemeProvider)

#### <a name="apidoc.element.material-ui.MuiThemeProvider.default"></a>[function <span class="apidocSignatureSpan">material-ui.MuiThemeProvider.</span>default ()](#apidoc.element.material-ui.MuiThemeProvider.default)
- description and source-code
```javascript
function MuiThemeProvider() {
  (0, _classCallCheck3.default)(this, MuiThemeProvider);
  return (0, _possibleConstructorReturn3.default)(this, (MuiThemeProvider.__proto__ || (0, _getPrototypeOf2.default)(MuiThemeProvider
)).apply(this, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.NestedList"></a>[module material-ui.NestedList](#apidoc.module.material-ui.NestedList)

#### <a name="apidoc.element.material-ui.NestedList.default"></a>[function <span class="apidocSignatureSpan">material-ui.NestedList.</span>default (props)](#apidoc.element.material-ui.NestedList.default)
- description and source-code
```javascript
function NestedList(props) {
  var children = props.children,
      open = props.open,
      nestedLevel = props.nestedLevel,
      style = props.style;


  if (!open) {
    return null;
  }

  return _react2.default.createElement(
    _List2.default,
    { style: style },
    _react.Children.map(children, function (child) {
      return (0, _react.isValidElement)(child) ? (0, _react.cloneElement)(child, {
        nestedLevel: nestedLevel + 1
      }) : child;
    })
  );
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.Overlay"></a>[module material-ui.Overlay](#apidoc.module.material-ui.Overlay)

#### <a name="apidoc.element.material-ui.Overlay.default"></a>[function <span class="apidocSignatureSpan">material-ui.Overlay.</span>default ()](#apidoc.element.material-ui.Overlay.default)
- description and source-code
```javascript
function Overlay() {
  (0, _classCallCheck3.default)(this, Overlay);
  return (0, _possibleConstructorReturn3.default)(this, (Overlay.__proto__ || (0, _getPrototypeOf2.default)(Overlay)).apply(this
, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.Paper"></a>[module material-ui.Paper](#apidoc.module.material-ui.Paper)

#### <a name="apidoc.element.material-ui.Paper.default"></a>[function <span class="apidocSignatureSpan">material-ui.Paper.</span>default ()](#apidoc.element.material-ui.Paper.default)
- description and source-code
```javascript
function Paper() {
  (0, _classCallCheck3.default)(this, Paper);
  return (0, _possibleConstructorReturn3.default)(this, (Paper.__proto__ || (0, _getPrototypeOf2.default)(Paper)).apply(this, arguments
));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.Popover"></a>[module material-ui.Popover](#apidoc.module.material-ui.Popover)

#### <a name="apidoc.element.material-ui.Popover.default"></a>[function <span class="apidocSignatureSpan">material-ui.Popover.</span>default (props, context)](#apidoc.element.material-ui.Popover.default)
- description and source-code
```javascript
function Popover(props, context) {
  (0, _classCallCheck3.default)(this, Popover);

  var _this = (0, _possibleConstructorReturn3.default)(this, (Popover.__proto__ || (0, _getPrototypeOf2.default)(Popover)).call(
this, props, context));

  _this.timeout = null;

  _this.renderLayer = function () {
    var _this$props = _this.props,
        animated = _this$props.animated,
        animation = _this$props.animation,
        anchorEl = _this$props.anchorEl,
        anchorOrigin = _this$props.anchorOrigin,
        autoCloseWhenOffScreen = _this$props.autoCloseWhenOffScreen,
        canAutoPosition = _this$props.canAutoPosition,
        children = _this$props.children,
        onRequestClose = _this$props.onRequestClose,
        style = _this$props.style,
        targetOrigin = _this$props.targetOrigin,
        useLayerForClickAway = _this$props.useLayerForClickAway,
        other = (0, _objectWithoutProperties3.default)(_this$props, ['animated', 'animation', 'anchorEl', 'anchorOrigin', 'autoCloseWhenOffScreen
', 'canAutoPosition', 'children', 'onRequestClose', 'style', 'targetOrigin', 'useLayerForClickAway']);


    var styleRoot = style;

    if (!animated) {
      styleRoot = {
        position: 'fixed',
        zIndex: _this.context.muiTheme.zIndex.popover
      };

      if (!_this.state.open) {
        return null;
      }

      return _react2.default.createElement(
        _Paper2.default,
        (0, _extends3.default)({ style: (0, _simpleAssign2.default)(styleRoot, style) }, other),
        children
      );
    }

    var Animation = animation || _PopoverAnimationDefault2.default;

    return _react2.default.createElement(
      Animation,
      (0, _extends3.default)({
        targetOrigin: targetOrigin,
        style: styleRoot
      }, other, {
        open: _this.state.open && !_this.state.closing
      }),
      children
    );
  };

  _this.componentClickAway = function (event) {
    event.preventDefault();
    _this.requestClose('clickAway');
  };

  _this.setPlacement = function (scrolling) {
    if (!_this.state.open) {
      return;
    }

    if (!_this.refs.layer.getLayer()) {
      return;
    }

    var targetEl = _this.refs.layer.getLayer().children[0];
    if (!targetEl) {
      return;
    }

    var _this$props2 = _this.props,
        targetOrigin = _this$props2.targetOrigin,
        anchorOrigin = _this$props2.anchorOrigin;

    var anchorEl = _this.props.anchorEl || _this.anchorEl;

    var anchor = _this.getAnchorPosition(anchorEl);
    var target = _this.getTargetPosition(targetEl);

    var targetPosition = {
      top: anchor[anchorOrigin.vertical] - target[targetOrigin.vertical],
      left: anchor[anchorOrigin.horizontal] - target[targetOrigin.horizontal]
    };

    if (scrolling && _this.props.autoCloseWhenOffScreen) {
      _this.autoCloseWhenOffScreen(anchor);
    }

    if (_this.props.canAutoPosition) {
      target = _this.getTargetPosition(targetEl); // update as height may have changed
      targetPosition = _this.applyAutoPositionIfNeeded(anchor, target, targetOrigin, anchorOrigin, targetPosition);
    }

    targetEl.style.top = Math.max(0, targetPosition.top) + 'px';
    targetEl.style.left = Math.max(0, targetPosition.left) + 'px';
    targetEl.style.maxHeight = window.innerHeight + 'px';
  };

  _this.handleResize = (0, _lodash2.default)(_this.setPlacement, 100);
  _this.handleScroll = (0, _lodash2.default)(_this.setPlacement.bind(_this, true), 50);

  _this.state = {
    open: props.open,
    closing: false
  };
  return _this;
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.PopoverAnimationDefault"></a>[module material-ui.PopoverAnimationDefault](#apidoc.module.material-ui.PopoverAnimationDefault)

#### <a name="apidoc.element.material-ui.PopoverAnimationDefault.default"></a>[function <span class="apidocSignatureSpan">material-ui.PopoverAnimationDefault.</span>default ()](#apidoc.element.material-ui.PopoverAnimationDefault.default)
- description and source-code
```javascript
function PopoverAnimationDefault() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, PopoverAnimationDefault);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = PopoverAnimationDefault.__proto__ || (0
, _getPrototypeOf2.default)(PopoverAnimationDefault)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    open: false
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.PopoverAnimationVertical"></a>[module material-ui.PopoverAnimationVertical](#apidoc.module.material-ui.PopoverAnimationVertical)

#### <a name="apidoc.element.material-ui.PopoverAnimationVertical.default"></a>[function <span class="apidocSignatureSpan">material-ui.PopoverAnimationVertical.</span>default ()](#apidoc.element.material-ui.PopoverAnimationVertical.default)
- description and source-code
```javascript
function PopoverAnimationVertical() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, PopoverAnimationVertical);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = PopoverAnimationVertical.__proto__ || (
0, _getPrototypeOf2.default)(PopoverAnimationVertical)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    open: false
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.RadioButton"></a>[module material-ui.RadioButton](#apidoc.module.material-ui.RadioButton)

#### <a name="apidoc.element.material-ui.RadioButton.default"></a>[function <span class="apidocSignatureSpan">material-ui.RadioButton.</span>default ()](#apidoc.element.material-ui.RadioButton.default)
- description and source-code
```javascript
function RadioButton() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, RadioButton);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = RadioButton.__proto__ || (0, _getPrototypeOf2
.default)(RadioButton)).call.apply(_ref, [this].concat(args))), _this), _this.handleSwitch = function (event) {
    if (_this.props.onCheck) {
      _this.props.onCheck(event, _this.props.value);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.RadioButtonGroup"></a>[module material-ui.RadioButtonGroup](#apidoc.module.material-ui.RadioButtonGroup)

#### <a name="apidoc.element.material-ui.RadioButtonGroup.default"></a>[function <span class="apidocSignatureSpan">material-ui.RadioButtonGroup.</span>default ()](#apidoc.element.material-ui.RadioButtonGroup.default)
- description and source-code
```javascript
function RadioButtonGroup() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, RadioButtonGroup);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = RadioButtonGroup.__proto__ || (0, _getPrototypeOf2
.default)(RadioButtonGroup)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    numberCheckedRadioButtons: 0,
    selected: ''
  }, _this.handleChange = function (event, newSelection) {
    _this.updateRadioButtons(newSelection);

    // Successful update
    if (_this.state.numberCheckedRadioButtons === 0) {
      if (_this.props.onChange) _this.props.onChange(event, newSelection);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.RaisedButton"></a>[module material-ui.RaisedButton](#apidoc.module.material-ui.RaisedButton)

#### <a name="apidoc.element.material-ui.RaisedButton.default"></a>[function <span class="apidocSignatureSpan">material-ui.RaisedButton.</span>default ()](#apidoc.element.material-ui.RaisedButton.default)
- description and source-code
```javascript
function RaisedButton() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, RaisedButton);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = RaisedButton.__proto__ || (0, _getPrototypeOf2
.default)(RaisedButton)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    hovered: false,
    keyboardFocused: false,
    touched: false,
    initialZDepth: 0,
    zDepth: 0
  }, _this.handleMouseDown = function (event) {
    // only listen to left clicks
    if (event.button === 0) {
      _this.setState({
        zDepth: _this.state.initialZDepth + 1
      });
    }
    if (_this.props.onMouseDown) {
      _this.props.onMouseDown(event);
    }
  }, _this.handleMouseUp = function (event) {
    _this.setState({
      zDepth: _this.state.initialZDepth
    });
    if (_this.props.onMouseUp) {
      _this.props.onMouseUp(event);
    }
  }, _this.handleMouseLeave = function (event) {
    if (!_this.state.keyboardFocused) {
      _this.setState({
        zDepth: _this.state.initialZDepth,
        hovered: false
      });
    }
    if (_this.props.onMouseLeave) {
      _this.props.onMouseLeave(event);
    }
  }, _this.handleMouseEnter = function (event) {
    if (!_this.state.keyboardFocused && !_this.state.touched) {
      _this.setState({
        hovered: true
      });
    }
    if (_this.props.onMouseEnter) {
      _this.props.onMouseEnter(event);
    }
  }, _this.handleTouchStart = function (event) {
    _this.setState({
      touched: true,
      zDepth: _this.state.initialZDepth + 1
    });

    if (_this.props.onTouchStart) {
      _this.props.onTouchStart(event);
    }
  }, _this.handleTouchEnd = function (event) {
    _this.setState({
      touched: true,
      zDepth: _this.state.initialZDepth
    });

    if (_this.props.onTouchEnd) {
      _this.props.onTouchEnd(event);
    }
  }, _this.handleKeyboardFocus = function (event, keyboardFocused) {
    var zDepth = keyboardFocused && !_this.props.disabled ? _this.state.initialZDepth + 1 : _this.state.initialZDepth;

    _this.setState({
      zDepth: zDepth,
      keyboardFocused: keyboardFocused
    });
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.RefreshIndicator"></a>[module material-ui.RefreshIndicator](#apidoc.module.material-ui.RefreshIndicator)

#### <a name="apidoc.element.material-ui.RefreshIndicator.default"></a>[function <span class="apidocSignatureSpan">material-ui.RefreshIndicator.</span>default ()](#apidoc.element.material-ui.RefreshIndicator.default)
- description and source-code
```javascript
function RefreshIndicator() {
  (0, _classCallCheck3.default)(this, RefreshIndicator);
  return (0, _possibleConstructorReturn3.default)(this, (RefreshIndicator.__proto__ || (0, _getPrototypeOf2.default)(RefreshIndicator
)).apply(this, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.RenderToLayer"></a>[module material-ui.RenderToLayer](#apidoc.module.material-ui.RenderToLayer)

#### <a name="apidoc.element.material-ui.RenderToLayer.default"></a>[function <span class="apidocSignatureSpan">material-ui.RenderToLayer.</span>default ()](#apidoc.element.material-ui.RenderToLayer.default)
- description and source-code
```javascript
function RenderToLayer() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, RenderToLayer);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = RenderToLayer.__proto__ || (0, _getPrototypeOf2
.default)(RenderToLayer)).call.apply(_ref, [this].concat(args))), _this), _this.onClickAway = function (event) {
    if (event.defaultPrevented) {
      return;
    }

    if (!_this.props.componentClickAway) {
      return;
    }

    if (!_this.props.open) {
      return;
    }

    var el = _this.layer;
    if (event.target !== el && event.target === window || document.documentElement.contains(event.target) && !_dom2.default.isDescendant
(el, event.target)) {
      _this.props.componentClickAway(event);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.ScaleIn"></a>[module material-ui.ScaleIn](#apidoc.module.material-ui.ScaleIn)

#### <a name="apidoc.element.material-ui.ScaleIn.default"></a>[function <span class="apidocSignatureSpan">material-ui.ScaleIn.</span>default ()](#apidoc.element.material-ui.ScaleIn.default)
- description and source-code
```javascript
function ScaleIn() {
  (0, _classCallCheck3.default)(this, ScaleIn);
  return (0, _possibleConstructorReturn3.default)(this, (ScaleIn.__proto__ || (0, _getPrototypeOf2.default)(ScaleIn)).apply(this
, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.ScaleInChild"></a>[module material-ui.ScaleInChild](#apidoc.module.material-ui.ScaleInChild)

#### <a name="apidoc.element.material-ui.ScaleInChild.default"></a>[function <span class="apidocSignatureSpan">material-ui.ScaleInChild.</span>default ()](#apidoc.element.material-ui.ScaleInChild.default)
- description and source-code
```javascript
function ScaleInChild() {
  (0, _classCallCheck3.default)(this, ScaleInChild);
  return (0, _possibleConstructorReturn3.default)(this, (ScaleInChild.__proto__ || (0, _getPrototypeOf2.default)(ScaleInChild)).
apply(this, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.SelectField"></a>[module material-ui.SelectField](#apidoc.module.material-ui.SelectField)

#### <a name="apidoc.element.material-ui.SelectField.default"></a>[function <span class="apidocSignatureSpan">material-ui.SelectField.</span>default ()](#apidoc.element.material-ui.SelectField.default)
- description and source-code
```javascript
function SelectField() {
  (0, _classCallCheck3.default)(this, SelectField);
  return (0, _possibleConstructorReturn3.default)(this, (SelectField.__proto__ || (0, _getPrototypeOf2.default)(SelectField)).apply
(this, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.SlideIn"></a>[module material-ui.SlideIn](#apidoc.module.material-ui.SlideIn)

#### <a name="apidoc.element.material-ui.SlideIn.default"></a>[function <span class="apidocSignatureSpan">material-ui.SlideIn.</span>default ()](#apidoc.element.material-ui.SlideIn.default)
- description and source-code
```javascript
function SlideIn() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, SlideIn);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = SlideIn.__proto__ || (0, _getPrototypeOf2
.default)(SlideIn)).call.apply(_ref, [this].concat(args))), _this), _this.getLeaveDirection = function () {
    return _this.props.direction;
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.SlideInChild"></a>[module material-ui.SlideInChild](#apidoc.module.material-ui.SlideInChild)

#### <a name="apidoc.element.material-ui.SlideInChild.default"></a>[function <span class="apidocSignatureSpan">material-ui.SlideInChild.</span>default ()](#apidoc.element.material-ui.SlideInChild.default)
- description and source-code
```javascript
function SlideInChild() {
  (0, _classCallCheck3.default)(this, SlideInChild);
  return (0, _possibleConstructorReturn3.default)(this, (SlideInChild.__proto__ || (0, _getPrototypeOf2.default)(SlideInChild)).
apply(this, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.Slider"></a>[module material-ui.Slider](#apidoc.module.material-ui.Slider)

#### <a name="apidoc.element.material-ui.Slider.default"></a>[function <span class="apidocSignatureSpan">material-ui.Slider.</span>default ()](#apidoc.element.material-ui.Slider.default)
- description and source-code
```javascript
function Slider() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, Slider);

  for (var _len3 = arguments.length, args = Array(_len3), _key3 = 0; _key3 < _len3; _key3++) {
    args[_key3] = arguments[_key3];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = Slider.__proto__ || (0, _getPrototypeOf2
.default)(Slider)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    active: false,
    dragging: false,
    focused: false,
    hovered: false,
    value: 0
  }, _this.track = null, _this.handle = null, _this.handleKeyDown = function (event) {
    var _this$props = _this.props,
        axis = _this$props.axis,
        min = _this$props.min,
        max = _this$props.max,
        step = _this$props.step;


    var action = void 0;

    switch ((0, _keycode2.default)(event)) {
      case 'page down':
      case 'down':
        if (axis === 'y-reverse') {
          action = 'increase';
        } else {
          action = 'decrease';
        }
        break;
      case 'left':
        if (axis === 'x-reverse') {
          action = 'increase';
        } else {
          action = 'decrease';
        }
        break;
      case 'page up':
      case 'up':
        if (axis === 'y-reverse') {
          action = 'decrease';
        } else {
          action = 'increase';
        }
        break;
      case 'right':
        if (axis === 'x-reverse') {
          action = 'decrease';
        } else {
          action = 'increase';
        }
        break;
      case 'home':
        action = 'min';
        break;
      case 'end':
        action = 'max';
        break;
    }

    if (action) {
      var newValue = void 0;

      // Cancel scroll
      event.preventDefault();

      switch (action) {
        case 'decrease':
          newValue = _this.state.value - step;
          break;
        case 'increase':
          newValue = _this.state.value + step;
          break;
        case 'min':
          newValue = min;
          break;
        case 'max':
          newValue = max;
          break;
      }

      // We need to use toFixed() because of float point errors.
      // For example, 0.01 + 0.06 = 0.06999999999999999
      newValue = parseFloat(newValue.toFixed(5));

      if (newValue > max) {
        newValue = max;
      } else if (newValue < min) {
        newValue = min;
      }

      if (_this.state.value !== newValue) {
        _this.setState({
          value: newValue
        });

        if (_this.props.onChange) {
          _this.props.onChange(event, newValue);
        }
      }
    }
  }, _this.handleDragMouseMove = function (event) {
    _this.onDragUpdate(event, 'mouse');
  }, _this.handleTouchMove = function (event) {
    _this.onDragUpdate(event, 'touch');
  }, _this.handleMouseEnd = function (event) {
    document.removeEventListener('mousemove', _this.handleDragMouseMove);
    document.removeEventListener('mouseup', _this.handleMouseEnd);

    _this.onDragStop(event);
  }, _this.handleTouchEnd = function (event) {
    document.removeEventListener('touchmove', _this.handleTouchMove);
    document.removeEventListener('touchup', _this.handleTouchEnd);
    document.removeEventListener('touchend', _this.handleTouchEnd);
    document.removeEventListener('touchcancel', _this.handleTouchEnd);

    _this.onDragStop(event);
  }, _this.handleTouchStart = function (event) {
    if (_this.props.disabled) {
      return;
    }

    var position = void 0;
    if (isMouseControlInverted(_this.props.axis)) {
      position = _this.getTrackOffset() - event.touches[0][mainAxisClientOffsetProperty[_this.props.axis]];
    } else {
      position = event.touches[0][mainAxisClientOffsetProperty[_this.props.axis]] - _this.getTrackOffset();
    }
    _this.setValueFromPosition(event, position);

    document.addEventListener('touchmove', _this.handleTouchMove);
    document.addEventListener('touchup', _this.handleTouchEnd);
    document.addEventListener('touchend', _this.handleTouchEnd);
    document.addEventListener('touchcancel', _this.handleTo ...
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.Snackbar"></a>[module material-ui.Snackbar](#apidoc.module.material-ui.Snackbar)

#### <a name="apidoc.element.material-ui.Snackbar.default"></a>[function <span class="apidocSignatureSpan">material-ui.Snackbar.</span>default ()](#apidoc.element.material-ui.Snackbar.default)
- description and source-code
```javascript
function Snackbar() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, Snackbar);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = Snackbar.__proto__ || (0, _getPrototypeOf2
.default)(Snackbar)).call.apply(_ref, [this].concat(args))), _this), _this.componentClickAway = function () {
    if (_this.timerTransitionId) {
      // If transitioning, don't close the snackbar.
      return;
    }

    if (_this.props.open !== null && _this.props.onRequestClose) {
      _this.props.onRequestClose('clickaway');
    } else {
      _this.setState({ open: false });
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.SnackbarBody"></a>[module material-ui.SnackbarBody](#apidoc.module.material-ui.SnackbarBody)

#### <a name="apidoc.element.material-ui.SnackbarBody.SnackbarBody"></a>[function <span class="apidocSignatureSpan">material-ui.</span>SnackbarBody (props, context)](#apidoc.element.material-ui.SnackbarBody.SnackbarBody)
- description and source-code
```javascript
function SnackbarBody(props, context) {
  var action = props.action,
      contentStyle = props.contentStyle,
      message = props.message,
      open = props.open,
      onActionTouchTap = props.onActionTouchTap,
      style = props.style,
      other = (0, _objectWithoutProperties3.default)(props, ['action', 'contentStyle', 'message', 'open', 'onActionTouchTap', 'style
']);
  var prepareStyles = context.muiTheme.prepareStyles;

  var styles = getStyles(props, context);

  var actionButton = action && _react2.default.createElement(_FlatButton2.default, {
    style: styles.action,
    label: action,
    onTouchTap: onActionTouchTap
  });

  return _react2.default.createElement(
    'div',
    (0, _extends3.default)({}, other, { style: prepareStyles((0, _simpleAssign2.default)(styles.root, style)) }),
    _react2.default.createElement(
      'div',
      { style: prepareStyles((0, _simpleAssign2.default)(styles.content, contentStyle)) },
      _react2.default.createElement(
        'span',
        null,
        message
      ),
      actionButton
    )
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.SnackbarBody.default"></a>[function <span class="apidocSignatureSpan">material-ui.SnackbarBody.</span>default ()](#apidoc.element.material-ui.SnackbarBody.default)
- description and source-code
```javascript
function WithWidth() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, WithWidth);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = WithWidth.__proto__ || (0, _getPrototypeOf2
.default)(WithWidth)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    width: null
  }, _this.handleResize = function () {
    clearTimeout(_this.deferTimer);
    _this.deferTimer = setTimeout(function () {
      _this.updateWidth();
    }, resizeInterval);
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.Step"></a>[module material-ui.Step](#apidoc.module.material-ui.Step)

#### <a name="apidoc.element.material-ui.Step.default"></a>[function <span class="apidocSignatureSpan">material-ui.Step.</span>default ()](#apidoc.element.material-ui.Step.default)
- description and source-code
```javascript
function Step() {
  var _ref3;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, Step);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref3 = Step.__proto__ || (0, _getPrototypeOf2
.default)(Step)).call.apply(_ref3, [this].concat(args))), _this), _this.renderChild = function (child) {
    var _this$props = _this.props,
        active = _this$props.active,
        completed = _this$props.completed,
        disabled = _this$props.disabled,
        index = _this$props.index,
        last = _this$props.last;


    var icon = index + 1;

    return _react2.default.cloneElement(child, (0, _simpleAssign2.default)({ active: active, completed: completed, disabled: disabled
, icon: icon, last: last }, child.props));
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.StepButton"></a>[module material-ui.StepButton](#apidoc.module.material-ui.StepButton)

#### <a name="apidoc.element.material-ui.StepButton.default"></a>[function <span class="apidocSignatureSpan">material-ui.StepButton.</span>default ()](#apidoc.element.material-ui.StepButton.default)
- description and source-code
```javascript
function StepButton() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, StepButton);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = StepButton.__proto__ || (0, _getPrototypeOf2
.default)(StepButton)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    hovered: false,
    touched: false
  }, _this.handleMouseEnter = function (event) {
    var onMouseEnter = _this.props.onMouseEnter;
    // Cancel hover styles for touch devices

    if (!_this.state.touched) {
      _this.setState({ hovered: true });
    }
    if (typeof onMouseEnter === 'function') {
      onMouseEnter(event);
    }
  }, _this.handleMouseLeave = function (event) {
    var onMouseLeave = _this.props.onMouseLeave;

    _this.setState({ hovered: false });
    if (typeof onMouseLeave === 'function') {
      onMouseLeave(event);
    }
  }, _this.handleTouchStart = function (event) {
    var onTouchStart = _this.props.onTouchStart;

    if (!_this.state.touched) {
      _this.setState({ touched: true });
    }
    if (typeof onTouchStart === 'function') {
      onTouchStart(event);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.StepConnector"></a>[module material-ui.StepConnector](#apidoc.module.material-ui.StepConnector)

#### <a name="apidoc.element.material-ui.StepConnector.PlainStepConnector"></a>[function <span class="apidocSignatureSpan">material-ui.StepConnector.</span>PlainStepConnector (props, context)](#apidoc.element.material-ui.StepConnector.PlainStepConnector)
- description and source-code
```javascript
function StepConnector(props, context) {
  var muiTheme = context.muiTheme,
      stepper = context.stepper;


  var styles = {
    wrapper: {
      flex: '1 1 auto'
    },
    line: {
      display: 'block',
      borderColor: muiTheme.stepper.connectorLineColor
    }
  };

<span class="apidocCodeCommentSpan">  /**
   * Clean up once we can use CSS pseudo elements
   */
</span>  if (stepper.orientation === 'horizontal') {
    styles.line.marginLeft = -6;
    styles.line.borderTopStyle = 'solid';
    styles.line.borderTopWidth = 1;
  } else if (stepper.orientation === 'vertical') {
    styles.wrapper.marginLeft = 14 + 11; // padding + 1/2 icon
    styles.line.borderLeftStyle = 'solid';
    styles.line.borderLeftWidth = 1;
    styles.line.minHeight = 28;
  }

  var prepareStyles = muiTheme.prepareStyles;


  return _react2.default.createElement(
    'div',
    { style: prepareStyles(styles.wrapper) },
    _react2.default.createElement('span', { style: prepareStyles(styles.line) })
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.StepConnector.default"></a>[function <span class="apidocSignatureSpan">material-ui.StepConnector.</span>default ()](#apidoc.element.material-ui.StepConnector.default)
- description and source-code
```javascript
function _class() {
  _classCallCheck(this, _class);

  return _possibleConstructorReturn(this, _Component.apply(this, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.StepContent"></a>[module material-ui.StepContent](#apidoc.module.material-ui.StepContent)

#### <a name="apidoc.element.material-ui.StepContent.default"></a>[function <span class="apidocSignatureSpan">material-ui.StepContent.</span>default ()](#apidoc.element.material-ui.StepContent.default)
- description and source-code
```javascript
function StepContent() {
  (0, _classCallCheck3.default)(this, StepContent);
  return (0, _possibleConstructorReturn3.default)(this, (StepContent.__proto__ || (0, _getPrototypeOf2.default)(StepContent)).apply
(this, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.StepLabel"></a>[module material-ui.StepLabel](#apidoc.module.material-ui.StepLabel)

#### <a name="apidoc.element.material-ui.StepLabel.default"></a>[function <span class="apidocSignatureSpan">material-ui.StepLabel.</span>default (props, context)](#apidoc.element.material-ui.StepLabel.default)
- description and source-code
```javascript
function StepLabel(props, context) {
  var active = props.active,
      children = props.children,
      completed = props.completed,
      userIcon = props.icon,
      iconContainerStyle = props.iconContainerStyle,
      last = props.last,
      style = props.style,
      other = (0, _objectWithoutProperties3.default)(props, ['active', 'children', 'completed', 'icon', 'iconContainerStyle', 'last
', 'style']);
  var prepareStyles = context.muiTheme.prepareStyles;

  var styles = getStyles(props, context);
  var icon = renderIcon(completed, userIcon, styles);

  return _react2.default.createElement(
    'span',
    (0, _extends3.default)({ style: prepareStyles((0, _simpleAssign2.default)(styles.root, style)) }, other),
    icon && _react2.default.createElement(
      'span',
      { style: prepareStyles((0, _simpleAssign2.default)(styles.iconContainer, iconContainerStyle)) },
      icon
    ),
    children
  );
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.Stepper"></a>[module material-ui.Stepper](#apidoc.module.material-ui.Stepper)

#### <a name="apidoc.element.material-ui.Stepper.default"></a>[function <span class="apidocSignatureSpan">material-ui.Stepper.</span>default ()](#apidoc.element.material-ui.Stepper.default)
- description and source-code
```javascript
function Stepper() {
  (0, _classCallCheck3.default)(this, Stepper);
  return (0, _possibleConstructorReturn3.default)(this, (Stepper.__proto__ || (0, _getPrototypeOf2.default)(Stepper)).apply(this
, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.Subheader"></a>[module material-ui.Subheader](#apidoc.module.material-ui.Subheader)

#### <a name="apidoc.element.material-ui.Subheader.default"></a>[function <span class="apidocSignatureSpan">material-ui.Subheader.</span>default (props, context)](#apidoc.element.material-ui.Subheader.default)
- description and source-code
```javascript
function Subheader(props, context) {
  var children = props.children,
      inset = props.inset,
      style = props.style,
      other = (0, _objectWithoutProperties3.default)(props, ['children', 'inset', 'style']);
  var _context$muiTheme = context.muiTheme,
      prepareStyles = _context$muiTheme.prepareStyles,
      subheader = _context$muiTheme.subheader;


  var styles = {
    root: {
      boxSizing: 'border-box',
      color: subheader.color,
      fontSize: 14,
      fontWeight: subheader.fontWeight,
      lineHeight: '48px',
      paddingLeft: inset ? 72 : 16,
      width: '100%'
    }
  };

  return _react2.default.createElement(
    'div',
    (0, _extends3.default)({}, other, { style: prepareStyles((0, _simpleAssign2.default)(styles.root, style)) }),
    children
  );
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.SvgIcon"></a>[module material-ui.SvgIcon](#apidoc.module.material-ui.SvgIcon)

#### <a name="apidoc.element.material-ui.SvgIcon.default"></a>[function <span class="apidocSignatureSpan">material-ui.SvgIcon.</span>default ()](#apidoc.element.material-ui.SvgIcon.default)
- description and source-code
```javascript
function SvgIcon() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, SvgIcon);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = SvgIcon.__proto__ || (0, _getPrototypeOf2
.default)(SvgIcon)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    hovered: false
  }, _this.handleMouseLeave = function (event) {
    _this.setState({ hovered: false });
    _this.props.onMouseLeave(event);
  }, _this.handleMouseEnter = function (event) {
    _this.setState({ hovered: true });
    _this.props.onMouseEnter(event);
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.Tab"></a>[module material-ui.Tab](#apidoc.module.material-ui.Tab)

#### <a name="apidoc.element.material-ui.Tab.default"></a>[function <span class="apidocSignatureSpan">material-ui.Tab.</span>default ()](#apidoc.element.material-ui.Tab.default)
- description and source-code
```javascript
function Tab() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, Tab);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = Tab.__proto__ || (0, _getPrototypeOf2.default
)(Tab)).call.apply(_ref, [this].concat(args))), _this), _this.handleTouchTap = function (event) {
    if (_this.props.onTouchTap) {
      _this.props.onTouchTap(_this.props.value, event, _this);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.TabTemplate"></a>[module material-ui.TabTemplate](#apidoc.module.material-ui.TabTemplate)

#### <a name="apidoc.element.material-ui.TabTemplate.default"></a>[function <span class="apidocSignatureSpan">material-ui.TabTemplate.</span>default (_ref)](#apidoc.element.material-ui.TabTemplate.default)
- description and source-code
```javascript
function TabTemplate(_ref) {
  var children = _ref.children,
      selected = _ref.selected,
      style = _ref.style;

  var templateStyle = (0, _simpleAssign2.default)({}, styles, style);
  if (!selected) {
    templateStyle.height = 0;
    templateStyle.overflow = 'hidden';
  }

  return _react2.default.createElement(
    'div',
    { style: templateStyle },
    children
  );
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.Table"></a>[module material-ui.Table](#apidoc.module.material-ui.Table)

#### <a name="apidoc.element.material-ui.Table.default"></a>[function <span class="apidocSignatureSpan">material-ui.Table.</span>default ()](#apidoc.element.material-ui.Table.default)
- description and source-code
```javascript
function Table() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, Table);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = Table.__proto__ || (0, _getPrototypeOf2
.default)(Table)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    allRowsSelected: false
  }, _this.onCellClick = function (rowNumber, columnNumber, event) {
    if (_this.props.onCellClick) _this.props.onCellClick(rowNumber, columnNumber, event);
  }, _this.onCellHover = function (rowNumber, columnNumber, event) {
    if (_this.props.onCellHover) _this.props.onCellHover(rowNumber, columnNumber, event);
  }, _this.onCellHoverExit = function (rowNumber, columnNumber, event) {
    if (_this.props.onCellHoverExit) _this.props.onCellHoverExit(rowNumber, columnNumber, event);
  }, _this.onRowHover = function (rowNumber) {
    if (_this.props.onRowHover) _this.props.onRowHover(rowNumber);
  }, _this.onRowHoverExit = function (rowNumber) {
    if (_this.props.onRowHoverExit) _this.props.onRowHoverExit(rowNumber);
  }, _this.onRowSelection = function (selectedRows) {
    if (_this.state.allRowsSelected) _this.setState({ allRowsSelected: false });
    if (_this.props.onRowSelection) _this.props.onRowSelection(selectedRows);
  }, _this.onSelectAll = function () {
    if (_this.props.onRowSelection) {
      if (!_this.state.allRowsSelected) {
        _this.props.onRowSelection('all');
      } else {
        _this.props.onRowSelection('none');
      }
    }

    _this.setState({ allRowsSelected: !_this.state.allRowsSelected });
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.TableBody"></a>[module material-ui.TableBody](#apidoc.module.material-ui.TableBody)

#### <a name="apidoc.element.material-ui.TableBody.default"></a>[function <span class="apidocSignatureSpan">material-ui.TableBody.</span>default ()](#apidoc.element.material-ui.TableBody.default)
- description and source-code
```javascript
function TableBody() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, TableBody);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = TableBody.__proto__ || (0, _getPrototypeOf2
.default)(TableBody)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    selectedRows: []
  }, _this.handleClickAway = function () {
    if (_this.props.deselectOnClickaway && _this.state.selectedRows.length) {
      _this.setState({
        selectedRows: []
      });
      if (_this.props.onRowSelection) {
        _this.props.onRowSelection([]);
      }
    }
  }, _this.onRowClick = function (event, rowNumber) {
    event.stopPropagation();

    if (_this.props.selectable) {
      // Prevent text selection while selecting rows.
      window.getSelection().removeAllRanges();
      _this.processRowSelection(event, rowNumber);
    }
  }, _this.onCellClick = function (event, rowNumber, columnNumber) {
    event.stopPropagation();
    if (_this.props.onCellClick) {
      _this.props.onCellClick(rowNumber, _this.getColumnId(columnNumber), event);
    }
  }, _this.onCellHover = function (event, rowNumber, columnNumber) {
    if (_this.props.onCellHover) {
      _this.props.onCellHover(rowNumber, _this.getColumnId(columnNumber), event);
    }
    _this.onRowHover(event, rowNumber);
  }, _this.onCellHoverExit = function (event, rowNumber, columnNumber) {
    if (_this.props.onCellHoverExit) {
      _this.props.onCellHoverExit(rowNumber, _this.getColumnId(columnNumber), event);
    }
    _this.onRowHoverExit(event, rowNumber);
  }, _this.onRowHover = function (event, rowNumber) {
    if (_this.props.onRowHover) {
      _this.props.onRowHover(rowNumber);
    }
  }, _this.onRowHoverExit = function (event, rowNumber) {
    if (_this.props.onRowHoverExit) {
      _this.props.onRowHoverExit(rowNumber);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.TableFooter"></a>[module material-ui.TableFooter](#apidoc.module.material-ui.TableFooter)

#### <a name="apidoc.element.material-ui.TableFooter.default"></a>[function <span class="apidocSignatureSpan">material-ui.TableFooter.</span>default ()](#apidoc.element.material-ui.TableFooter.default)
- description and source-code
```javascript
function TableFooter() {
  (0, _classCallCheck3.default)(this, TableFooter);
  return (0, _possibleConstructorReturn3.default)(this, (TableFooter.__proto__ || (0, _getPrototypeOf2.default)(TableFooter)).apply
(this, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.TableHeader"></a>[module material-ui.TableHeader](#apidoc.module.material-ui.TableHeader)

#### <a name="apidoc.element.material-ui.TableHeader.default"></a>[function <span class="apidocSignatureSpan">material-ui.TableHeader.</span>default ()](#apidoc.element.material-ui.TableHeader.default)
- description and source-code
```javascript
function TableHeader() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, TableHeader);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = TableHeader.__proto__ || (0, _getPrototypeOf2
.default)(TableHeader)).call.apply(_ref, [this].concat(args))), _this), _this.handleCheckAll = function (event, checked) {
    if (_this.props.onSelectAll) {
      _this.props.onSelectAll(checked);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.TableHeaderColumn"></a>[module material-ui.TableHeaderColumn](#apidoc.module.material-ui.TableHeaderColumn)

#### <a name="apidoc.element.material-ui.TableHeaderColumn.default"></a>[function <span class="apidocSignatureSpan">material-ui.TableHeaderColumn.</span>default ()](#apidoc.element.material-ui.TableHeaderColumn.default)
- description and source-code
```javascript
function TableHeaderColumn() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, TableHeaderColumn);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = TableHeaderColumn.__proto__ || (0, _getPrototypeOf2
.default)(TableHeaderColumn)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    hovered: false
  }, _this.onMouseEnter = function () {
    if (_this.props.tooltip !== undefined) {
      _this.setState({ hovered: true });
    }
  }, _this.onMouseLeave = function () {
    if (_this.props.tooltip !== undefined) {
      _this.setState({ hovered: false });
    }
  }, _this.onClick = function (event) {
    if (_this.props.onClick) {
      _this.props.onClick(event, _this.props.columnNumber);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.TableRow"></a>[module material-ui.TableRow](#apidoc.module.material-ui.TableRow)

#### <a name="apidoc.element.material-ui.TableRow.default"></a>[function <span class="apidocSignatureSpan">material-ui.TableRow.</span>default ()](#apidoc.element.material-ui.TableRow.default)
- description and source-code
```javascript
function TableRow() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, TableRow);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = TableRow.__proto__ || (0, _getPrototypeOf2
.default)(TableRow)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    hovered: false
  }, _this.onCellClick = function (event, columnIndex) {
    if (_this.props.selectable && _this.props.onCellClick) {
      _this.props.onCellClick(event, _this.props.rowNumber, columnIndex);
    }
    event.ctrlKey = true;
    _this.onRowClick(event);
  }, _this.onCellHover = function (event, columnIndex) {
    if (_this.props.hoverable) {
      _this.setState({ hovered: true });
      if (_this.props.onCellHover) _this.props.onCellHover(event, _this.props.rowNumber, columnIndex);
      _this.onRowHover(event);
    }
  }, _this.onCellHoverExit = function (event, columnIndex) {
    if (_this.props.hoverable) {
      _this.setState({ hovered: false });
      if (_this.props.onCellHoverExit) _this.props.onCellHoverExit(event, _this.props.rowNumber, columnIndex);
      _this.onRowHoverExit(event);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.TableRowColumn"></a>[module material-ui.TableRowColumn](#apidoc.module.material-ui.TableRowColumn)

#### <a name="apidoc.element.material-ui.TableRowColumn.default"></a>[function <span class="apidocSignatureSpan">material-ui.TableRowColumn.</span>default ()](#apidoc.element.material-ui.TableRowColumn.default)
- description and source-code
```javascript
function TableRowColumn() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, TableRowColumn);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = TableRowColumn.__proto__ || (0, _getPrototypeOf2
.default)(TableRowColumn)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    hovered: false
  }, _this.onClick = function (event) {
    if (_this.props.onClick) {
      _this.props.onClick(event, _this.props.columnNumber);
    }
  }, _this.onMouseEnter = function (event) {
    if (_this.props.hoverable) {
      _this.setState({ hovered: true });
      if (_this.props.onHover) {
        _this.props.onHover(event, _this.props.columnNumber);
      }
    }
  }, _this.onMouseLeave = function (event) {
    if (_this.props.hoverable) {
      _this.setState({ hovered: false });
      if (_this.props.onHoverExit) {
        _this.props.onHoverExit(event, _this.props.columnNumber);
      }
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.Tabs"></a>[module material-ui.Tabs](#apidoc.module.material-ui.Tabs)

#### <a name="apidoc.element.material-ui.Tabs.default"></a>[function <span class="apidocSignatureSpan">material-ui.Tabs.</span>default ()](#apidoc.element.material-ui.Tabs.default)
- description and source-code
```javascript
function Tabs() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, Tabs);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = Tabs.__proto__ || (0, _getPrototypeOf2.
default)(Tabs)).call.apply(_ref, [this].concat(args))), _this), _this.state = { selectedIndex: 0 }, _this.handleTabTouchTap = function
 (value, event, tab) {
    var valueLink = _this.getValueLink(_this.props);
    var index = tab.props.index;

    if (valueLink.value && valueLink.value !== value || _this.state.selectedIndex !== index) {
      valueLink.requestChange(value, event, tab);
    }

    _this.setState({ selectedIndex: index });

    if (tab.props.onActive) {
      tab.props.onActive(tab);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.TextField"></a>[module material-ui.TextField](#apidoc.module.material-ui.TextField)

#### <a name="apidoc.element.material-ui.TextField.default"></a>[function <span class="apidocSignatureSpan">material-ui.TextField.</span>default ()](#apidoc.element.material-ui.TextField.default)
- description and source-code
```javascript
function TextField() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, TextField);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = TextField.__proto__ || (0, _getPrototypeOf2
.default)(TextField)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    isFocused: false,
    errorText: undefined,
    hasValue: false
  }, _this.handleInputBlur = function (event) {
    _this.setState({ isFocused: false });
    if (_this.props.onBlur) {
      _this.props.onBlur(event);
    }
  }, _this.handleInputChange = function (event) {
    _this.setState({ hasValue: isValid(event.target.value) });
    if (_this.props.onChange) {
      _this.props.onChange(event, event.target.value);
    }
  }, _this.handleInputFocus = function (event) {
    if (_this.props.disabled) {
      return;
    }
    _this.setState({ isFocused: true });
    if (_this.props.onFocus) {
      _this.props.onFocus(event);
    }
  }, _this.handleHeightChange = function (event, height) {
    var newHeight = height + 24;
    if (_this.props.floatingLabelText) {
      newHeight += 24;
    }
    _reactDom2.default.findDOMNode(_this).style.height = newHeight + 'px';
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.TextFieldHint"></a>[module material-ui.TextFieldHint](#apidoc.module.material-ui.TextFieldHint)

#### <a name="apidoc.element.material-ui.TextFieldHint.default"></a>[function <span class="apidocSignatureSpan">material-ui.TextFieldHint.</span>default (props)](#apidoc.element.material-ui.TextFieldHint.default)
- description and source-code
```javascript
function TextFieldHint(props) {
  var prepareStyles = props.muiTheme.prepareStyles,
      style = props.style,
      text = props.text;


  var styles = getStyles(props);

  return _react2.default.createElement(
    'div',
    { style: prepareStyles((0, _simpleAssign2.default)(styles.root, style)) },
    text
  );
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.TextFieldLabel"></a>[module material-ui.TextFieldLabel](#apidoc.module.material-ui.TextFieldLabel)

#### <a name="apidoc.element.material-ui.TextFieldLabel.default"></a>[function <span class="apidocSignatureSpan">material-ui.TextFieldLabel.</span>default (props)](#apidoc.element.material-ui.TextFieldLabel.default)
- description and source-code
```javascript
function TextFieldLabel(props) {
  var muiTheme = props.muiTheme,
      className = props.className,
      children = props.children,
      htmlFor = props.htmlFor,
      onTouchTap = props.onTouchTap;
  var prepareStyles = muiTheme.prepareStyles;

  var styles = getStyles(props);

  return _react2.default.createElement(
    'label',
    {
      className: className,
      style: prepareStyles(styles.root),
      htmlFor: htmlFor,
      onTouchTap: onTouchTap
    },
    children
  );
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.TextFieldUnderline"></a>[module material-ui.TextFieldUnderline](#apidoc.module.material-ui.TextFieldUnderline)

#### <a name="apidoc.element.material-ui.TextFieldUnderline.default"></a>[function <span class="apidocSignatureSpan">material-ui.TextFieldUnderline.</span>default (props)](#apidoc.element.material-ui.TextFieldUnderline.default)
- description and source-code
```javascript
function TextFieldUnderline(props) {
  var disabled = props.disabled,
      disabledStyle = props.disabledStyle,
      error = props.error,
      errorStyle = props.errorStyle,
      focus = props.focus,
      focusStyle = props.focusStyle,
      muiTheme = props.muiTheme,
      style = props.style;
  var errorStyleColor = errorStyle.color;
  var prepareStyles = muiTheme.prepareStyles,
      _muiTheme$textField = muiTheme.textField,
      borderColor = _muiTheme$textField.borderColor,
      disabledTextColor = _muiTheme$textField.disabledTextColor,
      errorColor = _muiTheme$textField.errorColor,
      focusColor = _muiTheme$textField.focusColor;


  var styles = {
    root: {
      borderTop: 'none',
      borderLeft: 'none',
      borderRight: 'none',
      borderBottom: 'solid 1px',
      borderColor: borderColor,
      bottom: 8,
      boxSizing: 'content-box',
      margin: 0,
      position: 'absolute',
      width: '100%'
    },
    disabled: {
      borderBottom: 'dotted 2px',
      borderColor: disabledTextColor
    },
    focus: {
      borderBottom: 'solid 2px',
      borderColor: focusColor,
      transform: 'scaleX(0)',
      transition: _transitions2.default.easeOut()
    },
    error: {
      borderColor: errorStyleColor ? errorStyleColor : errorColor,
      transform: 'scaleX(1)'
    }
  };

  var underline = (0, _simpleAssign2.default)({}, styles.root, style);
  var focusedUnderline = (0, _simpleAssign2.default)({}, underline, styles.focus, focusStyle);

  if (disabled) underline = (0, _simpleAssign2.default)({}, underline, styles.disabled, disabledStyle);
  if (focus) focusedUnderline = (0, _simpleAssign2.default)({}, focusedUnderline, { transform: 'scaleX(1)' });
  if (error) focusedUnderline = (0, _simpleAssign2.default)({}, focusedUnderline, styles.error);

  return _react2.default.createElement(
    'div',
    null,
    _react2.default.createElement('hr', { style: prepareStyles(underline) }),
    _react2.default.createElement('hr', { style: prepareStyles(focusedUnderline) })
  );
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.TimeDisplay"></a>[module material-ui.TimeDisplay](#apidoc.module.material-ui.TimeDisplay)

#### <a name="apidoc.element.material-ui.TimeDisplay.default"></a>[function <span class="apidocSignatureSpan">material-ui.TimeDisplay.</span>default ()](#apidoc.element.material-ui.TimeDisplay.default)
- description and source-code
```javascript
function TimeDisplay() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, TimeDisplay);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = TimeDisplay.__proto__ || (0, _getPrototypeOf2
.default)(TimeDisplay)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    transitionDirection: 'up'
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.TimePicker"></a>[module material-ui.TimePicker](#apidoc.module.material-ui.TimePicker)

#### <a name="apidoc.element.material-ui.TimePicker.default"></a>[function <span class="apidocSignatureSpan">material-ui.TimePicker.</span>default ()](#apidoc.element.material-ui.TimePicker.default)
- description and source-code
```javascript
function TimePicker() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, TimePicker);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = TimePicker.__proto__ || (0, _getPrototypeOf2
.default)(TimePicker)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    time: null,
    dialogTime: new Date()
  }, _this.handleAcceptDialog = function (time) {
    _this.setState({
      time: time
    });
    if (_this.props.onChange) _this.props.onChange(null, time);
  }, _this.handleFocusInput = function (event) {
    event.target.blur();
    if (_this.props.onFocus) {
      _this.props.onFocus(event);
    }
  }, _this.handleTouchTapInput = function (event) {
    event.preventDefault();

    if (!_this.props.disabled) {
      _this.openDialog();
    }

    if (_this.props.onTouchTap) {
      _this.props.onTouchTap(event);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.TimePickerDialog"></a>[module material-ui.TimePickerDialog](#apidoc.module.material-ui.TimePickerDialog)

#### <a name="apidoc.element.material-ui.TimePickerDialog.default"></a>[function <span class="apidocSignatureSpan">material-ui.TimePickerDialog.</span>default ()](#apidoc.element.material-ui.TimePickerDialog.default)
- description and source-code
```javascript
function TimePickerDialog() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, TimePickerDialog);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = TimePickerDialog.__proto__ || (0, _getPrototypeOf2
.default)(TimePickerDialog)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    open: false
  }, _this.handleRequestClose = function () {
    _this.dismiss();
  }, _this.handleTouchTapCancel = function () {
    _this.dismiss();
  }, _this.handleTouchTapOK = function () {
    if (_this.props.onAccept) {
      _this.props.onAccept(_this.refs.clock.getSelectedTime());
    }
    _this.setState({
      open: false
    });
  }, _this.handleKeyUp = function (event) {
    switch ((0, _keycode2.default)(event)) {
      case 'enter':
        _this.handleTouchTapOK();
        break;
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.Toggle"></a>[module material-ui.Toggle](#apidoc.module.material-ui.Toggle)

#### <a name="apidoc.element.material-ui.Toggle.default"></a>[function <span class="apidocSignatureSpan">material-ui.Toggle.</span>default ()](#apidoc.element.material-ui.Toggle.default)
- description and source-code
```javascript
function Toggle() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, Toggle);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = Toggle.__proto__ || (0, _getPrototypeOf2
.default)(Toggle)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    switched: false
  }, _this.handleStateChange = function (newSwitched) {
    _this.setState({
      switched: newSwitched
    });
  }, _this.handleToggle = function (event, isInputChecked) {
    if (_this.props.onToggle) {
      _this.props.onToggle(event, isInputChecked);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.Toolbar"></a>[module material-ui.Toolbar](#apidoc.module.material-ui.Toolbar)

#### <a name="apidoc.element.material-ui.Toolbar.default"></a>[function <span class="apidocSignatureSpan">material-ui.Toolbar.</span>default ()](#apidoc.element.material-ui.Toolbar.default)
- description and source-code
```javascript
function Toolbar() {
  (0, _classCallCheck3.default)(this, Toolbar);
  return (0, _possibleConstructorReturn3.default)(this, (Toolbar.__proto__ || (0, _getPrototypeOf2.default)(Toolbar)).apply(this
, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.ToolbarGroup"></a>[module material-ui.ToolbarGroup](#apidoc.module.material-ui.ToolbarGroup)

#### <a name="apidoc.element.material-ui.ToolbarGroup.default"></a>[function <span class="apidocSignatureSpan">material-ui.ToolbarGroup.</span>default ()](#apidoc.element.material-ui.ToolbarGroup.default)
- description and source-code
```javascript
function ToolbarGroup() {
  (0, _classCallCheck3.default)(this, ToolbarGroup);
  return (0, _possibleConstructorReturn3.default)(this, (ToolbarGroup.__proto__ || (0, _getPrototypeOf2.default)(ToolbarGroup)).
apply(this, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.ToolbarSeparator"></a>[module material-ui.ToolbarSeparator](#apidoc.module.material-ui.ToolbarSeparator)

#### <a name="apidoc.element.material-ui.ToolbarSeparator.default"></a>[function <span class="apidocSignatureSpan">material-ui.ToolbarSeparator.</span>default ()](#apidoc.element.material-ui.ToolbarSeparator.default)
- description and source-code
```javascript
function ToolbarSeparator() {
  (0, _classCallCheck3.default)(this, ToolbarSeparator);
  return (0, _possibleConstructorReturn3.default)(this, (ToolbarSeparator.__proto__ || (0, _getPrototypeOf2.default)(ToolbarSeparator
)).apply(this, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.ToolbarTitle"></a>[module material-ui.ToolbarTitle](#apidoc.module.material-ui.ToolbarTitle)

#### <a name="apidoc.element.material-ui.ToolbarTitle.default"></a>[function <span class="apidocSignatureSpan">material-ui.ToolbarTitle.</span>default ()](#apidoc.element.material-ui.ToolbarTitle.default)
- description and source-code
```javascript
function ToolbarTitle() {
  (0, _classCallCheck3.default)(this, ToolbarTitle);
  return (0, _possibleConstructorReturn3.default)(this, (ToolbarTitle.__proto__ || (0, _getPrototypeOf2.default)(ToolbarTitle)).
apply(this, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.Tooltip"></a>[module material-ui.Tooltip](#apidoc.module.material-ui.Tooltip)

#### <a name="apidoc.element.material-ui.Tooltip.default"></a>[function <span class="apidocSignatureSpan">material-ui.Tooltip.</span>default ()](#apidoc.element.material-ui.Tooltip.default)
- description and source-code
```javascript
function Tooltip() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, Tooltip);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = Tooltip.__proto__ || (0, _getPrototypeOf2
.default)(Tooltip)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    offsetWidth: null
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.TouchRipple"></a>[module material-ui.TouchRipple](#apidoc.module.material-ui.TouchRipple)

#### <a name="apidoc.element.material-ui.TouchRipple.default"></a>[function <span class="apidocSignatureSpan">material-ui.TouchRipple.</span>default (props, context)](#apidoc.element.material-ui.TouchRipple.default)
- description and source-code
```javascript
function TouchRipple(props, context) {
  (0, _classCallCheck3.default)(this, TouchRipple);

  // Touch start produces a mouse down event for compat reasons. To avoid
  // showing ripples twice we skip showing a ripple for the first mouse down
  // after a touch start. Note we don't store ignoreNextMouseDown in this.state
  // to avoid re-rendering when we change it.
  var _this = (0, _possibleConstructorReturn3.default)(this, (TouchRipple.__proto__ || (0, _getPrototypeOf2.default)(TouchRipple
)).call(this, props, context));

  _this.handleMouseDown = function (event) {
    // only listen to left clicks
    if (event.button === 0) {
      _this.start(event, false);
    }
  };

  _this.handleMouseUp = function () {
    _this.end();
  };

  _this.handleMouseLeave = function () {
    _this.end();
  };

  _this.handleTouchStart = function (event) {
    event.stopPropagation();
    // If the user is swiping (not just tapping), save the position so we can
    // abort ripples if the user appears to be scrolling.
    if (_this.props.abortOnScroll && event.touches) {
      _this.startListeningForScrollAbort(event);
      _this.startTime = Date.now();
    }
    _this.start(event, true);
  };

  _this.handleTouchEnd = function () {
    _this.end();
  };

  _this.handleTouchMove = function (event) {
    // Stop trying to abort if we're already 300ms into the animation
    var timeSinceStart = Math.abs(Date.now() - _this.startTime);
    if (timeSinceStart > 300) {
      _this.stopListeningForScrollAbort();
      return;
    }

    // If the user is scrolling...
    var deltaY = Math.abs(event.touches[0].clientY - _this.firstTouchY);
    var deltaX = Math.abs(event.touches[0].clientX - _this.firstTouchX);
    // Call it a scroll after an arbitrary 6px (feels reasonable in testing)
    if (deltaY > 6 || deltaX > 6) {
      var currentRipples = _this.state.ripples;
      var ripple = currentRipples[0];
      // This clone will replace the ripple in ReactTransitionGroup with a
      // version that will disappear immediately when removed from the DOM
      var abortedRipple = _react2.default.cloneElement(ripple, { aborted: true });
      // Remove the old ripple and replace it with the new updated one
      currentRipples = shift(currentRipples);
      currentRipples = [].concat((0, _toConsumableArray3.default)(currentRipples), [abortedRipple]);
      _this.setState({ ripples: currentRipples }, function () {
        // Call end after we've set the ripple to abort otherwise the setState
        // in end() merges with this and the ripple abort fails
        _this.end();
      });
    }
  };

  _this.ignoreNextMouseDown = false;

  _this.state = {
    // This prop allows us to only render the ReactTransitionGroup
    // on the first click of the component, making the inital render faster.
    hasRipples: false,
    nextKey: 0,
    ripples: []
  };
  return _this;
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.YearButton"></a>[module material-ui.YearButton](#apidoc.module.material-ui.YearButton)

#### <a name="apidoc.element.material-ui.YearButton.default"></a>[function <span class="apidocSignatureSpan">material-ui.YearButton.</span>default ()](#apidoc.element.material-ui.YearButton.default)
- description and source-code
```javascript
function YearButton() {
  var _ref;

  var _temp, _this, _ret;

  (0, _classCallCheck3.default)(this, YearButton);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = YearButton.__proto__ || (0, _getPrototypeOf2
.default)(YearButton)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
    hover: false
  }, _this.handleMouseEnter = function () {
    _this.setState({ hover: true });
  }, _this.handleMouseLeave = function () {
    _this.setState({ hover: false });
  }, _this.handleTouchTap = function (event) {
    if (_this.props.onTouchTap) {
      _this.props.onTouchTap(event, _this.props.year);
    }
  }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.autoprefixer"></a>[module material-ui.autoprefixer](#apidoc.module.material-ui.autoprefixer)

#### <a name="apidoc.element.material-ui.autoprefixer.default"></a>[function <span class="apidocSignatureSpan">material-ui.autoprefixer.</span>default (muiTheme)](#apidoc.element.material-ui.autoprefixer.default)
- description and source-code
```javascript
default = function (muiTheme) {
  var isClient = typeof navigator !== 'undefined';
  var userAgent = muiTheme.userAgent;

  if (userAgent === undefined && isClient) {
    userAgent = navigator.userAgent;
  }

  if (userAgent === undefined && !hasWarnedAboutUserAgent) {
    process.env.NODE_ENV !== "production" ? (0, _warning2.default)(false, 'Material-UI: userAgent should be supplied in the muiTheme
 context\n      for server-side rendering.') : void 0;

    hasWarnedAboutUserAgent = true;
  }

  if (userAgent === false) {
    // Disabled autoprefixer
    return null;
  } else if (userAgent === 'all' || userAgent === undefined) {
    // Prefix for all user agent
    return function (style) {
      var isFlex = ['flex', 'inline-flex'].indexOf(style.display) !== -1;
      var stylePrefixed = _inlineStylePrefixer2.default.prefixAll(style);

      if (isFlex) {
        var display = stylePrefixed.display;
        if (isClient) {
          // We can't apply this join with react-dom:
          // #https://github.com/facebook/react/issues/6467
          stylePrefixed.display = display[display.length - 1];
        } else {
          stylePrefixed.display = display.join('; display: ');
        }
      }

      return stylePrefixed;
    };
  } else {
    var _ret = function () {
      var prefixer = new _inlineStylePrefixer2.default({
        userAgent: userAgent
      });

      return {
        v: function v(style) {
          return prefixer.prefix(style);
        }
      };
    }();

    if ((typeof _ret === 'undefined' ? 'undefined' : (0, _typeof3.default)(_ret)) === "object") return _ret.v;
  }
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.callOnce"></a>[module material-ui.callOnce](#apidoc.module.material-ui.callOnce)

#### <a name="apidoc.element.material-ui.callOnce.default"></a>[function <span class="apidocSignatureSpan">material-ui.callOnce.</span>default ()](#apidoc.element.material-ui.callOnce.default)
- description and source-code
```javascript
function callOnce() {
  if (process.env.NODE_ENV !== 'production') {
    return function (style) {
      if (style[CALLED_ONCE]) {
        process.env.NODE_ENV !== "production" ? (0, _warning2.default)(false, 'Material-UI: You cannot call prepareStyles() on the
 same style object more than once.') : void 0;
      }
      style[CALLED_ONCE] = true;
      return style;
    };
  }
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.childUtils"></a>[module material-ui.childUtils](#apidoc.module.material-ui.childUtils)

#### <a name="apidoc.element.material-ui.childUtils.createChildFragment"></a>[function <span class="apidocSignatureSpan">material-ui.childUtils.</span>createChildFragment (fragments)](#apidoc.element.material-ui.childUtils.createChildFragment)
- description and source-code
```javascript
function createChildFragment(fragments) {
  var newFragments = {};
  var validChildrenCount = 0;
  var firstKey = void 0;

  // Only create non-empty key fragments
  for (var key in fragments) {
    var currentChild = fragments[key];

    if (currentChild) {
      if (validChildrenCount === 0) firstKey = key;
      newFragments[key] = currentChild;
      validChildrenCount++;
    }
  }

  if (validChildrenCount === 0) return undefined;
  if (validChildrenCount === 1) return newFragments[firstKey];
  return (0, _reactAddonsCreateFragment2.default)(newFragments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.childUtils.extendChildren"></a>[function <span class="apidocSignatureSpan">material-ui.childUtils.</span>extendChildren (children, extendedProps, extendedChildren)](#apidoc.element.material-ui.childUtils.extendChildren)
- description and source-code
```javascript
function extendChildren(children, extendedProps, extendedChildren) {
  return _react2.default.Children.map(children, function (child) {
    if (!_react2.default.isValidElement(child)) {
      return child;
    }

    var newProps = typeof extendedProps === 'function' ? extendedProps(child) : extendedProps;

    var newChildren = typeof extendedChildren === 'function' ? extendedChildren(child) : extendedChildren ? extendedChildren : child
.props.children;

    return _react2.default.cloneElement(child, newProps, newChildren);
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.material-ui.colorManipulator"></a>[module material-ui.colorManipulator](#apidoc.module.material-ui.colorManipulator)

#### <a name="apidoc.element.material-ui.colorManipulator.convertColorToString"></a>[function <span class="apidocSignatureSpan">material-ui.colorManipulator.</span>convertColorToString (color)](#apidoc.element.material-ui.colorManipulator.convertColorToString)
- description and source-code
```javascript
function convertColorToString(color) {
  var type = color.type,
      values = color.values;


  if (type.indexOf('rgb') > -1) {
    // Only convert the first 3 values to int (i.e. not alpha)
    for (var i = 0; i < 3; i++) {
      values[i] = parseInt(values[i]);
    }
  }

  var colorString = void 0;

  if (type.indexOf('hsl') > -1) {
    colorString = color.type + '(' + values[0] + ', ' + values[1] + '%, ' + values[2] + '%';
  } else {
    colorString = color.type + '(' + values[0] + ', ' + values[1] + ', ' + values[2];
  }

  if (values.length === 4) {
    colorString += ', ' + color.values[3] + ')';
  } else {
    colorString += ')';
  }

  return colorString;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.colorManipulator.convertHexToRGB"></a>[function <span class="apidocSignatureSpan">material-ui.colorManipulator.</span>convertHexToRGB (color)](#apidoc.element.material-ui.colorManipulator.convertHexToRGB)
- description and source-code
```javascript
function convertHexToRGB(color) {
  if (color.length === 4) {
    var extendedColor = '#';
    for (var i = 1; i < color.length; i++) {
      extendedColor += color.charAt(i) + color.charAt(i);
    }
    color = extendedColor;
  }

  var values = {
    r: parseInt(color.substr(1, 2), 16),
    g: parseInt(color.substr(3, 2), 16),
    b: parseInt(color.substr(5, 2), 16)
  };

  return 'rgb(' + values.r + ', ' + values.g + ', ' + values.b + ')';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.colorManipulator.darken"></a>[function <span class="apidocSignatureSpan">material-ui.colorManipulator.</span>darken (color, coefficient)](#apidoc.element.material-ui.colorManipulator.darken)
- description and source-code
```javascript
function darken(color, coefficient) {
  color = decomposeColor(color);
  coefficient = clamp(coefficient, 0, 1);

  if (color.type.indexOf('hsl') > -1) {
    color.values[2] *= 1 - coefficient;
  } else if (color.type.indexOf('rgb') > -1) {
    for (var i = 0; i < 3; i++) {
      color.values[i] *= 1 - coefficient;
    }
  }
  return convertColorToString(color);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.colorManipulator.decomposeColor"></a>[function <span class="apidocSignatureSpan">material-ui.colorManipulator.</span>decomposeColor (color)](#apidoc.element.material-ui.colorManipulator.decomposeColor)
- description and source-code
```javascript
function decomposeColor(color) {
  if (color.charAt(0) === '#') {
    return decomposeColor(convertHexToRGB(color));
  }

  var marker = color.indexOf('(');

  process.env.NODE_ENV !== "production" ? (0, _warning2.default)(marker !== -1, 'Material-UI: The ' + color + ' color was not parsed
 correctly,\n  because it has an unsupported format (color name or RGB %). This may cause issues in component rendering.') : void 0;

  var type = color.substring(0, marker);
  var values = color.substring(marker + 1, color.length - 1).split(',');
  values = values.map(function (value) {
    return parseFloat(value);
  });

  return { type: type, values: values };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.colorManipulator.emphasize"></a>[function <span class="apidocSignatureSpan">material-ui.colorManipulator.</span>emphasize (color)](#apidoc.element.material-ui.colorManipulator.emphasize)
- description and source-code
```javascript
function emphasize(color) {
  var coefficient = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : 0.15;

  return getLuminance(color) > 0.5 ? darken(color, coefficient) : lighten(color, coefficient);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.colorManipulator.fade"></a>[function <span class="apidocSignatureSpan">material-ui.colorManipulator.</span>fade (color, value)](#apidoc.element.material-ui.colorManipulator.fade)
- description and source-code
```javascript
function fade(color, value) {
  color = decomposeColor(color);
  value = clamp(value, 0, 1);

  if (color.type === 'rgb' || color.type === 'hsl') {
    color.type += 'a';
  }
  color.values[3] = value;

  return convertColorToString(color);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.colorManipulator.getContrastRatio"></a>[function <span class="apidocSignatureSpan">material-ui.colorManipulator.</span>getContrastRatio (foreground, background)](#apidoc.element.material-ui.colorManipulator.getContrastRatio)
- description and source-code
```javascript
function getContrastRatio(foreground, background) {
  var lumA = getLuminance(foreground);
  var lumB = getLuminance(background);
  var contrastRatio = (Math.max(lumA, lumB) + 0.05) / (Math.min(lumA, lumB) + 0.05);

  return Number(contrastRatio.toFixed(2)); // Truncate at two digits
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.colorManipulator.getLuminance"></a>[function <span class="apidocSignatureSpan">material-ui.colorManipulator.</span>getLuminance (color)](#apidoc.element.material-ui.colorManipulator.getLuminance)
- description and source-code
```javascript
function getLuminance(color) {
  color = decomposeColor(color);

  if (color.type.indexOf('rgb') > -1) {
    var rgb = color.values.map(function (val) {
      val /= 255; // normalized
      return val <= 0.03928 ? val / 12.92 : Math.pow((val + 0.055) / 1.055, 2.4);
    });
    return Number((0.2126 * rgb[0] + 0.7152 * rgb[1] + 0.0722 * rgb[2]).toFixed(3)); // Truncate at 3 digits
  } else if (color.type.indexOf('hsl') > -1) {
    return color.values[2] / 100;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.colorManipulator.lighten"></a>[function <span class="apidocSignatureSpan">material-ui.colorManipulator.</span>lighten (color, coefficient)](#apidoc.element.material-ui.colorManipulator.lighten)
- description and source-code
```javascript
function lighten(color, coefficient) {
  color = decomposeColor(color);
  coefficient = clamp(coefficient, 0, 1);

  if (color.type.indexOf('hsl') > -1) {
    color.values[2] += (100 - color.values[2]) * coefficient;
  } else if (color.type.indexOf('rgb') > -1) {
    for (var i = 0; i < 3; i++) {
      color.values[i] += (255 - color.values[i]) * coefficient;
    }
  }

  return convertColorToString(color);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.material-ui.dateUtils"></a>[module material-ui.dateUtils](#apidoc.module.material-ui.dateUtils)

#### <a name="apidoc.element.material-ui.dateUtils.addDays"></a>[function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>addDays (d, days)](#apidoc.element.material-ui.dateUtils.addDays)
- description and source-code
```javascript
function addDays(d, days) {
  var newDate = cloneDate(d);
  newDate.setDate(d.getDate() + days);
  return newDate;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.dateUtils.addMonths"></a>[function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>addMonths (d, months)](#apidoc.element.material-ui.dateUtils.addMonths)
- description and source-code
```javascript
function addMonths(d, months) {
  var newDate = cloneDate(d);
  newDate.setMonth(d.getMonth() + months);
  return newDate;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.dateUtils.addYears"></a>[function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>addYears (d, years)](#apidoc.element.material-ui.dateUtils.addYears)
- description and source-code
```javascript
function addYears(d, years) {
  var newDate = cloneDate(d);
  newDate.setFullYear(d.getFullYear() + years);
  return newDate;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.dateUtils.cloneAsDate"></a>[function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>cloneAsDate (d)](#apidoc.element.material-ui.dateUtils.cloneAsDate)
- description and source-code
```javascript
function cloneAsDate(d) {
  var clonedDate = cloneDate(d);
  clonedDate.setHours(0, 0, 0, 0);
  return clonedDate;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.dateUtils.cloneDate"></a>[function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>cloneDate (d)](#apidoc.element.material-ui.dateUtils.cloneDate)
- description and source-code
```javascript
function cloneDate(d) {
  return new Date(d.getTime());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.dateUtils.dateTimeFormat"></a>[function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>dateTimeFormat (locale, options)](#apidoc.element.material-ui.dateUtils.dateTimeFormat)
- description and source-code
```javascript
function dateTimeFormat(locale, options) {
  process.env.NODE_ENV !== "production" ? (0, _warning2.default)(locale === 'en-US', 'Material-UI: The ' + locale + ' locale is
not supported by the built-in DateTimeFormat.\n  Use the 'DateTimeFormat' prop to supply an alternative implementation.') : void 0;

  this.format = function (date) {
    if (options.month === 'short' && options.weekday === 'short' && options.day === '2-digit') {
      return dayList[date.getDay()] + ', ' + monthList[date.getMonth()] + ' ' + date.getDate();
    } else if (options.year === 'numeric' && options.month === 'numeric' && options.day === 'numeric') {
      return date.getMonth() + 1 + '/' + date.getDate() + '/' + date.getFullYear();
    } else if (options.year === 'numeric' && options.month === 'long') {
      return monthLongList[date.getMonth()] + ' ' + date.getFullYear();
    } else if (options.weekday === 'narrow') {
      return dayAbbreviation[date.getDay()];
    } else if (options.year === 'numeric') {
      return date.getFullYear().toString();
    } else if (options.day === 'numeric') {
      return date.getDate();
    } else {
      process.env.NODE_ENV !== "production" ? (0, _warning2.default)(false, 'Material-UI: Wrong usage of DateTimeFormat') : void
 0;
    }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.dateUtils.formatIso"></a>[function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>formatIso (date)](#apidoc.element.material-ui.dateUtils.formatIso)
- description and source-code
```javascript
function formatIso(date) {
  return new Date(date.toDateString() + ' 12:00:00 +0000').toISOString().substring(0, 10);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.dateUtils.getDaysInMonth"></a>[function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>getDaysInMonth (d)](#apidoc.element.material-ui.dateUtils.getDaysInMonth)
- description and source-code
```javascript
function getDaysInMonth(d) {
  var resultDate = getFirstDayOfMonth(d);

  resultDate.setMonth(resultDate.getMonth() + 1);
  resultDate.setDate(resultDate.getDate() - 1);

  return resultDate.getDate();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.dateUtils.getFirstDayOfMonth"></a>[function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>getFirstDayOfMonth (d)](#apidoc.element.material-ui.dateUtils.getFirstDayOfMonth)
- description and source-code
```javascript
function getFirstDayOfMonth(d) {
  return new Date(d.getFullYear(), d.getMonth(), 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.dateUtils.getFirstDayOfWeek"></a>[function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>getFirstDayOfWeek ()](#apidoc.element.material-ui.dateUtils.getFirstDayOfWeek)
- description and source-code
```javascript
function getFirstDayOfWeek() {
  var now = new Date();
  return new Date(now.setDate(now.getDate() - now.getDay()));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.dateUtils.getWeekArray"></a>[function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>getWeekArray (d, firstDayOfWeek)](#apidoc.element.material-ui.dateUtils.getWeekArray)
- description and source-code
```javascript
function getWeekArray(d, firstDayOfWeek) {
  var dayArray = [];
  var daysInMonth = getDaysInMonth(d);
  var weekArray = [];
  var week = [];

  for (var i = 1; i <= daysInMonth; i++) {
    dayArray.push(new Date(d.getFullYear(), d.getMonth(), i));
  }

  var addWeek = function addWeek(week) {
    var emptyDays = 7 - week.length;
    for (var _i = 0; _i < emptyDays; ++_i) {
      week[weekArray.length ? 'push' : 'unshift'](null);
    }
    weekArray.push(week);
  };

  dayArray.forEach(function (day) {
    if (week.length > 0 && day.getDay() === firstDayOfWeek) {
      addWeek(week);
      week = [];
    }
    week.push(day);
    if (dayArray.indexOf(day) === dayArray.length - 1) {
      addWeek(week);
    }
  });

  return weekArray;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.dateUtils.isAfterDate"></a>[function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>isAfterDate (d1, d2)](#apidoc.element.material-ui.dateUtils.isAfterDate)
- description and source-code
```javascript
function isAfterDate(d1, d2) {
  var date1 = cloneAsDate(d1);
  var date2 = cloneAsDate(d2);

  return date1.getTime() > date2.getTime();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.dateUtils.isBeforeDate"></a>[function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>isBeforeDate (d1, d2)](#apidoc.element.material-ui.dateUtils.isBeforeDate)
- description and source-code
```javascript
function isBeforeDate(d1, d2) {
  var date1 = cloneAsDate(d1);
  var date2 = cloneAsDate(d2);

  return date1.getTime() < date2.getTime();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.dateUtils.isBetweenDates"></a>[function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>isBetweenDates (dateToCheck, startDate, endDate)](#apidoc.element.material-ui.dateUtils.isBetweenDates)
- description and source-code
```javascript
function isBetweenDates(dateToCheck, startDate, endDate) {
  return !isBeforeDate(dateToCheck, startDate) && !isAfterDate(dateToCheck, endDate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.dateUtils.isEqualDate"></a>[function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>isEqualDate (d1, d2)](#apidoc.element.material-ui.dateUtils.isEqualDate)
- description and source-code
```javascript
function isEqualDate(d1, d2) {
  return d1 && d2 && d1.getFullYear() === d2.getFullYear() && d1.getMonth() === d2.getMonth() && d1.getDate() === d2.getDate();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.dateUtils.localizedWeekday"></a>[function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>localizedWeekday (DateTimeFormat, locale, day, firstDayOfWeek)](#apidoc.element.material-ui.dateUtils.localizedWeekday)
- description and source-code
```javascript
function localizedWeekday(DateTimeFormat, locale, day, firstDayOfWeek) {
  var weekdayFormatter = new DateTimeFormat(locale, { weekday: 'narrow' });
  var firstDayDate = getFirstDayOfWeek();

  return weekdayFormatter.format(addDays(firstDayDate, day + firstDayOfWeek));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.dateUtils.monthDiff"></a>[function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>monthDiff (d1, d2)](#apidoc.element.material-ui.dateUtils.monthDiff)
- description and source-code
```javascript
function monthDiff(d1, d2) {
  var m = void 0;
  m = (d1.getFullYear() - d2.getFullYear()) * 12;
  m += d1.getMonth();
  m -= d2.getMonth();
  return m;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.dateUtils.yearDiff"></a>[function <span class="apidocSignatureSpan">material-ui.dateUtils.</span>yearDiff (d1, d2)](#apidoc.element.material-ui.dateUtils.yearDiff)
- description and source-code
```javascript
function yearDiff(d1, d2) {
  return ~~(monthDiff(d1, d2) / 12);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.material-ui.deprecatedExport"></a>[module material-ui.deprecatedExport](#apidoc.module.material-ui.deprecatedExport)

#### <a name="apidoc.element.material-ui.deprecatedExport.default"></a>[function <span class="apidocSignatureSpan">material-ui.deprecatedExport.</span>default (object, deprecatedPath, supportedPath)](#apidoc.element.material-ui.deprecatedExport.default)
- description and source-code
```javascript
function deprecatedExport(object, deprecatedPath, supportedPath) {
  process.env.NODE_ENV !== "production" ? (0, _warning2.default)(false, 'Importing ' + getName(object) + 'from \'' + deprecatedPath
 + '\' has been deprecated, use \'' + supportedPath + '\' instead.') : void 0;
  return object;
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.deprecatedPropType"></a>[module material-ui.deprecatedPropType](#apidoc.module.material-ui.deprecatedPropType)

#### <a name="apidoc.element.material-ui.deprecatedPropType.default"></a>[function <span class="apidocSignatureSpan">material-ui.deprecatedPropType.</span>default (validator, reason)](#apidoc.element.material-ui.deprecatedPropType.default)
- description and source-code
```javascript
function deprecated(validator, reason) {
  return function validate(props, propName, componentName, location, propFullName) {
    var componentNameSafe = componentName || '<<anonymous>>';
    var propFullNameSafe = propFullName || propName;

    if (props[propName] != null) {
      var messageKey = componentName + '.' + propName;

      process.env.NODE_ENV !== "production" ? (0, _warning2.default)(warned[messageKey], 'The ' + location + ' '' + propFullNameSafe
 + '' of ' + (''' + componentNameSafe + '' is deprecated. ' + reason)) : void 0;

      warned[messageKey] = true;
    }

    for (var _len = arguments.length, args = Array(_len > 5 ? _len - 5 : 0), _key = 5; _key < _len; _key++) {
      args[_key - 5] = arguments[_key];
    }

    return validator.apply(undefined, [props, propName, componentName, location, propFullName].concat(args));
  };
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.getMuiTheme"></a>[module material-ui.getMuiTheme](#apidoc.module.material-ui.getMuiTheme)

#### <a name="apidoc.element.material-ui.getMuiTheme.default"></a>[function <span class="apidocSignatureSpan">material-ui.getMuiTheme.</span>default (muiTheme)](#apidoc.element.material-ui.getMuiTheme.default)
- description and source-code
```javascript
function getMuiTheme(muiTheme) {
  for (var _len = arguments.length, more = Array(_len > 1 ? _len - 1 : 0), _key = 1; _key < _len; _key++) {
    more[_key - 1] = arguments[_key];
  }

  muiTheme = _lodash2.default.apply(undefined, [{
    zIndex: _zIndex2.default,
    isRtl: false,
    userAgent: undefined
  }, _lightBaseTheme2.default, muiTheme].concat(more));

  var _muiTheme = muiTheme,
      spacing = _muiTheme.spacing,
      fontFamily = _muiTheme.fontFamily,
      palette = _muiTheme.palette;

  var baseTheme = { spacing: spacing, fontFamily: fontFamily, palette: palette };

  muiTheme = (0, _lodash2.default)({
    appBar: {
      color: palette.primary1Color,
      textColor: palette.alternateTextColor,
      height: spacing.desktopKeylineIncrement,
      titleFontWeight: _typography2.default.fontWeightNormal,
      padding: spacing.desktopGutter
    },
    avatar: {
      color: palette.canvasColor,
      backgroundColor: (0, _colorManipulator.emphasize)(palette.canvasColor, 0.26)
    },
    badge: {
      color: palette.alternateTextColor,
      textColor: palette.textColor,
      primaryColor: palette.primary1Color,
      primaryTextColor: palette.alternateTextColor,
      secondaryColor: palette.accent1Color,
      secondaryTextColor: palette.alternateTextColor,
      fontWeight: _typography2.default.fontWeightMedium
    },
    bottomNavigation: {
      backgroundColor: palette.canvasColor,
      unselectedColor: (0, _colorManipulator.fade)(palette.textColor, 0.54),
      selectedColor: palette.primary1Color,
      height: 56,
      unselectedFontSize: 12,
      selectedFontSize: 14
    },
    button: {
      height: 36,
      minWidth: 88,
      iconButtonSize: spacing.iconSize * 2
    },
    card: {
      titleColor: (0, _colorManipulator.fade)(palette.textColor, 0.87),
      subtitleColor: (0, _colorManipulator.fade)(palette.textColor, 0.54),
      fontWeight: _typography2.default.fontWeightMedium
    },
    cardMedia: {
      color: _colors.darkWhite,
      overlayContentBackground: _colors.lightBlack,
      titleColor: _colors.darkWhite,
      subtitleColor: _colors.lightWhite
    },
    cardText: {
      textColor: palette.textColor
    },
    checkbox: {
      boxColor: palette.textColor,
      checkedColor: palette.primary1Color,
      requiredColor: palette.primary1Color,
      disabledColor: palette.disabledColor,
      labelColor: palette.textColor,
      labelDisabledColor: palette.disabledColor
    },
    chip: {
      backgroundColor: (0, _colorManipulator.emphasize)(palette.canvasColor, 0.12),
      deleteIconColor: (0, _colorManipulator.fade)(palette.textColor, 0.26),
      textColor: (0, _colorManipulator.fade)(palette.textColor, 0.87),
      fontSize: 14,
      fontWeight: _typography2.default.fontWeightNormal,
      shadow: '0 1px 6px ' + (0, _colorManipulator.fade)(palette.shadowColor, 0.12) + ',\n        0 1px 4px ' + (0, _colorManipulator
.fade)(palette.shadowColor, 0.12)
    },
    datePicker: {
      color: palette.primary1Color,
      textColor: palette.alternateTextColor,
      calendarTextColor: palette.textColor,
      selectColor: palette.primary2Color,
      selectTextColor: palette.alternateTextColor,
      calendarYearBackgroundColor: palette.canvasColor
    },
    dialog: {
      titleFontSize: 22,
      bodyFontSize: 16,
      bodyColor: (0, _colorManipulator.fade)(palette.textColor, 0.6)
    },
    dropDownMenu: {
      accentColor: palette.borderColor
    },
    enhancedButton: {
      tapHighlightColor: _colors.transparent
    },
    flatButton: {
      color: _colors.transparent,
      buttonFilterColor: '#999999',
      disabledTextColor: (0, _colorManipulator.fade)(palette.textColor, 0.3),
      textColor: palette.textColor,
      primaryTextColor: palette.primary1Color,
      secondaryTextColor: palette.accent1Color,
      fontSize: _typography2.default.fontStyleButtonFontSize,
      fontWeight: _typography2.default.fontWeightMedium
    },
    floatingActionButton: {
      buttonSize: 56,
      miniSize: 40,
      color: palette.primary1Color,
      iconColor: palette.al ...
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.iOSHelpers"></a>[module material-ui.iOSHelpers](#apidoc.module.material-ui.iOSHelpers)

#### <a name="apidoc.element.material-ui.iOSHelpers.getOffsetTop"></a>[function <span class="apidocSignatureSpan">material-ui.iOSHelpers.</span>getOffsetTop (elem)](#apidoc.element.material-ui.iOSHelpers.getOffsetTop)
- description and source-code
```javascript
function getOffsetTop(elem) {
  var yPos = elem.offsetTop;
  var tempEl = elem.offsetParent;

  while (tempEl != null) {
    yPos += tempEl.offsetTop;
    tempEl = tempEl.offsetParent;
  }

  return yPos;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.iOSHelpers.isIOS"></a>[function <span class="apidocSignatureSpan">material-ui.iOSHelpers.</span>isIOS ()](#apidoc.element.material-ui.iOSHelpers.isIOS)
- description and source-code
```javascript
function isIOS() {
  return (/iPad|iPhone|iPod/.test(window.navigator.userAgent) && !window.MSStream
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.material-ui.makeSelectable"></a>[module material-ui.makeSelectable](#apidoc.module.material-ui.makeSelectable)

#### <a name="apidoc.element.material-ui.makeSelectable.makeSelectable"></a>[function <span class="apidocSignatureSpan">material-ui.</span>makeSelectable (MyComponent)](#apidoc.element.material-ui.makeSelectable.makeSelectable)
- description and source-code
```javascript
function makeSelectable(MyComponent) {
  var _class, _temp2;

  return _temp2 = _class = function (_Component) {
    (0, _inherits3.default)(_class, _Component);

    function _class() {
      var _ref;

      var _temp, _this, _ret;

      (0, _classCallCheck3.default)(this, _class);

      for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
        args[_key] = arguments[_key];
      }

      return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = _class.__proto__ || (0, _getPrototypeOf2
.default)(_class)).call.apply(_ref, [this].concat(args))), _this), _this.hasSelectedDescendant = function (previousValue, child) {
        if (_react2.default.isValidElement(child) && child.props.nestedItems && child.props.nestedItems.length > 0) {
          return child.props.nestedItems.reduce(_this.hasSelectedDescendant, previousValue);
        }
        return previousValue || _this.isChildSelected(child, _this.props);
      }, _this.handleItemTouchTap = function (event, item) {
        var itemValue = item.props.value;

        if (itemValue !== _this.props.value) {
          if (_this.props.onChange) {
            _this.props.onChange(event, itemValue);
          }
        }
      }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
    }

    (0, _createClass3.default)(_class, [{
      key: 'extendChild',
      value: function extendChild(child, styles, selectedItemStyle) {
        var _this2 = this;

        if (child && child.type && child.type.muiName === 'ListItem') {
          var selected = this.isChildSelected(child, this.props);
          var selectedChildrenStyles = void 0;
          if (selected) {
            selectedChildrenStyles = (0, _simpleAssign2.default)({}, styles, selectedItemStyle);
          }

          var mergedChildrenStyles = (0, _simpleAssign2.default)({}, child.props.style, selectedChildrenStyles);

          this.keyIndex += 1;

          return _react2.default.cloneElement(child, {
            onTouchTap: function onTouchTap(event) {
              _this2.handleItemTouchTap(event, child);
              if (child.props.onTouchTap) {
                child.props.onTouchTap(event);
              }
            },
            key: this.keyIndex,
            style: mergedChildrenStyles,
            nestedItems: child.props.nestedItems.map(function (child) {
              return _this2.extendChild(child, styles, selectedItemStyle);
            }),
            initiallyOpen: this.isInitiallyOpen(child)
          });
        } else {
          return child;
        }
      }
    }, {
      key: 'isInitiallyOpen',
      value: function isInitiallyOpen(child) {
        if (child.props.initiallyOpen) {
          return child.props.initiallyOpen;
        }
        return this.hasSelectedDescendant(false, child);
      }
    }, {
      key: 'isChildSelected',
      value: function isChildSelected(child, props) {
        return props.value === child.props.value;
      }
    }, {
      key: 'render',
      value: function render() {
        var _this3 = this;

        var _props = this.props,
            children = _props.children,
            selectedItemStyle = _props.selectedItemStyle,
            other = (0, _objectWithoutProperties3.default)(_props, ['children', 'selectedItemStyle']);


        this.keyIndex = 0;
        var styles = {};

        if (!selectedItemStyle) {
          var textColor = this.context.muiTheme.baseTheme.palette.textColor;
          styles.backgroundColor = (0, _colorManipulator.fade)(textColor, 0.2);
        }

        return _react2.default.createElement(
          MyComponent,
          (0, _extends3.default)({}, other, this.state),
          _react.Children.map(children, function (child) {
            return _this3.extendChild(child, styles, selectedItemStyle);
          })
        );
      }
    }]);
    return _class;
  }(_react.Component), _class.propTypes = {
    children: _react.PropTypes.node,
    onChange: _react.PropTypes.func,
    selectedItemStyle: _react.PropTypes.object,
    value: _react.Prop ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.makeSelectable.default"></a>[function <span class="apidocSignatureSpan">material-ui.makeSelectable.</span>default (MyComponent)](#apidoc.element.material-ui.makeSelectable.default)
- description and source-code
```javascript
function makeSelectable(MyComponent) {
  var _class, _temp2;

  return _temp2 = _class = function (_Component) {
    (0, _inherits3.default)(_class, _Component);

    function _class() {
      var _ref;

      var _temp, _this, _ret;

      (0, _classCallCheck3.default)(this, _class);

      for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
        args[_key] = arguments[_key];
      }

      return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = _class.__proto__ || (0, _getPrototypeOf2
.default)(_class)).call.apply(_ref, [this].concat(args))), _this), _this.hasSelectedDescendant = function (previousValue, child) {
        if (_react2.default.isValidElement(child) && child.props.nestedItems && child.props.nestedItems.length > 0) {
          return child.props.nestedItems.reduce(_this.hasSelectedDescendant, previousValue);
        }
        return previousValue || _this.isChildSelected(child, _this.props);
      }, _this.handleItemTouchTap = function (event, item) {
        var itemValue = item.props.value;

        if (itemValue !== _this.props.value) {
          if (_this.props.onChange) {
            _this.props.onChange(event, itemValue);
          }
        }
      }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
    }

    (0, _createClass3.default)(_class, [{
      key: 'extendChild',
      value: function extendChild(child, styles, selectedItemStyle) {
        var _this2 = this;

        if (child && child.type && child.type.muiName === 'ListItem') {
          var selected = this.isChildSelected(child, this.props);
          var selectedChildrenStyles = void 0;
          if (selected) {
            selectedChildrenStyles = (0, _simpleAssign2.default)({}, styles, selectedItemStyle);
          }

          var mergedChildrenStyles = (0, _simpleAssign2.default)({}, child.props.style, selectedChildrenStyles);

          this.keyIndex += 1;

          return _react2.default.cloneElement(child, {
            onTouchTap: function onTouchTap(event) {
              _this2.handleItemTouchTap(event, child);
              if (child.props.onTouchTap) {
                child.props.onTouchTap(event);
              }
            },
            key: this.keyIndex,
            style: mergedChildrenStyles,
            nestedItems: child.props.nestedItems.map(function (child) {
              return _this2.extendChild(child, styles, selectedItemStyle);
            }),
            initiallyOpen: this.isInitiallyOpen(child)
          });
        } else {
          return child;
        }
      }
    }, {
      key: 'isInitiallyOpen',
      value: function isInitiallyOpen(child) {
        if (child.props.initiallyOpen) {
          return child.props.initiallyOpen;
        }
        return this.hasSelectedDescendant(false, child);
      }
    }, {
      key: 'isChildSelected',
      value: function isChildSelected(child, props) {
        return props.value === child.props.value;
      }
    }, {
      key: 'render',
      value: function render() {
        var _this3 = this;

        var _props = this.props,
            children = _props.children,
            selectedItemStyle = _props.selectedItemStyle,
            other = (0, _objectWithoutProperties3.default)(_props, ['children', 'selectedItemStyle']);


        this.keyIndex = 0;
        var styles = {};

        if (!selectedItemStyle) {
          var textColor = this.context.muiTheme.baseTheme.palette.textColor;
          styles.backgroundColor = (0, _colorManipulator.fade)(textColor, 0.2);
        }

        return _react2.default.createElement(
          MyComponent,
          (0, _extends3.default)({}, other, this.state),
          _react.Children.map(children, function (child) {
            return _this3.extendChild(child, styles, selectedItemStyle);
          })
        );
      }
    }]);
    return _class;
  }(_react.Component), _class.propTypes = {
    children: _react.PropTypes.node,
    onChange: _react.PropTypes.func,
    selectedItemStyle: _react.PropTypes.object,
    value: _react.Prop ...
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.menuUtils"></a>[module material-ui.menuUtils](#apidoc.module.material-ui.menuUtils)

#### <a name="apidoc.element.material-ui.menuUtils.HotKeyHolder"></a>[function <span class="apidocSignatureSpan">material-ui.menuUtils.</span>HotKeyHolder ()](#apidoc.element.material-ui.menuUtils.HotKeyHolder)
- description and source-code
```javascript
function HotKeyHolder() {
  var _this = this;

  (0, _classCallCheck3.default)(this, HotKeyHolder);

  this.clear = function () {
    _this.timerId = null;
    _this.lastKeys = null;
  };
}
```
- example usage
```shell
...
  }
  _this.state = {
    focusIndex: newFocusIndex,
    isKeyboardFocused: props.initiallyKeyboardFocused,
    keyWidth: props.desktop ? 64 : 56
  };

  _this.hotKeyHolder = new _menuUtils.HotKeyHolder();
  return _this;
}

(0, _createClass3.default)(Menu, [{
  key: 'componentDidMount',
  value: function componentDidMount() {
    if (this.props.autoWidth) {
...
```



# <a name="apidoc.module.material-ui.muiThemeable"></a>[module material-ui.muiThemeable](#apidoc.module.material-ui.muiThemeable)

#### <a name="apidoc.element.material-ui.muiThemeable.default"></a>[function <span class="apidocSignatureSpan">material-ui.muiThemeable.</span>default ()](#apidoc.element.material-ui.muiThemeable.default)
- description and source-code
```javascript
function muiThemeable() {
  return function (Component) {
    var MuiComponent = function MuiComponent(props, context) {
      var _context$muiTheme = context.muiTheme,
          muiTheme = _context$muiTheme === undefined ? getDefaultTheme() : _context$muiTheme;


      return _react2.default.createElement(Component, (0, _extends3.default)({ muiTheme: muiTheme }, props));
    };

    MuiComponent.contextTypes = {
      muiTheme: _react.PropTypes.object.isRequired
    };

    return MuiComponent;
  };
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.navigation_arrow_drop_right"></a>[module material-ui.navigation_arrow_drop_right](#apidoc.module.material-ui.navigation_arrow_drop_right)

#### <a name="apidoc.element.material-ui.navigation_arrow_drop_right.default"></a>[function <span class="apidocSignatureSpan">material-ui.navigation_arrow_drop_right.</span>default ()](#apidoc.element.material-ui.navigation_arrow_drop_right.default)
- description and source-code
```javascript
function _class() {
  _classCallCheck(this, _class);

  return _possibleConstructorReturn(this, _Component.apply(this, arguments));
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.rtl"></a>[module material-ui.rtl](#apidoc.module.material-ui.rtl)

#### <a name="apidoc.element.material-ui.rtl.default"></a>[function <span class="apidocSignatureSpan">material-ui.rtl.</span>default (muiTheme)](#apidoc.element.material-ui.rtl.default)
- description and source-code
```javascript
function rtl(muiTheme) {
  if (muiTheme.isRtl) {
    return function (style) {
      if (style.directionInvariant === true) {
        return style;
      }

      var flippedAttributes = {
        // Keys and their replacements.
        right: 'left',
        left: 'right',
        marginRight: 'marginLeft',
        marginLeft: 'marginRight',
        paddingRight: 'paddingLeft',
        paddingLeft: 'paddingRight',
        borderRight: 'borderLeft',
        borderLeft: 'borderRight'
      };

      var newStyle = {};

      (0, _keys2.default)(style).forEach(function (attribute) {
        var value = style[attribute];
        var key = attribute;

        if (flippedAttributes.hasOwnProperty(attribute)) {
          key = flippedAttributes[attribute];
        }

        switch (attribute) {
          case 'float':
          case 'textAlign':
            if (value === 'right') {
              value = 'left';
            } else if (value === 'left') {
              value = 'right';
            }
            break;

          case 'direction':
            if (value === 'ltr') {
              value = 'rtl';
            } else if (value === 'rtl') {
              value = 'ltr';
            }
            break;

          case 'transform':
            if (!value) break;
            var matches = void 0;
            if (matches = value.match(reTranslate)) {
              value = value.replace(matches[0], matches[1] + -parseFloat(matches[4]));
            }
            if (matches = value.match(reSkew)) {
              value = value.replace(matches[0], matches[1] + -parseFloat(matches[4]) + matches[5] + matches[6] ? ', ' + (-parseFloat
(matches[7]) + matches[8]) : '');
            }
            break;

          case 'transformOrigin':
            if (!value) break;
            if (value.indexOf('right') > -1) {
              value = value.replace('right', 'left');
            } else if (value.indexOf('left') > -1) {
              value = value.replace('left', 'right');
            }
            break;
        }

        newStyle[key] = value;
      });

      return newStyle;
    };
  }
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# <a name="apidoc.module.material-ui.timeUtils"></a>[module material-ui.timeUtils](#apidoc.module.material-ui.timeUtils)

#### <a name="apidoc.element.material-ui.timeUtils.addHours"></a>[function <span class="apidocSignatureSpan">material-ui.timeUtils.</span>addHours (d, hours)](#apidoc.element.material-ui.timeUtils.addHours)
- description and source-code
```javascript
function addHours(d, hours) {
  var newDate = clone(d);
  newDate.setHours(d.getHours() + hours);
  return newDate;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.timeUtils.addMinutes"></a>[function <span class="apidocSignatureSpan">material-ui.timeUtils.</span>addMinutes (d, minutes)](#apidoc.element.material-ui.timeUtils.addMinutes)
- description and source-code
```javascript
function addMinutes(d, minutes) {
  var newDate = clone(d);
  newDate.setMinutes(d.getMinutes() + minutes);
  return newDate;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.timeUtils.addSeconds"></a>[function <span class="apidocSignatureSpan">material-ui.timeUtils.</span>addSeconds (d, seconds)](#apidoc.element.material-ui.timeUtils.addSeconds)
- description and source-code
```javascript
function addSeconds(d, seconds) {
  var newDate = clone(d);
  newDate.setSeconds(d.getMinutes() + seconds);
  return newDate;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.timeUtils.formatTime"></a>[function <span class="apidocSignatureSpan">material-ui.timeUtils.</span>formatTime (date)](#apidoc.element.material-ui.timeUtils.formatTime)
- description and source-code
```javascript
function formatTime(date) {
  var format = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : 'ampm';
  var pedantic = arguments.length > 2 && arguments[2] !== undefined ? arguments[2] : false;

  if (!date) return '';
  var hours = date.getHours();
  var mins = date.getMinutes().toString();

  if (format === 'ampm') {
    var isAM = hours < 12;
    hours = hours % 12;
    var additional = isAM ? ' am' : ' pm';
    hours = (hours || 12).toString();

    if (mins.length < 2) mins = '0' + mins;

    if (pedantic) {
      // Treat midday/midnight specially http://www.nist.gov/pml/div688/times.cfm
      if (hours === '12' && mins === '00') {
        return additional === ' pm' ? '12 noon' : '12 midnight';
      }
    }

    return hours + (mins === '00' ? '' : ':' + mins) + additional;
  }

  hours = hours.toString();

  if (hours.length < 2) hours = '0' + hours;
  if (mins.length < 2) mins = '0' + mins;

  return hours + ':' + mins;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.timeUtils.getTouchEventOffsetValues"></a>[function <span class="apidocSignatureSpan">material-ui.timeUtils.</span>getTouchEventOffsetValues (event)](#apidoc.element.material-ui.timeUtils.getTouchEventOffsetValues)
- description and source-code
```javascript
function getTouchEventOffsetValues(event) {
  var el = event.target;
  var boundingRect = el.getBoundingClientRect();

  return {
    offsetX: event.clientX - boundingRect.left,
    offsetY: event.clientY - boundingRect.top
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.timeUtils.isInner"></a>[function <span class="apidocSignatureSpan">material-ui.timeUtils.</span>isInner (props)](#apidoc.element.material-ui.timeUtils.isInner)
- description and source-code
```javascript
function isInner(props) {
  if (props.type !== 'hour') {
    return false;
  }
  return props.value < 1 || props.value > 12;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.timeUtils.rad2deg"></a>[function <span class="apidocSignatureSpan">material-ui.timeUtils.</span>rad2deg (rad)](#apidoc.element.material-ui.timeUtils.rad2deg)
- description and source-code
```javascript
function rad2deg(rad) {
  return rad * 57.29577951308232;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.material-ui.withWidth"></a>[module material-ui.withWidth](#apidoc.module.material-ui.withWidth)

#### <a name="apidoc.element.material-ui.withWidth.default"></a>[function <span class="apidocSignatureSpan">material-ui.withWidth.</span>default ()](#apidoc.element.material-ui.withWidth.default)
- description and source-code
```javascript
function withWidth() {
  var options = arguments.length > 0 && arguments[0] !== undefined ? arguments[0] : {};
  var _options$largeWidth = options.largeWidth,
      largeWidth = _options$largeWidth === undefined ? 992 : _options$largeWidth,
      _options$mediumWidth = options.mediumWidth,
      mediumWidth = _options$mediumWidth === undefined ? 768 : _options$mediumWidth,
      _options$resizeInterv = options.resizeInterval,
      resizeInterval = _options$resizeInterv === undefined ? 166 : _options$resizeInterv;


  return function (MyComponent) {
    return function (_Component) {
      (0, _inherits3.default)(WithWidth, _Component);

      function WithWidth() {
        var _ref;

        var _temp, _this, _ret;

        (0, _classCallCheck3.default)(this, WithWidth);

        for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
          args[_key] = arguments[_key];
        }

        return _ret = (_temp = (_this = (0, _possibleConstructorReturn3.default)(this, (_ref = WithWidth.__proto__ || (0, _getPrototypeOf2
.default)(WithWidth)).call.apply(_ref, [this].concat(args))), _this), _this.state = {
          width: null
        }, _this.handleResize = function () {
          clearTimeout(_this.deferTimer);
          _this.deferTimer = setTimeout(function () {
            _this.updateWidth();
          }, resizeInterval);
        }, _temp), (0, _possibleConstructorReturn3.default)(_this, _ret);
      }

      (0, _createClass3.default)(WithWidth, [{
        key: 'componentDidMount',
        value: function componentDidMount() {
          this.updateWidth();
        }
      }, {
        key: 'componentWillUnmount',
        value: function componentWillUnmount() {
          clearTimeout(this.deferTimer);
        }
      }, {
        key: 'updateWidth',
        value: function updateWidth() {
          var innerWidth = window.innerWidth;
          var width = void 0;

          if (innerWidth >= largeWidth) {
            width = LARGE;
          } else if (innerWidth >= mediumWidth) {
            width = MEDIUM;
          } else {
            // innerWidth < 768
            width = SMALL;
          }

          if (width !== this.state.width) {
            this.setState({
              width: width
            });
          }
        }
      }, {
        key: 'render',
        value: function render() {
          var width = this.state.width;

<span class="apidocCodeCommentSpan">          /**
           * When rendering the component on the server,
           * we have no idea about the screen width.
           * In order to prevent blinks and help the reconciliation
           * we are not rendering the component.
           *
           * A better alternative would be to send client hints.
           * But the browser support of this API is low:
           * http://caniuse.com/#search=client%20hint
           */
</span>          if (width === null) {
            return null;
          }

          return _react2.default.createElement(
            _reactEventListener2.default,
            { target: 'window', onResize: this.handleResize },
            _react2.default.createElement(MyComponent, (0, _extends3.default)({
              width: width
            }, this.props))
          );
        }
      }]);
      return WithWidth;
    }(_react.Component);
  };
}
```
- example usage
```shell
...
  }
}

return stylePrefixed;
    };
  } else {
    var _ret = function () {
var prefixer = new _inlineStylePrefixer2.default({
  userAgent: userAgent
});

return {
  v: function v(style) {
    return prefixer.prefix(style);
  }
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
