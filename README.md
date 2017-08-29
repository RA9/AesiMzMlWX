# WebGL graphic mockup for The TGS Team's setup
This repo is intended for the TGS/FCC team, to introduce the project.
Please contact post an Issue if you would like to be involved.
It is at this point you may offer insight and technical understanding to become involved.
# OVERVIEW
I am getting desperate at almost my first year of learning to be a developer to build a resume. I found a Graphics shop local to me, that 1. Did not have a working website. 2. Is grateful for the assistance, I believe from his prior hosting that he was royally screwed. And 3. Has an increadable reputation as member of the community, and near perfect marks of taking care of his clients since... my notes are in the car. Quite some time though. [<~ ammend this]

Noone offers a webGL depth map for product mockup, and I want to change that. At best they do alpha blending.
He does Banners, Cards, Signs, and Shirts. I plan to collect a base image to create the mesh, blanks, and maps.
A person comes to the site wanting to have something made, they offer some details to create an account, the file system must be exposed to store a users images, I'd like to support single color masks from png & sgv. Possibly Jpeg, to the exclusion of screen print shirts 6 color index. Enforce 300ppi on the source. Offer translation, xy control, and resizing. An object model to communicate with the shop these characteristics for reconstruction. Shirts are really THE most complicated model of the project, and the starting point.
Screenprint:
Select(material(color, sizes[])), blank loads
User drops in their images using layers (sent to users folder and populated to the dom via image tags is the only route I've found for canvas but a localstorage/webworker solution is desireable) and .pngs/.svgs/fonts as masks. OR Image colors are indexed and options are offered to flatten extra colors and slice to layers. position, scale, "wow that looks real, I hope it actually looks like that".
User calls and say they wanted to start project "########", offers a time to come in, arrangements are made, and they are updated on the status. I don't presume to know the business model but PCIDSS can be avoided in this manner and I don't think they could handle an interstate scale influx, who could? but preparing them for the ability to scale up, would presumably indebt any reasonable proprietor to those that made it possible.

The project sits in the users directory, they can save it, edit it, export it, delete it, eat it I don't care and that is exposed to the site operator at cpanel upon user prompt to prepare it. XSS, man in the middle, injection, the usual defensive fronts when dealing with this, I am not the expert and know when to ask for help. System integrity at the user, LAMP, and production are vital. Not trying to get him hacked or shut off his computers, liabilities, its peoples livelyhoods. I saw a Dutch Bros cup but I'm pretty sure they're not raking in a massive profit.

If TGS had the system in place to handle the legal responsibiliies of taking online payments out of state, holds, bookkeeping, and could pick and choose the most interesting projects as schedule allowed. I think that'd be an amazing situation to create a few extra jobs.

The problem we are solving is the difficulty of having to pay a designer to clean up or mockup for production. Its time intensive, expensive in turn and you want 100% assurance that the user is clear on how to get what they need and happy, without consulting your wallet again.

I think this has the potential to blow away everyone else in this for a downpayment of time and energy and see it as liscensable from our team as a unit if not a really good way to put something flashy-shiney on a resume. Realisticly projects need more than one person anyways. Lets see if we end up being friends and mentors to each other.

Feel free to PM, push, or issue any input or questions you have or related experience, I'd prefer to keep any server configurations off the public repo, PM for the current link and details. I'm just rambling now. -etisdew
