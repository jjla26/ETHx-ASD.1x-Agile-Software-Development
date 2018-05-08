## Course introduction
 
0:00 / 3:03Velocidad: Presiona ARRIBA para acceder al menú, luego usa las teclas de ARRIBA y ABAJO para cambiar a diferentes velocidades, y presiona ENTER para cambiar a la velocidad seleccionada.Velocidad1.0xHaz clic en este botón para silenciar o activar el sonido del vídeo o usa los botones ARRIBA o ABAJO para aumentar o disminuir el nivel de volumen.Muy alto Volumen.Transcripción de video
Inicio de la transcripción. Saltar al final.
BERTRAND MEYER: agile methods are one of the most important developments
in two decades of software engineering.
And I'm not exaggerating.
Everywhere in the industry, people are looking at agile methods
and often practicing them or some form of agile development.
Every software employer is going to give preference to candidates
that master agile concepts.
In this course, we are going to review agile methods so
that you can take the best out of them.
My name is Bertrand Meyer.
I'm a professor at Politecnico di Milano and Innopolis University.
And I was previously a ETH.
I also have another hat.
I am founder and CEO of a software company called Eiffel Software.
So I have this double experience-- academic on one side,
industrial on the other side.
And I hope you'll see that this course benefits from this dual experience.
Now, many presentations of agile methods are partisan.
They really want you to kneel down and to start praying
and adopt this or that agile method.
This one is different.
I'm not preaching one method or another.
The only thing I'm really preaching is software quality
and software productivity.
So we're going to see what agile methods are about.
But we're not going to advertise for a particular method.
And in fact-- surprise, surprise-- in agile methods,
there are some good aspects and some not so good aspects
as well, as in every human endeavor.
And it is very important to keep one's cool
and to decide what is best for you, for your project.
So this is going to be an analysis, without any bias,
of agile methods as they exist today.
The course is divided into six parts.
The first part presents the agile manifesto
and the context of agile methods.
The second part presents the agile principles--
what key methodological ideas underlie the agile movement.
The third one presents agile roles.
How does agile redefine traditional software jobs and tasks,
in particular, the manager's role?
The next part, the fourth one, highlights agile practices.
What are the concrete techniques that agile-type teams
use to apply the methods?
The next, and fifth, part describes the agile artifacts.
What practical tools are essential to the work of agile developers?
And the final part is an agile assessment.
Among agile ideas, which ones are essentially hyped and useless?
Which ones are actually harmful?
And which ones will truly help you produce software better?
In the words of the title of the textbook that goes with this course,
we look at the good, the hype, and the ugly.
I hope you enjoy this course.
Agile methods are one of the most important ideas on the software scene
today.
This course will enable you to master them and decide for yourself what
they can do for you, for your projects, and for your career.

# Curso   Week 1   1.2 Context   Introduction to week 1

## Introduction to week 1
 
INSTRUCTOR: This first lecture is called context, and as the name suggests
it introduces the fundamental ideas behind Agile methods
and the general background.
There's four segments.
The first segment is about the Agile manifesto.
That is, the foundational text that at the beginning of this century
introduced the fundamental Agile principles to the world.
Out of the manifesto, came a number of full-fledged methods.
And these methods are the topic of segment number two.
The methods embody the agile principles.
In segment three, we take a look at the key Agile principles,
as described in the Agile Manifesto.
That is to say, as seen by the originators of the Agile ideas.
Now, this is not necessarily, as we will see later the best
way to present Agile principles.
But this is what we will look at in segment three.
And finally, in segment four, we will review Agile values.
The values are at a more abstract level than the principles.
They are a kind of general philosophy that underlies the entire Agile
movement and from which everything else follows.

# Curso   Week 1   1.2 Context   The Agile Manifesto

## The Agile Manifesto
 
