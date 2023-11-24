# **Q1. React: Employee Information**

## **Create an Employee Information module as shown below:**




---

## Requirements and Conditions

### **1. There is a reusable component in the module named Dropdown:**

* It renders a `<select>` element.
* It receives 3 props:

  \
  * labelText - used to render the default option in the dropdown

    \
  * options - This is an array of strings where each object is rendered as an option in the dropdown. Each option should have a value equal to object instance (string).

    \
  * onChange - The onChange function to be called on option 	selection to pass the selected value to the parent.


### **2. The module must have the following functionalities:**

* It renders 2 Dropdown components.

  \
* The first Dropdown component is used to render country options. When a country is selected it should be rendered as:


```javascript

<label data-testid="country-selected">
Country Selected: <selectedCountry>
</label>
```


* The second Dropdown component is used to render language options. When a language is selected it should be rendered as:


```javascript

< label data-testid="language-selected"> 
Language Selected: <selectedLanguage> 
</label>
```


### **3. The following data-testid attributes are required in the component for the tests to pass:**


* The div containing country options dropdown: `'country-options'`

  \
* The div containing language options dropdown: `'language-options'`

  \
* The label rendering selected country: `'country-selected'`

  \
* The label rendering selected language: `'language-selected'`

  \
* Inside the Dropdown component select element: `'dropdown'`




:::info
Please note that the component has the data-testid attributes for test cases, certain classes and ids for rendering purposes. They should not be changed.

:::




---


**Software Instructions**

> The question(s) requires **==Node 14 LTS or above.==**
>
> ## [Download & Install Node.JS](https://nodejs.org/en/download/)
>
> \


## Git Instructions

> Use the following commands to work with this project





:::tip
**Run**


```
npm start
```

:::





:::tip
**Test**


```
npm test
```

:::





:::tip
**Install**


```
npm install
```

:::



## 🤟🏻🤟🏻 Good Luck 🤟🏻🤟🏻