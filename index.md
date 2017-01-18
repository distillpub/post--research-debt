<script src="assets/d3.min.js"></script>
<script src="assets/distill-hover-box.js"></script>

<style>
d-fn {
  display: none;
}
sup, sub {
  vertical-align: baseline;
  position: relative;
  top: -0.4em;
}
sub {
  top: 0.4em;
}
.post p sup a, .post ul sup a {
  background-image: none;
  text-decoration: none;
  margin-left: 2px;
  margin-right: 4px;
  font-weight: bold;
  font-size: 90%;
  color: #77A;
}
</style>


<h1>{{ distill.title }}</h1>

{{> byline.html}}

<figure style="margin-top: 0px; margin-bottom: 30px;">
<img src="assets/debt-mountain.jpg">
</figure>

Achieving a research-level understanding of most topics is like climbing a mountain. Aspiring researchers must struggle to understand vast bodies of work that came before them, to learn techniques, and to gain intuition. Upon reaching the top, the new researcher begins doing novel work, throwing new stones onto the top of the mountain and making it a little taller for whoever comes next.

Mathematics is a striking example of this. For centuries, brilliant minds have climbed the mountain range of mathematics and laid new boulders at the top. Over time, different peaks formed, built on top of particularly beautiful results. Now the peaks of mathematics are so numerous and steep that no person can climb them all. Even with a lifetime of dedicated effort, a mathematician may only enjoy some of their vistas.

People expect the climb to be hard. It reflects the tremendous progress and cumulative effort that’s gone into mathematics. The climb is seen as an intellectual pilgrimage, the labor a rite of passage. But the climb could be massively easier. It's entirely possible to build paths and staircases into these mountains.<d-fn>That is, really outstanding tutorials, reviews, textbooks, and so on.</d-fn> The climb isn’t something to be proud of.

<!--... Ideas could be tens, perhaps hundreds, of times easier to understand. The climb isn’t something to be proud of.-->

The climb isn’t progress: the climb is a mountain of debt.


The Debt
--------

Programmers talk about technical debt: there are ways to write software that are faster in the short run but problematic in the long run. Managers talk about institutional debt: institutions can grow quickly at the cost of bad practices creeping in. Both are easy to accumulate but hard to get rid of.

Research can also have debt. It comes in several forms:

* **Poor Exposition** -- Often, there is no good explanation of important ideas and one has to struggle to understand them. This problem is so pervasive that we take it for granted and don't appreciate how much better things could be.

<!--Poor exposition is one of the most visible and pervasive forms of research debt (much like poor documentation in technical debt). Explanations of core ideas don’t exist or are hard to follow. The situation is often so bad that we don’t realize exposition could be much better: we accept rope ladders when we could make elevators.-->

* **Undigested Ideas** -- Most ideas start off rough and hard to understand. They become radically easier as we polish them, developing the right analogies, language, and ways of thinking.


<!--Often ideas start off very rough and hard to understand and become radically easier as we polish them, developing the right analogies, language, visualizations and abstractions. For example, at one point calculus was something that only geniuses could understand, but we now teach it in high school: something changed, and I don’t think it was us.<d-fn>This form of debt seems particularly tragic, because I think people frequently have a much more digested version of the idea in their heads. Unfortunately, they don't communicate it except in personal conversations because it is often hard to communicate and fragile. (An additional challenge is that people often have intuitions they know aren’t 100% right, even though they are useful.) The result is that everyone needs to repolish the ideas for themselves, and the ideas aren’t progressively refined.</d-fn>-->

* **Bad abstractions and notation** -- Abstractions and notation are the user interface of research, shaping how we think and communicate. Unfortunately, we often get stuck with the first formalisms to develop, even when they're really suboptimal.  For example, something with extra electrons is negative, and [pi is wrong](http://tauday.com/).

<!--* **Bad abstractions and notation** -- Abstractions and notation are the user interface of research. When ideas first develop, formalisms develop with them, for communication and researchers’ own thoughts. These initial formalisms tend to be far from optimal but we often get stuck with them. For example, something with extra electrons negative, and pi is wrong.-->

