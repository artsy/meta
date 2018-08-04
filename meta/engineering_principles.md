# Engineering Principles

We have [company values](what_is_artsy.md), and are working on our shared values with design and product. However,
when we make decisions on what and how to do engineering we need guiding principals. Things that make Artsy's
development culture unique and drive us to do great work.

### Open Source by Default

We consider the data and relationships that make Artsy difficult to copy, code only represents the past and
close-to present. A code project should start as open, then move to closed if there are valid business needs that
need to be hidden.

Working in the open allows individual to retain their work and ideas post-Artsy. We can share the exact problem we
see with others, and provide great high ways to teach by direct reference.

Expectations for OSS apps are different than OSS libs, an app has little-to-no desire for community contributions.
Instead it's more of a reference tool. Tools and libraries we can build communities around, but most projects don’t
get large enough for their stewardship to become burdensome.

- Examples:

  - artsy/meta
  - artsy/force
  - artsy/eigen
  - artsy/emission

- Further Reading:

  - https://artsy.github.io/series/open-source-by-default/
  - https://ashfurrow.com/blog/open-source-ideology/
  - https://code.dblock.org/2015/02/09/becoming-open-source-by-default.html
  - https://www.objc.io/issues/22-scale/artsy/

### Own Your Dependencies

Take the best dependencies to fit your problem and make them better. Rather than try re-invent the wheel, give time
to take the best dependencies and make them fit into our use cases. We’re not the biggest team, so the most value
for someone's time can be achieved by writing the glue code between larger projects.

Consider all of the pieces related to your app as being part of your work. E.g. just like you would consider
working on an API when you're doing front-end work, making sure that React or TypeScript behave like we'd want is
an important part of product work. It's another part of our stack.

Aim to be a trusted contributor to the communities surrounding your work, communicate clearly, publicly and be
empathetic to the priorities of others.

- Examples:

  - Grape
  - CocoaPods
  - The Artsy Omakase

### Incremental Revolution

Introduce new technologies slowly and incrementally. Avoid re-writes. Build tools to allow hybrids of different
types of technology when possible. Sometimes you need to make a big leap, but aim to approach them incrementally.

Explore bleeding-edge technologies on projects with an end-date and can become safely classed "done". These can be
used to inform decisions on long-running projects. Run spike projects when trying to settle between technology
trade-offs.

- Examples

  - Emission / Reaction
  - Stitch
  - Metaphysics

- Further Reading

  - Building a Pod Library http://artsy.github.io/blog/2018/04/17/making-a-components-pod/
  - http://artsy.github.io/blog/2017/09/05/Modernizing-Force/

### Minimal Viable Process

As a team grows, so does the need for processes. Find ways to add process without additional work. Build automated
tools to help others. Use systems like RFCs to broaden the availability of information on process changes.

For meetings over 2-3 people, provide agendas and make as many people optional as possible. We've seen great
success on automation via documentation for recurring meetings.

- Examples

  - Danger
  - Peril
  - RFC Process
  - artsy/meta

- Further Reading

  - http://artsy.github.io/blog/2018/05/25/support-process/
  - http://artsy.github.io/blog/2017/09/04/Introducing-Peril/
  - http://artsy.github.io/blog/2018/02/02/artsy-apogee/

### Scale your Impact

We built an outsized reputation for our size as an engineering team via the above principals. This gives the
ability to move local impact to larger impact.

Consider ways in which you can expand the scope of impact for your time:

- Avoid private messaging when you could communicate in a public channel
- Team presentations could be worked for public consumption
- Internal notes could be turned into blog posts
- Documentation on teams and processes could be open for others to reference and learn from
- A regular meetup could be converted into a franchisable system for others to replicate

The small improvements eventually add up so that you can feel like you're doing industry level work as a part of
building Artsy.

- Examples

  - Artsy x React Native
  - JavaScriptures
  - Learn Swift at Artsy
  - Artsy Blog
  - artsy/meta
  - Peer Labs
  - http://artsy.github.io/blog/2015/04/03/artsy-engineering-compensation-framework/

### De-siloing Engineers

Provides people the ability to work in many spaces and not feel blocked by another team. Common languages, common
terminology and common ideas. There's definitely space for experimentation, but within a shared framework. The aim
is not to stifle creativity, but increase individual scope.

- Examples

  - Moving to React Native
  - Teach Swift via Swift at Artsy
  - Migrating Admin tools to shared Front-End stacks
  - Consolidated Analytics schema
  - Dev Swap which switches teams and responsibilities

- Further Reading
  - https://www.youtube.com/watch?v=hlLhtWLghGA
  - http://artsy.github.io/blog/2017/09/11/DevSwap/
  - http://artsy.github.io/artsy-x-react-native.html
