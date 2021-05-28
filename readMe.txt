## React-Native-Redux
App.js >> store, font, navigate
/store ** using "useSelector" to get the state
    /actions (dispatch()) >> action type, state (function to update state)
    /reducers (export to rootReducer App.js) >> initialState, **Reducers (Switch case with action type, Business Logic)
/navigate > react-navigation, react-navigation-material-bottom-tabs
    - Setup all screen
    - createStackNavigator, createBottomTabNavigator, createDrawerNavigator (hamburger menu)
/screens > screen to navigate
    - React component, useSelector state, render, StyleSheet
    - *FiltersScreen >> useEffect(),useCallback(),dispatch, useState() {state,setState}
    - * MealDetailScreen >> useSelector(), useEffect(),useCallback()
/components > React component,  state useSelector, render, StyleSheet
/asserts > fonts, resources, img
/constants > constants, utils
/model


# React hook (function component)
- class component ซึ่งเป็น component ที่มีการเก็บ state และสามารถเรียกใช้งาน lifecycle hooks 
- functional component ที่รับ props จาก class component เพื่อมาแสดงค่าอีกที

* useState: เพิ่ม State ใน Functional Component
* useEffect: เพิ่ม Lifecycle Hooks ใน Functional Component 
    - componentDidMount หรือ componentDidUpdate
more: 
* useContext
* useReducer
* useCallback
* useMemo
* useRef
* useImperativeMethods
* useMutationEffect
* useLayoutEffect

ref: 
react hook: https://medium.com/@rennerwin/%E0%B9%80%E0%B8%9E%E0%B8%B4%E0%B9%88%E0%B8%A1%E0%B8%84%E0%B8%A7%E0%B8%B2%E0%B8%A1%E0%B8%AA%E0%B8%B2%E0%B8%A1%E0%B8%B2%E0%B8%A3%E0%B8%96%E0%B9%83%E0%B8%AB%E0%B9%89%E0%B8%81%E0%B8%B1%E0%B8%9A-functional-component-%E0%B8%94%E0%B9%89%E0%B8%A7%E0%B8%A2-react-hooks-%E0%B8%88%E0%B8%B2%E0%B8%81-react-16-7-0-b41e94d3464d