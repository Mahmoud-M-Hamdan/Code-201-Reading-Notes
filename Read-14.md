# Read14-a

## Transforms

In this Lesson7
CSS
Transform Syntax
2D Transforms
Combining Transforms
Transform Origin
Perspective
3D Transforms
Transform Style
Backface Visibility
SHARE
Share on Twitter
 
Share on Facebook
 
Share on Google+
ads via Carbon
Enjoy this lesson? Show your support by purchasing the book.
ads via Carbon
With CSS3 came new ways to position and alter elements. Now general layout techniques can be revisited with alternative ways to size, position, and change elements. All of these new techniques are made possible by the transform property.

The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

Within this lesson we’ll take a look at both two-dimensional and three-dimensional transforms. Generally speaking, browser support for the transform property isn’t great, but it is getting better every day. For the best support vendor prefixes are encouraged, however you may need to download the nightly version of Chrome to see all of these transforms in action.

## Transform Syntax transform-syntax
The actual syntax for the transform property is quite simple, including the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses.
 
Notice how the transform property includes multiple vendor prefixes to gain the best support across all browsers. The un-prefixed declaration comes last to overwrite the prefixed versions, should a browser fully support the transform property.

In the interest of brevity, the remainder of this lesson will not include vendor prefixes. They are, however, strongly encouraged for any code in a production environment. Over time we will be able to remove these prefixes, however keeping them in is the safest approach for the time being.

## 2D Transforms two-dimensional-transforms

Elements may be distorted, or transformed, on both a two-dimensional plane or a three-dimensional plane. Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes. Three-dimensional transforms work on both the x and y axes, as well as the z axis. These three-dimensional transforms help define not only the length and width of an element, but also the depth. We’ll start by discussing how to transform elements on a two-dimensional plane, and then work our way into three-dimensional transforms.


## 2D Rotate

The transform property accepts a handful of different values. The rotate value provides the ability to rotate an element from 0 to 360 degrees. Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise. The default point of rotation is the center of the element, 50% 50%, both horizontally and vertically. Later we will discuss how you can change this default point of rotation.

## 2D Scale


Using the scale value within the transform property allows you to change the appeared size of an element. The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger.

## Translate 2D 

The translate value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document. Using the translateX value will change the position of an element on the horizontal axis while using the translateY value will change the position of an element on the vertical axis.

As with the scale value, to set both the x and y axis values at once, use the translate value and declare the x axis value first, followed by a comma, and then the y axis value.

The distance values used within the translate value may be any general length measurement, most commonly pixels or percentages. Positive values will push an element down and to the right of its default position while negative values will pull an element up and to the left of its default position.


# Read14-b

## What Google Learned From Its Quest to Build the Perfect Team
Like most 25-year-olds, Julia Rozovsky wasn’t sure what she wanted to do with her life. She had worked at a consulting firm, but it wasn’t a good match. Then she became a researcher for two professors at Harvard, which was interesting but lonely. Maybe a big corporation would be a better fit. Or perhaps a fast-growing start-up. All she knew for certain was that she wanted to find a job that was more social. ‘‘I wanted to be part of a community, part of something people were building together,’’ she told me. She thought about various opportunities — Internet companies, a Ph.D. program — but nothing seemed exactly right. So in 2009, she chose the path that allowed her to put off making a decision: She applied to business schools and was accepted by the Yale School of Management.

When Rozovsky arrived on campus, she was assigned to a study group carefully engineered by the school to foster tight bonds. Study groups have become a rite of passage at M.B.A. programs, a way for students to practice working in teams and a reflection of the increasing demand for employees who can adroitly navigate group dynamics. A worker today might start the morning by collaborating with a team of engineers, then send emails to colleagues marketing a new brand, then jump on a conference call planning an entirely different product line, while also juggling team meetings with accounting and the party-planning committee. To prepare students for that complex world, business schools around the country have revised their curriculums to emphasize team-focused learning.

Every day, between classes or after dinner, Rozovsky and her four teammates gathered to discuss homework assignments, compare spreadsheets and strategize for exams. Everyone was smart and curious, and they had a lot in common: They had gone to similar colleges and had worked at analogous firms. These shared experiences, Rozovsky hoped, would make it easy for them to work well together. But it didn’t turn out that way. ‘‘There are lots of people who say some of their best business-school friends come from their study groups,’’ Rozovsky told me. ‘‘It wasn’t like that for me.’’

