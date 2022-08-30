# Backend Markup Language (BML)

BML is a client based markup standard designed to provide a set of routines and properties in order
to accomplish a series of tasks through a dedicated software runtime. It's inspired by [YAML](https://en.wikipedia.org/wiki/YAML)
to keep things simple and human readable. It's client based and entirely depends on the software it
runs from. It can be extended via a scripting language to extract complex resources. You could
apprehend it as the opposite of a traditional markup language like XML or HTML that provides the
final output for a given task.

BML gives you a high level description of all the steps necessary for a given software to obtain
the desired output. So it contains intelligence and logic while depending on a comprehensive
software to be run. It's very simple to read and easy to learn, so that most educated people can
have access to it, understand what it does and improve it to fit their expectations. It's like a
blueprint as opposed of being a simple output or a comprehensive source code.

## Dedicated Language

BML is a dedicated language meaning it has to be extended with a concrete scenario in mind. For
instance the VBML is a BML based language that provides direct access to video resources on the
Internet.

It's often a good practice to prefix BML with an explicit letter that defines the expected scenario
when parsing and running its content. That's useful for defining a constrained scope and being
efficient at a given task, it's also easier to guess what it might do without extracting the
content itself.

Which makes it substantially different than other standards like linked data which proposes to
interlink generic data. BML is deeply singular and specific about a set of given tasks it's trying
to achieve efficently. It's also constrained and finite, which gives it a peculiar philosophical
stance.

## Script Language

BML comes with a simple and high level scripting language. It's based on a very simple syntax with
a focus on efficiency and simplicity. It enables the user to specify a set of routines and
properties according to what he wants to achieve with his program. It's entirely sandboxed meaning
it should not make a program crash no matter what the user writes in the BML input.

The scripting language is simple enough and could be used with a rudimentary knowledge about coding
practices. Which is supposed to empower end users to do more with their sofware, without learning
a comprehensive programming language.

## History

This standard was designed based on my practical experience at extracting video resources on the
Internet. Which requires dedicated scripting together with a client based software that retrieves
video resources on the Internet. It was intially designed with a [Video Browser](http://omega.gg/about/VideoBrowser)
in mind (like [MotionBox](http://omega.gg/MotionBox)). Then came the idea of having a base standard
that would allow other scenarios that are not necessarily related to video. For instance MBML for
music or EBML for ebooks.

## Sample

```
version: 1.0.0

string: Hello World

ROUTINE: |
    SET count 41
    RETURN (ADD count 1)
```

## Samples

- [duckduckgo.yml](https://github.com/omega-gg/backend/blob/master/duckduckgo.vbml): DuckDuckGo video search engine.
- [bittorrent.yml](https://github.com/omega-gg/backend/blob/master/bittorrent.vbml): BitTorrent video retriever.
- [youtube.yml](https://github.com/omega-gg/backend/blob/master/youtube.vbml): Youtube video retriever.
- [opensubtitles.yml](https://github.com/omega-gg/backend/blob/master/opensubtitles.vbml): OpenSubtitles subtitles retriever.
- [tmdb.yml](https://github.com/omega-gg/backend/blob/master/tmdb.vbml): TMDb cover retriever.

## Authors

- Benjamin Arnaud aka [bunjee](http://bunjee.me) | <bunjee@omega.gg>
