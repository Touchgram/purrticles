# Purrticles public samples and issues
This repo is the public storage of all samples and issues for the Purrticles app.

The repo was created to accompany Purrticles v1.0 because it has a developer focus and we want to make samples available as well as give you an [issue tracker][p2] for adding requests, or **voting on the priority** of our [suggested enhancements][p4] or [bugs][p5]. 

## About Purrticles
[Purrticles][p1] is usable as a standalone design and developer tool that can create code and other assets to do with particles. It is easier to use than the XCode particle design interface because it understands field defaults and lets you see just the _Applied_ parameters.

V1.0 is limited to SpriteKit code. 

Purrticles acts as a companion to Touchgram (below) - you can directly copy particle definitions from Purrticles and use them in Touchgram v1.3.6 onwards.

Future versions will provide [more options][p4] for exploratory design and other game and UI engines.

### Texture Images
A particle emitter often uses a _texture_ to specify the basic shape for each particle.

If you don't specify a texture, it defaults to a simple rectangular shader, for now a solid block of colour.

Adding your own images is [not yet possible][p6]. A near-future version of Purrticles will add it.

See the list of bundled [textures](./textures/README.md) from which you can copy the files.

### Mac version
A Mac version of Purrticles was developed in parallel with the iPhone and iPad versions. It is coming soon in August 2025, as our entrant in the [Shipaton 2025][sh1] competition from [Revenue Cat][rc1].

If you save your documents in iCloud, the purrticles folder there will let you open from iOS or Mac.


## Developer notes
Purrticles was developed from the start as a pure SwiftUI app which hosts use of SpriteKit.

A few interesting challenges have been met along the way, some of these have been explored with public test projects
- [SwiftUI][gh1]
- [SpriteKit][gh2] especially [resizing][gh3] and [video export][gh4].

### Matching XCode Features
The interface of Purrticles v1.0 was obviously designed to match the SpriteKit particle editor in XCode as closely as possible.

Any features of that editor which are not yet in Purrticles are therefore labelled as [bugs][p5]. As of v1.0 shipping, there are no other known bugs in the app (that was a _lot_ of testing and fine-tuning especially on different iOS versions, thanks to SwiftUI's _interesting evolution_).

As of v1.0.2, Purrticles already goes past the XCode editor, with features:
- Applied tab showing only the _non-default_ parameter settings, making it easier
- Full tab providing an interface to edit settings such as RGBA color ranges
- Generating Swift code (you can save a `.sks` file in XCode but the visual editor doesn't give you source code).

  
## About Touchgram
[Touchgram][tg1] is a platform for creating messages that respond to touch. It's an add-on that dramatically expands what kind of content you can send through iMessage.

It runs on top of SpriteKit and uses particle effects:

1. As feedback to follow where you touch, (eg: flames as you trace a rune) and
2. as effects on composed pages (eg: Snow on a Christmas card).

It's currently available on the [app store for iMessage][tg4].

## Terms and Privacy
A common set of legal terms apply to Touchgram, Purrticles and any other helper tools or associated products we release.

We try very hard to preserve your privacy, so **all use of Touchgram to make content is anonymous.** Apple's iMessage technology helps here - the Touchgram code is not able to see any details identifying who is sending a message or the recipients. 

Our core terms are fairness, just behave decently and don't rip-off other creators. Oh, and create great, weird and gorgeous stuff!

- [Privacy][tg2]
- [Terms for Use][tg3]


[tg1]: https://www.touchgram.com
[tg2]: https://www.touchgram.com/privacy
[tg3]: https://www.touchgram.com/terms
[tg4]: https://apps.apple.com/us/app/touchgram-for-imessage/id1447336478
[p1]:  https://www.touchgram.com/purrticles
[p2]: https://github.com/Touchgram/purrticles/issues
[p3]: https://www.reddit.com/r/purrticles/
[p4]: https://github.com/Touchgram/purrticles/issues?q=is%3Aissue%20state%3Aopen%20label%3Aenhancement
[p5]: https://github.com/Touchgram/purrticles/issues?q=is%3Aissue%20state%3Aopen%20label%3Abug
[p6]: https://github.com/Touchgram/purrticles/issues/15

[gh1]: https://github.com/AndyDentFree/swiftgooey
[gh2]: https://github.com/AndyDentFree/SpriteKittenly
[gh3]: https://github.com/AndyDentFree/SpriteKittenly/tree/master/ResizingRemit
[gh4]: https://github.com/AndyDentFree/SpriteKittenly/tree/master/VidExies

[rc1]: https://www.revenuecat.com/
[sh1]: https://www.shipaton.com/