PROFESSOR: The Agile Manifesto is the 15-year-old text
which first presented Agile ideas.
And it's remarkable to see how aptly it still characterizes the Agilist's view
today.
So let's see what it has to say.
Agile methods came into prominence at the time
of the publication of the so-called Agile Manifesto in 2001.
This was, as the name suggests, a pamphlet,
a manifesto, designed to attract the world's attention on the need
to develop software differently.
The manifesto was the work of a number of people.
The original signatories of the manifesto, they're listed here.
Most of them, perhaps all of them, are in fact software consultants.
And the manifesto gained a lot of visibility,
and has continued to be quoted widely since then.
You can find it online at agilemanifesto.org.
And here's what it says.
We need to go through it in order to understand what Agile is about, as seen
in the eyes of its own creators.
It's a text that contrasts certain old ways of doing software, shown here
on the right.
At least viewed as old by the authors of the manifesto
with a number of alternatives.
They take care to indicate that they do not completely
reject the stuff on the right.
They say while there is value in the items on the right,
we value the items on the left more.
We are uncovering, they say, better ways of developing software,
not just by talking about it, but by doing it.
By actually developing software, we are practitioners.
And by helping others as consultants to do it.
Through this work, we have come to value the stuff on the left over the stuff
on the right.
Individuals and interactions over processes and tools.
Working software over comprehensive documentation.
Customer collaboration over contract negotiation.
Responding to change over following a plan.
So you can see the difference between the stuff on the left and the stuff
on the right.
The stuff on the right is really traditional,
or viewed as traditional management-oriented techniques.
Techniques that emphasize projects that are strictly managed.
And the stuff on the left is more into individuals and collaboration
and informality and people.
So going through the four elements here.
Individuals and interactions rather overly managed processes and tools.
Working software, second point, rather than comprehensive documentation.
There's a tendency in traditional projects
to insist on documenting absolutely every thing that the software is
going to do.
Well, the Agile view here is to say documents are only documents.
And really what counts is software that actually runs.
This is the last word which solves all questions.
Documents only say what the software should do.
Software, by definition, says what the program does.
3, customer collaboration over contract negotiation.
Of course, you need to make sure that your software satisfies
the needs of the customers.
You can go have the lawyers involved.
You can go weeks describing and discussing
exactly what it is that the customer wants, and accepting it or not.
It's much better to involve the customers,
to involve the people representing the business
from beginning to end in the project, in the development.
And finally, responding to change over following a plan.
One of the characteristics of software, and of course
we haven't waited for the Agilists to tell us that, is that software changes.
Hence the word soft in the very name of the field.
Well, what's the Agilists emphasize here is that plans are great.
But in the words of the German strategist Helmut von Moltke,
the best battle plan doesn't survive the first contact with the enemy.
And it's the same thing in software: requirements
and advanced descriptions of what systems should do are great.
But as soon as you start implementing stuff and showing it to customers,
they're going to want something different.
Hence, what is really more important than following a plan is
to be able to respond to change.
These general ideas are complemented in the Agile Manifesto by 12 principles.
And we're going to go through them, because this
is necessary to understand what Agile is about in the very words
of its own creators.
First, our highest priority is to satisfy the customer
through early and continuous delivery of valuable software.
There are several ideas here.
We need to satisfy the customers.
So the prime role of business representatives,
of people who are going to use the system in the end,
and the emphasis on early and continuous delivery of valuable software.
Software that doesn't just run, but does something useful.
And it has to be early.
That is to say right from the start, we're
going to start producing software rather than
producing documents, or requirements, or designs, or architectures.
And it's going to be continuous.
That is to say, throughout the development,
we're going to produce software again and again.
2, welcome changing requirements.
Well, between you and me, welcome is a little bit strong,
because very few people welcome having to change what they have already done.
But the idea is clear.
It's that software is soft, and we have to accept rather than welcome perhaps,
that requirements are going to change even late in development.
Even when you're ready to ship, or you think you're ready to ship.
Agile processes harness change for the customer's competitive advantage.
So psychologically, this is quite important here.
Change is not just something we accept as a necessary evil.
It's something that we welcome, in their words.
Because being able to react quickly to requests for changes
is going to give the business a competitive advantage.
3, deliver software frequently from a couple of weeks to a couple of months,
with a preference to the shorter time scale.
That is to say, weeks rather than months.
So we are done with the old style of going away
for months to work separately in the various parts of the system,
and then trying to merge everything.
Instead we are going to have very short iterations
where we put everything together.
4, businesspeople and developers will work together daily
throughout a project.
So it's not that we talk to the customers,
to our users at the beginning to define the requirements,
and at the end to check that we met the requirements.
We're actually going to involve them throughout.
5, build projects around individuals.
So this is the emphasis on personal contact, and on individuals.
In particular, individual developers and supported developers.
Give them the tools, give them the support that they need
and trust them to get the job done.
Emphasis on trust.
6, the most efficient and effective method
of conveying information to and within the development team
is face to face conversation.
Again, emphasis on personal interaction.
7, this is really a repetition because it has been said already.
Working software is the primary measure of progress.
Documents, requirements, designs, and so on are great,
but they are not what is going to show you that you really progress.
In the Agile view, the only measure of progress,
or at least the primary measure of progress
is the working software that you have actually produced so far.
8, promote sustainable development.
Don't overwork developers.
It doesn't work in the long term.
Make sure that everyone can maintain a constant pace indefinitely.
9, technical excellence.
Emphasis on making things right, on doing things right,
and on having good design and high quality code.
10, simplicity, which is defined here as the art
of maximizing the amount of work
not done.
We'll come back to that.
It is essential.
So emphasis on finding the simplest possible solution.
11, the best architecture's requirements and designs
emerge from self-organizing teams.
So the idea is that we should not over manage developers,
but we should trust them to organize themselves.
And of course, these are all points to which
we're going to go back throughout this course.
And finally, number 12, at regular intervals,
meet and discuss what you have done in order
to reflect on the successes and failures, and in order
of course to adjust the team's behavior accordingly.
This is Agile as viewed by its creators of course,
at a high level of abstraction.
And we're going to see the details of the practices,
artifacts, and other techniques that make it possible to put
these general ideas into practice.
So what we've seen in this first segment of our first lecture
is a set of principles defining Agile as seen by its creators.
It's actually quite a few principles, 12 of them.
And they give us the general idea.
To benefit from this course, it's going to be useful for you to have access
to the corresponding textbook.
It's called Agile, the Good, the Hype, and the Ugly.
It was published by Springer.
It's available both in paper and PDF, electronically.
And in particular, if you want to go deeper into some of the material
that I will cover in this course, the book will be useful.

