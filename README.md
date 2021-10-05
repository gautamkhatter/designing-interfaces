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

### About Patterns In General:- 
<hr>
<p>In essence, patterns are structural and behavioral features that improve the “habitability” of something—a user interface, a website, an object-oriented program, or a building. 
They make things easier to understand or more beautiful; they make tools more useful 
and usable</p>

#### Patterns are:-

<br>
<p><code>Concrete, not general</code><br>
All designers depend upon good design principles, like “Prevent errors,” “Create a 
strong visual hierarchy,” and “Don’t make the user think.” It’s rather hard, however, 
to design an actual working interface starting from fundamental principles! Patterns 
are concrete enough to help fill the space between high-level general principles and 
the low-level “grammar” of user interface design (widgets, text, graphic elements, 
alignment grids, and so on).</p>

<br>
<p><code>Valid across different platforms and systems</code><br>
Patterns may be more concrete than principles or heuristics, but they do define abstractions—the best patterns aren’t specific to a single platform or idiom. Some even 
work in both print and interactive systems. Ideally, each pattern captures some minor 
truth about how people work best with a created artifact, and it remains true even 
while the underlying technologies and media change.</p>

<br>
<p><code>Products, not processes</code><br>
Unlike heuristics or user-centered design techniques, which usually advise on how to 
go about finding a solution to an engineering or design problem, patterns are possible 
solutions. </p>

<br>
<p><code>Suggestions, not requirements</code><br>
You should almost always follow good design principles and heuristics, of course. 
And organizations need designers to follow style guides so that their products stay 
self-consistent. But patterns are intended to be only suggestions; you can follow them 
or reject them, depending on your design context and user needs.
</p>

<br>
<p><code>Relationships among elements, not single elements</code><br>
A text field is not a pattern. The spatial relationships between a text field and a piece 
of help text near it, however, might be a pattern. Likewise, changes in a set of elements 
over time—as a user interacts with the software—may constitute a pattern, though 
some patterns capture only static relationships.</p>

<br>
<p><code>Customized to each design context</code><br>
When a pattern is instantiated in a design, the designer should adjust the pattern as 
needed to fit the situation. You could use some of the pattern examples verbatim, but 
as long as you understand why the pattern works, why not be creative? Fit the pattern 
to your particular users and requirements.</p>
