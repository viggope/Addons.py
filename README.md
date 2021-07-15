
# Addons
  Addons is a module with the content of many cool features, that makes the python programming much easier!

## Features
  * Add colours to your output on the run page to adapt your text
  * Avoid having to do calculations yourself with the calculator features




#### Other information
  We uses a shortcut so you don't need to type the long class names (You don't need to type this)

    fm = functions.math()
    fc = functions.colors()
    fe = functions.extra()
    fs = functions.statements()
    fAy = functions.ability()
    ft = functions.texting()
    fb = functions.bool()
    f_en = functions.encrypting()
    f_re = functions.remote()
    _fa = functions._advanced_()
    f_sl = functions.slicing()

  To use this feature, type your code like this:
  
    functions.fc.green_text('Hello green world!')
  
  
  You can use the color() function instead of typing the color as a whole line.
  
  This is recommended to do
  
    fc = functions.fc
    fm = functions.fm
_______________________________________________________________________________________________________________________________
  
#### Commands and functions
  
  This cool function from the class "_math_" sets the variable to a specific value if the variable is more than another value:
  
    fm.set_after(_a_, _b_, _c_):
  
  The __syntax__ for the current function:
  
    var = set_after(var, 10, 0)
  __Use:__
    
    testvalue = 0
    while True:
        testvalue += 1
        testvalue = fm.set_after(testvalue, 10, 0)
        print(testvalue)
        time.sleep(0.5)
  
  
  Another function but from the class "_texting_":
  
    reverse(word):
  
  __Syntax:__
  
    print(ft.reverse('Was it a car or a cat I saw?'))
  __Use:__
    
    value = input("Enter a palindrome >")
    if value == ft.reverse(value):
        print("You won!")
    else:
        print("Oops, that's not same word reversed")
  
  
 
_______________________________________________________________________________________________________________________________

![5d69e29f0d71aaa04ed9725100199b4e](https://user-images.githubusercontent.com/59804534/123821406-a74a7e00-d8fb-11eb-9e73-3ad8d85d1ead.png)
