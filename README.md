# TypicalsConvertingLibrary
a nice converting lib (that u can use for reanimations too btw!)

with some extra features

# Main Usage

```
local Library = loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/TypicallyAUser/TypicalsConvertingLibrary/main/Main", true))()
```

# Docs | Main

lib.Noclip(instance) - puts noclip on anything

lib.GetHatData(hatid, false or true) - returns the size and name of the hat | false is no notification, true is notification

lib.GetHatFromMesh(hatid) - returns the hat from the mesh, works best with r15 and r6 compatible scripts and is the best way to detect a hat

lib.ReanimationRigGet() - returns the reanimation rig instance for compatibility with all reanimations

lib.LoadLibraryFix() - fixes the load library inside of your convert/script

lib.Notification(title, text, icon, duration) - makes a notification, good for reanimations or scripts

lib.Net() -- executes my net | supports most exploits

lib.FindHat(Name, Size) - finds the hat with the hat or size, size isnt needed | can be used with lib.GetHatData as so, GetHatData[1] for name

lib.Align(Part0, Part1, Position, Angle) - mostly no delay alignement | has velocity built in

lib.Align2(Part0, Part1, Position, Angle) - same thing as Align1 but without velocity built in

lib.RemoveMesh(instance) - removes the mesh of the instance | automatically finds the mesh without the name of it

# Docs | Animations

lib.R6(rig.Animate) - gives your rig r6 animations

# Docs | Hat Duplicate Finder

execute the loadstring - renames all duplicates of the same hat or hat with the same exact name

# Docs | Anti-Ragdoll

execute the loadstring - Removes all ragdoll scripts and constraints, recommended to put at the top of your reanimation
