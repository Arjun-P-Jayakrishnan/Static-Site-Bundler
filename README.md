# Static Site Bundler

## Idea	

The main goal of this bundler compared to many other alternatives is that its is just used to create only a static files  and mainly html and css files.

##	Collaboration
If you see this idea as something fun just message me on linked in and happy to collaborate 😀.

##	Background

### Reason 😒

The portfolio that i created contained multiple lines of html and multiple css files .I needed a solution to write them as separate html and css files not like a link but just different sections in a single page. 

Yes you can use **React, Next, Solid** and many others to create beautiful and  colorful websites which are **dynamic**. Yeah but i thought its better to start from the roots before climbing up the ladder of abstraction. I know ,its not a good thing but i thought its fun to try out certain new things so here we are!.

## Key Concepts

###	Loader/Transformer ⚙️
Basically what we do here is we will turn all files into JavaScript.

### Dependency Resolution 🔎

The actual bundlers have this concept of dependency resolution i.e. you will have to replace any code which is used as dependency by copying it to the required file. Say example:-

i have multiply( a , b) which i am importing from some util class but on run time it has to be converted to a single file and hence we copy the multiply function to the first class

 In *dependency resolution* we will need to *find each file* and once all files are found we go for **bundling**.

###	Bundling 🪢

The process is to combine all these files into one.


##	Idea

This project just aims to solve the merge issue of multiple static pages into a single file or sub-files depending on a **config file**. When you run the bundler you will receive files based on the config files in each section.

The basic idea here is that **config file dictates**,  where and how each files must be merged and which not to , since *it may have to be a link file* (like a href ) etc. This is **not** for   a JavaScript based dynamic project as you may notice that the static files are only merged. It is done purpose fully as it was not the main intension and i particularly don't have  any idea how to do it.

### Dependency Resolution

Here we are not going to do the usual dependency resolution but just finding file and its contents.


