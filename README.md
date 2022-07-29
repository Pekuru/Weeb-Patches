#### Weeb Patches
------------
So you're here because you got interested, and you want to either make your own, or add to the collection. Check the Resource folder, it has the things I used.  However, for some added effect, here is a little rundown of the xcf set-up and how i got the patch border to work.

Layer group with the effects:
- Group folder: Pass through
- - Fabric: Multiply 50%
- - Minor details: Multiply 50%

To make the border somewhat fancy you can try the following:
1. Using the select tool, select all the parts you want to keep (or reverse, select what you want to remove)
2. With the border of the patch selected hit `Selection to path` (Make sure you don't accidently grab the canvas edges)
3. With the path now in the paths section pick a color you want for your border and hit `Stroke path`. Experiment with the radius a bit, but 10px seems to be reasonable.
4. Select the `Hardness 25` brush and set it's size to half the size of the border you just created. use a lighter color then you had before.
5. Now stroke the path again, however, use the `stroke with a paint tool` option.

Now you got yourself a nice looking edge around your patch!
