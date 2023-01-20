# gdg-practice

Projects made as a part of Google Student Developer Club

## nav-bar-practice

A simple HTML navbar with redirects to other pages.


![nav bar preview](./nav-bar-preview.PNG)

```
                    ┎─────> Home.html
                    |
                    ├─────> News.html
Navigation Bar ─────|
                    ├─────> Contact.html
                    |
                    └─────> About.html
```                   



## html-form-practice

A simple HTML form (`Name`, `Age`, `Username`, `Password`) with input validation, regular expression (regex) and pattern matching.
<br>

The following regex ensures the `Username` contains at least 1 capital letter and digit

```   
(?=.*\d)(?=.*[A-Z]).{2,}
```   
<br>

The following regex ensures the `Password` contains at least 1 capital letter

```   
(?=.*[A-Z]).{1,}
```   