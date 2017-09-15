# Subscript and superscript text - SWift 4
**Subscript and superscript text** is a Swift Extension for **Swift 4** which provides easy creation of a custom superscripted or subscripted text for 
a UILabel from a String to a NSMutableAttributedString. This extension is great if you are developing an app with scientific purposes, 
where you have to write equation or unit of measure.

### USAGE
Using the function customText, you'll easily create a perfect custom subscript or superscript text.
</br>**SUPERSCRIPT:** put the word, or phrase, you need to elevate between two braces, **{** and **}**
</br>**SUBSCRIPT:** put the word, or phrase, you need to subscript between **£** and **$**

Here's a code example
```swift
let myLabel1 = UILabel()
let myLabel2 = UILabel()
var subScriptText = "(H£2$) 0.117 kJ/mol"
var superScriptText = "−1.88·10{−6} cm{3}/mol (298 K)"
var finalSubScript : NSMutableAttributedString = subScriptText.customText()
var finalSuperScript : NSMutableAttributedString = superScriptText.customText()

myLabel1.attributedText = finalSubScript
myLabel2.attributedText = finalSuperScript
```
The result will be:</br>
Subscript:</br>
![Subscript](http://i66.tinypic.com/aad9ae.png)
</br>Superscript:</br>
![Superscript](http://i65.tinypic.com/iyietk.png)

### INSTALLATION
Drag the file inside your project and you're ready to go!

### LICENSE
No license. Free to use for everyone
