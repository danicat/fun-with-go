# fun-with-go
This is the home of my "Fun with..." trilogy of talks.

## Episode 1: Fun with Pointers

Originally presented at [Gophercon UK 2019](https://gophercon.co.uk).

In this talk you will learn how to use pointers effectively in Go. We’ll cover from the basics of pointer declaration and usage, to the implications of allocating memory on the stack versus the heap. We'll also see some practical use cases and interesting behaviours when using pointers, including when to use pointer receivers vs value receivers, unsafe package tricks and when a nil pointer is not exactly nil (hint: interfaces!).

Links:
- [Presentation](https://docs.google.com/presentation/d/e/2PACX-1vSVN5pXkK8CFimGIVqaUXpJxo0OUILbPMAMD1s0S1dZwXX-Z6lW9H5W7_rTAiDGacW2MSTpA0cnhZB_/pub?start=false&loop=false&delayms=3000)
- [Recording](https://youtu.be/yEiaCx0fR9k?si=Hlpv12LF1Gx2FbJB)

## Episode 2: Fun with Slices

Originally presented at [GoCon 2023 (Japan)](https://gocon.jp/2023/)

Slices can be seen in almost every Go program, but many developers are still unware of how they exactly work. On the surface we might think they are simple constructs that allows us to handle multiple elements of a single type, but they are more than just a collection.

Specially for people new to Go, slices can be a source of pain because of the behaviors it possess that you wouldn't expect from a traditional dynamic array or list.

In this session we are going to do a deep dive on the slice type, starting from arrays and slice declaration syntax, slicing operations, copying, resizing and its surprising (or not) side effects.

The session will be composed most of code examples using the playground, with an eventual dive into the compiler source code to see the relevant bits of slice implementation.

Links:
- [Presentation](https://docs.google.com/presentation/d/e/2PACX-1vQDvy-3KT6-cqbxzJ2UY8sFe86mOknAGJiP5aDD_FwWusezgVzdItYIiVDxNMX9O30k10IX27PNI9Hx/pub?start=false&loop=false&delayms=3000)
- [Recording](https://youtu.be/9yHts5xZtX8?si=LNk01dx0fWAbwnNx)
