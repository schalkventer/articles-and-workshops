# Article

## The case for Web Workers post-2020

### A brave new web

**From where I'm standing it seems that JavaScript Web Workers occupy an interesting space as we head into a post-2020 web development landscape.**

In some respects 2020 and after is very similar to the last decade. JavaScript continues it's endless march \(either to your delight or horror\) to all corners of our devices and world, even making it's way to outer-space by means of [NodeJS now running in NASA spacesuits](https://openjsf.org/wp-content/uploads/sites/84/2020/02/Case_Study-Node.js-NASA.pdf). Indeed, JavaScript seems to be eating the world, and the web itself is no exception.

Four years ago, Ronan Cremin, a sitting member on the W3C reported \(to everyone's mixture of amusement and horror\) that the average size of a website in 2016 is now the same as the acclaimed 1993 video game, Doom:

> "Recall that Doom is a multi-level first person shooter that ships with an advanced 3D rendering engine and multiple levels, each comprised of maps, sprites and sound effects. By comparison, 2016’s web struggles to deliver a page of web content in the same size. If that doesn’t give you pause you’re missing something. So where does this leave us?"

Luckily the internet has gotten faster right?

To a certain degree yes. Even my parents are now streaming daily, on-demand, HD video content to their television. This seems like a pretty big leap from my early youth where I left my computer on overnight just to download a single MP3 file \(given that the connection didn't drop\).

Unfortunately our problem isn't size _per se_.

It is that size is often a proxy for something more intangible. The amount of time your browser spends parsing and executing HTML, CSS and JavaScript. Furthermore, between these three languages, it is turns out that one plays an astronomically bigger role in detoriating web performance. In 2018, Google's Chrome enigeering manager, Addy Osmani, published an article, titled [_The Cost Of JavaScript In 2018_](https://medium.com/@addyosmani/the-cost-of-javascript-in-2018-7d8950fbb5d4)_._ Concluding that:

> "Byte-for-byte, JavaScript is still the most expensive resource we send to mobile phones, because it can delay interactivity in large ways. \[...\]
>
> As much as I love JavaScript, it’s always the most expensive part of your site."

In theory, the case for web performance should already be well established.

It has been covered and studied ad neasum by teams and exports over the last 5 years. A cursory Google search should bring up a plethora of reports: from Pinterest's report that they were able increase sign-up by 15% when they reduced perceived wait times by 40%, to the BCC's findings that they lost an extra 10% of users for every additional second their site took to load, and Google finding that 53% of mobile sites bouncing when the site took more than 3 seconds to load.

### The webpage as software

**Which brings me to the part that I find interesting:**

If you've been doing any type of front-end development over the last decade, you will aware of a radical shift that has started surfacing it's, often-hated by the old-guard, head. There is an increasing amount of developers that are essentially now building full-blown JavaScript-powered software right inside our browsers. So much so that Chris Coyier, of Codepen and CSS-Tricks fame, penned an extremely widely shared article last year, titled The Great Divide, in which he remarks that:

> Two "front-end web developers" can be standing right next to each other and have little, if any, skill sets in common. That's downright bizarre to me for a job title so specific and ubiquitous. I'm sure that's already the case with a job title like designer, but front-end web developer is a niche within a niche already."

He also directs us to a direct quote from Jay Freestone:

> "Over the last few years, we’ve started to see a significant shift in the role of the front-end developer. As applications have become increasingly JavaScript-heavy there has been a necessity for front-end engineers to understand and practice architectural principles that were traditionally in the domain of back-end developers, such as API design and data modeling."

Whether this is a good thing or a bad thing, I'm certainly not qualified to answer. However, from where I'm standing I concur with Chris' sentiment that this is infact _a thing_. 

This is quite a step for this humble language that was as initially created in 1993 to be a simple scripting language.

### How did we get here?

**I mentioned Doom above, so it is only fitting that we go all the way back to its release date:Almost two decades ago**

Jurrassic Park just won 3 Academy Awards and a Grammy. It easily surpasses E.T. as the highest grossing film of all time. In my home country of South Africa, our first post-apartheid interm constitution is approved and implemented by parlament. Furthermore, and perhaps less noteworthy at the time, the first GUI-driven web browser called Mosiac is released by Netscape. 

Prior to this, browsing the web was essential an exercise in the command-line, not unlike running `npm start` or `cat README.md`. However, being able to view the web markup through a GUI application indistinguishable from any native Windows 3.1 or Mac application ended up setting cogs in motions that seem to only be coming to head in our current decade.

Whereas the constraints of the command-line brought with it certain expectations around presentation, having the World Wide Web delivered in the same manner as native OS-level applications meant that user were expecting suddenly expecting a lot of the same presentational quirks.

