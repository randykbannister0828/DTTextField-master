# DTTextField

## Introduction

UITextField library with floating placeholder and error label.

## Example

Clone the repo and run the example project from the Example directory.

## Requirements

* Xcode 11.0+
* Swift 5.0+


## Usage

1. Open a storyboard or Xib file.  
2. Drag and drop a `UITextField` to a ViewController.  
3. In Identity Inspector, replace the class from `UITextField` to `DTTextField` and the module to `DTTextField`.  

## Properties

| Property name | Type | Remark |
| ------------- |------------- | ----- |
| errorMessage | String | Add your error message to this property|
| errorFont | UIFont | Change font of error text |
| errorTextColor | UIColor | Change color of error text |
| paddingYErrorLabel | CGFloat | Error text top padding |
| floatPlaceholderColor | UIColor | To change float placeholder color |
| floatPlaceholderActiveColor | UIColor | To change float placeholder color while TextField is active(First responder)|
| floatPlaceholderFont | UIFont | Change font of float placeholder |
| paddingYFloatLabel | CGFloat | float placeholder top padding |
| placeholderColor | UIColor | change placeholder color |
| animateFloatPlaceholder | Bool | animate float placeholder label |
| hideErrorWhenEditing | Bool | hide error label when typing |
| floatingDisplayStatus | enum | maintain display status always, never, defaults | 


### Important Properties

| Property name | Type | Remark |
| ------------- |------------- | ----- |
| dtLayer | CALayer | If you want to formate DTTextField than use dtLayer property instead of layer (e.g. background color) |
| borderColor | UIColor | Change border color of DTTextField |
| canShowBorder | Bool | Toggle border of DTTextField |
| dtborderStyle | enum | none, rounded , sqare , top , bottom , left , right |

## Methods

| Method Name | Remark |
| ------------|--------|
| showError | to show error message |
| hideError | to hide error message |

## Note

Don't give height constraint to DTTextField otherwise it won't work properly.

## TODO
* Add inbuilt validation

## Author

Randy Bannister :sunglasses:
