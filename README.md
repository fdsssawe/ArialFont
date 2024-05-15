### Arial font for vercel usage
Package includes file that exports font and font itself.
Usage :
```
import pathForArial from "arial-for-vercel"
```
To use it in registerFont()
```
try {
    registerFont(pathForArial, { family: "Arial" })
}
catch(e){
    console.log(e)
}
```
If you want to do the same thing for your own font but not sure how to, feel free to contact <a href="https://t.me/sashazhov">me</a>.