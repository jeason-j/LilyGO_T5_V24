# LilyGO T5 V24 Board test code

![](image/1.jpg)
## 1.Install the following dependency library files:
**The following two libraries are not original branches, they are my modified branches.**
- [lewisxGxEPD](https://github.com/lewisxhe/GxEPD)
- [lewisxButton2](https://github.com/lewisxhe/Button2)


**Select the appropriate header file based on the screen you purchased.**
```
// select the display class to use, only one
// select the display class to use, only one
// #include <GxGDEP015OC1/GxGDEP015OC1.h>    // 1.54" b/w               //G702-A
// #include <GxGDEW0154Z04/GxGDEW0154Z04.h>  // 1.54" b/w/r 200x200        //H215
// #include <GxGDEW0154Z17/GxGDEW0154Z17.h>  // 1.54" b/w/r 152x152     //H222

// #include <GxGDE0213B1/GxGDE0213B1.h>      // 2.13" b/w               //G702-B
// #include <GxGDEW0213Z16/GxGDEW0213Z16.h>  // 2.13" b/w/r             //H219
// #include <GxGDE0213B72/GxGDE0213B72.h>       // 2.13" b/w
// #include <GxGDE0213B72B/GxGDE0213B72B.h>       // 2.13" b/w

// #include <GxGDEH029A1/GxGDEH029A1.h>      // 2.9" b/w                //G702-C
// #include <GxGDEW029T5/GxGDEW029T5.h>      // 2.9" b/w IL0373
#include <GxGDEW029Z10/GxGDEW029Z10.h>    // 2.9" b/w/r              //H224 YBW

// #include <GxGDEW027C44/GxGDEW027C44.h>    // 2.7" b/w/r                 //H220
// #include <GxGDEW027W3/GxGDEW027W3.h>      // 2.7" b/w                //H225

//#include <GxGDEW042T2/GxGDEW042T2.h>      // 4.2" b/w
//#include <GxGDEW042Z15/GxGDEW042Z15.h>    // 4.2" b/w/r
//#include <GxGDEW0583T7/GxGDEW0583T7.h>    // 5.83" b/w
//#include <GxGDEW075T8/GxGDEW075T8.h>      // 7.5" b/w
//#include <GxGDEW075Z09/GxGDEW075Z09.h>    // 7.5" b/w/r
```