# Frontend-Level1
for AutoX Frontend Interview Test
 # **Q2. React: Employee Information**

## **Create an Employee Information module as shown below:**

> Expect result:
> 
[![Watch Video](https://github.com/AutoXSpace/Frontend-Level1/blob/f8e75827476ac37fa1b660af85c82fbf198ed616/public/q1-fe-exam-thumbnail.png)](https://github.com/AutoXSpace/Frontend-Level1/assets/151896391/b10f3851-d2d2-4efb-9779-5e2a7cdc62eb)


---

## Requirements and Conditions

### **1. There is a reusable component in the module named Dropdown:**

    * It renders a `<select>` element.
    * It receives 3 props:
    
      
      * `labelText` - used to render the default option in the dropdown
    
        
      * `options` - This is an array of strings where each object is rendered as an option in the dropdown. Each option should have a value equal to object instance (string).
    
        
      * `onChange` - The onChange function to be called on option selection to pass the selected value to the parent.
    

### **2. The module must have the following functionalities:**

    * It renders 2 Dropdown components.

  
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


    * The `div` containing country options dropdown: `'country-options'`
    
      
    * The `div` containing language options dropdown: `'language-options'`
    
      
    * The `label` rendering selected country: `'country-selected'`
    
      
    * The `label` rendering selected language: `'language-selected'`
    
      
    * Inside the Dropdown component select element: `'dropdown'`



**Please note that the component has the data-testid attributes for test cases, certain classes and ids for rendering purposes. They should not be changed.


### **4. Input Data for test:**

```
1. Default Country option: "Select Country"

2. Country data:
 [
    "Armenia",
    "Australia",
    "Austria",
    "Azerbaijan",
    "Burkina Faso",
    "Costa Rica",
    "Croatia",
    "Thailand"
]

3. Default Language option: "Select Country"

4. Language data:
[
  "English",
  "German",
  "Azerbaijani",
  "Arabic",
  "Bengali",
  "Belarusian",
  "Russian",
  "Dutch",
  "Thai"
]

```




**Software Instructions**

> The question(s) requires **==Node 14 LTS or above.==**
>
> ## [Download & Install Node.JS](https://nodejs.org/en/download/)
>


## Git Instructions

> Use the following commands to work with this project



**Run**


```
npm start
```




**Test**


```
npm test
```



**Install**


```
npm install
```




## 🤟🏻🤟🏻 Good Luck 🤟🏻🤟🏻
