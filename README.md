# EWW - Free asset set

All free assets made by EWW

## How to create a character spritesheet ?

### Prepare

 - You need one animation of 4 sprites moving top and bottom
 - Download TexturePacker https://www.codeandweb.com/texturepacker

### Generate spritesheet
 
 - Use TexturePacker :=) (TBD Tutorial)
 - Make sure to have the neccssary animations in your json file

```javascript
 "animations": {
	"idle": [],
	"idle_s": [],
	"idle_ne": [],
	"idle_nw": [],
	"idle_sw": [],
	"idle_se": [],
	"move_sw": [],
	"move_se": [],
	"move_nw": [],
	"move_ne": []
},
```


and on meta an absolute path to your image file
```javascript
"meta": {
	"image": "https://raw.githubusercontent.com/Endlesswebworlds/EWW-assets/main/Characters/levi/levi.png",
}
```


---
Licence : LICENSE-CC-BY-NC-ND-4.0
