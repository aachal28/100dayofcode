# Common coding errors

*Copy each of the code blocks below with 👉 to `main.py`, click run, and see if you can fix them!
Make sure to get rid of any old code from `main.py` before you start the next one.*

Sometimes you get errors when coding. Here are the most popular errors:

## NameError

- You'll see this error message if:
  - you get the name of a function wrong
  - you misspell it
  - get the capitalization wrong
    
&nbsp;

👉 Let's try to run this code and see what error message we get. Add this code to your coding editor and hit `run`.


```python
Print("What could go wrong?")
```


What do you think is wrong? It's always important to read the error messages as they try to be helpful.  

```
Traceback (most recent call last):
  File "main.py", line 1, in <module>
    Print("What could go wrong?")
NameError: name 'Print' is not defined
```
Did you notice the p in `print` is capitalized? `print` is only lower case letters.
   



## SyntaxError
- You will see this message if:
  - you have the order of the symbols wrong
  - you forget `()` or `" "`
    
&nbsp;

👉 We will get an error when we run this code. Copy this code to your coding editor and hit `run`.

```python
print "Hello Again"
```


What do you think is wrong?
```
  File "main.py", line 1
    print "Hello Again"
          ^
SyntaxError: Missing parentheses in call to 'print'. Did you mean print("Hello Again")?
```
That's right. You forgot `()`.

&nbsp;

👉 What is causing the error here? Copy the code and hit `run` to find out.
```python
print(Please work)
```
```
  File "main.py", line 1
    print(Please work)
                 ^
SyntaxError: invalid syntax
```
You need `" "`.

&nbsp;

### You will only get better at debugging by practicing! You'll find lots of errors in your own code as you go, so make sure you get practice by trying all the "Fix my code" activities whenever you see them!
