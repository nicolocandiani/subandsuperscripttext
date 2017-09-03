# Subscript and superscript text 
**Subscript and superscript text** is a Swift Extension which provides easy creation of a custom superscripted or subscripted text for 
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
Copyright (C) 2017 Developed by Nicolò Candiani

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
