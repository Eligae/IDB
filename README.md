# IDEA
## Mechanism

using `PyQt` for front.

needs data of **id, password, where it is gonna be uesd(ex. site, game), 2nd pw, distinguished words(just input word like ***github***)**

it might look like this(for example, in json)
```json
{
    "data" : {
        "num1" : {
            "id" : "Riaco",
            "password" : "Totodile0!",
            "used" : "https://github.com",
            "2nd password" : null,
            "distinguish" : "github",
        }, 
    }
}
```

## Front

1. find

>need one input. if user input one word, or a link to find whatever user had inputed in data, this program will get the right id & pw for user to input.

2. save

>need a set of input lines to save data to find in future.
>
>like the json data before, 5 data has to be inputed, except 2nd password, which is not needed, might be null.


## Why?

it might be short project to learn about **DBMS**.

But in reality, it might be a good tool to use, because some passwords are not easy to remember, cause we use to many sites with different ids.

Of course, this program is off-line, so no worries for security of this program.
