# Wedding Cake Train

My sister-in-law is a pastry chef. When we were talking through ideas for the cake she said "...and then a little train on top." She probably meant marzipan – I was thinking something else.

A model railway for my wedding cake. The locomotive rotates on five ball bearings through the little landscape, bolted down to a 3D printed turntable, so nothing can derail or fall over. It's battery powered, with a little wagon carrying the bride and groom and LED fairylights above.

<table>
<tr>
<td width="50%"><img src="images/hero-image.jpg" alt="The finished diorama, locomotive and wedding couple"></td>
<td width="50%"><img src="images/top-view.jpg" alt="Top view of the diorama"></td>
</tr>
</table>

![In the cake](images/in-the-cake.gif)

## A few things you should know

**This is a showcase, not really a build guide.** There are no step-by-step assembly instructions here. You get the STLs, a parts list and the story. If you want to build one you'll have to fill in some blanks yourself, and I'm happy to help if you get stuck.

> [!TIP]
> Questions, or you built one? Come say hi on my [Discord Server](https://glnnk.art/discord).

**The parts list has gaps.** Screw lengths, bearing sizes, the exact N20 motor — I built this in the two weeks before my own wedding and wrote none of it down. Anything I still need to look up is marked `XXX` or `???`. I'll fill it in when I get round to taking it apart again.

## Contents

- [The Base](#the-base)
- [The Landscape](#the-landscape)
- [The Rolling Stock](#the-rolling-stock)
- [Done](#done)
- [Printed Parts](#printed-parts)
- [Everything Else](#everything-else)
- [CAD Source](#cad-source)
- [License](#license)
- [The End](#the-end)

## The Base

![CAD cross-section](images/cad-screencapture.gif)

<table>
<tr>
<td width="50%"><img src="images/3d-model-01.jpg" alt="CAD view of the base assembly"></td>
<td width="50%"><img src="images/3d-model-02.jpg" alt="CAD view showing the ring gear and bearings"></td>
</tr>
</table>

A ring that rides on five ball bearings, driven from underneath by an N20 gearmotor through a spur gear meshing with a ring gear on the underside. 

![The printed parts](images/3d-prints.jpg)

<table>
<tr>
<td width="50%"><img src="images/motor-wiring.jpg" alt="Motor and wiring on the base plate"></td>
<td width="50%"><img src="images/battery-feet.jpg" alt="Battery box and feet on the underside"></td>
</tr>
</table>

I originally intended to put the batteries below the turntable, but ultimately decided to raise the acrylic base off the table using some feet (that's also where I hid the switch) and glued the battery box to the bottom.

Two outer housing halves hold the whole stack together. The tolerances are tight: you can hold the thing upside down and it just keeps running.

<table>
<tr>
<td width="50%"><img src="images/base-test.gif" alt="Turntable running during testing"></td>
<td width="50%"><img src="images/tracks-closeup.gif" alt="Close-up of the ring gear driving the turntable"></td>
</tr>
</table>

The track is printed separately and glued on top of the inner/outer cover. 

![Gluing the track down](images/glue-tracks.jpg)

## The Landscape

I painted the rails, added ballast (a wild mix of actual model train ballast and dirt from the garden) and covered the rest of the 3D printed surface with AK Terrains "Dark Earth"

<table>
<tr>
<td width="33%"><img src="images/ballast-tracks.jpg" alt="Ballasted track"></td>
<td width="33%"><img src="images/ballast-groundcover.jpg" alt="Ground cover applied"></td>
<td width="33%"><img src="images/ballast-groundcover-closeup.jpg" alt="Close-up of ballast and ground cover"></td>
</tr>
</table>

I used grass tufts and small flower patches, then mixed scatter and flocking for the greenery.

<table>
<tr>
<td width="50%"><img src="images/landscape01.jpg" alt="Landscaping in progress"></td>
<td width="50%"><img src="images/landscape02.jpg" alt="Landscaping nearly complete"></td>
</tr>
</table>

Last came the small stuff — NOCH sunflowers, tiny tulips, plus a few mushrooms and fern leaves.

<table>
<tr>
<td width="33%"><img src="images/sunflowers.jpg" alt="Sunflowers"></td>
<td width="33%"><img src="images/tiny-tulip.jpg" alt="A tulip on a fingertip"></td>
<td width="33%"><img src="images/mushrooms-fern.jpg" alt="Mushrooms and fern leaves"></td>
</tr>
</table>

![Track detail](images/track-detail.jpg)

## The Rolling Stock

I took apart an Egger-Bahn Nr. 5 steam locomotive, the smoke stack is a screw, and I designed a little block that fits the locomotive shell and is held by said smoke stack.

![Locomotive demo](images/locomotive-demo.gif)

<table>
<tr>
<td width="50%"><img src="images/locomotive.jpg" alt="The Egger-Bahn Nr. 5 opened up"></td>
<td width="50%"><img src="images/locomotive-base.jpg" alt="CAD model of the locomotive mounting block"></td>
</tr>
</table>

The locomotive and wagon sit on different length M3 standoffs which are bolted to the turntable (it really needs these countersunk screws, there's like a mm clearance between the screws and the motor mount).

<table>
<tr>
<td width="50%"><img src="images/gear-standoff-screws.jpg" alt="Ring gear and standoff screws"></td>
<td width="50%"><img src="images/standoffs.jpg" alt="Standoffs mounted to the turntable"></td>
</tr>
</table>

A train needs a wagon. I printed a base, added a balsa wood deck and a railing and weathered it a bit. It still comes off — there's a hole in the middle of the deck to reach the screw hidden underneath.

<table>
<tr>
<td width="50%"><img src="images/wagon01.jpg" alt="The balsa wagon deck"></td>
<td width="50%"><img src="images/wagon02.jpg" alt="Underside of the wagon showing the mounting hole"></td>
</tr>
</table>

On top goes this lovely Faller couple.

<table>
<tr>
<td width="50%"><img src="images/couple-closeup.jpg" alt="The bride and groom on the wagon"></td>
<td width="50%"><img src="images/almost-finished.gif" alt="Almost finished, under the acrylic cover"></td>
</tr>
</table>

## Done

![The finished diorama running](images/finished.gif)

<table>
<tr>
<td width="50%"><img src="images/side-view.jpg" alt="Side view of the finished diorama"></td>
<td width="50%"><img src="images/finished-holding.jpg" alt="The finished diorama with the cover on"></td>
</tr>
</table>

Nobody saw it coming, and the reactions were everything I hoped for. 

## Printed Parts

All files are in [`hardware/`](hardware). Mine all printed fine in PLA without supports.

| File | Qty | Notes |
|---|---|---|
| `base.stl` | 1 | The static bottom plate. Motor, switch and wiring mount here. |
| `rotating-base.stl` | 1 | The turntable itself, with the ring gear on the underside. |
| `bearing-clamp.stl` | 5 | Print a spare or two. |
| `bearing-washer.stl` | 5 | Same — print a spare or two. |
| `spur-gear.stl` | 1 | Use the smallest nozzle you own. |
| `cover-inner.stl` | 1 | Holds the stack together, unscrews for landscaping. |
| `cover-outer.stl` | 1 | Same. |
| `track-inner.stl` | 1 | Glued on top of the inner cover. |
| `track-outer.stl` | 1 | Glued on top of the outer cover. |
| `wire-port.stl` | 1 | Pass-through for the motor and LED wiring. |
| `feet.stl` | 4 | Print 5 if you're skipping the switch. |
| `feet-switch.stl` | 1 | The foot that houses the on/off switch. |
| `feet-spacer.stl` | 1 | Only needed for alignment, fits the hole I cut in the acrylic |
| `wagon.stl` | 1 | For you to build your own stuff upon |

## Everything Else

| Part | Qty | Notes |
|---|---|---|
| M3 threaded insert | 8 | |
| M3 `XXX` countersunk screw | 8 | Length still to measure. |
| `XXX` ball bearing | 5 | Size still to measure. |
| `XXX` bearing screw | 5 | |
| `XXX` bearing nut | 5 | |
| Short M3 screw | 2 | Clamps the motor. |
| N20 `XXX` gearmotor | 1 | Ratio unknown. |
| 2x AAA battery box | 1 | Runs on 1.5 V cells. |
| 1N4001 diode | 2 | In series with the motor to drop its speed. |
| Subminiature switch | 1 | I used a Thonk subminiature toggle. |
| LED fairy lights | 1 | Wired in parallel with the motor. |
| M3 standoffs | — | Various lengths, for the locomotive and the wagon. |
| Short M3 countersunk screws | — | For the wagon and standoffs. |
| Acrylic cake box | 1 | Not sure about the diameter, plus I drilled a big hole in the bottom. |

**Use whatever landscaping material you've got.** Ballast, soil, static grass tufts, scatter, flocking, small flowers, rocks. You could probably fit a little tree in the middle, if you don't need the hole for a stand.

## CAD Source

Both models are live on Onshape if you want to modify them.

> [!IMPORTANT]
> I use the free Onshape tier, which means every document I make is public by default and can't be used commercially. If you wanna use these files commercially, you'll need a paid plan.

- [Turntable base and housing](https://cad.onshape.com/documents/0534680432f928d55f5637b8/w/070eebe062f51dfbc72e6f51/e/2e5d7204ab34ca21dbeffe79)
- [Wagon](https://cad.onshape.com/documents/e7e2d45f9a1b3e202a1c16bf/w/f8e6280103d02880bf80f3d3/e/86b6b1e3a390ab58f4482ebc)

## License

[CC BY-NC-SA 4.0](LICENSE). Remix it, print it, post it — credit me, keep it non-commercial, and share your version under the same terms.

# The End
I hope this was a fun project and you got through with ease. If you're having difficulties at any point, please reach out. You can join my [Discord Server](https://glnnk.art/discord) for support.
I'd also love to see your creations! Tag me on Instagram or send me a photo to add here.
Check out my other stuff on [YouTube](https://glnnk.art/youtube) or [Instagram](https://instagram.com/glnnk.art).
You can [Buy me a coffee](https://www.paypal.com/paypalme/finnglink) if you've found my work helpful :)