Instead, Rozovsky’s study group was a source of stress. ‘‘I always felt like I had to prove myself,’’ she said. The team’s dynamics could put her on edge. When the group met, teammates sometimes jockeyed for the leadership position or criticized one another’s ideas. There were conflicts over who was in charge and who got to represent the group in class. ‘‘People would try to show authority by speaking louder or talking over each other,’’ Rozovsky told me. ‘‘I always felt like I had to be careful not to make mistakes around them.’’

ADVERTISEMENT

Continue reading the main story

So Rozovsky started looking for other groups she could join. A classmate mentioned that some students were putting together teams for ‘‘case competitions,’’ contests in which participants proposed solutions to real-world business problems that were evaluated by judges, who awarded trophies and cash. The competitions were voluntary, but the work wasn’t all that different from what Rozovsky did with her study group: conducting lots of research and financial analyses, writing reports and giving presentations. The members of her case-competition team had a variety of professional experiences: Army officer, researcher at a think tank, director of a health-education nonprofit organization and consultant to a refugee program. Despite their disparate backgrounds, however, everyone clicked. They emailed one another dumb jokes and usually spent the first 10 minutes of each meeting chatting. When it came time to brainstorm, ‘‘we had lots of crazy ideas,’’ Rozovsky said.

One of her favorite competitions asked teams to come up with a new business to replace a student-run snack store on Yale’s campus. Rozovsky proposed a nap room and selling earplugs and eyeshades to make money. Someone else suggested filling the space with old video games. There were ideas about clothing swaps. Most of the proposals were impractical, but ‘‘we all felt like we could say anything to each other,’’ Rozovsky told me. ‘‘No one worried that the rest of the team was judging them.’’ Eventually, the team settled on a plan for a micro­gym with a handful of exercise classes and a few weight machines. They won the competition. (The micro­gym — with two stationary bicycles and three treadmills — still exists.)

Rozovsky’s study group dissolved in her second semester (it was up to the students whether they wanted to continue). Her case team, however, stuck together for the two years she was at Yale.

It always struck Rozovsky as odd that her experiences with the two groups were dissimilar. Each was composed of people who were bright and outgoing. When she talked one on one with members of her study group, the exchanges were friendly and warm. It was only when they gathered as a team that things became fraught. By contrast, her case-competition team was always fun and easygoing. In some ways, the team’s members got along better as a group than as individual friends.

‘‘I couldn’t figure out why things had turned out so different,’’ Rozovsky told me. ‘‘It didn’t seem like it had to happen that way.’’

Editors’ Picks

An Ode to the Pleasures of Flossing

Giannis Is What Happens When N.B.A. Dreams Come True

Why Do American Grocery Stores Still Have an Ethnic Aisle?
Continue reading the main story

ADVERTISEMENT

Continue reading the main story

Our data-saturated age enables us to examine our work habits and office quirks with a scrutiny that our cubicle-bound forebears could only dream of. Today, on corporate campuses and within university laboratories, psychologists, sociologists and statisticians are devoting themselves to studying everything from team composition to email patterns in order to figure out how to make employees into faster, better and more productive versions of themselves. ‘‘We’re living through a golden age of understanding personal productivity,’’ says Marshall Van Alstyne, a professor at Boston University who studies how people share information. ‘‘All of a sudden, we can pick apart the small choices that all of us make, decisions most of us don’t even notice, and figure out why some people are so much more effective than everyone else.’’


Yet many of today’s most valuable firms have come to realize that analyzing and improving individual workers ­— a practice known as ‘‘employee performance optimization’’ — isn’t enough. As commerce becomes increasingly global and complex, the bulk of modern work is more and more team-based. One study, published in The Harvard Business Review last month, found that ‘‘the time spent by managers and employees in collaborative activities has ballooned by 50 percent or more’’ over the last two decades and that, at many companies, more than three-quarters of an employee’s day is spent communicating with colleagues.

In Silicon Valley, software engineers are encouraged to work together, in part because studies show that groups tend to innovate faster, see mistakes more quickly and find better solutions to problems. Studies also show that people working in teams tend to achieve better results and report higher job satisfaction. In a 2015 study, executives said that profitability increases when workers are persuaded to collaborate more. Within companies and conglomerates, as well as in government agencies and schools, teams are now the fundamental unit of organization. If a company wants to outstrip its competitors, it needs to influence not only how people work but also how they work together.

