# common readme
**_Module consumers!_** Frustrated by each module having its own wildly unique README format? Annoyed by modules that omit critical sections like **API** or **Examples**? Stuck scrolling through API docs before you even know what the module does?

**_Module authors!_** Tired of making up your readme format every time you write it? Do you just want consistent readmes pre-populated with your module's name, description and license without worrying about the structure every time?

__________

What if there was a common format for the benefit of producers and consumers?

A _common readme_ for node modules.

This can save everybody time by adhering to 4 principles:

1. **No lock in.** No special formats or tooling; run common-readme once for pure vanilla markdown.
2. **No surprises.** Pull as many details out of package.json -- like name, description, and license -- as possible. No time wasted on configuration.
3. **Cognitive funnelling.** Start with the most general information at the top (Name, Description, Examples) and if the reader maintains interest, narrow down to specifics (API, Installation). This makes it easy for readers to "short circuit" and continue the hunt for the right module elsewhere without wasting time delving into unnecessary details.
4. **Consistency.** Your brain can scan a document much faster when it can anticipate its structure.

## Common format

__________

common-readme operates on the principle of cognitive funneling.

Ideally, someone who's slightly familiar with your module should be able to refresh their memory without hitting "page down". As your reader continues through the document, they should receive a progressively greater amount of knowledge. -- perlmodstyle

Here are some READMEs generated using common-readme:

- [collide-2d-aabb-aabb](https://github.com/hackergrrl/collide-2d-aabb-aabb)
- [goertzel](https://github.com/hackergrrl/goertzel)
- [twitter-kv](https://github.com/hackergrrl/twitter-kv)
 ([_Submit a pull request_](https://github.com/hackergrrl/common-readme/pulls) and add yours here!)

## Usage
With [npm](https://www.npmjs.com/) installed, run

`$ npm install -g common-readme`

`common-readme` is a command line program. You run it when you've started a new module that has a package.json set up.

When run, a brand new README is generated and written to your terminal. You can redirect this to README.md and use it as a basis for your new module.

``$ common-readme > README.m``

This brand new readme will be automatically populated with values from package.json such as name, description, and license. Stub sections will be created for everything else (Usage, API, etc), ready for you to fill in.

## Why?
<details>
<summary>This isn't a crazy new idea. Other ecosystems like Perl's CPAN have been benefiting from a common readme format for years. Furthermore:</summary>

1. The node community is powered by us people and the modules we share. It's our documentation that links us together. Our README is the first thing developers see and it should be maximally effective at communicating its purpose and function.

1. There is much wisdom to be found from the many developers who have written many many modules. Common readme aims to distill that experience into a common format that stands to benefit us all; especially newer developers!

1. Writing the same boilerplate is a waste of every author's time -- we might as well generate the common pieces and let the author focus on the content.

1. Scanning through modules on npm is a part of every node developer's regular development cycle. Having a consistent format lets the brain focus on content instead of structure.
</details>

## The Art of README
For even more background, wisdom, and ideas, take a look at the article that inspired common-readme:

Art of README.
Install
With [npm](https://www.npmjs.com/) installed, run

"npm install -g common-readme"
You can now execute the common-readme command.

Acknowledgments
A standard readme format for the Node community isn't a new idea. Inspiration came from many conversations and unrealized efforts in the community:

standard/standard#141
richardlitt/standard-readme
zwei/standard-readme
This, in addition to my own experiences evaluating hundreds of node modules and their READMEs.

I was partly inspired by the audacity of the honey-badger-don't-care efforts of standard.

I also did a great deal of Perl archaeology -- it turns out the monks of the Perl community already did much of the hard work of figuring out great READMEs and the wisdom around small module development well over a decade ago.

Thanks to @mafintosh, @andrewosh, and @feross for many long conversations about readmes and Node.

See Also
READMEs love readme!

License
ISC
| Проверка | таблицы |
| :-------| -----:|
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |
