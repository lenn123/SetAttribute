## Contributing

For more information on contributing to this repository visit [Contributing to a GitHub repository](https://world.mendix.com/display/howto50/Contributing+to+a+GitHub+repository)!

## Typical usage scenario

Mendix does not allow the developer to change / set the value of an attribute in the Modeler. Use this widget to find domNodes (by a normal selector string, e.g. .class, #id, .mx-name-mxId) and set the value of an attribute. Further it is possible to append an attribute. This can be used to add custom classes / styling to domNodes that are not directly usable.

##Examples

Use domNode: input to find input widgets and set attribute: type and get the right mobile keyboard:
- datetime
- email
- month
- number
- range
- search
- tel
- url

Use attribute: class and append: true to add classes

Use attribute: style and append: true to add css

![Widget configuration](https://cloud.githubusercontent.com/assets/9658410/20215470/c0cb4d2c-a814-11e6-8aa6-5095b3e57513.png)
![Custom attribute](https://cloud.githubusercontent.com/assets/9658410/20215471/c0dcee24-a814-11e6-9b16-6df2adb6181e.png)
![Add style](https://cloud.githubusercontent.com/assets/9658410/20215472/c0e67a52-a814-11e6-9afb-9bef84dc31da.png)


## Known bugs
None