# Curso   Week 1   1.2 Context   Agile Methods

## Agile Methods
 
0:00 / 9:41Velocidad: Presiona ARRIBA para acceder al menú, luego usa las teclas de ARRIBA y ABAJO para cambiar a diferentes velocidades, y presiona ENTER para cambiar a la velocidad seleccionada.Velocidad1.25xHaz clic en este botón para silenciar o activar el sonido del vídeo o usa los botones ARRIBA o ABAJO para aumentar o disminuir el nivel de volumen.Muy alto Volumen.Transcripción de video
Inicio de la transcripción. Saltar al final.
PROFESSOR: Agile ideas have been combined
into a number of full fledged methods, sometimes called methodologies.
And in this segment, we're going to study four of them.
They're not the only ones.
There are a number of them out there, but these four
are the ones that have garnered the most attention.
We will start with extreme programming, which
was only the first to hit the public.
Then we'll continue with Lean Software and with the Crystal methodology.
And we will end with the one that is the most visible today, that is really
dominant on the scene, namely Scrum.
Agile development is generally practiced in the form
of one of the so-called agile methods.
Agile methods including in particular, the four listed here.
And there are a coherent sets of rules and practices
that all draw their roots in the general ideas that we've started to see.
The four best known ones are XP, which stands for Extreme Programming,
and whose author is Ken Beck.
Lean Software was devised by Mary Poppendieck
with her husband Tom Poppendieck.
Crystal was devised by Alistair Cockburn, and Scrum
by Ken Schwaber and Ken Sutherland.
I've given here the names of the creators of these methods,
because there's a strong personal connotation
to each one of these methods that is closely connected
to the personality of their creators and to the books that each one of these
have written about the corresponding methods.
The first one to gain wide attention is XP Extreme Programming,
which came out in the 90s.
And XP Extreme Programming can be seen as a reaction
against the culture that was predominant in software engineering circles
at the time.
A culture that emphasized process, that emphasized plans, diagrams.
Things like UML, or CMMI.
UML is the Unified Modeling Language.
It's in particular, a diagramming convention for describing systems.
CMMI, which is the Capability Maturity Model Integration,
is a standard for defining best practices in software development.
And these are all approaches that emphasize management,
that emphasize process and documents.
And extreme programming was in part a reaction against this.
Drawing attention to the fact that what really matters in the end
is the programs, and of course, the programming and the programmers.
In the end, it's not diagrams that work or not.
It's not documentation that tells you whether you have a working system.
What counts is the software, the programs as we
have already seen, in the principles of the Agile Manifesto.
So Extreme Programming made a major contribution
by rehabilitating so to speak, the work of programmers,
and putting programs and programming at the center of software development.
Lean Software is an attempt to apply to software
a number of ideas and principles which have
proved their value in other engineering fields,
in particular, in the car industry.
There's the famous set of practices developed in particular,
by Toyota in Japan, which have been very influential, not just in the automobile
industry, but throughout industry, in particular industries, that
make material things.
And the Poppendiecks applied these ideas to software,
emphasizing in particular the need to get rid of what they call waste.
While waste is clear in industries that make material things.
But the Poppendiecks claim that we should also be on the lookout for waste
in software, and get rid of things like for example, useless documentation,
which they view as waste, in order to concentrate
on stuff that is going to be actually delivered to the customer.
Crystal is a little bit different from the others in that it
is more of a combination of agile ideas and more traditional ideas.
Crystal is actually the name for a set of methods
characterized by various degrees of importance of process in management.
Alistair Cockburn, who developed the Crystal set of methods
is trying to combine the best of Agile with a best of more process
oriented approaches.
Scrum is the approach that has come to dominate the scene in recent years.
And Scrum is less technical than, for example, the XP.
It's not so much software-focused.
It's more of a management method which emphasizes ideas
that we are going to study in detail, such as the importance
of self-organizing teams as opposed to teams that are closely managed
by a manager, and the importance of a specific kind of short release
iterations known as Sprints.
It's important to note that in practice these days when we talk about Agile,
we really talk about Scrum.
This is the approach that officially at least,
most organizations using Agile methods have really adopted.
And it has somehow on the surface at least, wiped out all the others.
This view however, is not entirely accurate.
Because when you look under the surface, and when we
you see what people who say they're using Scrum are actually using, well,
they really use a lot of ideas from the other methods, in particular, XP.
Especially when it comes to the more technical aspects of the process,
many of the XP ideas, even if people don't necessarily
realize that they come from Extreme Programming,
have made their way into the standard form of Agile methods usually known
as Scrum.
When we continue at a high level of abstraction,
at a bird's eye view of what Agile methods are,
which is our purpose for this segment, it's
important to know that initially with XP, one
could view the use of Agile methods as a reaction against Dilbert's boss.
So, so to speak, against the management aspect
in favor of the view of the Dilberts of this world.
And it is this rehabilitation of programming that I have talked about.
There's also another aspect to Agile methods
which is not that emphasized in the Agile literature,
but which it is really important to understand if you
want to know what Agile is about.
It's the idea that I call negotiator scope.
It expressed quite clearly in one of the books of Ken Beck about Agile.
By the way, you can check the bibliography.
When I say Beck 05, I refer to a particular book.
And the bibliographic list is in the materials for the course.
Also, while I'm at it, you may have noticed these little symbols,
such as shown here.
These are not official symbols for the methods.
These are mine, but they will be used whenever
I present an idea that is particularly associated with Extreme Programming,
with Lean, with Crystal, or with Scrum.
So coming back to the negotiator scope contract
idea,
what Beck tells us is write contract for software development at fixed time,
cost, and quality, but call for an ongoing negotiation
of the precise scope of the system.
And so what this means in plainer English is that in the ideal world
people often renounce the traditional commitment to both quality,
functionality, and to do all three of quality, functionality, and delivery.
In particular, functionality and delivery date.
So the general idea is we can promise you a certain delivery date,
or we can commit ourselves to a specific set of functionality.
But it is very difficult to commit on both.
And so this is very much the world as viewed by consultants.
And it is one of the implicit characteristics of Agile methods,
while not completely implicit since Beck explains it here.
But that is going to be one of the points
that we will have to discuss when we assess the value of Agile methods,
and how much one should retain in practice.
So what we've seen in this segment is that a number of Agile methods
have emerged.
I've cited four of them.
Extreme programming, Lean Software, Crystal and Scrum.
They shared the basic ideas, but differ in their goals and points of emphasis.

