# Designing Interfaces Notes

### Preface:-
<hr>
<p>One could say,<code>“The applications that are easy to use are designed to be intuitive.”</code><br> <br>Well, 
yes. That’s almost a tautology.</p>

<p>Except that the word “intuitive” is a little bit deceptive. Jef Raskin once pointed out that 
when we say “intuitive” in the context of software, we really mean “familiar.” Computer 
mice aren’t intuitive to someone who’s never seen one (though a growling grizzly bear 
would be). There’s nothing innate or instinctive in the human brain to account for it. But 
once you’ve taken ten seconds to learn to use a mouse, it’s familiar, and you’ll never forget 
it. Same for blue underlined text, play/pause buttons, and so on.</p>

<br>
<p>Rephrased: <code>“The applications that are easy to use are designed to be familiar.”</code></p>

<p>Now we’re getting somewhere. “Familiar” doesn’t necessarily mean that everything about 
a given application is identical to some genre-defining product (e.g., Word, Photoshop, 
Mac OS, or a Walkman). People are smarter than that. As long as the parts are recognizable enough and the relationships among the parts are clear, then people can apply their 
previous knowledge to a novel interface and figure it out</p>

<br>
<hr>

### Patterns In General:- 
<hr>
<p>In essence, patterns are structural and behavioral features that improve the “habitability” of something—a user interface, a website, an object-oriented program, or a building. 
They make things easier to understand or more beautiful; they make tools more useful 
and usable</p>

#### Patterns are:-

<br>
<p><b><i>Concrete, not general</i></b><br>
All designers depend upon good design principles, like “Prevent errors,” “Create a 
strong visual hierarchy,” and “Don’t make the user think.” It’s rather hard, however, 
to design an actual working interface starting from fundamental principles! Patterns 
are concrete enough to help fill the space between high-level general principles and 
the low-level “grammar” of user interface design (widgets, text, graphic elements, 
alignment grids, and so on).</p>

<br>
<p><b><i>Valid across different platforms and systems</i></b><br>
Patterns may be more concrete than principles or heuristics, but they do define abstractions—the best patterns aren’t specific to a single platform or idiom. Some even 
work in both print and interactive systems. Ideally, each pattern captures some minor 
truth about how people work best with a created artifact, and it remains true even 
while the underlying technologies and media change.</p>

<br>
<p><b><i>Products, not processes</i></b><br>
Unlike heuristics or user-centered design techniques, which usually advise on how to 
go about finding a solution to an engineering or design problem, patterns are possible 
solutions. </p>

<br>
<p><b><i>Suggestions, not requirements</i></b><br>
You should almost always follow good design principles and heuristics, of course. 
And organizations need designers to follow style guides so that their products stay 
self-consistent. But patterns are intended to be only suggestions; you can follow them 
or reject them, depending on your design context and user needs.
</p>

<br>
<p><b><i>Relationships among elements, not single elements</i></b><br>
A text field is not a pattern. The spatial relationships between a text field and a piece 
of help text near it, however, might be a pattern. Likewise, changes in a set of elements 
over time—as a user interacts with the software—may constitute a pattern, though 
some patterns capture only static relationships.</p>

<br>
<p><b><i>Customized to each design context</i></b><br>
When a pattern is instantiated in a design, the designer should adjust the pattern as 
needed to fit the situation. You could use some of the pattern examples verbatim, but 
as long as you understand why the pattern works, why not be creative? Fit the pattern 
to your particular users and requirements.</p>
<br>

### Other Pattern Collections


<p>In the mid-1990s, the publication of <code>Design Patterns</code> by Erich Gamma, Richard Helm, 
Ralph Johnson, and John Vlissides profoundly changed the practice of commercial software architecture. This book is a collection of patterns describing object-oriented “microarchitectures.” If you have a background in software engineering, this is the book that 
probably introduced you to the idea of patterns. Many other authors have written books 
about software patterns since this book. Software patterns such as these do make software 
more habitable—for those who write the software, not those who use it! 
 <br> <br>
  The first substantial set of user-interface patterns was <code>“Common Ground,”</code> the predecessor to the book you’re reading now. Many other collections and languages followed, 
  notably Martijn van Welie’s <code>Interaction Design Patterns</code>; van Duyne, Landay, and Hong’s 
  <code>The Design of Sites</code>; the Little Springs mobile patterns, now known as <code>Design4Mobile</code>; the 
  Yahoo! Design Pattern Library, which morphed into <code>Designing Web Interfaces</code>; and the 
