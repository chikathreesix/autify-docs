# Available Assertions

## Assertions for page

Keyword name | Overview | Arguments
--- | --- | ---
Page Should Contain Element | Verify that the specified element exists on the page | HTML Element
Title Should Be | Verifies that the page title matches the specified text | Text
Location Should Be | Verifies that the current URL matches with the specified text | Text (URL)
Location Should Contain | Verifies that the current URL contains the specified text | Text (URL)

## Assertions for element

キーワード名 | 概要 | Arguments | Target element types
--- | --- | --- | ---
Element Should Be Visible | Verifies that the element is visible | N/A | All
Element Should Not Be Visible | Verifies that the element is not visible | N/A | All
Element Text Should Be | Verifies that the text of the element matches the specified text | Text | All
Element Should Contain | Verifies that the element contains the specified text | Text | All
Element Should Not Contain | Verifies that the element doesn't contain the specified text | Text | All
Element Should Be Enabled | Verifies that the element is enabled | N/A | `button`, `input`, `select`, `textarea`, `optgroup`, `option`, `fieldset`
Element Should Be Disabled | Verifies that the element is disabled | N/A | `button`, `input`, `select`, `textarea`, `optgroup`, `option`, `fieldset`
Textarea Should Contain | Verifies that the textarea contains the specified text | Text | `textarea`
Textarea Value Should Be | Verifies that the content of the textarea matches the specified text | Text | `textarea`
Textfield Should Contain | Verifies that the textfield contains the specified text | Text | `input`
Textfield Value Should Be | Verifies that the textfield contains the specified text | Text | `input`
Checkbox Should Be Selected | Verifies that the checkbox is selected | N/A | `input[type="checkbox"]`
Checkbox Should Not Be Selected | Verifies that the checkbox is not selected | N/A | `input[type="checkbox"]`
Radio Button Should Not Be Selected | Verifies that the radio button is not selected | N/A | `input[type="radio"]`
List Selection Should Be | Verifies that the specified text is selected in the dropdown | Text | `select`
List Should Have No Selections | Verifies that nothing is selected in the dropdown | N/A | `select`
