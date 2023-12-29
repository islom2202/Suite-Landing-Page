# I have learned:
1. New features
2. Problems I faced



## 1. New features:
-  **background** - instead of background-image it is better to write it shortly :
    ~~~
    background: url('assets/images/pattern-blur.svg') no-repeat;
    ~~~


## 2. Problems I faced
1. pseudo-elements' content set to image or background-image were not working:
   ~~~
   content: url('assets/images/pattern-blur.svg'); ⨉
   ~~~
   because the path was wrong:
   ~~~
   content: url('../assets/images/pattern-blur.svg')
   ~~~