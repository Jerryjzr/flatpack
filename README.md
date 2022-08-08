# flatpack
There is not a lot to unpack. Like... for real.

https://user-images.githubusercontent.com/66600478/183345870-d31b0fc4-497d-4f51-bbe5-db83cf9a2b46.mp4

https://user-images.githubusercontent.com/66600478/183403170-353edabf-4271-400f-9db7-fafc17dc54a0.mp4

https://user-images.githubusercontent.com/66600478/183500945-2cf039b2-9133-45dd-af40-6a08152f20f8.mp4
(flatpack and flathead printing gridfinity parts)


###### Technical Data:

- folded volume of roughly 220x210x75mm (so, make sure your spoolbox has that
  inner dimension, as there are some with slightly different dimensions)
- buildvolume of 120x114x114mm, so 1.6 liters
- heated bed
- powered through an external (!) powerbrick with 150W, uses 100W max
- the design would theoretically allow for an AC bed, and then a small psu
  inside for having everything in one box but that was deemed to dangerous for
  the average user by me, so i did not went that way

###### Some words of caution:


- As you can imagine, a fixed bed cantilever is not optimal for fast speeds or
  a big printvolume.
- Thankfully, we dont have to deal with a big printvolume, but with speed. Or
  better: the rapid change of directions. This is a problem with any movement
  system, and it is even more with this.
- So why the fixed bed cantilever? Because it simply looks cool.
- Also, i used dual rails for load distribution for Y and Z; these are a bit
  problematic to align, and can and will cost you a few grey hairs.
- last word of caution would probably be to take your time building flatpack, and make sure everything is square, and everything that should move moves well, while everything that should not move really doesnt move or flexes 


## This is free for everyone to download and build, or of course to just look at it and take some ideas from it. :)


- As you can imagine, a fixed bed cantilever is not optimal for fast speeds or a big printvolume.
- Thankfully, we dont have to deal with a big printvolume, but with speed. Or better: the rapid change of
directions. This is a problem with any movement system, and it is even more with this.
- So why the fixed bed cantilever? Because it simply looks cool.
- Also, i used dual rails for load distribution for Y and Z; these are a bit problematic to align, and
can and will cost you a few grey hairs.
- its a (functioning) prototype, and with that will get much more work done

###### ToDo-List
- the XY-joiner is right now not printable on flatpack. In reprap-fashion everything should be though. That will be fixed
- with that said, the XY-joiner is also too complicated to print. With the redesign to be able to be printed on flatpack, i hope i will also tackle that.
- flathead has no spoolholder. I want to design a spoolholder, that can travel along in the spoolbox of your actual spool you´re carrying with you
- i may want to change to a Mellow Orbiter Extruder, as that seems to be the better extruder. Also its nearly the same shape, and the same price
- Fanduct for partcooling is still not optimal i think. I simply cant design a proper fanduct. But i also started a repo for ["caterpillar"](https://www.github.com/eponra/caterpillar), which is my partcoolingsolution using CF tubes, which will be merged into flatpack eventually.
- the 3-mount-bedmounting is not optimal, as i simply drilled holes and threaded M3 threads into that. I may find a better solution down the road
- you can twist the base. Thats not supposed to happen, and one solution is to drill through the aluminium extrusions to get screws into the extrusions under the bed. I think there must also be another way...

![prototyping](https://user-images.githubusercontent.com/66600478/183500214-0299970e-6995-443d-a172-a0e379b12d8e.jpg)
(for a break, the latest switch from a totally different hotend/partcooling setup to the actual one. Thats not all steps, just a few)

## Design files

[Fusion 360](https://a360.co/3vLUHdm)

This link is sadly viewable only, as i am using the free version of Autodesk
Fusion 360.

The link to the latest stable F360 file is [here](https://drive.google.com/file/d/11LgXLBMvyC8zmfqN7jgGPJatx4k_127C/view).

The link to the latest stable .step file is [here](https://drive.google.com/file/d/1zsAKuO8Nb--h5dHGaoO5eWXcXt3RKrQH/view).

###### A few words of gratitude:

The initial idea of a fixed bed cantilever was not mine, but came from
[apsu](https://github.com/apsu), a constant resident of the
#reprap-and-custombuilds channel in the [3D Printing
discord](https://discord.gg/pQRvDQHk67).  With this i built flathead, the
bigger brother of flatpack, and without [apsu](https://github.com/apsu/) none
of this would have happened.

The initial idea to make this foldable, came from @Ogre.

Also, special thanks to [oliof](https://github.com/oliof/), another extremely
helpful member and Mod of 3D printing, and also a walking dictionary on obscure
3D printing and mechanical knowledge.  And of course, a thank you to everyone
else i forgot from 3D printing and especially the #reprap-and-custombuilds
channel.

Also, everyone nagging me multiple times a day in the super secret
#wheres-flatpack channel...


Flatpack is licensed under [GPL v3.0](/LICENSE).
