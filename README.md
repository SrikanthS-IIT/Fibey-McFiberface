# Fibey-McFiberface
<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/SrikanthS-IIT/Fibey-McFiberface/">Fibey McFiberface</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://www.srikanthsugavanam.com/">Srikanth Sugavanam</a> is licensed under <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1" alt=""></a></p>

This project has been supported by DST-CRG Grant, as awarded by the Science and Engineering Research Board, a statutory body of the Department of Science and Technology (DST), Government of India.

An open source repository of 3D printable fiber optic component holders compatible with metric optical tables.
![image](https://github.com/user-attachments/assets/ff8ed29e-2c1b-4b41-9089-ad5e9d1e78e6) 
![image](https://github.com/user-attachments/assets/37232884-780f-457b-82a3-2fb833d8216c)


## Why?

One of the problems I faced when making fiber lasers at my lab at IIT Mandi is the sheer amount of table space and tape I was using to hold down my components. I already had an optical table, but fiber optic holders and fixtures for day-to-day components are hard to come by, are (mindboggingly, and nonsensically) costly, or simply not available. 

I turned to the 3D printing open source community. While there were some interesting ideas, I couldn't find anything that really was "bench-ready". 

So I decided to make Fibey McFiberFace, or Fibeys for short. 

## What are Fibeys?

Fibeys are open source, modular 3D printables to hold down your fiber components on a standard metric optical table. At present, I have designed the following key components - 

1. A lean, but sturdy mini optical fiber spool for holding both bare and jacketed fibers. 
2. A modular metric bracket, which has a slot that can hold any item you want to design.
3. A modular fit peg that goes with the bracket for holding a back-to-back.
4. A non-modular fiber component holder for more compact settings. 
5. And of course, M6 screws that print in 5 minutes. 

## Design considerations

When designing the Fibeys, I have carefully considered several practical aspects. For instance - 

1. I have checked the losses of the fiber spool for bare and tight jacketed fibers - it is hardly indistinguishable from connector losses, as the mandrel diameter is larger than the recommended limit for SMF28-type fibers.
2. I have added a non-obtrusive lip to the fiber spools so that the fibers don't "jump" out after they are put in place. 
3. I have designed them to use a minimal amount of print material. For instance, the spools hardly use 15 mg of PLA. I increased the sturdiness by adding spokes with holes, such that the walls provide extra support. Similarly, the screw design is slightly contrived - however I have done this on purpose to ensure that the layer lines run along the length of the stems for strength. Superglue works fantastically to hold the screws together.
4. And these items print rapidly. For instance, I printed a set of 3 back to backs on ABS in about 48 minutes. This will be much faster with PLA for sure.
5. Above all, I wanted the design to be as modular as possible. The slotted metric bracket (item 2 in the list above) is to allow you to add any item you would like. For instance, right now I am experimenting with an enclosure for housing a nonlinear polarization controller block, and the results are quite promising. I am also designing a modular and scalable enclosure box.

I will keep adding to the Git, so do keep visiting. At the same time, I am very keen to have your feedback, and also see how you use the Fibeys. Please feel free to use and modify, and let me know if there is anything that you would like me to make and add to the project! Happy to answer any questions. :)

## Technical stuff

- **3D printer** - Creality K1C.
- **Materials** - Creality Hyper PLA and Hyper ABS.
- **Design software** - TinkerCAD. 

I am quite new to 3D printing, so at present I am not tweaking too many settings, and settling with the default. 3D printing has indeed come a long way in this respect - I just have to upload the design, and then walk away from it without any worries.  

Also, I have used TinkerCAD for all the designs above. I have also used Fusion 360, but there is hardly any difference in the print quality. Fusion offers some advanced contouring features, which can prove to be useful if your designs require it. For now, TinkerCAD rules. 

Finally, sandpaper is your friend. Sometimes, the Creality software decides to add a brim, which throws the tolerances off a bit. Sanding the edges a bit solves the problem, however be careful of the microplastics. 

