Atom React.js Snippets (StandardJS)
====================================================================================================================================================================

An [Atom](https://atom.io/) snippet library for React.js, based on the package by [AJ Webb](https://travis-ci.org/webbushka/atom-react-snippets). This library has been modified to use StandardJS formatting and ES6 syntax.

Install
-------

Go to `Packages > Settings View > Open` once in settings go to the Install tab and search for **react-snippets**

Restart Atom

Development
-----------

```sh
$ cd ~/.atom/packages
$ git clone https://github.com/hwknsj/atom-react-snippets.git
$ cd atom-react-snippets
$ apm install
$ apm link
```

Snippets
--------

The **⇥** means the `TAB` key

| Trigger      | Content |
| -------:     | ------- |
| `_i→`       | import empty |
| `_ir→`      | import react |
| `_irc→`     | import react and component |
| `_irp→`     | import react and prop-types |
| `_ircp→`    | import react, component and prop-types |
| `_ird→`     | import react-dom |
| `_ex→`      | export |
| `_exd→`     | export default |
| `_cdm→`     | `componentDidMount method` |
| `_cwm→`     | `componentWillMount method` |
| `_cwr→`     | `componentWillReceiveProps method` |
| `_scu→`     | `shouldComponentUpdate method` |
| `_cwup→`    | `componentWillUpdate method` |
| `_cdup→`    | `componentDidUpdate method` |
| `_cwun→`    | `componentWillUnmount method` |
| `_cdc→`     | `componentDidCatch method` |
| `_cx→`      | `cx` |
| `_fup→`     | `forceUpdate` |
| `_cct→`     | component contextTypes |
| `_cpt→`     | component propTypes |
| `_cdp→`     | component defaultProps |
| `_scct→`    | static component contextTypes |
| `_scpt→`    | static component propTypes |
| `_scdp→`    | static component defaultProps |
| `_cer→`     | class component skeleton |
| `_rsc→`     | stateless component skeleton |
| `_rscp→`    | stateless component skeleton with PropTypes |
| `_rscr→`    | stateless component skeleton with explicit `return` |
| `_rscc→`    | stateless component skeleton with `handleClick` |
| `_rsf→`     | stateless function |
| `_cdn→`     | component display name |
| `_ren→`     | `render() method` |
| `_sst→`     | `setState()` |
| `_props→`   | `this.props.` |
| `_state→`   | `this.state.` |
| `_rrc→`     | `React.render()` |
| `_frag→`    | `<React.Fragment></React.Fragment>` |
| `_cns→`     | `constructor method` |
| `_clss→`    | class extends |
| `_dnghtml→` | `dangerouslySetInnerHTML` |

In this version the PropTypes snippets prefix has changed to `_pt` instead of `rp`. All snippets have two versions to allow for required and not required types.

| Trigger  | Content |
| -------: | ------- |
| `_pta→`   | `PropTypes.array,` |
| `_ptar→`  | `PropTypes.array.isRequired,` |
| `_ptb→`   | `PropTypes.bool,` |
| `_ptbr→`  | `PropTypes.bool.isRequired,` |
| `_ptf→`   | `PropTypes.func,` |
| `_ptfr→`  | `PropTypes.func.isRequired,` |
| `_ptn→`   | `PropTypes.number,` |
| `_ptnr→`  | `PropTypes.number.isRequired,` |
| `_pto→`   | `PropTypes.object.,` |
| `_ptor→`  | `PropTypes.object.isRequired,` |
| `_pts→`   | `PropTypes.string,` |
| `_ptsr→`  | `PropTypes.string.isRequired,` |
| `_ptnd→`  | `PropTypes.node,` |
| `_ptndr→` | `PropTypes.node.isRequired,` |
| `_ptel→`  | `PropTypes.element,` |
| `_ptelr→` | `PropTypes.element.isRequired,` |
| `_pti→`   | `PropTypes.instanceOf(ClassName),` |
| `_ptir→`  | `PropTypes.instanceOf(ClassName).isRequired,` |
| `_pte→`   | `PropTypes.oneOf(['News', 'Photos']),` |
| `_pter→`  | `PropTypes.oneOf(['News', 'Photos']).isRequired,` |
| `_ptet→`  | `PropTypes.oneOfType([PropTypes.string, PropTypes.number]),` |
| `_ptetr→` | `PropTypes.oneOfType([PropTypes.string, PropTypes.number]).isRequired,` |
| `_ptao→`  | `PropTypes.arrayOf(PropTypes.number),` |
| `_ptaor→` | `PropTypes.arrayOf(PropTypes.number).isRequired,` |
| `_ptoo→`  | `PropTypes.objectOf(PropTypes.number),` |
| `_ptoor→` | `PropTypes.objectOf(PropTypes.number).isRequired,` |
| `_ptsh→`  | `PropTypes.shape({color: PropTypes.string, fontSize: PropTypes.number}),` |
| `_ptshr→` | `PropTypes.shape({color: PropTypes.string, fontSize: PropTypes.number}).isRequired,` |

Contributing
------------

1.	Fork it!
2.	Create your feature branch: `git checkout -b my-new-feature`
3.	Commit your changes: `git commit -m 'Add some feature'`
4.	Push to the branch: `git push origin my-new-feature`
5.	Submit a pull request

License
-------

[MIT License](http://zenorocha.mit-license.org/)

Credit
------

The React.js snippets were originally created by [orktes](https://atom.io/users/orktes) in [Atom React](https://atom.io/packages/react) in ES5 syntax.
