# api documentation for  [material-ui (v0.17.1)](http://material-ui.com/)  [![npm package](https://img.shields.io/npm/v/npmdoc-material-ui.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-material-ui) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-material-ui.svg)](https://travis-ci.org/npmdoc/node-npmdoc-material-ui)
#### React Components that Implement Google's Material Design.

[![NPM](https://nodei.co/npm/material-ui.png?downloads=true)](https://www.npmjs.com/package/material-ui)

[![apidoc](https://npmdoc.github.io/node-npmdoc-material-ui/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-material-ui_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-material-ui/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-material-ui/build/screen-capture.npmPackageListing.svg)



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
1.  object <span class="apidocSignatureSpan">material-ui.</span>AutoComplete.contextTypes
1.  object <span class="apidocSignatureSpan">material-ui.</span>AutoComplete.defaultProps
1.  object <span class="apidocSignatureSpan">material-ui.</span>AutoComplete.propTypes

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
n/a
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
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.defaultProps.onNewRequest"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.defaultProps.</span>onNewRequest ()](#apidoc.element.material-ui.AutoComplete.defaultProps.onNewRequest)
- description and source-code
```javascript
function onNewRequest() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.defaultProps.onUpdateInput"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.defaultProps.</span>onUpdateInput ()](#apidoc.element.material-ui.AutoComplete.defaultProps.onUpdateInput)
- description and source-code
```javascript
function onUpdateInput() {}
```
- example usage
```shell
n/a
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
n/a
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
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.onClose"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>onClose ()](#apidoc.element.material-ui.AutoComplete.propTypes.onClose)
- description and source-code
```javascript
onClose = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.onFocus"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>onFocus ()](#apidoc.element.material-ui.AutoComplete.propTypes.onFocus)
- description and source-code
```javascript
onFocus = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.onKeyDown"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>onKeyDown ()](#apidoc.element.material-ui.AutoComplete.propTypes.onKeyDown)
- description and source-code
```javascript
onKeyDown = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.onNewRequest"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>onNewRequest ()](#apidoc.element.material-ui.AutoComplete.propTypes.onNewRequest)
- description and source-code
```javascript
onNewRequest = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.onUpdateInput"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>onUpdateInput ()](#apidoc.element.material-ui.AutoComplete.propTypes.onUpdateInput)
- description and source-code
```javascript
onUpdateInput = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.material-ui.AutoComplete.propTypes.open"></a>[function <span class="apidocSignatureSpan">material-ui.AutoComplete.propTypes.</span>open ()](#apidoc.element.material-ui.AutoComplete.propTypes.open)
- description and source-code
```javascript
open = function () { [native code] }
```
- example usage
```shell
n/a
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



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
