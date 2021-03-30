# Lab 10: Overloading and Overriding

In this lab, you will review this documentation and implement
the classes and methods as defined here.

## Implementation

The following code is provided for you in the `main.cpp`. Use this
code as-is: do not make any modifications.

~~~cpp
int main() {
    Terrier* terrier = new Terrier("Todd");
    terrier->eat(10);
    terrier->speak("yip yip");
    terrier->speak("yip",5);
    std::cout << *terrier << std::endl;
    return 0;
}
~~~

Given the provided code in the `main` function, your output should be

    yip yip
    Speaking yip at volume 5
    Name:Todd
    Amount Eaten: 10


## Turning in the Lab

Turn in your Github URL when the lab is complete.