<!--* **Bad definitions, abstractions, and notation** -- Formalisms like abstractions and notation are the user interface of research. When ideas first develop, formalisms develop with them, for communication and researchers’ own thoughts. These initial formalisms are often far from the best possible ones. Better formalisms arise over time, from general refinement of ideas, deliberate work on the formalism, or opportunities in new media. Unfortunately, poor formalisms are extremely persistent, even once better ones are found.<d-fn>One reason bad formalisms persist is that the switching costs are high, but there’s another, subtler reason. Becoming an expert in a field causes the formalisms to become part of you, in the same way language is. When one sees new formalisms, they often feel worse: you’re not fluent in the new notation, so it feels clunky, and you’ve learned to cope with any shortcomings of your familiar formalism that it fixes. Even genuine, significant improvements may seem minor or unimportant to an expert. Sadly, it’s the novice who faces the brunt of the cost.</d-fn> For example: something with extra electrons is negative, pi is wrong, and topology is better defined in terms of closure.-->

<!--* **Unavailable Tools**  -- Whether you are a student programming for the first time, or an expert trying to reproduce an experiment, being able to easily dive into topics and get your hands dirty is critical. Availability of tools makes it easier to learn because people can test their mental models.<d-fn>Rapid feedback is a documentation all of its own, and quick results are an incredible motivation</d-fn> It also facilitates the reproduction of results and the translation of research into application. Sadly, these tools are often not public, or the public versions are unusable.-->

* **Noise** -- Being a researcher is like standing in the middle of construction site. Countless papers scream for your attention and there's no easy way to filter or summarize them.<d-fn>Because most work is explained poorly, it takes a lot of energy to understand each piece of work. For many papers, I want a simple one sentence explanation of it, but need to fight with it to get that sentence. Because the simplest way to get the attention of interested parties is to get everyone’s attention, we get flooded with work. Because we incentivize people being “prolific,” we get flooded with a lot of work…</d-fn> I think noise is the main way experts experience research debt.


<!--* **Noise** -- If becoming a researcher is like climbing a mountain, being a researcher is often like standing in the middle of construction site: loud. When hundreds of papers are published each day, with no easy way to filter or summarize them, the energy needed to keep up with a field is too high.<d-fn>Because most work is explained poorly, it takes a lot of energy to understand each piece of work. For many papers, I want a simple one sentence explanation of it, but need to fight with it to get that sentence. Because the simplest way to get the attention of interested parties is to get everyone’s attention, we get flooded with work. Because we incentivize people being “prolific,” we get flooded with a lot of work…</d-fn> I think noise is the main way experts experience research debt.-->

The insidious thing about research debt is that it's normal. Everyone takes it for granted, and doesn't realize that things could be different. For example, it's normal to give very mediocre explanations of research, and people perceive that to be the ceiling of explanation quality. On the rare occasions that truly excellent explanations come along, people see them as one-off miracles rather than a sign that we could systematically be doing better.



<!--These problems arise from trading short term gains for long term costs, much like technical debt. However, research debt is different in two important ways. Firstly, it’s hard to see because it so incredibly pervasive. Secondly, the cost of the debt primarily falls on other people, especially newcomers, in the form of interpretive labor. -->

Interpretive Labor
------------------

