# Change Log 

## [1.15.6](https://github.com/alibaba-fusion/next/compare/1.15.5...1.15.6) (2019-06-13)


### Bug Fixes

* **Balloon:** position shouldn't be chanaged when no space, close [#774](https://github.com/alibaba-fusion/next/issues/774) ([a6d55f8](https://github.com/alibaba-fusion/next/commit/a6d55f8))
* **Dialog:** title radius when bg color #close-783 ([8692936](https://github.com/alibaba-fusion/next/commit/8692936)), closes [#close-783](https://github.com/alibaba-fusion/next/issues/close-783)
* **Field:** setError valiate - #close 747 ([25adbd1](https://github.com/alibaba-fusion/next/commit/25adbd1))
* **NumberPicker:** support null to clear value. relate [#780](https://github.com/alibaba-fusion/next/issues/780) ([15ae286](https://github.com/alibaba-fusion/next/commit/15ae286))
* **Search:** hasIcon with shape=simple. Close [#734](https://github.com/alibaba-fusion/next/issues/734) ([033bfb8](https://github.com/alibaba-fusion/next/commit/033bfb8))
* **Slider:** lazyLoad pre and next pics, close [#706](https://github.com/alibaba-fusion/next/issues/706) ([f841201](https://github.com/alibaba-fusion/next/commit/f841201))




## [1.15.5](https://github.com/alibaba-fusion/next/compare/1.15.4...1.15.5) (2019-06-06)


### Bug Fixes

* **CascaderSelect:** clear search input  change ([bff0134](https://github.com/alibaba-fusion/next/commit/bff0134))
* **Date-picker:** prop 'onOk' typescript declaration File wrong ([3c21dcd](https://github.com/alibaba-fusion/next/commit/3c21dcd))
* **Nav:** disorder when set margin(t, b) of hoz Nav, close [#744](https://github.com/alibaba-fusion/next/issues/744) ([f6f9625](https://github.com/alibaba-fusion/next/commit/f6f9625))
* **RangePicker:** to start month  after selected ([2ea6cf6](https://github.com/alibaba-fusion/next/commit/2ea6cf6))
* **Select:** warning in select base, close [#771](https://github.com/alibaba-fusion/next/issues/771) ([dae7047](https://github.com/alibaba-fusion/next/commit/dae7047))
* **Table:** resizeable won't work if isTree on, close [#384](https://github.com/alibaba-fusion/next/issues/384) ([bf1eb55](https://github.com/alibaba-fusion/next/commit/bf1eb55))


### Features

* **Table:** add API filterMenuProps ([61ab2b0](https://github.com/alibaba-fusion/next/commit/61ab2b0))




## [1.15.4](https://github.com/alibaba-fusion/next/compare/1.15.3...1.15.4) (2019-05-31)


### Bug Fixes

* **Table:** React.Fragment is supported in 16.2.4, use [] instead ([aec5368](https://github.com/alibaba-fusion/next/commit/aec5368))


### Features

* **Select:** add API tagInline to make it won't wrap ([d21f8a1](https://github.com/alibaba-fusion/next/commit/d21f8a1))




## [1.15.3](https://github.com/alibaba-fusion/next/compare/1.15.2...1.15.3) (2019-05-30)


### Bug Fixes

* **Select:** tag should show all content but it ellipsis, close [#751](https://github.com/alibaba-fusion/next/issues/751) ([46122aa](https://github.com/alibaba-fusion/next/commit/46122aa))




## [1.15.2](https://github.com/alibaba-fusion/next/compare/1.15.1...1.15.2) (2019-05-29)


### Bug Fixes

* **Nav:** active line should have disappear animation ([8a1ad70](https://github.com/alibaba-fusion/next/commit/8a1ad70))
* **NumberPicker:** UI for button height not eq input ([c8b78bb](https://github.com/alibaba-fusion/next/commit/c8b78bb))
* **Tag:** checkable selected Tag border should be able to config ([c06f513](https://github.com/alibaba-fusion/next/commit/c06f513))
* **Tag:** resolve overflow issues, close [#727](https://github.com/alibaba-fusion/next/issues/727) ([538e1d4](https://github.com/alibaba-fusion/next/commit/538e1d4))
* **Tag:** text overflow for custom height ([5b52372](https://github.com/alibaba-fusion/next/commit/5b52372))


### Features

* **Upload:** add upload border-radius variable ([fb3f8e4](https://github.com/alibaba-fusion/next/commit/fb3f8e4))




## [1.15.1](https://github.com/alibaba-fusion/next/compare/1.15.0...1.15.1) (2019-05-27)


### Bug Fixes

* **ConfigProvider:** locale should deep merge zh-cn.js, close [#719](https://github.com/alibaba-fusion/next/issues/719) ([c10baa2](https://github.com/alibaba-fusion/next/commit/c10baa2))
* **Tag:** check icon should use variable, close [#720](https://github.com/alibaba-fusion/next/issues/720) ([709d5d4](https://github.com/alibaba-fusion/next/commit/709d5d4))
* **Tag:** clean up scss ([7c643a3](https://github.com/alibaba-fusion/next/commit/7c643a3))


### Deprecated

* **Table:** getRowProps => rowProps, getCellProps => cellProps ([185d70a](https://github.com/alibaba-fusion/next/commit/185d70a)), closes [#724](https://github.com/alibaba-fusion/next/issues/724)


### Features

* add followTrigger for component with overlay ([f98fb15](https://github.com/alibaba-fusion/next/commit/f98fb15))
* **Balloon:** make font-size font-weight configurable ([e6f7137](https://github.com/alibaba-fusion/next/commit/e6f7137))
* **Button:** component support div or span ([66341a0](https://github.com/alibaba-fusion/next/commit/66341a0))
* **Calendar:** support 0.x locale.format ([c2d7db2](https://github.com/alibaba-fusion/next/commit/c2d7db2))
* **Calendar:** support 0.x YearCellRender ([1ee70af](https://github.com/alibaba-fusion/next/commit/1ee70af))
* **Core:** split shadow distance from sdn to sdny ([85101eb](https://github.com/alibaba-fusion/next/commit/85101eb))
* **DatePicker:** support 0.x ranges ([59d0483](https://github.com/alibaba-fusion/next/commit/59d0483))
* **Nav:** add theme configuration about hover ([27ccded](https://github.com/alibaba-fusion/next/commit/27ccded))
* **NumberPicker:** support 0.x onDisabled ([947d3d2](https://github.com/alibaba-fusion/next/commit/947d3d2))
* **Pagintion:** add config variables ([7a27465](https://github.com/alibaba-fusion/next/commit/7a27465))
* **Slider:** support 0.x onBeforeChange ([34603cc](https://github.com/alibaba-fusion/next/commit/34603cc))
* **Table:** add columnProps/titleAddons/titleProps of rowSelection ([965118f](https://github.com/alibaba-fusion/next/commit/965118f))
* **Tag:** change tag var sections ([b71c883](https://github.com/alibaba-fusion/next/commit/b71c883))
* **Tag:** closable normal has custom colors ([da08e11](https://github.com/alibaba-fusion/next/commit/da08e11))
* **Tag:** primary and closable primary use same style ([28d4738](https://github.com/alibaba-fusion/next/commit/28d4738))
* **Tag:** primary theme customization ([b82e7b1](https://github.com/alibaba-fusion/next/commit/b82e7b1))
* **Transfer:** make footer shadow configurable ([9df069d](https://github.com/alibaba-fusion/next/commit/9df069d))




# [1.15.0](https://github.com/alibaba-fusion/next/compare/1.14.6...1.15.0) (2019-05-24)


### Bug Fixes

* fusion cool render issues ([fbdffaa](https://github.com/alibaba-fusion/next/commit/fbdffaa))
* **Calendar:** select month auto change date view ([354f545](https://github.com/alibaba-fusion/next/commit/354f545))
* **Field:** resetDefault when parseValue false ([e2c2b00](https://github.com/alibaba-fusion/next/commit/e2c2b00))
* **Message:** can`t close after click ([53fe94d](https://github.com/alibaba-fusion/next/commit/53fe94d))
* **Select:** init flatten ds ([57667a4](https://github.com/alibaba-fusion/next/commit/57667a4))
* **Select:** value no show fillProps with empty dataSource. Close [#715](https://github.com/alibaba-fusion/next/issues/715) ([70a15ab](https://github.com/alibaba-fusion/next/commit/70a15ab))


### Features

* **Select:** add api to customize show tag content ([4c29109](https://github.com/alibaba-fusion/next/commit/4c29109))
* **Select:** add maxTagPlaceholder ([bfc9b20](https://github.com/alibaba-fusion/next/commit/bfc9b20))




## [1.14.6](https://github.com/alibaba-fusion/next/compare/1.14.5...1.14.6) (2019-05-23)


### Bug Fixes

* **CascaderSelect:** Fixed [#676](https://github.com/alibaba-fusion/next/issues/676) ([b8a0ba2](https://github.com/alibaba-fusion/next/commit/b8a0ba2))
* **Field:** init values with parseName=false ([0c92cfb](https://github.com/alibaba-fusion/next/commit/0c92cfb))




## [1.14.5](https://github.com/alibaba-fusion/next/compare/1.14.4...1.14.5) (2019-05-22)


### Bug Fixes

* **Field:** parseName defaults ([#683](https://github.com/alibaba-fusion/next/issues/683)) ([7fe0130](https://github.com/alibaba-fusion/next/commit/7fe0130))
* **Field:** revert typescript of Field to any ([c35d935](https://github.com/alibaba-fusion/next/commit/c35d935))
* **Input:** maxLength in safari on Mac. Close [#671](https://github.com/alibaba-fusion/next/issues/671) ([f771d67](https://github.com/alibaba-fusion/next/commit/f771d67))
* **Tab:** should not listen to extra keyboard events ([50e1699](https://github.com/alibaba-fusion/next/commit/50e1699))



## [1.14.4](https://github.com/alibaba-fusion/next/compare/1.14.3...1.14.4) (2019-05-16)


### Bug Fixes

* fix DatePicker,Switch,Upload to a11y ([99ef836](https://github.com/alibaba-fusion/next/commit/99ef836))
* **Checkbox:** number 0 should be rendered ([93318d8](https://github.com/alibaba-fusion/next/commit/93318d8))
* **Field:** no react key props for errors ([93127d6](https://github.com/alibaba-fusion/next/commit/93127d6))
* **Menu:** Resolve expanding and selecting in uncontrolled mode ([#667](https://github.com/alibaba-fusion/next/issues/667)) ([0ba7e4a](https://github.com/alibaba-fusion/next/commit/0ba7e4a))
* **Menu:** Resolve items that created by `React.forwardRef` ([807d8de](https://github.com/alibaba-fusion/next/commit/807d8de))
* **Select:** hight first item with remote datasource. Close [#654](https://github.com/alibaba-fusion/next/issues/654) ([d784ee0](https://github.com/alibaba-fusion/next/commit/d784ee0))


### Features

* add file types/ to customize index.d.ts ([c537d81](https://github.com/alibaba-fusion/next/commit/c537d81))
* **Menu:** add API embeddable ([6d21bb1](https://github.com/alibaba-fusion/next/commit/6d21bb1))
* **Nav:** add API embeddable ([1379df3](https://github.com/alibaba-fusion/next/commit/1379df3))
* **Table:** add API sortIcons to customize sort icons ([7abcf7c](https://github.com/alibaba-fusion/next/commit/7abcf7c))




## [1.14.3](https://github.com/alibaba-fusion/next/compare/1.14.2...1.14.3) (2019-05-09)


### Bug Fixes

* **Core:** clip-path in sr-only destroys scrolling performance ([49ff99f](https://github.com/alibaba-fusion/next/commit/49ff99f))
* **Dialog:** fixed height dialog ([c334b2b](https://github.com/alibaba-fusion/next/commit/c334b2b))
* **Menu** empty focus key when blur using undefined ([#634](https://github.com/alibaba-fusion/next/issues/634)) ([8c6a3af](https://github.com/alibaba-fusion/next/commit/8c6a3af))
* **Slider:** dots should be cursor: pointer; ([1754a74](https://github.com/alibaba-fusion/next/commit/1754a74))
* **Table:** using clientHeight instead of maxBodyHeight ([33abd4a](https://github.com/alibaba-fusion/next/commit/33abd4a))
* **Upload:** a11y problem ([97ab17b](https://github.com/alibaba-fusion/next/commit/97ab17b))



## [1.14.2](https://github.com/alibaba-fusion/next/compare/1.14.1...1.14.2) (2019-04-29)


### Bug Fixes

* **Balloon:** autoFocus should be false when triggerType is focus ([af7cce1](https://github.com/alibaba-fusion/next/commit/af7cce1))
* **DatePicker:** delete input, can`t select date ([cf9f9e4](https://github.com/alibaba-fusion/next/commit/cf9f9e4))
* **Loading:** backwards compatible fullscreen ([3ff5972](https://github.com/alibaba-fusion/next/commit/3ff5972))
* **Loading:** fix offset for fullscreen ([481c409](https://github.com/alibaba-fusion/next/commit/481c409))
* **Overlay:** touch events to dismiss overlay ([b35a59c](https://github.com/alibaba-fusion/next/commit/b35a59c))
* **Select:** issue [#550](https://github.com/alibaba-fusion/next/issues/550) add api followTrigger ([9312ea8](https://github.com/alibaba-fusion/next/commit/9312ea8))
* **Step:** step keydown event bubble bug ([4a843f0](https://github.com/alibaba-fusion/next/commit/4a843f0))
* **Table:** add deprecated API to make 0.x 1.x behave the same ([43f17aa](https://github.com/alibaba-fusion/next/commit/43f17aa))
* **Tag:** fix state not matching props ([#614](https://github.com/alibaba-fusion/next/issues/614)) ([52d09dd](https://github.com/alibaba-fusion/next/commit/52d09dd))




## [1.14.1](https://github.com/alibaba-fusion/next/compare/1.14.0...1.14.1) (2019-04-24)


### Bug Fixes

* **Tab:** capsure tab shakes ([a19901f](https://github.com/alibaba-fusion/next/commit/a19901f))
* **Tab:** wrong initial position due to animation ([fbd079e](https://github.com/alibaba-fusion/next/commit/fbd079e))
* **Tag:** pass checked state to onChange ([57cfa20](https://github.com/alibaba-fusion/next/commit/57cfa20))
* **Tree:** error when checkKey not in dataSource ([b925d76](https://github.com/alibaba-fusion/next/commit/b925d76))




# [1.14.0](https://github.com/alibaba-fusion/next/compare/1.13.13...1.14.0) (2019-04-11)


### Bug Fixes

* support function component ([a1b1f41](https://github.com/alibaba-fusion/next/commit/a1b1f41))
* **Radio:** add configurations ([f5dbaa9](https://github.com/alibaba-fusion/next/commit/f5dbaa9))
* **Tab:** add default maxHeight for tab popup ([5358921](https://github.com/alibaba-fusion/next/commit/5358921))
* **Tab:** change variable order ([8451ef8](https://github.com/alibaba-fusion/next/commit/8451ef8))
* **Tab:** issues of closable ([05ec227](https://github.com/alibaba-fusion/next/commit/05ec227))
* **Tab:** remove invalid character in variable name ([8dbd6df](https://github.com/alibaba-fusion/next/commit/8dbd6df))
* **Tab:** slide related issues ([986178a](https://github.com/alibaba-fusion/next/commit/986178a))
* **Table:** merge cell with GroupHeader GroupFooter, close [#547](https://github.com/alibaba-fusion/next/issues/547) ([4a420cb](https://github.com/alibaba-fusion/next/commit/4a420cb))
* **TreeSelect:** supoort a11y, add aria attrs ([d34bdc2](https://github.com/alibaba-fusion/next/commit/d34bdc2))


### Deprecated

* **Balloon:** triggerType=focus is deprecated at Balloon ([32710a3](https://github.com/alibaba-fusion/next/commit/32710a3))
* **Dropdown:** triggerType="focus" is deprecated ([a07bb54](https://github.com/alibaba-fusion/next/commit/a07bb54))


### Features

* add accessibility.scss ([127fbe7](https://github.com/alibaba-fusion/next/commit/127fbe7))
* **Breadcrumb:** add component props ([3e9c3ae](https://github.com/alibaba-fusion/next/commit/3e9c3ae))
* **Collapse:** add title hover theme variables ([19f3501](https://github.com/alibaba-fusion/next/commit/19f3501))
* **DatePicker:** add keyboard control ([025f752](https://github.com/alibaba-fusion/next/commit/025f752))
* **Dialog:** quick  dialog padding ([14a4ded](https://github.com/alibaba-fusion/next/commit/14a4ded))
* **Input:** add api hasBorder for TextArea. Close [#266](https://github.com/alibaba-fusion/next/issues/266) ([d3c8e23](https://github.com/alibaba-fusion/next/commit/d3c8e23))
* **Message:** configable message icon type ([7a80c13](https://github.com/alibaba-fusion/next/commit/7a80c13))
* **Overlay:** custom keycode trigger ([7ebfb99](https://github.com/alibaba-fusion/next/commit/7ebfb99))
* **Select:** support a11y. Close [#327](https://github.com/alibaba-fusion/next/issues/327) ([22a42e7](https://github.com/alibaba-fusion/next/commit/22a42e7))
* **Slider:** split variable for dots height & width ([2f5c247](https://github.com/alibaba-fusion/next/commit/2f5c247))
* **Step:** support keyborad direction and use semantic label ([7225e8b](https://github.com/alibaba-fusion/next/commit/7225e8b))
* **Tab:** adding more configuration of wrapped tab ([e72129e](https://github.com/alibaba-fusion/next/commit/e72129e))
* **Tab:** support more config ([70511e9](https://github.com/alibaba-fusion/next/commit/70511e9))
* **Table:** make header padding configurable ([3b7a23b](https://github.com/alibaba-fusion/next/commit/3b7a23b))
* **Tag:** add content min width theme variable ([8bfef9a](https://github.com/alibaba-fusion/next/commit/8bfef9a))
* **Upload:** allow down load when disabled ([975cbab](https://github.com/alibaba-fusion/next/commit/975cbab))
* **Upload:** card and drag configurable item ([9b485d7](https://github.com/alibaba-fusion/next/commit/9b485d7))




## [1.13.13](https://github.com/alibaba-fusion/next/compare/1.13.12...1.13.13) (2019-04-11)


### Bug Fixes

* **Pagination:** pagination dropdown position ([93482f7](https://github.com/alibaba-fusion/next/commit/93482f7))
* **Table:** mismatch between minWidth and value, close [#554](https://github.com/alibaba-fusion/next/issues/554) ([c589863](https://github.com/alibaba-fusion/next/commit/c589863))




## [1.13.12](https://github.com/alibaba-fusion/next/compare/1.13.11...1.13.12) (2019-04-04)


### Bug Fixes

* **Balloon:** babel exports issue ([74a09a4](https://github.com/alibaba-fusion/next/commit/74a09a4))




## [1.13.11](https://github.com/alibaba-fusion/next/compare/1.13.10...1.13.11) (2019-04-04)


### Bug Fixes

* **Balloon:** popup won\'t goaway when hover out of disabled Button ([c569486](https://github.com/alibaba-fusion/next/commit/c569486)), closes [close#308](https://github.com/close/issues/308)
* **Balloon:** strengthen robustness for align, close[#517](https://github.com/alibaba-fusion/next/issues/517) ([a820b1a](https://github.com/alibaba-fusion/next/commit/a820b1a))
* **Rating:** remove form tag ([fa87aa9](https://github.com/alibaba-fusion/next/commit/fa87aa9))
* **Search:** search config bug ([6919e41](https://github.com/alibaba-fusion/next/commit/6919e41))
* **Select:** AutoComplete can input space with popupContent. Close [#500](https://github.com/alibaba-fusion/next/issues/500) ([07dc088](https://github.com/alibaba-fusion/next/commit/07dc088))
* **Tab:** adding api document ([3ba4f26](https://github.com/alibaba-fusion/next/commit/3ba4f26))




<a name="1.13.10"></a>
## [1.13.10](https://github.com/alibaba-fusion/next/compare/1.13.9...1.13.10) (2019-03-28)


### Bug Fixes

* **Input:** fix lineheight. Close [#214](https://github.com/alibaba-fusion/next/issues/214) ([706adce](https://github.com/alibaba-fusion/next/commit/706adce))
* **Menu:** filter duplicate keys ([e8e6e52](https://github.com/alibaba-fusion/next/commit/e8e6e52))
* **Nav:** remove focus style which equals to hover ([f31320f](https://github.com/alibaba-fusion/next/commit/f31320f))
* **NumberPicker:** remove padding in inline mode ([a5c59a7](https://github.com/alibaba-fusion/next/commit/a5c59a7))
* **Range:** revert unnecessary style change ([7ed0bb9](https://github.com/alibaba-fusion/next/commit/7ed0bb9))
* **Select:** use mouse to select text. Close [#469](https://github.com/alibaba-fusion/next/issues/469) ([d474b7a](https://github.com/alibaba-fusion/next/commit/d474b7a))
* **Select:** value={0} display bug. Close [#449](https://github.com/alibaba-fusion/next/issues/449) ([6e7e642](https://github.com/alibaba-fusion/next/commit/6e7e642))
* **SplitButton:** normal icon color override ([b18c332](https://github.com/alibaba-fusion/next/commit/b18c332))
* **Switch:** disable handle not centered when config border ([f28bf52](https://github.com/alibaba-fusion/next/commit/f28bf52))
* **Tab:** right border missing in capsule shape ([8ff454e](https://github.com/alibaba-fusion/next/commit/8ff454e))
* **Table:** style confusion caused by vertical scrollbar, close [#473](https://github.com/alibaba-fusion/next/issues/473) ([9149879](https://github.com/alibaba-fusion/next/commit/9149879))
* **Transfer:** fix wrong Type of `title` props in `TransferPanel` ([d088da9](https://github.com/alibaba-fusion/next/commit/d088da9))
* **Upload:** Resolve context missing ([8a26eec](https://github.com/alibaba-fusion/next/commit/8a26eec))


### Features

* **Balloon:** make Tooltip's shadow configurable ([9a6a931](https://github.com/alibaba-fusion/next/commit/9a6a931))
* **Menu:** add API to set selectIcon right ([b5dd678](https://github.com/alibaba-fusion/next/commit/b5dd678))
* **Slider:** make slider dots configurable ([027c2a4](https://github.com/alibaba-fusion/next/commit/027c2a4))




<a name="1.13.9"></a>

## [1.13.9](https://github.com/alibaba-fusion/next/compare/1.13.8...1.13.9) (2019-03-19)

### Bug Fixes

-   **CascaderSelect:** support value not in data ([93e4227](https://github.com/alibaba-fusion/next/commit/93e4227))
-   **Overlay:** fix position typo ([71bf7d2](https://github.com/alibaba-fusion/next/commit/71bf7d2))
-   **Select:** hasSelectAll bug under controled ([fd5faf4](https://github.com/alibaba-fusion/next/commit/fd5faf4))
-   **Table:** warning when stickyHeader + lock with enough space ([46a38f6](https://github.com/alibaba-fusion/next/commit/46a38f6))
-   **Util:** Prevent warning on production ([0fcde5a](https://github.com/alibaba-fusion/next/commit/0fcde5a))

<a name="1.13.8"></a>

## [1.13.8](https://github.com/alibaba-fusion/next/compare/1.13.7...1.13.8) (2019-03-14)

### Bug Fixes

-   **ConfigProvider:** config on components should take higher priority ([87917c8](https://github.com/alibaba-fusion/next/commit/87917c8))

<a name="1.13.7"></a>

## [1.13.7](https://github.com/alibaba-fusion/next/compare/1.13.6...1.13.7) (2019-03-13)

### Bug Fixes

-   **Select:** css override fail when using theme ([5f80ead](https://github.com/alibaba-fusion/next/commit/5f80ead))

<a name="1.13.6"></a>

## [1.13.6](https://github.com/alibaba-fusion/next/compare/1.13.5...1.13.6) (2019-03-13)

### Bug Fixes

-   **DatePicker:** disabledDate will auto disable month ([94276d2](https://github.com/alibaba-fusion/next/commit/94276d2))
-   **Step:** labelPlacement value change dbl times ([3c7ae73](https://github.com/alibaba-fusion/next/commit/3c7ae73))
-   **Tag:** close button not showing in select when text too long ([fd341f8](https://github.com/alibaba-fusion/next/commit/fd341f8))
-   **Upload:** className not pass in ([cb33e75](https://github.com/alibaba-fusion/next/commit/cb33e75))
-   **Upload:** drag upload no trigger onDrop ([5f58f29](https://github.com/alibaba-fusion/next/commit/5f58f29))
-   **Upload:** fix setValue fail in onSuccess ([384c379](https://github.com/alibaba-fusion/next/commit/384c379))

### Features

-   **ConfigProvider:** add ErrorBoundary ([ada2b5b](https://github.com/alibaba-fusion/next/commit/ada2b5b))
-   **Range:** RTL feature of Range Component ([2127ee6](https://github.com/alibaba-fusion/next/commit/2127ee6))
-   **Select:** can unselect all ([77077a2](https://github.com/alibaba-fusion/next/commit/77077a2))
-   **Tab:** RTL feature of Tab ([142af04](https://github.com/alibaba-fusion/next/commit/142af04))

<a name="1.13.5"></a>

## [1.13.5](https://github.com/alibaba-fusion/next/compare/1.13.3...1.13.5) (2019-03-07)

### Bug Fixes

-   **Collapse:** fix nested collapse icon ([7a6842a](https://github.com/alibaba-fusion/next/commit/7a6842a))
-   **DatePicker:** date range picker select time error ([59eaa9c](https://github.com/alibaba-fusion/next/commit/59eaa9c))
-   **Step:** step-item param of labelPlacement change update bug ([f0939af](https://github.com/alibaba-fusion/next/commit/f0939af))
-   **Tab:** can't scroll when active item is inside view ([a8f4d18](https://github.com/alibaba-fusion/next/commit/a8f4d18))
-   **Table:** extra lock columns when enough space && dataSource=[], close[#364](https://github.com/alibaba-fusion/next/issues/364) ([b9c2328](https://github.com/alibaba-fusion/next/commit/b9c2328))

### Features

-   **NumberPicker:** consider [。] as [.](<[8369b4a](https://github.com/alibaba-fusion/next/commit/8369b4a)>)
-   **Upload:** add rtl support ([5505d6d](https://github.com/alibaba-fusion/next/commit/5505d6d))

<a name="1.13.4"></a>

## [1.13.4](https://github.com/alibaba-fusion/next/compare/1.13.3...1.13.4) (2019-02-28)

### Features

-   **NumberPicker:** consider [。] as [.](<[8369b4a](https://github.com/alibaba-fusion/next/commit/8369b4a)>)

<a name="1.13.3"></a>

## [1.13.3](https://github.com/alibaba-fusion/next/compare/1.13.2...1.13.3) (2019-02-28)

### Bug Fixes

-   use offset when positioning overlay, do not adjust range tooltip ([ac22b05](https://github.com/alibaba-fusion/next/commit/ac22b05))
-   **Range:** set height for bare-range like input ([b7a6242](https://github.com/alibaba-fusion/next/commit/b7a6242))
-   **Select:** add aria-hidden to dropdown arrow. Close [#322](https://github.com/alibaba-fusion/next/issues/322) ([b546f05](https://github.com/alibaba-fusion/next/commit/b546f05))
-   **Select:** reset role to menu. Close [#326](https://github.com/alibaba-fusion/next/issues/326) ([1ba6d5e](https://github.com/alibaba-fusion/next/commit/1ba6d5e))
-   **Select:** throw error when children contain null ([b703efb](https://github.com/alibaba-fusion/next/commit/b703efb))
-   **Tab:** a11y support closeable tab ([86c4e10](https://github.com/alibaba-fusion/next/commit/86c4e10))
-   **Tab:** css syntax flaw ([0d7518e](https://github.com/alibaba-fusion/next/commit/0d7518e))
-   **Table:** index with expanded table when expandedIndexSimulate is true ([7ce3f7e](https://github.com/alibaba-fusion/next/commit/7ce3f7e))
-   **Tree:** can`t drag external element ([a247a09](https://github.com/alibaba-fusion/next/commit/a247a09))
-   **Tree:** throw error when children contain null or string ([7a2c9cc](https://github.com/alibaba-fusion/next/commit/7a2c9cc))
-   **Search:** mod search role Close [#330](https://github.com/alibaba-fusion/next/issues/330) ([e5aac4d](https://github.com/alibaba-fusion/next/commit/e5aac4d))
-   **Transfer:** add a11y support for transfer ([4856363](https://github.com/alibaba-fusion/next/commit/4856363))

<a name="1.13.2"></a>

## [1.13.2](https://github.com/alibaba-fusion/next/compare/1.13.1...1.13.2) (2019-02-22)

### Bug Fixes

-   **Table:** correct cell(recored, index) when expandedIndexSimulate ([2ba1ba8](https://github.com/alibaba-fusion/next/commit/2ba1ba8))

<a name="1.13.1"></a>

## [1.13.1](https://github.com/alibaba-fusion/next/compare/1.13.0...1.13.1) (2019-02-21)

### Bug Fixes

-   **NumberPicker:** support rtl ([74980bd](https://github.com/alibaba-fusion/next/commit/74980bd))

### Features

-   rtl support for Collapse and Loading ([a80c4c5](https://github.com/alibaba-fusion/next/commit/a80c4c5))
-   **Affix:** receive the change of offset props ([f190bc7](https://github.com/alibaba-fusion/next/commit/f190bc7))
-   **Badge:** support rtl ([0deedb7](https://github.com/alibaba-fusion/next/commit/0deedb7))
-   **Breadcrumb:** support rtl ([ba2a287](https://github.com/alibaba-fusion/next/commit/ba2a287))
-   **Card:** move rtl.scss ([ab95d34](https://github.com/alibaba-fusion/next/commit/ab95d34))
-   **Card:** support rtl ([6dd0673](https://github.com/alibaba-fusion/next/commit/6dd0673))
-   **Cascader:** support rtl ([1ed6e25](https://github.com/alibaba-fusion/next/commit/1ed6e25))
-   **Checkbox:** RTL feature ([313f1ac](https://github.com/alibaba-fusion/next/commit/313f1ac))
-   **Dropdown:** support rtl ([a9beb00](https://github.com/alibaba-fusion/next/commit/a9beb00))
-   **Field:** add api autoValidate=false to close onChange validate ([b9b0129](https://github.com/alibaba-fusion/next/commit/b9b0129))
-   **Field:** api spliceArray to splice Array like name.{index} ([484841b](https://github.com/alibaba-fusion/next/commit/484841b))
-   **Form:** support autoValidate=false to close auto validate ([4bec5db](https://github.com/alibaba-fusion/next/commit/4bec5db))
-   **Form:** support rtl ([9fd345e](https://github.com/alibaba-fusion/next/commit/9fd345e))
-   **Grid:** support rtl ([f4ba7b4](https://github.com/alibaba-fusion/next/commit/f4ba7b4))
-   **Paragraph:** add rtl prop ([d6b3ea5](https://github.com/alibaba-fusion/next/commit/d6b3ea5))
-   **Rating:** support custom display of rating grade ([df55fcf](https://github.com/alibaba-fusion/next/commit/df55fcf))
-   **Rating:** support rtl ([d793959](https://github.com/alibaba-fusion/next/commit/d793959))
-   **Switch:** RTL feature along with some eslint fixes ([1642c0c](https://github.com/alibaba-fusion/next/commit/1642c0c))
-   **Table:** API expandedIndexSimulate added ([a227aa2](https://github.com/alibaba-fusion/next/commit/a227aa2))
-   **Table:** support rtl ([c36d2c0](https://github.com/alibaba-fusion/next/commit/c36d2c0))
-   **Transfer:** support rtl prop ([1575d2f](https://github.com/alibaba-fusion/next/commit/1575d2f))
-   **Tree:** support rtl ([37fa931](https://github.com/alibaba-fusion/next/commit/37fa931))

<a name="1.13.0"></a>

# [1.13.0](https://github.com/alibaba-fusion/next/compare/1.12.8...1.13.0) (2019-02-21)

<a name="1.12.8"></a>

## [1.12.8](https://github.com/alibaba-fusion/next/compare/1.12.7...1.12.8) (2019-02-21)

<a name="1.12.7"></a>

## [1.12.7](https://github.com/alibaba-fusion/next/compare/1.12.6...1.12.7) (2019-02-21)

### Bug Fixes

-   **Radio:** child can contain null ([c703b60](https://github.com/alibaba-fusion/next/commit/c703b60))

<a name="1.12.6"></a>

## [1.12.6](https://github.com/alibaba-fusion/next/compare/1.12.5...1.12.6) (2019-02-21)

### Bug Fixes

-   **Cascader:** set listStyle height style error ([61ea4f7](https://github.com/alibaba-fusion/next/commit/61ea4f7))
-   **Input:** add name to input dom ([51d151f](https://github.com/alibaba-fusion/next/commit/51d151f))

<a name="1.12.5"></a>

## [1.12.5](https://github.com/alibaba-fusion/next/compare/1.12.4...1.12.5) (2019-02-20)

### Bug Fixes

-   style for rtl in Menu & Slider ([573694a](https://github.com/alibaba-fusion/next/commit/573694a))
-   **Message:** can`t config content font-size ([2c18b4d](https://github.com/alibaba-fusion/next/commit/2c18b4d))
-   **Radio:** a11y ([f26cb24](https://github.com/alibaba-fusion/next/commit/f26cb24))
-   **Table:** can't set className via getRowProps in tree mode, close [#343](https://github.com/alibaba-fusion/next/issues/343) ([44c20cb](https://github.com/alibaba-fusion/next/commit/44c20cb))

### Features

-   **Tag:** wrap in ConfigProvider ([95233cc](https://github.com/alibaba-fusion/next/commit/95233cc))

<a name="1.12.4"></a>

## [1.12.4](https://github.com/alibaba-fusion/next/compare/1.12.3...1.12.4) (2019-02-14)

### Bug Fixes

-   **Checkbox:** group didn't honor children's indeternimated state ([f90a747](https://github.com/alibaba-fusion/next/commit/f90a747))
-   **Input:** textarea placeholder in ie11 ([069c73b](https://github.com/alibaba-fusion/next/commit/069c73b))
-   **Select:** could add tag while popup not visible ([662a959](https://github.com/alibaba-fusion/next/commit/662a959))
-   **Table:** can't scroll horizontally when body scrollTop !== 0 ([5935b52](https://github.com/alibaba-fusion/next/commit/5935b52))
-   **Table:** head selection emptied wrongly ([adb3b59](https://github.com/alibaba-fusion/next/commit/adb3b59))

### Features

-   **Icon:** suport size of inherit ([48e7f1d](https://github.com/alibaba-fusion/next/commit/48e7f1d))
-   **Progress:** remove tabindex ([602b267](https://github.com/alibaba-fusion/next/commit/602b267))
-   **Step:** uniform parameter of step ([e1d2ab5](https://github.com/alibaba-fusion/next/commit/e1d2ab5))

<a name="1.12.3"></a>

## [1.12.3](https://github.com/alibaba-fusion/next/compare/1.12.2...1.12.3) (2019-01-28)

### Bug Fixes

-   **Pagination:** locale text error ([406c198](https://github.com/alibaba-fusion/next/commit/406c198))
-   **Tab:** extra is covered by other elements ([c3d913f](https://github.com/alibaba-fusion/next/commit/c3d913f))
-   **Tab:** inproperly focus when using with field ([0d3bd2c](https://github.com/alibaba-fusion/next/commit/0d3bd2c))

<a name="1.12.2"></a>

## [1.12.2](https://github.com/alibaba-fusion/next/compare/1.12.1...1.12.2) (2019-01-28)

### Bug Fixes

-   **Util:** DO NOT process any non-string type value ([2a3280f](https://github.com/alibaba-fusion/next/commit/2a3280f))

<a name="1.12.1"></a>

## [1.12.1](https://github.com/alibaba-fusion/next/compare/1.12.0...1.12.1) (2019-01-27)

### Bug Fixes

-   **Upload:** import method from wrong path ([7c1a6b6](https://github.com/alibaba-fusion/next/commit/7c1a6b6))

<a name="1.12.0"></a>

# [1.12.0](https://github.com/alibaba-fusion/next/compare/1.11.11...1.12.0) (2019-01-25)

### Bug Fixes

-   **Card:** not compute card footer in height ([45da06d](https://github.com/alibaba-fusion/next/commit/45da06d))
-   **Cascader:** array will reverse ([24e2a0d](https://github.com/alibaba-fusion/next/commit/24e2a0d))
-   **Dialog:** add aria-label for close icon ([4a1d8ea](https://github.com/alibaba-fusion/next/commit/4a1d8ea))
-   **Form:** add role=grid to form ([b2f3cad](https://github.com/alibaba-fusion/next/commit/b2f3cad))
-   **Menu:** keycode.space trigger click ([531492e](https://github.com/alibaba-fusion/next/commit/531492e))
-   **NumberPicker:** no onBlur while click btn ([6e70f1e](https://github.com/alibaba-fusion/next/commit/6e70f1e))
-   **Pagination:** pageSizeSelector is overlay ([9b7464a](https://github.com/alibaba-fusion/next/commit/9b7464a))
-   **Search:** disable not work ([1bedb19](https://github.com/alibaba-fusion/next/commit/1bedb19))
-   **Select:** Option value can be array ([fe350f2](https://github.com/alibaba-fusion/next/commit/fe350f2))
-   **Select:** display text should not change while under controlled ([b962954](https://github.com/alibaba-fusion/next/commit/b962954))
-   **Select:** text should updated with dataSource changed ([16588fe](https://github.com/alibaba-fusion/next/commit/16588fe))
-   **Switch:** add focus state, close [#177](https://github.com/alibaba-fusion/next/issues/177) ([479206d](https://github.com/alibaba-fusion/next/commit/479206d))
-   **Tab:** also update doc ([d7d0ab5](https://github.com/alibaba-fusion/next/commit/d7d0ab5))
-   **Tab:** pure/text/capsule extra align center ([3f3282b](https://github.com/alibaba-fusion/next/commit/3f3282b))
-   **Tab:** TabItem no 'disabled' prop in API document ([28ed342](https://github.com/alibaba-fusion/next/commit/28ed342))
-   **Tree:** expandKeys will reset on async load data ([b1818d1](https://github.com/alibaba-fusion/next/commit/b1818d1))
-   **TreeSelect:** support defaultValue/value is null string ([ab04292](https://github.com/alibaba-fusion/next/commit/ab04292))
-   **Upload:** expose error to OnError in beforeUpload, Close [#128](https://github.com/alibaba-fusion/next/issues/128) ([1981db5](https://github.com/alibaba-fusion/next/commit/1981db5))

### Features

-   **Badge:** support aria ([d890f47](https://github.com/alibaba-fusion/next/commit/d890f47))
-   **Breadcrumb:** support a11y ([bd93737](https://github.com/alibaba-fusion/next/commit/bd93737))
-   **CascaderSelect:** support a11y ([4a40b2a](https://github.com/alibaba-fusion/next/commit/4a40b2a))
-   **CascaderSelect:** support itemRender ([9afffaa](https://github.com/alibaba-fusion/next/commit/9afffaa))
-   **Collapse:** accessibility support ([48bee98](https://github.com/alibaba-fusion/next/commit/48bee98))
-   **ConfigProvider:** support set rtl when setting locale ([72f3b0f](https://github.com/alibaba-fusion/next/commit/72f3b0f))
-   **DatePicker:** add dateCellRender monthCellRender prop ([ca549f9](https://github.com/alibaba-fusion/next/commit/ca549f9))
-   **DatePicker:** add inputProps prop ([3d92b8a](https://github.com/alibaba-fusion/next/commit/3d92b8a))
-   **Dialog:** throw Error when occur in onOk ([35e1a9a](https://github.com/alibaba-fusion/next/commit/35e1a9a))
-   **Dropdown:** support aria ([df2a05d](https://github.com/alibaba-fusion/next/commit/df2a05d))
-   **Nav:** support aria ([bf4de51](https://github.com/alibaba-fusion/next/commit/bf4de51))
-   **NumberPicker:** a11y support ([8eacabf](https://github.com/alibaba-fusion/next/commit/8eacabf))
-   **Pagination:** add a11y support ([b922a06](https://github.com/alibaba-fusion/next/commit/b922a06))
-   **Progress:** progress accessibility support ([524e97f](https://github.com/alibaba-fusion/next/commit/524e97f))
-   **Radio:** support name props for Radio & customer tagName for Group ([3e4e971](https://github.com/alibaba-fusion/next/commit/3e4e971))
-   **Range:** a11y ([4d2b69c](https://github.com/alibaba-fusion/next/commit/4d2b69c))
-   **Rating:** accessibility support ([f68a23c](https://github.com/alibaba-fusion/next/commit/f68a23c))
-   **Slider:** support aria ([c9bf1d2](https://github.com/alibaba-fusion/next/commit/c9bf1d2))
-   **SplitButton:** add leftButtonProps ([4d854e0](https://github.com/alibaba-fusion/next/commit/4d854e0))
-   **Step:** support aria ([3b55daa](https://github.com/alibaba-fusion/next/commit/3b55daa))
-   **Switch:** switch a11y ([2c2645c](https://github.com/alibaba-fusion/next/commit/2c2645c))
-   **Tab:** tab a11y ([7a47360](https://github.com/alibaba-fusion/next/commit/7a47360))
-   **Table:** add alignHeader & remove locale ([7f99ed0](https://github.com/alibaba-fusion/next/commit/7f99ed0))
-   **TimePicker:** support a11y ([590dae6](https://github.com/alibaba-fusion/next/commit/590dae6))
-   **Tree:** support a11y ([e7ec789](https://github.com/alibaba-fusion/next/commit/e7ec789))
-   **Upload:** add error text for text list ([32149af](https://github.com/alibaba-fusion/next/commit/32149af))
-   **Upload:** add progress props ([f2d460c](https://github.com/alibaba-fusion/next/commit/f2d460c))
-   **Upload:** disallow remove when disabled, Close [#132](https://github.com/alibaba-fusion/next/issues/132) ([e535cde](https://github.com/alibaba-fusion/next/commit/e535cde))
-   **Upload:** image list error text display ([69bbc64](https://github.com/alibaba-fusion/next/commit/69bbc64))
-   **Upload:** mod upload config ability ([432ef76](https://github.com/alibaba-fusion/next/commit/432ef76))
-   **Upload:** support custom request method ([1a9a7b6](https://github.com/alibaba-fusion/next/commit/1a9a7b6))
-   **Upload:** trigger error when exceed limit ([cf71c2a](https://github.com/alibaba-fusion/next/commit/cf71c2a))

<a name="1.11.11"></a>

## [1.11.11](https://github.com/alibaba-fusion/next/compare/1.11.10...1.11.11) (2019-01-22)

### Bug Fixes

-   **Form:** no need form-element-large-size in form ([08420c6](https://github.com/alibaba-fusion/next/commit/08420c6))
-   **NumberPicker:** value set to min while next value < min by click + ([6863b9f](https://github.com/alibaba-fusion/next/commit/6863b9f))
-   **Select:** double trigger onVisibleChange while click arrow ([20f2e1c](https://github.com/alibaba-fusion/next/commit/20f2e1c))

<a name="1.11.10"></a>

## [1.11.10](https://github.com/alibaba-fusion/next/compare/1.11.9...1.11.10) (2019-01-17)

### Bug Fixes

-   **Loading:** block style ([7e9ea48](https://github.com/alibaba-fusion/next/commit/7e9ea48))
-   **Loading:** tests for inline class ([da1c10a](https://github.com/alibaba-fusion/next/commit/da1c10a))
-   **Tab:** add float right ([11f6d99](https://github.com/alibaba-fusion/next/commit/11f6d99))
-   **Tab:** rtl support ([2151ee8](https://github.com/alibaba-fusion/next/commit/2151ee8))

<a name="1.11.9"></a>

## [1.11.9](https://github.com/alibaba-fusion/next/compare/1.11.8...1.11.9) (2019-01-16)

### Bug Fixes

-   **Loading:** fix fullscreen in demo ([6378cc0](https://github.com/alibaba-fusion/next/commit/6378cc0))
-   **Nav:** overflow when icon-only without icon ([6b28cee](https://github.com/alibaba-fusion/next/commit/6b28cee))
-   **Slider:** can swipe vertical & width 100% invertical ([3998ec2](https://github.com/alibaba-fusion/next/commit/3998ec2))
-   **Tab:** extra align middle by default ([3f38491](https://github.com/alibaba-fusion/next/commit/3f38491))

<a name="1.11.8"></a>

## [1.11.8](https://github.com/alibaba-fusion/next/compare/1.11.7...1.11.8) (2019-01-09)

### Bug Fixes

-   **CascaderSelect:** value type not equal dataSource value ([3cc1785](https://github.com/alibaba-fusion/next/commit/3cc1785))
-   **ConfigProvider:** check locales before set ([a0da7bf](https://github.com/alibaba-fusion/next/commit/a0da7bf))
-   **Form:** remove warning while message write in jsx ([87d6085](https://github.com/alibaba-fusion/next/commit/87d6085))
-   **Form:** switch aligin while size=large ([db989ee](https://github.com/alibaba-fusion/next/commit/db989ee))
-   **Nav:** can't config nav group label font size/height ([5f439a5](https://github.com/alibaba-fusion/next/commit/5f439a5))
-   **Nav:** icon-only overflow bug fix ([1bc40fe](https://github.com/alibaba-fusion/next/commit/1bc40fe))
-   **Radio:** button shape hover border covers checked border ([33be122](https://github.com/alibaba-fusion/next/commit/33be122))
-   **Select:** fix Select with useVirtual when empty dataSource ([#164](https://github.com/alibaba-fusion/next/issues/164)) ([54da63f](https://github.com/alibaba-fusion/next/commit/54da63f))
-   **Tab:** max-call-exceeded ([d8de050](https://github.com/alibaba-fusion/next/commit/d8de050))
-   **Timeline:** timline-item warning has function type prop ([18c48f4](https://github.com/alibaba-fusion/next/commit/18c48f4))
-   **Validate:** value can be false ([0e871d8](https://github.com/alibaba-fusion/next/commit/0e871d8))

<a name="1.11.7"></a>

## [1.11.7](https://github.com/alibaba-fusion/next/compare/1.11.6...1.11.7) (2019-01-02)

### Bug Fixes

-   **Menu:** to much data overflow when popupAlign is outside ([726da77](https://github.com/alibaba-fusion/next/commit/726da77))
-   **Switch:** tweak switch off-state right padding ([7882d35](https://github.com/alibaba-fusion/next/commit/7882d35))
-   **Table:** wrong value of offsetTop when set scrollToRow, close [#117](https://github.com/alibaba-fusion/next/issues/117) ([ac086c4](https://github.com/alibaba-fusion/next/commit/ac086c4))

### Features

-   **CascaderSelect:** support itemRender ([7f9b0f5](https://github.com/alibaba-fusion/next/commit/7f9b0f5))

<a name="1.11.6"></a>

## [1.11.6](https://github.com/alibaba-fusion/next/compare/1.11.5...1.11.6) (2018-12-26)

### Bug Fixes

-   **Cascader:** keyboard not blur ([3e43e6a](https://github.com/alibaba-fusion/next/commit/3e43e6a))
-   **Pagination:** select dropdown menu position error on scrolling ([70375c1](https://github.com/alibaba-fusion/next/commit/70375c1))
-   **Tab:** can not render when child have null item ([fb20367](https://github.com/alibaba-fusion/next/commit/fb20367))
-   **Tab, Grid:** inconsistency between doc and code ([5145fe7](https://github.com/alibaba-fusion/next/commit/5145fe7)) ([b07f5ac](https://github.com/alibaba-fusion/next/commit/b07f5ac)) ([43a4fd1](https://github.com/alibaba-fusion/next/commit/43a4fd1))
-   **Table:** style conflict with align ([aa32515](https://github.com/alibaba-fusion/next/commit/aa32515))
-   **Upload:** allow remove file when disabled ([2590a70](https://github.com/alibaba-fusion/next/commit/2590a70))

<a name="1.11.5"></a>

## [1.11.5](https://github.com/alibaba-fusion/next/compare/1.11.4...1.11.5) (2018-12-19)

### Bug Fixes

-   **NumberPicker:** float bug by chrome. Close [#79](https://github.com/alibaba-fusion/next/issues/79) ([4ac7f41](https://github.com/alibaba-fusion/next/commit/4ac7f41))
-   **Select:** defaultValue with async dataSource ([6fd23ba](https://github.com/alibaba-fusion/next/commit/6fd23ba))
-   **Table:** can't find unmounted component ([f004b52](https://github.com/alibaba-fusion/next/commit/f004b52))
-   **Typescripts:** perfect typescripts ([4459f14](https://github.com/alibaba-fusion/next/commit/4459f14))

<a name="1.11.4"></a>

## [1.11.4](https://github.com/alibaba-fusion/next/compare/1.11.3...1.11.4) (2018-12-18)

### Bug Fixes

-   **Cascader:** scrollbar style error ([04695d9](https://github.com/alibaba-fusion/next/commit/04695d9))
-   **Table:** rowHeight changed when resizing useVirtual ([aeaf513](https://github.com/alibaba-fusion/next/commit/aeaf513))

<a name="1.11.3"></a>

## [1.11.3](https://github.com/alibaba-fusion/next/compare/1.11.2...1.11.3) (2018-12-13)

### Bug Fixes

-   **Balloon:** ltr when set rtl on it own ([8cc4a8a](https://github.com/alibaba-fusion/next/commit/8cc4a8a))
-   **ConfigProvider:** remove warning when not using rtl ([f59dd15](https://github.com/alibaba-fusion/next/commit/f59dd15))
-   **Form:** css hack only in ie9 ([f5e77bc](https://github.com/alibaba-fusion/next/commit/f5e77bc))
-   **Input:** loading and hint not cannot occur at the same time ([cf97c99](https://github.com/alibaba-fusion/next/commit/cf97c99))
-   **Input:** padding reversed when select arrow translate 180 ([d5e9573](https://github.com/alibaba-fusion/next/commit/d5e9573))
-   **Menu:** keyboard not blur ([dda5a16](https://github.com/alibaba-fusion/next/commit/dda5a16))
-   **Slider:** dots' trigger area changed from <button> to parent <li> ([346f684](https://github.com/alibaba-fusion/next/commit/346f684))
-   **Step:** rtl style bugfix ([cadfec8](https://github.com/alibaba-fusion/next/commit/cadfec8))
-   **Table:** Avoid display error when browser scale ([b07b680](https://github.com/alibaba-fusion/next/commit/b07b680))
-   **Table:** lock columns cant align with whole table when affixed ([f1531c3](https://github.com/alibaba-fusion/next/commit/f1531c3))
-   **Timeline:** timeline-item cannot set className ([23754a3](https://github.com/alibaba-fusion/next/commit/23754a3))
-   **Upload:** forbid deleting file when upload is disabled ([e0936e5](https://github.com/alibaba-fusion/next/commit/e0936e5))
-   **Upload:** no space between upload and file list ([181517c](https://github.com/alibaba-fusion/next/commit/181517c))

<a name="1.11.2"></a>

## [1.11.2](https://github.com/alibaba-fusion/next/compare/1.11.1...1.11.2) (2018-12-06)

### Bug Fixes

-   **Overlay:** fix postion caculate error ([d38a78f](https://github.com/alibaba-fusion/next/commit/d38a78f))

<a name="1.11.1"></a>

## [1.11.1](https://github.com/alibaba-fusion/next/compare/1.11.0...1.11.1) (2018-12-06)

### Bug Fixes

-   scss ([ac04e9d](https://github.com/alibaba-fusion/next/commit/ac04e9d))

<a name="1.11.0"></a>

# [1.11.0](https://github.com/alibaba-fusion/next/compare/1.10.3...1.11.0) (2018-12-05)

### Features

-   **Select/Input/Message:** rtl supported in Select/Input/Message ([3bb15c8](https://github.com/alibaba-fusion/next/commit/3bb15c8))
-   **Affix:** implement affix by {position: absolute} ([da3e3ec](https://github.com/alibaba-fusion/next/commit/da3e3ec))
-   **Balloon:** support rtl ([64522d1](https://github.com/alibaba-fusion/next/commit/64522d1))
-   **Button:** support rtl ([d863787](https://github.com/alibaba-fusion/next/commit/d863787))
-   **Calendar:** support rtl ([d1c1e44](https://github.com/alibaba-fusion/next/commit/d1c1e44))
-   **ConfigProvider:** config-provider support rtl ([e91591a](https://github.com/alibaba-fusion/next/commit/e91591a))
-   **ConfigProvider:** support set global rtl ([622dda4](https://github.com/alibaba-fusion/next/commit/622dda4))
-   **DatePicker:** support rtl ([2d140fb](https://github.com/alibaba-fusion/next/commit/2d140fb))
-   **Dialog:** add rtl support ([bd3a66e](https://github.com/alibaba-fusion/next/commit/bd3a66e))
-   **Icon:** support rtl ([027fa40](https://github.com/alibaba-fusion/next/commit/027fa40)) ([fc5c02b](https://github.com/alibaba-fusion/next/commit/fc5c02b))
-   **Menu:** support rtl ([5241d7b](https://github.com/alibaba-fusion/next/commit/5241d7b))
-   **Nav:** support rtl ([923593a](https://github.com/alibaba-fusion/next/commit/923593a))
-   **Overlay:** add rtl prop for overlay ([6d77142](https://github.com/alibaba-fusion/next/commit/6d77142)) ([e5630de](https://github.com/alibaba-fusion/next/commit/e5630de))
-   **Pagination:** support rtl ([d34959c](https://github.com/alibaba-fusion/next/commit/d34959c))
-   **Progress:** add color & backgroundColor props ([1e9cd94](https://github.com/alibaba-fusion/next/commit/1e9cd94))
-   **Progress:** add rtl support ([cbe6747](https://github.com/alibaba-fusion/next/commit/cbe6747))
-   **Radio:** support rtl ([6a906a9](https://github.com/alibaba-fusion/next/commit/6a906a9))
-   **Search:** add rtl to search ([931729a](https://github.com/alibaba-fusion/next/commit/931729a))
-   **Slider:** support rtl ([c7416ab](https://github.com/alibaba-fusion/next/commit/c7416ab))
-   **Step:** support rtl ([a0645a0](https://github.com/alibaba-fusion/next/commit/a0645a0))
-   **Timeline:** support rtl ([0f3860b](https://github.com/alibaba-fusion/next/commit/0f3860b))
-   **TimePicker:** support rtl ([310155a](https://github.com/alibaba-fusion/next/commit/310155a))

<a name="1.10.3"></a>

## [1.10.3](https://github.com/alibaba-fusion/next/compare/1.10.2...1.10.3) (2018-12-05)

<a name="1.10.2"></a>

## [1.10.2](https://github.com/alibaba-fusion/next/compare/1.10.1...1.10.2) (2018-12-04)

### Bug Fixes

-   **CascaderSelect:** split of null bug ([1afac48](https://github.com/alibaba-fusion/next/commit/1afac48))
-   **Table:** maxBodyHeight both accept Number and String ([552f747](https://github.com/alibaba-fusion/next/commit/552f747))
-   **Table:** pass affixProps to affix ([0540cba](https://github.com/alibaba-fusion/next/commit/0540cba))
-   **Tree:** selectable=false cursor:default ([66bc721](https://github.com/alibaba-fusion/next/commit/66bc721))

<a name="1.10.1"></a>

## [1.10.1](https://github.com/alibaba-fusion/next/compare/1.10.0...1.10.1) (2018-11-29)

<a name="1.10.0"></a>

# [1.10.0](https://github.com/alibaba-fusion/next/compare/1.9.21...1.10.0) (2018-11-28)

### Bug Fixes

-   **Search:** medium search will overflow box when height = s-7 ([14dfbb0](https://github.com/alibaba-fusion/next/commit/14dfbb0))
-   **Search:** pass visible into Autocomplete ([9fae8fe](https://github.com/alibaba-fusion/next/commit/9fae8fe))

### Features

-   **Cascader:** add useVirtual prop, open virtual scroller ([769e156](https://github.com/alibaba-fusion/next/commit/769e156))
-   **CascaderSelect:** add useVirtual prop ([a2b724d](https://github.com/alibaba-fusion/next/commit/a2b724d))
-   **Form:** Item support function children ([c3ced42](https://github.com/alibaba-fusion/next/commit/c3ced42))
-   **Search:** divide \$search-normal-corner into medium & large variable ([3903b5e](https://github.com/alibaba-fusion/next/commit/3903b5e))
-   **Select:** add item from dataSource to onChange(v,e, item) ([ff0405f](https://github.com/alibaba-fusion/next/commit/ff0405f))
-   **Select:** support virtuallist in simple case ([b982efe](https://github.com/alibaba-fusion/next/commit/b982efe))
-   **Tag:** add selectable tag theme demos ([dfdd536](https://github.com/alibaba-fusion/next/commit/dfdd536))
-   **Transfer:** Support for disabling panel operations ([40f6743](https://github.com/alibaba-fusion/next/commit/40f6743))
-   **VirtualList:** add API jumpIndex ([2d137e2](https://github.com/alibaba-fusion/next/commit/2d137e2))
-   **VirtualList:** add new component ([29b78f5](https://github.com/alibaba-fusion/next/commit/29b78f5))
-   **VirtualList:** consider as items of the same height by default ([c9576ec](https://github.com/alibaba-fusion/next/commit/c9576ec))

<a name="1.9.21"></a>

## [1.9.21](https://github.com/alibaba-fusion/next/compare/1.9.20...1.9.21) (2018-11-27)

### Bug Fixes

-   **Input:** bug of value=0 with htmlType=number ([0805a38](https://github.com/alibaba-fusion/next/commit/0805a38))
-   **Message:** When there are multiple Message, the first can't close ([d3004f4](https://github.com/alibaba-fusion/next/commit/d3004f4))
-   **Search:** left border-raduis not 0 ([8713611](https://github.com/alibaba-fusion/next/commit/8713611))
-   **Select:** bug of autoWidth ([829f53b](https://github.com/alibaba-fusion/next/commit/829f53b))
-   **Select:** bug of autoWidth ([b80e4bb](https://github.com/alibaba-fusion/next/commit/b80e4bb))
-   **Select:** bug of onEnter ([17e13cd](https://github.com/alibaba-fusion/next/commit/17e13cd))
-   **Select:** double onKeyDown ([4b2e1b3](https://github.com/alibaba-fusion/next/commit/4b2e1b3))

<a name="1.9.20"></a>

## [1.9.20](https://github.com/alibaba-fusion/next/compare/1.9.19...1.9.20) (2018-11-21)

### Bug Fixes

-   **ConfigProvider:** Isolate multiple context data ([ca4bbd4](https://github.com/alibaba-fusion/next/commit/ca4bbd4)), closes [#43](https://github.com/alibaba-fusion/next/issues/43)
-   **ConfigProvider:** Update cache in expection ([a6c6151](https://github.com/alibaba-fusion/next/commit/a6c6151))
-   **Rating:** Enhance robustness ([6e40724](https://github.com/alibaba-fusion/next/commit/6e40724))

<a name="1.9.19"></a>

## [1.9.19](https://github.com/alibaba-fusion/next/compare/1.9.18...1.9.19) (2018-11-16)

### Bug Fixes

-   **Affix:** update postion in didmount ([1438cdf](https://github.com/alibaba-fusion/next/commit/1438cdf))
-   **Checkbox:** Change label type from string to any reanderable ([858083e](https://github.com/alibaba-fusion/next/commit/858083e))
-   **DatePicker:** add onChange params type ([5c753f1](https://github.com/alibaba-fusion/next/commit/5c753f1))
-   **DatePicker:** disabledHours no use in time end panel ([31e1256](https://github.com/alibaba-fusion/next/commit/31e1256))
-   **Range:** Scale tips become hollow on browser zoom ([1ed7f49](https://github.com/alibaba-fusion/next/commit/1ed7f49))
-   **Tab:** maxCall exceeded when parent using flex display ([c916d21](https://github.com/alibaba-fusion/next/commit/c916d21))
-   **Table:** style chaos when head sticky ([e952632](https://github.com/alibaba-fusion/next/commit/e952632))
-   **TreeSelect:** 'key' undefined error without treeCheckable prop ([ca4afe5](https://github.com/alibaba-fusion/next/commit/ca4afe5))

### Features

-   **Cascader:** loadData add argument source data ([2ca6a99](https://github.com/alibaba-fusion/next/commit/2ca6a99))

<a name="1.9.18"></a>

## [1.9.18](https://github.com/alibaba-fusion/next/compare/1.9.17...1.9.18) (2018-11-14)

<a name="1.9.17"></a>

## [1.9.17](https://github.com/alibaba-fusion/next/compare/1.9.16...1.9.17) (2018-11-13)

### Bug Fixes

-   **Breadcrumb:** fix use Link Tag no style ([503c945](https://github.com/alibaba-fusion/next/commit/503c945))
-   **Calendar:** week words error ([674de83](https://github.com/alibaba-fusion/next/commit/674de83))
-   **Range:** Prevent right-button dragging ([24b6769](https://github.com/alibaba-fusion/next/commit/24b6769))
-   **Tab:** Make bg-color configurable ([c353b1c](https://github.com/alibaba-fusion/next/commit/c353b1c))
-   **Upload:** Upload Card no i18n ([27e76b4](https://github.com/alibaba-fusion/next/commit/27e76b4))
-   **Calendar:** add api to format cell's label ([7a87917](https://github.com/alibaba-fusion/next/commit/7a87917))

<a name="1.9.16"></a>

## [1.9.16](https://github.com/alibaba-fusion/next/compare/1.9.15...1.9.16) (2018-11-09)

<a name="1.9.15"></a>

## [1.9.15](https://github.com/alibaba-fusion/next/compare/1.9.14...1.9.15) (2018-11-02)

### Bug Fixes

-   **Select:** bug of cacheValue=false ([6fce5d8](https://github.com/alibaba-fusion/next/commit/6fce5d8))
-   **Select:** bug of cacheValue=false ([bb2acdf](https://github.com/alibaba-fusion/next/commit/bb2acdf))
-   **Tab:** content panel collapsed in vertical mode ([9974a22](https://github.com/alibaba-fusion/next/commit/9974a22))
-   **Table:** error when lock without header ([9081865](https://github.com/alibaba-fusion/next/commit/9081865))
-   **Tree:** error when set expendedKeys/selectedKeys not in dataSource ([cd35aa0](https://github.com/alibaba-fusion/next/commit/cd35aa0))
-   **TreeSelect:** error when set value with keys aren't in dataSource ([dc8d9e8](https://github.com/alibaba-fusion/next/commit/dc8d9e8))
-   **TreeSelect:** show all tree while searchValue clear ([c04b3d3](https://github.com/alibaba-fusion/next/commit/c04b3d3))

<a name="1.9.14"></a>

## [1.9.14](https://github.com/alibaba-fusion/next/compare/1.9.13...1.9.14) (2018-10-29)

### Bug Fixes

-   **Locale:** use OK instead of Ok ([9782c6d](https://github.com/alibaba-fusion/next/commit/9782c6d))
-   **Search:** add type for search-simple-dark-bg-opacity ([57891de](https://github.com/alibaba-fusion/next/commit/57891de))
-   **Select:** minWidth of popupContent ([f6a4883](https://github.com/alibaba-fusion/next/commit/f6a4883))
-   **Upload:** error fileList not show ([87195d2](https://github.com/alibaba-fusion/next/commit/87195d2))
-   **Search:** add hover color variables ([385ab2d](https://github.com/alibaba-fusion/next/commit/385ab2d))
-   **Search:** remove search button box-shadow ([3713040](https://github.com/alibaba-fusion/next/commit/3713040))
-   **Search:** use hover-color in main scss ([14aea57](https://github.com/alibaba-fusion/next/commit/14aea57))

<a name="1.9.13"></a>

## [1.9.13](https://github.com/alibaba-fusion/next/compare/1.9.12...1.9.13) (2018-10-28)

### Bug Fixes

-   **TimePicker:** cann't config bg of input ([e5cae7b](https://github.com/alibaba-fusion/next/commit/e5cae7b))

<a name="1.9.12"></a>

## [1.9.12](https://github.com/alibaba-fusion/next/compare/1.9.11...1.9.12) (2018-10-24)

### Bug Fixes

-   **Balloon:** in theme platform & range ([dd78f6d](https://github.com/alibaba-fusion/next/commit/dd78f6d))
-   **scripts:** unify eslint config ([39ced54](https://github.com/alibaba-fusion/next/commit/39ced54))
-   **Upload:** add style to reset <a> ([b2b78f5](https://github.com/alibaba-fusion/next/commit/b2b78f5))

<a name="1.9.11"></a>

## [1.9.11](https://github.com/alibaba-fusion/next/compare/1.9.10...1.9.11) (2018-10-19)

<a name="1.9.10"></a>

## [1.9.10](https://github.com/alibaba-fusion/next/compare/1.9.9...1.9.10) (2018-10-19)

<a name="1.9.9"></a>

## [1.9.9](https://github.com/alibaba-fusion/next/compare/1.9.8...1.9.9) (2018-10-18)

### Bug Fixes

-   **Input:** input border-radius with one addonText ([b5051cf](https://github.com/alibaba-fusion/next/commit/b5051cf))
-   **MenuButton:** remove box-shadow ([6a976ca](https://github.com/alibaba-fusion/next/commit/6a976ca))
-   **NumverPicker:** remove box-shadow ([2c3e29f](https://github.com/alibaba-fusion/next/commit/2c3e29f))

<a name="1.9.8"></a>

## [1.9.8](https://github.com/alibaba-fusion/next/compare/1.9.7...1.9.8) (2018-10-18)

<a name="1.9.7"></a>

## [1.9.7](https://github.com/alibaba-fusion/next/compare/1.9.5...1.9.7) (2018-10-17)

### Bug Fixes

-   **Nav:** primary/secondary active border ([4c2c211](https://github.com/alibaba-fusion/next/commit/4c2c211))
-   **Menu:** Group.Item cant pass custom className ([eaf25707](https://github.com/alibaba-fusion/next/commit/eaf25707))

<a name="1.9.5"></a>

## [1.9.5](https://github.com/alibaba-fusion/next/compare/1.9.4...1.9.5) (2018-10-16)

### Bug Fixes

-   **Util:** Resolve env.isProduction in correct ([190ae61](https://github.com/alibaba-fusion/next/commit/190ae61))
-   **Util:** Undefined return statement ([2dcf9d3](https://github.com/alibaba-fusion/next/commit/2dcf9d3))

<a name="1.9.4"></a>

## [1.9.4](https://github.com/alibaba-fusion/next/compare/1.9.3...1.9.4) (2018-10-16)

<a name="1.9.3"></a>

## [1.9.3](https://github.com/alibaba-fusion/next/compare/1.9.2...1.9.3) (2018-10-16)

<a name="1.9.2"></a>

## [1.9.2](https://github.com/alibaba-fusion/next/compare/1.9.1...1.9.2) (2018-10-15)

### Bug Fixes

-   **Core:** wrong path ([a94b7d0](https://github.com/alibaba-fusion/next/commit/a94b7d0))

<a name="1.9.1"></a>

## [1.9.1](https://github.com/alibaba-fusion/next/compare/1.9.0...1.9.1) (2018-10-15)

### Bug Fixes

-   **Progress:** progress number bug ([8fc476d](https://github.com/alibaba-fusion/next/commit/8fc476d))

### Features

-   **Next:** add dingtalk qrcode to readme ([da35dfe](https://github.com/alibaba-fusion/next/commit/da35dfe))