Five years ago, Google — one of the most public proselytizers of how studying workers can transform productivity — became focused on building the perfect team. In the last decade, the tech giant has spent untold millions of dollars measuring nearly every aspect of its employees’ lives. Google’s People Operations department has scrutinized everything from how frequently particular people eat together (the most productive employees tend to build larger networks by rotating dining companions) to which traits the best managers share (unsurprisingly, good communication and avoiding micromanaging is critical; more shocking, this was news to many Google managers).

The company’s top executives long believed that building the best teams meant combining the best people. They embraced other bits of conventional wisdom as well, like ‘‘It’s better to put introverts together,’’ said Abeer Dubey, a manager in Google’s People Analytics division, or ‘‘Teams are more effective when everyone is friends away from work.’’ But, Dubey went on, ‘‘it turned out no one had really studied which of those were true.’’

Sign Up for The Great Read  Every weekday, we recommend one piece of exceptional writing from The Times — a narrative or essay that takes you someplace you might not expect to go. Get it sent to your inbox.
In 2012, the company embarked on an initiative — code-named Project Aristotle — to study hundreds of Google’s teams and figure out why some stumbled while others soared. Dubey, a leader of the project, gathered some of the company’s best statisticians, organizational psychologists, sociologists and engineers. He also needed researchers. Rozovsky, by then, had decided that what she wanted to do with her life was study people’s habits and tendencies. After graduating from Yale, she was hired by Google and was soon assigned to Project Aristotle.

ADVERTISEMENT

Continue reading the main story

Project Aristotle’s researchers began by reviewing a half-century of academic studies looking at how teams worked. Were the best teams made up of people with similar interests? Or did it matter more whether everyone was motivated by the same kinds of rewards? Based on those studies, the researchers scrutinized the composition of groups inside Google: How often did teammates socialize outside the office? Did they have the same hobbies? Were their educational backgrounds similar? Was it better for all teammates to be outgoing or for all of them to be shy? They drew diagrams showing which teams had overlapping memberships and which groups had exceeded their departments’ goals. They studied how long teams stuck together and if gender balance seemed to have an impact on a team’s success.

No matter how researchers arranged the data, though, it was almost impossible to find patterns — or any evidence that the composition of a team made any difference. ‘‘We looked at 180 teams from all over the company,’’ Dubey said. ‘‘We had lots of data, but there was nothing showing that a mix of specific personality types or skills or backgrounds made any difference. The ‘who’ part of the equation didn’t seem to matter.’’

Some groups that were ranked among Google’s most effective teams, for instance, were composed of friends who socialized outside work. Others were made up of people who were basically strangers away from the conference room. Some groups sought strong managers. Others preferred a less hierarchical structure. Most confounding of all, two teams might have nearly identical makeups, with overlapping memberships, but radically different levels of effectiveness. ‘‘At Google, we’re good at finding patterns,’’ Dubey said. ‘‘There weren’t strong patterns here.’’

As they struggled to figure out what made a team successful, Rozovsky and her colleagues kept coming across research by psychologists and sociologists that focused on what are known as ‘‘group norms.’’ Norms are the traditions, behavioral standards and unwritten rules that govern how we function when we gather: One team may come to a consensus that avoiding disagreement is more valuable than debate; another team might develop a culture that encourages vigorous arguments and spurns groupthink. Norms can be unspoken or openly acknowledged, but their influence is often profound. Team members may behave in certain ways as individuals — they may chafe against authority or prefer working independently — but when they gather, the group’s norms typically override individual proclivities and encourage deference to the team.

Project Aristotle’s researchers began searching through the data they had collected, looking for norms. They looked for instances when team members described a particular behavior as an ‘‘unwritten rule’’ or when they explained certain things as part of the ‘‘team’s culture.’’ Some groups said that teammates interrupted one another constantly and that team leaders reinforced that behavior by interrupting others themselves. On other teams, leaders enforced conversational order, and when someone cut off a teammate, group members would politely ask everyone to wait his or her turn. Some teams celebrated birthdays and began each meeting with informal chitchat about weekend plans. Other groups got right to business and discouraged gossip. There were teams that contained outsize personalities who hewed to their group’s sedate norms, and others in which introverts came out of their shells as soon as meetings began.