There’s a tradeoff between the energy put into explaining an idea, and the energy needed to understand it. On one extreme, the explainer can painstakingly craft a beautiful explanation, leading their audience to understanding without even realizing it could have been difficult. On the other extreme, the explainer can do the absolute minimal work and abandon their audience to struggling. This energy is called [interpretive labor](https://acesounderglass.com/2015/06/09/interpretive-labor/), and it tends to fall on the person trying to understand.

Explanations don’t always happen one-to-one. People give lectures, write books, or communicate online. In these one-to-many cases, there's no additional cost to share the explanation with more people. However, the cost of understanding is paid by each and every member of the audience. As a result, the cost of understanding often has a huge multiplier in the interpretive labor tradeoff.<d-fn>More formally, if N people are trying to understand each other, it takes each one O(1) effort to write an explanation of their ideas but O(N) effort to understand each of the other N-1 people's ideas. The result is that energy cost looks like O(a + bN) where a and b are coefficients for the trade off between energy on the explanation side and energy on the understanding side. That is a is the energy spent on explaining and b is the corresponding effort needed to understand.</d-fn>  For example, my average blog post is read by over 100,000 people; if I can save each reader just one second, I’ve saved humanity 30 hours.<d-fn>In some sense, this suggests I should be willing to spend 14 hours to save one second. I don’t go that far, but I do try to keep it in mind.</d-fn>

In research, we often have a group of researchers all trying to understand each other. Just like before, the cost of explaining stays constant as the group grows, but the cost of understanding everyone else increases. At some size, the effort to understand everyone else becomes too much. As a defense mechanism, people specialize, focusing on a narrower area of interest. The maintainable size of the field is controlled by how you trade off the energy between communicating and understanding.

Interpretive labor is most obviously linked to “poor exposition” component of technical debt, but I think the same mechanism is behind most of it. Thoughtfully picking notation and abstractions is interpretive labor, making it easier for others to understand and think. Polishing an idea, figuring out the right framing, analogies, and pictures is interpretive labor. <!--Open sourcing clean code instead of just sketching something in a paper is interpretive labor.--> Making your work easy to filter and quickly get the core idea of is interpretive labor.

<!--Research debt is progressive piling on of interpretive labor. It saves individual researchers’ energy, at the cost of making it harder for the community to understand and build on their work, fragmenting the field.-->

Research debt is the accumulation of missing interpretive labor. It’s extremely natural for young ideas to go through a stage of debt, like early prototypes in engineering. The problem is that we often stop at that point. Young ideas aren’t ending points for us to put in a paper and abandon. When we let things stop there the debt piles up. It becomes harder to understand and build on each other’s work and the field fragments.


<figure>
  <img src="assets/fpo-circle-3.png">
</figure>

Supporting Distillation
-----------------------

Research distillation is the opposite of research debt. It combines deep technical expertise, empathy, design and writing skills to grow clarity and distill ideas.

In my experience, research distillation is an incredibly satisfying activity. It’s doing justice to our research, stripping out crud and laying bare beautiful insights. It’s sharing the rush of insight with others -- and vicariously reliving understanding for the first time, ourselves.

I think many people would be excited to do research distillation. Unfortunately, it’s hard to do so seriously because the research community doesn’t really support or celebrate it. It isn’t seen as a real research contribution. There is a strange kind of informal support for this work, which I’ve benefitted from a great deal,* but it’s tricky to build a career on.

If you are someone who is excited to distill ideas, to seek clarity, and build beautiful explanations, then I think we are letting you down. You have something incredibly precious to contribute and we aren’t supporting you as much as we ought to. I’m sorry for that. Many of us would like to support you more and that’s why we’ve created Distill.

Distill is an umbrella for two efforts to support research distillation and other non-traditional contributions:

* **The Distill Journal** -- A venue to give traditional validation to non-traditional contributions.

* **The Distill Prize** -- A $10,000 prize to acknowledge outstanding explanations of machine learning.




This is just a start: there’s a lot more that needs to be done. A complete ecosystem for this kind of work needs several other components, including places where one can learn these skills and reliable sources of employment doing this kind of work. We’re optimistic that will come with time.


Further Reading: Examples
--------------------------

**Visual Mathematics:** Several mathematicians have made remarkable efforts to visually explain certain topics. The most striking example is [Tristan Needham](https://www.usfca.edu/faculty/tristan-needham): his book [*Visual Complex Analysis*]() is a breathtaking tour-de-force, and he's been working for the last several years on a similar book, *Visual Differential Geometry*. Similarly, Nathan Carter's [*Visual Group Theory*]() does a remarkable job bringing a visual perspective to the topic and laying intuition bare. On a smaller scale, there's been a great deal of exploration -- both historically, and even more recently -- in visual mathematical proofs; see [MathOverflow: Proofs Without Words](http://mathoverflow.net/questions/8846/proofs-without-words) for examples.

**Explorable Explanations:**

Further Reading: Philosophy
----------------------------

A number of people and communities have addressed

* **Mathematics:** There seems to be a growing appreciation of the

  Mathematical culture is the only place I've really seen the contribution of distilling knowledge deeply acknowledged and celebrated. Some great comments and references are collected in this [MathOverflow thread](http://mathoverflow.net/questions/43690/whats-a-mathematician-to-do). I'd draw particular attention to section 6 of Thurston's essay [On Proof and Progress in Mathematics](https://arxiv.org/pdf/math/9404236v1.pdf) where he recounts accidentally killing a field by drowning it in research debt.

  In addition to this culture, there are a number of cases of mathematicians going to remarkable lengths

<!-- <p style="padding-left: 40px;">*Within a couple of years, a dramatic evacuation of the field started to take place...  I was killing the field. <br> <br>
The results I proved ... were documented in a conventional, formidable mathematician’s style...  This created a high entry barrier: I think many graduate students and mathematicians were discouraged that it was hard to learn and understand the proofs of key theorems.*</p> -->




<section class="appendix">

  <h3>Footnotes</h3>

  <d-fn-list></d-fn-list>


  <h3>Acknowledgments</h3>
  <p>This essay has benefitted from the comments of many people, including: Dan Mané, Shan Carter, Emma Pierson, Michael Nielsen, Cassandra Xia, Geoffrey Irving, Elizabeth Van Nostrand, Maithra Raghu, Greg Brockman, Hannah Davis, Devon Zuegel, Wojciech Zaremba, Vikas Sindhwani, Pierre Sermanet, Mike Schuster, George Dahl, Jascha Sohl-dickstein, Adam Roberts, Greg Corrado, Samy Bengio, Yomna Nasser, Katherine Ye, Dave Rushton-Smith, Martin Wattenberg, Fernanda Viegas, Eric Breck,	Aaron Courville. </p>


  <h3>Author Contributions</h3>

  <h3 id="citation">Errors, Reuse, and Citation</h3>
  <p>If you see mistakes or want to suggest changes, please submit a pull request on <a href="{{{distill.github}}}">github</a>.
  <p>Diagrams and text are licensed under Creative Commons Attribution <a href="https://creativecommons.org/licenses/by/2.0/">CC-BY 2.0</a>, unless noted otherwise, with the source available on available on <a href="{{{distill.github}}}">github</a>. The figures that have been reused from other sources don't fall under this license and can be recognized by a note in their caption: "Figure from …".
  <p>For attribution in academic contexts, please cite this work as
  <pre class="citation"></pre>
  <p>BibTeX citation
  {{=<% %>=}}
<pre class="citation"></pre>

  <%={{ }}=%>
  <h3>References</h3>
  <ul class="references">

  </ul>

</section>




<script>
function process_d_fns() {
  var fns = window.document.getElementsByTagName("d-fn");
  fns = Object.keys(fns).map(k => fns[k]);
  var fn_content = [];

  // Deal with each footnote.
  fns.forEach((e,n) => {
    n = (n+1)+"";
    fn_content.push(e.innerHTML);
    var key = "fn-"+n;
    DistillHoverBox.contentMap[key] = e.innerHTML;
    var sup = window.document.createElement("sup");
    //sup.innerHTML = "<a href=\"#fn-"+n+"\" id=\"fn-ref-"+n+"\" >"+n+"</a>";
    sup.innerHTML = "<a id=\"fn-ref-"+n+"\" style=\"cursor:pointer\">"+n+"</a>";
    e.parentNode.replaceChild(sup, e);
    DistillHoverBox.bind("#fn-ref-"+n, key)
  });

  // Render footnotes at bottom
  var fn_list = window.document.getElementsByTagName("d-fn-list")[0];
  var ol = window.document.createElement("ol");
  fn_list.parentNode.replaceChild(ol, fn_list);
  fn_content.forEach((content, n) => {
    var li = window.document.createElement("li");
    li.innerHTML = "<a id=\"fn-"+(n+1)+"\"></a>" + content;
    ol.appendChild(li);
    ol.appendChild(window.document.createElement("br"));
  });

}

process_d_fns();
</script>