rest of the O’Reilly design pattern library, including <code>Designing Social Interfaces, Designing 
  Gestural Interfaces</code>, and the first edition of this book</p>

<br>
<p>This book does not present a complete process for constructing an interface design. When 
doing design, a sound process is critical. You need to have certain elements in a design process:</p>

- Field research, to find out what the intended users are like and what they already do
- Goal and task analysis, to describe and clarify what users will do with what you’re building.
- Design models, such as personas (models of users), scenarios (models of common tasks and situations), and prototypes (models of the interface itself)
- Empirical testing of the design at various points during development, like usability testing and <i>in situ</i> observations of the design used by real users.
- Enough time to iterate over several versions of the design, because you won’t get it right the first time.

<br>
<p>These topics transcend the scope of this book, but there are plenty of other excellent resources and workshops out there that cover them in depth</p>
<p>But there’s a deeper reason why this book won’t give you a recipe for designing an interface. 
Good design can’t be reduced to a recipe. It’s a creative process, and one that changes under 
you as you work—in any given project, for instance, you won’t understand some design issues until you’ve designed your way into a dead end. I’ve personally done that many times</p>
<p>And design isn’t linear. Most chapters in this book are arranged more or less by scale, 
and therefore by their approximate order in the design progression: large decisions about 
Preface xxi
content and scope are made first, followed by navigation, page design, and eventually 
the details of interactions with forms and toolbars and such. But you’ll often find yourself moving back and forth through this progression. Maybe you’ll know very early in 
a project how a certain screen should look, and that’s a “fixed point;” you may have to 
work backward from there to figure out the right navigational structure. (It’s not ideal, but 
things like this do happen in real life.)</p>

<br><br>
Here are some ways you can use these patterns:
<p><b><i>Learning</i></b><br>
If you don’t have much design experience, a set of patterns can serve as a learning tool. 
You may want to read over it to get ideas, or refer back to specific patterns as the need 
arises. Just as expanding your vocabulary helps you express ideas in language, expanding your interface design “vocabulary” helps you create more expressive designs.</p>

<p><b><i>Examples</i></b><br>
Each pattern in this book has at least one example. Some have many; they might be 
useful to you as a sourcebook. You may find wisdom in the examples that is missing 
in the text of the pattern. If you’re a designer who knows the patterns already, the 
examples may be the most useful aspect of the book for you.</p>
  
  <p><b><i>Terminology</i></b><br>
If you talk to users, engineers, or managers about interface design, or if you write 
specifications, then you could use the pattern names as a way of communicating and 
discussing ideas. This is another well-known benefit of pattern languages. (The terms 
“singleton” and “factory,” for instance, were originally pattern names, but they’re now 
in common use among software engineers.)</p>
  
  <p><b><i>Comparison of design alternatives</i></b><br>
If you initially decided to use Module Tabs to organize material on a page and it’s not 
working quite as well as you hoped, you might use these patterns to come up with alternatives, such as Titled Sections or an Accordion. Other sets of “either/or” patterns are 
presented in this book, often with reasons to choose one pattern or another. Skilled 
designers know that presenting alternative designs to clients frequently leads to a 
better choice in the end.</p>

  <p><b><i>Inspiration</i></b><br>
Each pattern description tries to capture the reasons why the pattern works to make 
an interface easier or more fun. If you get it, but want to do something a little different 
from the examples, you can be creative with your “eyes open.” You could also use the 
book to jumpstart your creative process by flipping through it for ideas.</p>
  
<br>
  <p>One more word of <b>caution</b>: a catalog of patterns is not a checklist. You cannot measure the 
quality of a thing by counting the patterns in it. Each design project has a unique context, 
and even if you need to solve a common design problem (such as how to fit too much 
content onto a page), a given pattern might be a poor solution within that context. No 
reference can substitute for good design judgment. Nor can it substitute for a good design 
process, which helps you find and recover from design mistakes.
</p>

<br><br>

<h3 align="center">The End</h3>
