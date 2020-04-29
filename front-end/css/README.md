# CSS

## Notes

* ID's are unique.
  * Each element can have only one ID.
  * Each page can have only one element with that ID.
* Classes are NOT unique.
  * You can use the same class on multiple elements.
  * You can use multiple classes on the same element.
* [The DOM is just a tree of objects. CSS selects parts of that tree and applies attributes to those objects. It's all just code, it's just a shorthand for adding a bunch of attributes to a bunch of objects.](https://www.reddit.com/r/javascript/comments/9jpvon/do_you_even_need_a_css_framework/)
* [Always design your CSS format from the inside out](https://www.quora.com/What-is-the-best-way-to-prevent-divs-from-overlapping-I-have-3-divs-The-First-div-changes-its-size-and-overlaps-the-second-one-which-is-a-set-of-images)
  * format the elements within their container so that they look correct regardless of the size of the container.
  * similarly format those containers within their own containers
  * repeat until `<body>` is the containers
  * never use absolute widths \(px, in, cm, etc.\) for anything
* body tag takes up the whole width and height of the browser screen.

## Links

* [Code guide by @mdo](http://codeguide.co/)
* [CSS Reference](https://cssreference.io/)
* [CSS Blocks](https://github.com/linkedin/css-blocks) - High performance, maintainable stylesheets.
* [Opticss](https://github.com/linkedin/opticss) - CSS Optimizer.
* [CSS Puns](https://saijogeorge.com/css-puns/)
* [Magic of CSS](https://adamschwartz.co/magic-of-css/)
* [Min](https://github.com/owenversteeg/min) - World's smallest \(995 bytes\) CSS framework.
* [Emotion](https://emotion.sh/) - Performant and flexible CSS-in-JS library.
* [Why We Use Styled Components at Decisiv](https://medium.com/@_alanbsmith/why-we-use-styled-components-at-decisiv-a8ac6e1507ac)
* [The case for CSS modules - Mark Dalgleish](https://www.youtube.com/watch?v=zR1lOuyQEt8)
* [Michael Chan - Inline Styles: themes, media queries, contexts, & when it's best to use CSS \(2015\)](https://www.youtube.com/watch?v=ERB1TJBn32c)
* [Understanding the CSS box model for inline elements](https://hacks.mozilla.org/2015/03/understanding-inline-box-model/)
* [astroturf](https://github.com/4Catalyzer/astroturf) - An "artificial" css-in-js for those that want it all.
* [Pesticide](https://chrome.google.com/webstore/detail/pesticide-for-chrome/bblbgcheenepgnnajgfpiicnbbdmmooh) - Kill your CSS layout bugs. \([Code](https://github.com/mrmrs/pesticide)\)
* [Spectre](https://github.com/picturepan2/spectre) - Lightweight, Responsive and Modern CSS Framework.
* [Tachyons](https://github.com/tachyons-css/tachyons) - Functional CSS for humans.
* [CSS Animation 101](https://github.com/cssanimation/css-animation-101#readme)
* [Understanding static and relative positioning](https://webplatform.github.io/docs/tutorials/static_and_relative_positioning/)
* [Tailwind utility-first CSS framework](https://tailwindcss.com/docs/what-is-tailwind/)
* [CSStype](https://github.com/frenic/csstype) - Strict TypeScript and Flow types for style based on MDN data.
* [normalize.css](https://github.com/necolas/normalize.css) - Modern alternative to CSS resets.
* [Julia Muzafarova CSS Pens](https://codepen.io/miocene/)
* [CSS Modules](https://github.com/css-modules/css-modules) - Documentation about css-modules.
* [nano-css](https://github.com/streamich/nano-css) - CSS-in-JS library that you can actually use in production. Motto of nano-css is simple: create the smallest possible CSS-in-JS library and provide all features of any other library through addons.
* [Why I Write CSS in JavaScript \(2019\)](https://mxstbr.com/thoughts/css-in-js/)
* [Styled System](https://github.com/jxnblk/styled-system) - Responsive, theme-based style props for building design systems with React.
* [Rebass](https://github.com/rebassjs/rebass) - React primitive UI components built with styled-system..
* [TypeStyle](https://github.com/typestyle/typestyle) - Making CSS type safe.
* [The Three Tenets of Styled System \(2019\)](https://jxnblk.com/blog/the-three-tenets-of-styled-system/)
* [CSS Scan Chrome Extension](https://getcssscan.com/) - Instantly inspect and copy computed CSS.
* [DropCSS](https://github.com/leeoniya/dropcss) - Simple, thorough and fast unused-CSS cleaner.
* [CSS Standardization - The State of the Web with Jen Simmons \(2019\)](https://www.youtube.com/watch?v=TQ7NqpFMbFs)
* [Water.css](https://github.com/kognise/water.css) - Just-add-css collection of styles to make simple websites just a little nicer.
* [Loaders.css](https://github.com/ConnorAtherton/loaders.css) - Delightful and performance-focused pure css loading animations.
* [Artem Sapegin: Custom CSS is the Path to Inconsistent UI \(2018\)](https://www.youtube.com/watch?v=t5VTLwAias8)
* [Learn CSS Layout the pedantic way](http://book.mixu.net/css/) \([Code](https://github.com/mixu/cssbook)\)
* [CSSFX](https://cssfx.dev/) - Beautifully simple click-to-copy CSS effects.
* [CSS Working Group Editor Drafts](https://drafts.csswg.org/)
* [CSS Houdini Experiments](https://css-houdini.rocks/)
* [CSS-Only Chat](https://github.com/kkuchta/css-only-chat) - Truly monstrous async web chat using no JS whatsoever on the frontend.
* [Theme UI](https://github.com/system-ui/theme-ui) - Build consistent, themeable React UIs based on design system constraints and design tokens.
* [Nice comment on problems & solutions to writing CSS](https://github.com/tachyons-css/tachyons/issues/12#issuecomment-309565525)
* [tachyons tldr](https://tachyons-tldr.now.sh/#/classes)
* [A real-life journey into the opinionated world of 'utility-first' CSS \(2018\)](https://www.youtube.com/watch?v=2-q4asoHUqU)
* [CSS and Scalability \(2016\)](https://mrmrs.cc/writing/scalable-css/)
* [cssdb](https://cssdb.org/) - Comprehensive list of CSS features and their positions in the process of becoming implemented web standards.
* [Relearn CSS layout: Every Layout](https://absolutely.every-layout.dev/) - How to better harness the built-in algorithms that power browsers and CSS. \([HN](https://news.ycombinator.com/item?id=20196061)\) \([Blog](https://every-layout.dev/blog/algorithmic-design/)\)
* [Basscss](https://github.com/basscss/basscss) - Low-level CSS Toolkit.
* [PurgeCSS](https://github.com/FullHuman/purgecss) - Remove unused css.
* [CSS Remedy](https://github.com/mozdevs/cssremedy) - Start your project with a remedy for the technical debt of CSS.
* [CSS Camera](https://github.com/WoodNeck/css-camera) - New way to see a web page with CSS3 3D transform.
* [Devices.css](https://github.com/picturepan2/devices.css) - Modern devices in pure CSS.
* [clean-css](https://github.com/jakubpawlowicz/clean-css) - Fast and efficient CSS optimizer for Node.js platform and any modern browser.
* [25 Days of CSS Animations: Teaching Myself CSS through Motion Design \(2019\)](https://dev.to/acupoftee/25-days-of-css-animations-teaching-myself-css-through-motion-design-4l10)
* [TACHYONS theme editor](https://components.ai/tachyons-theme/)
* [Starter files, final projects and FAQ for Advanced CSS course](https://github.com/jonasschmedtmann/advanced-css-course)
* [Pure CSS – Lace](https://diana-adrianne.com/purecss-lace/) \([HN](https://news.ycombinator.com/item?id=21440508)\)
* [Pure CSS Drawing Essentials](https://diana-adrianne.com/how/) - Top 5 CSS properties I rely on to produce Pure CSS art.
* [Artem Sapegin: Say Hello to Box, Flex and Stack: Layouts in the Component Era \(2019\)](https://www.youtube.com/watch?v=zvuKuFgp96o)
* [CSS Utility Classes and "Separation of Concerns" \(2017\)](https://adamwathan.me/css-utility-classes-and-separation-of-concerns/) \([HN](https://news.ycombinator.com/item?id=21553496)\)
* [Роман Дворнов — CSS definition syntax \(Russian\)](https://www.youtube.com/watch?v=8kjE1n6mQ2s)
* [The Power \(and Fun\) of Scope with CSS Custom Properties \(2019\)](https://css-tricks.com/the-power-and-fun-of-scope-with-css-custom-properties/)
* [CSS Architecture for Modern JavaScript Applications \(2019\)](https://www.madebymike.com.au/writing/css-architecture-for-modern-web-applications/?utm_source=CSS-Weekly&utm_campaign=Issue-388&utm_medium=email)
* [Browser Default Styles](https://browserdefaultstyles.com/)
* [The box model is not layout \(2019\)](https://kilianvalkhof.com/2019/design/the-box-model-is-not-layout/)
* [MDN CSS Layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout)
* [Smooth CSS shadows generator](https://brumm.af/shadows)
* [CSS Layout](https://csslayout.io/patterns) - Collection of popular layouts and patterns made with CSS. \([Code](https://github.com/phuoc-ng/csslayout)\)
* [CSS Protips](https://github.com/AllThingsSmitty/css-protips#readme) - Collection of tips to help take your CSS skills pro.
* [Focus Overlay](https://github.com/mmahandev/FocusOverlay) - Library for creating animated overlays on focused elements.
* [Six Questions to Understand the CSS Box Model \(2017\)](https://medium.com/launch-school/https-medium-com-dembasiby-understanding-the-css-box-model-b005a82593a6)
* [High-level advice and guidelines for writing sane, manageable, scalable CSS](https://cssguidelin.es/)
* [CSS Circles \(2019\)](https://cloudfour.com/thinks/css-circles/)
* [CSShake](https://github.com/elrumordelaluz/csshake) - CSS classes to move your DOM.
* [JSS](https://github.com/cssinjs/jss) - Authoring tool for CSS which uses JavaScript as a host language.
* [List of 300+ CSS properties](https://www.web4college.com/css-play/index.php)
* [Magical Rainbow Gradients with CSS Houdini and React Hooks \(2020\)](https://www.joshwcomeau.com/posts/rainbow-button/)
* [Shapy](https://shapy.app/) - Gradient shape editor that helps you discover and explore the power of CSS gradients. \([Code](https://github.com/vicbergquist/shapy)\)
* [CSS clip-path maker](https://bennettfeely.com/clippy/)
* [CSS Scroll Shadows](https://css-scroll-shadows.now.sh/) - Adjust the controls and see the CSS scroll shadows change. \([Code](https://github.com/stefanjudis/css-scroll-shadows/)\)
* [CSS Triangle Generator](http://apps.eky.hk/css-triangle-generator/)
* [Tint & Shade Generator](https://maketintsandshades.com/) - Display tints and shades of a given hex color in 10% increments.
* [Writing efficient CSS selectors \(2011\)](https://csswizardry.com/2011/09/writing-efficient-css-selectors/)
* [A Modern CSS Reset \(2019\)](https://hankchizljaw.com/wrote/a-modern-css-reset/)
* [The CSS Cascade](https://wattenberger.com/blog/css-cascade) - How browsers resolve competing CSS styles.
* [Intrinsic Sizing In CSS \(2020\)](https://ishadeed.com/article/intrinsic-sizing-in-css/)
* [CSS in Real Life blog](https://css-irl.info/)
* [Old CSS, new CSS \(2020\)](https://eev.ee/blog/2020/02/01/old-css-new-css/) \([HN](https://news.ycombinator.com/item?id=22215931)\)
* [Learn CSS Positioning](https://ishadeed.com/article/learn-css-positioning/)
* [CSS Triggers](https://csstriggers.com/)
* [Bounce.js](http://bouncejs.com/) - Tool and JS library that lets you create beautiful CSS3 powered animations. \([Code](https://github.com/tictail/bounce.js)\)
* [Selectors Explained](https://hugogiraudel.github.io/selectors-explained/) - Translate CSS selectors into plain English. \([Code](https://github.com/HugoGiraudel/selectors-explained)\)
* [Simpsons in CSS](https://pattle.github.io/simpsons-in-css/) \([Code](https://github.com/pattle/simpsons-in-css)\) \([HN](https://news.ycombinator.com/item?id=22429958)\)
* [CSS-Element-Queries](http://marcj.github.io/css-element-queries/) - High-speed element dimension/media queries in valid css. \([Code](https://github.com/marcj/css-element-queries)\)
* [Hint.css](https://kushagra.dev/lab/hint/) - Pure CSS tooltip library for your lovely websites. \([Code](https://github.com/chinchang/hint.css)\)
* [Intrinsic Sizing In CSS \(2020\)](https://ishadeed.com/article/intrinsic-sizing-in-css/)
* [CSS Zen Garden](http://www.csszengarden.com/) \([HN](https://news.ycombinator.com/item?id=22627018)\)
* [CSS3 Patterns Gallery](https://leaverou.github.io/css3patterns/) \([Code](https://github.com/LeaVerou/css3patterns)\)
* [All CSS named colors on a single page](https://sapegin.github.io/csscolors/) \([Code](https://github.com/sapegin/csscolors)\)
* [CSS Findings From The New Facebook Design \(2020\)](https://ishadeed.com/article/new-facebook-css/)
* [MoreToggles.css](https://jnkkkk.github.io/MoreToggles.css/) - Pure CSS library that provides you with a variety of nice-looking toggles. \([Code](https://github.com/JNKKKK/MoreToggles.css)\)
* [Styling Ordered Lists with CSS Counters \(2020\)](https://joshwcomeau.com/css/styling-ordered-lists-with-css-counters/)
* [postcss-trash-killer](https://github.com/Rammfall/postcss-trash-killer) - Postcss plugin which wil be remove all unused css.
* [Solved with CSS! Logical Styling Based on the Number of Given Elements \(2018\)](https://css-tricks.com/solved-with-css-logical-styling-based-on-the-number-of-given-elements/)
* [CSS Doodle](https://css-doodle.com/) - Web component for drawing patterns with CSS. \([Code](https://github.com/css-doodle/css-doodle)\)
* [Sakura](https://github.com/oxalorg/sakura) - Minimal classless css framework / theme.
* [Sakura Bookmarklet](https://oxal.org/projects/sakura/bookmark) - Enable Sakura.css on any website.
* [Skeleton](http://getskeleton.com/) - Dead Simple, Responsive Boilerplate for Mobile-Friendly Development. \([Code](https://github.com/dhg/Skeleton)\)
* [Do We Actually Need Specificity In CSS? \(2015\)](https://philipwalton.com/articles/do-we-actually-need-specificity-in-css/) \([HN](https://news.ycombinator.com/item?id=22897510)\)
* [The Simplicity of Specificity \(2015\)](https://codepen.io/davidkpiano/post/the-simplicity-of-specificity)
* [Concentric-CSS](https://github.com/brandon-rhodes/Concentric-CSS) - Standard order for CSS properties that starts at the outer edge of the box model and moves inward.
* [Pattern.css](https://bansal.io/pattern-css) - CSS only library to fill your empty background with beautiful patterns. \([Code](https://github.com/bansal-io/pattern.css)\) \([HN](https://news.ycombinator.com/item?id=22933697)\)
* [Watched Box](https://github.com/Heydon/watched-box) - Easiest way to get working with ResizeObserver and creating container queries with JavaScript.
* [Hamburgers](https://jonsuh.com/hamburgers/) - Tasty CSS-animated Hamburgers. \([Code](https://github.com/jonsuh/hamburgers)\)

