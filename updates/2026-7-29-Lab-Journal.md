Homelab Journal Update — One Year Later

It's been over a year since my last journal update, and the lab has changed dramatically. My last post documented configuring a single D-Link smart switch. Since then, the project has grown from a small networking experiment into a self-hosted environment with dedicated compute and storage, enterprise networking equipment, structured cabling, and multiple production services.

Looking Back

When I started, my goal was simply to learn networking. I had a consumer router, a D-Link smart switch, and a desire to understand concepts like VLANs and managed switching.

That first switch taught me the basics of subnetting, switch management, and Layer 2 networking. It also sparked a much bigger project than I originally planned.

Infrastructure Growth

Over the past year, nearly every part of the lab has changed.

The environment now consists of dedicated compute and storage servers instead of a single machine running everything. Docker workloads—including Jellyfin, Immich, and the Arr stack—run on a dedicated compute node while a separate storage server hosts the media library and shared data.

After moving into a new home, I terminated every existing CAT5e run, installed a patch panel, and brought wired networking to every room. Later, I upgraded to a used enterprise Ruckus managed PoE switch, installed a ceiling-mounted access point, and began replacing consumer networking equipment with enterprise hardware.

Documentation

One goal this year was improving documentation alongside the infrastructure.

Rather than maintaining a single network diagram, I began documenting the evolution of the lab through versioned topology diagrams. Each revision captures a major milestone, making it easier to see how the architecture has changed over time instead of only showing its current state.

What I've Learned

The biggest lesson this year wasn't about any specific technology—it was about planning.

Separating compute from storage simplified maintenance. Enterprise networking equipment introduced capabilities that consumer hardware couldn't provide. Structured cabling made future upgrades significantly easier. Most importantly, documenting every major change forced me to think through design decisions before implementing them.

Looking Ahead

The lab is still a work in progress. Upcoming projects include implementing VLAN segmentation, expanding automation, improving monitoring, and continuing to document every major milestone as the environment evolves.

Looking back at where this started, it's rewarding to see how far the project has come—and even more exciting to see how much there is still left to learn.
