---
layout: post
title: "Fires"
---

* table of contents placeholder
{:toc}

# Overview

Most EUCs use lithium-ion batteries, which, unfortunately, can ignite into
intense fires if misused. Electroheads provides an excellent overview in this
video:

<iframe width="560" height="315" src="https://www.youtube.com/embed/TPVVtTACQhE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Thankfully these fires are rare. An organized effort to catalog fires at [the
Electric Unicycle
Forum](https://forum.electricunicycle.org/topic/21506-fire-history/#comment-353291)
has only found 58 as of November 2022.

In the absence of important safety certifications like UL 2272, it's important
to buy EUCs from reputable manufacturers and distributors who will do basic
safety checks.

You can further ensure your safety by following a few simple charging rules,
having a fire detector nearby, monitoring your wheel's voltage levels, and
inspecting your batteries yearly. A fireproof container or fire extinguisher
tested specifically for lithium-ion battery fires can also help.

A couple of wheels are sold with lithium iron phosphate (LiFePO4)
batteries. These batteries will not have the same thermal runaway as regular
lithium-ion batteries, so the fire risk is removed.

# How to charge lithium-ion battery packs

There are just a few things to do regarding charging.

First, balance your batteries regularly. This implies fully charging the battery
and leaving it on the charger for a few more hours. When the pack is nearly
fully charged, it will automatically start balancing the cells. Onewheel expert
Mario Contino explains in detail here (this generally applies to both Onewheels
and EUCs):

<iframe width="560" height="315" src="https://www.youtube.com/embed/Bdbx2Wq-xSw?start=1084" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Second, don't allow the batteries to be depleted. The "0%" battery level shown
by the apps is a safe level, but if the battery is neglected for an extended
amount of time and goes below that level ("overdischarge"), the battery may be
badly damaged. Don't attempt to charge it. In this case you should either take
the batteries to an experienced battery repair person to see how bad the damage
is, or just recycle them.

Third, only use chargers compatible with your wheel. Using a charger with a
higher voltage ("overcharging") will likely start a fire.

# When to worry

In general, it's a good idea to check that the battery charges as expected. It's
also a good idea to inspect the battery for damage after a hard impact, or once
a year. Here are some warning signs to look out for:

- battery doesn't charge
- battery voltage drops much faster than usual
- battery charges, but not fully
- battery has been exposed to water
- battery is rusty or deformed

If the battery doesn't charge, or the voltage/battery level drops much faster
than usual, this indicates that the battery has a short. If the battery charges,
but not fully, this could indicate that cells are damaged or that the cells are
imbalanced. Water often causes a short if it gets into the battery. And physical
damage to the battery can cause a short. Any of these are a cause to consider
the battery a fire hazard, and the battery should probably be recycled.

Pre-production wheels and EUC models with a history of fires call for extra
caution, for obvious reasons.

Lithium-ion batteries should not be thrown away. In the US, they can be recycled
at Home Depot, Best Buy, Staples, and other stores. See [the EPA's
guide](https://www.epa.gov/recycle/used-lithium-ion-batteries) for more info.
{: class="warning"}

# How to stop a fire

Because lithium-ion battery fires are difficult to extinguish, it's important to
use products that have been rigorously tested for lithium-ion battery
fires. (Mario Contino shows how one poorly tested product fails in a video
[here](https://youtu.be/CXXBDq8vp2A).)

Submerging a wheel in water is a cheap and low-tech way of stopping a fire, if
you can find a safe way to do it. I would only consider a fireproof sack or case
for smaller battery packs, because containers made for larger battery fires are
expensive.

In my opinion, an F-500 EA fire extinguisher is the most practical way to stop a
fire for most wheels.

Battery fires often reignite after being extinguished with traditional
extinguishers or water.
{: class="warning"}

Lithium-ion battery fires release toxic gases, including hydrogen fluoride and
carbon monoxide.
{: class="warning"}

## Submerge in water

Unlike many other fires, spraying water will not stop a lithium-ion battery
fire. Instead, you need to *completely submerge* the batteries in water. When
submerged, the water cools the batteries enough to end the thermal runaway. (And
when removed from the water, the batteries can reignite again.)

## Fireproof sacks/cases

There are lots of fireproof lithium-ion bags and containers, though most are
meant only for storing battery packs rather than an entire wheel (and usually
smaller battery packs like you might see for a
drone). [FireSak](https://firesak.com/) is one made for EUC riders. I'm not
fully convinced by the FireSak tests, so I won't endorse it, but it may control
some fires, especially for smaller battery packs.[^firesak]

[^firesak]: [Here](https://youtu.be/CUeSSEoxQ1E)'s a video of a FireSak test
    from Ginger On Wheels, who sells the FireSak. Meanwhile, [this
    video](https://youtu.be/WFLHCIbDJAw?t=941) from Go George Go captures a real
    Begode Monster Pro fire in a FireSak. (It does not go well.) The FireSak
    testing does not seem comparable to a bad EUC fire.
	
<!-- something about Zarges when they start offering different BatterySafe sizes
-->
	
CellBlock FCS makes much more robust [battery
cases](https://cellblockfcs.com/large-lithium-ion-battery-cases/) that can
contain larger battery fires. The downside is that they're expensive (thousands
of dollars).

## Fire extinguishers

Traditional fire extinguishers aren't effective against lithium-ion battery
fires, but there are alternatives.

F-500 EA, AVD, and Imprex C are all extinguisher types that work specifically
against lithium-ion battery fires. They're sold under different brand names in
different countries. Of these, F-500 EA seems to require the least volume of
extinguisher per watt hour, so I recommend it for larger battery packs. In the
US, F-500 EA extinguishers can be bought directly from [Hazard Control
Technologies](https://hct-world.com/products/equipment/fire-extinguishers/).

[CellBlockEX](https://cellblockfcs.com/cellblockex/) is a dry granulate
extinguisher that can stop thermal runaway. Rather than using a hand-held
extinguisher, you set a bag of this on your unicycle so that it will be released
if a fire starts. In an email, they recommended "2-3 cubic inches of CellBlockEX
per 1 Wh," which translates to 2 or 3 of their 55 liter bags for a larger EUC.

Class D fire extinguishers are not effective against PEV fires. These
extinguishers are for *metallic* lithium, not the *ionic* lithium in PEV
batteries.
{: class="warning"}

# (Lack of) safety certifications

UL 2272 is the relevant battery safety standard for e-mobility devices like
hoverboards and e-scooters, and, presumably, EUCs. It was created in response to
hoverboard fires, and requires a variety of common-sense tests of the vehicle
and battery system.[^ul2272]

[^ul2272]: For more info about UL 2272, see [UL 2272 and the Safety of Personal
    e-Mobility
    Devices](https://collateral-library-production.s3.amazonaws.com/uploads/asset_file/attachment/12042/10414_HoverboardSafety_V2R6_FINAL.pdf).

As of November 2022, I'm not aware of any EUCs with UL 2272 certification. In
the absence of this certification, it's important to buy EUCs from reputable
manufacturers and distributors who will do basic safety checks. Among other
things, distributors generally handle replacements for defective parts, and some
ship wheels with safer battery packs than you'd get directly from the
manufacturer.

For the batteries themselves, there's both UL 2271 and CE certification (which
requires compliance with IEC 62133-2). UL 2271 is more comprehensive, and I
don't know if any EUC batteries currently have it. Most if not all EUC batteries
will have CE certification because it's required to sell the batteries in
Europe. This is a meaningful certification that includes tests for crushing,
mechanical shock, overcharging, short circuits, etc.
