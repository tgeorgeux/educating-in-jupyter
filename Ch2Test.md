

# Chapter 2: Why we use Jupyter notebooks to teach

**[Resource: slides on what makes faculty try out teaching practices and what they do now](https://drive.google.com/open?id=1PivtwPVoUmNHOP1OPWJZr3jNaCcCaqQ4zQJTpjwklD8)**


# Goal

Introduce Jupyter notebooks, their pedagogical utility, and how you can use them to enhance your teaching and learning.


# Outline - (for internal drafting use only)

You've made it through the introduction, and you're still reading. At this point you're willing to be convinced that Jupyter Notebooks are right for you. This chapter answers the following questions:



1.  What exactly is a Jupyter Notebooks from an educators point of view?
    1.  An executable file containing a mixture of content: text, images, videos, objects, code, and
    1.  A set of tools that operates on that file
1.  Motivate Instructors to try Jupyter Notebooks by: 
    1.  Demonstrate that you can increase the student's ability to:
        1.  engage
        1.  participate
        1.  understand
        1.  perform well
        1.  prepare their for career
    1.  Demonstrate that educators will: 
        1.  believe it'll fit with your students learning
        1.  know you have the needed resources
        1.  understand the necessary logistics,
        1.  have clear expectations of what it will do.
    1.  Show explicitly how Jupyter helps a student and an educator do the above 9 items. _We recommend making use of shorter less personal anecdotes. For example, anecdotes could be based on real stories but structured like "Suzie a humanities teacher has this problem and this is how she used Jupyter to solve it." (See "[How Learning Works: Seven Research-Based Principles for Smart Teaching](https://firstliteracy.org/wp-content/uploads/2015/07/How-Learning-Works.pdf)" for a beautiful example of anecdotes like this.). We should ask the group for the best anecdotes for each idea._


# Why do we as educators use Jupyter?

As teachers we are responsible for a vast array of activities, including creating lessons, lectures, courses, assignments, and supportive environments; encouraging engagement and performance in the classroom; helping students learn to think critically so they can become lifelong learners and problem solvers; making material relevant and meaningful to students' diverse interests and backgrounds; assessing student learning (including grading and evaluation); encouraging students to persist with emotional labor (feedback, communication, etc.); and trying out teaching and learning practices that improve our ability to do all of these things.

In short, teachers design learning environments. We use Jupyter Notebooks to design learning environments to help support these activities. The goal of this handbook is to provide you with ideas to help you address your own pedagogical goals. We believe that incorporating Jupyter Notebooks in our teaching has allowed us to help improve students' understanding of course content, help increase student engagement and participation in class, and help make concepts more meaningful and relevant to students' diverse interests. 

Below we will attempt to demonstrate through a series of anecdotes that you, as an educator, can help increase your students' 1) engagement, 2) participation, 3) understanding, 4) performance, 5) preparation their for career, using Jupyter notebooks. 


## But what is a Jupyter Notebook?

Project Jupyter is actually three things: a collection of standards, a community, and set of software tools. A Jupyter Notebook one part of Jupyter; it is a document that supports mixing executable code, equations, visualizations, and narrative text. Specifically, Jupyter Notebooks are a tool that allows the user to bring together data, code, and prose, to tell an interactive, computational story. Whether analyzing a corpus of American Literature, creating music and art, or illustrating the engineering concepts behind Digital Signal Processing, the notebooks can combine explanations traditionally found in textbooks with _the interactivity of an application_.

_Visual of a notebook - Side Box with an anatomy of a notebook - descriptions with arrows to particular cells. Link to Binder: Try it now._



*   _Title Cell: Point out prose (markdown)_
*   _Introduction Cell: Links to other content_
*   _Engaging visualization (a few lines of code 5 or less)_
*   _Make the example interactive with widgets_
*   _Add a cell with a problem to solve_
*   _Solution cell_

_It would be nice also to have a callout box here that illustrates a relatively simple use of JN for say, one learning objective -- or maybe one of each of the following: domain knowledge, programming, and other use._

_Jupyter Notebook is a free, open source platform that students like to learn with. For teachers, it increases our efficiency and decreases cognitive load so we can engage students using narrative, lecture, or flipped classrooms. We use Jupyter Notebooks in small classes and for classes that have hundreds of students. Jupyter Notebooks enable us and our students to have a conversation with a problem and link to resources, like audio, video, images, visualizations--and even allow students to mix and remix these. And yet students need to install nothing beyond a modern web browser to use this free software. Jupyter Notebooks can be used for teaching part of one lecture or can be used to teach a whole course. _

Jupyter Notebooks can be used to organize classroom materials and objects, store and provide access to reading materials for students, present and share lecture materials, perform live coding, explore and interact with materials, support self-paced learning, grade students' homework, solve homework problems, or make materials reusable to others. Read on to find out how we have used Jupyter Notebooks for teaching and learning to benefit both our students and ourselves.** **Jupyter Notebooks support a wide range of learning goals, including learning to program, learning domain knowledge, and practicing communication skills like storytelling. The authors of this book have used Jupyter Notebooks to teach: 



*   Sciences
    *   Physics and astronomy 
    *   Biology
    *   Cognitive Science
    *   Computer science
    *   Data science
    *   Statistics
    *   Social sciences
*   Writing
    *   Writing Seminar
    *   Writing and technical communication
*   Digital Humanities 
    *   Music
    *   Text analysis
    *   Metadata processing
*   Engineering 
    *   Chemical engineering (kinetics and reactor design)
*   Introduction to Programming 
    *   High school
    *   CS0 and CS1 (college and university-level courses)

This has included the following topics:



*   Building models/simulations (with and without programming)
*   Using widgets to demonstrate and interact with simulations
*   Visualizations of process and data
*   Signal processing
*   Complexity science


## 1) Increasing Student Engagement


### Using Jupyter Notebooks to Have Conversations with Data

Students who are more engaged learn more (TODO citation). The creators of Jupyter describe it as a set of open-source tools for interactive and exploratory computing, and a platform for creating computational narratives. Jupyter allows educators to narrate a "conversation between the student and data". Consider this example, using the data of life expectancy of many countries over the years:

_I use a short bit of code to make a graph showing the time evolution, in what is called a "spaghetti plot" (see figure). Looking at this messy graphic, I point out how most of the lines show growth over time: life expectancy is improving all over the world. But a couple of lines show a marked dip in a given year. I can ask students: which country had that dip? What happened there? Why? With a bit more coding, we identify that Cambodia had a shocking life expectancy of about 30 years in 1977, and Rwanda had even worse life expectancy in 1992. We then have the opportunity to discuss why these countries experienced a mortality crisis. The data brings to life a meaningful discussion, with many possible paths involving history, politics, economics, and health. -- Lorena Barba_



<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/TimsTest0.png). Store image on your image server and adjust path/filename if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/TimsTest0.png "image_tooltip")


From: [http://go.gwu.edu/engcomp2lesson4](http://go.gwu.edu/engcomp2lesson4)

Jupyter notebooks are _tools of connection_: tools that engage learners in transitions in their thinking. The opportunity of intermingling computation into a narrative, creating a _conversation with data_ is a powerful and effective form of communication. An educator using Jupyter has a new form of content to create and share with learners: _computable content_. In a world where every subject matter can have a data-supported treatment, where computational devices are omnipresent and pervasive, the union of natural language and computation creates compelling communication and learning opportunities.


## 2) Increasing Student Participation

TODO : Could add Lindsey's example of students dictating what the professor does in the notebook.


## 3) Increasing Student Understanding


### The "CFD Python" story: Guiding Learners at their Own Pace

The fundamental theory behind Computational Fluid Dynamics (CFD) used in Aerospace Engineering is based on understanding the Navier-Stokes equations. "CFD Python" is a collection of Jupyter Notebooks based on a practical module that I began using in class in my Computational Fluid Dynamics (CFD) course at Boston University in 2009. The 5-week module develops worked examples that build on each other to incrementally guide the learner to create a program to solve the Navier-Stokes equations of fluid mechanics, in 12 steps.

_In 2013, I was invited to teach a 2 day mini-course in the Latin-American School in High-Performance Computing, in Argentina. The Jupyter Notebooks platform allowed me to create a guided narrative to support learners with different background experience and knowledge. For that event, we wrote Notebooks based on the CFD course module, to use as instructional scaffolding in the minicourse. Twenty students worked through the notebooks as self-paced lessons, while I went from desk to desk asking and answering questions. About four of the students completed all 12 steps in the 2 days, a bulk of them achieved up to about Step 8, and a few of them lagged behind in Steps 4 or 5 by the end of the course. For those who completed the full module, they had achieved in 2 days what my regular students in the classroom normally took 5 weeks to do. Seeing that was an eye-opening moment: both the power of worked examples in code, and the ability to allow learners to follow their own pace made a remarkable difference in these learners. -- Lorena Barba_

REF — Barba, Lorena A., and Forsyth, Gilbert F. (2018). CFD Python: the 12 steps to Navier–Stokes equations. Journal of Open Source Education, 1(9), 21, [https://doi.org/10.21105/jose.0002](https://doi.org/10.21105/jose.0002) 

Based on the experience developing the "CFD Python" learning module [[https://doi.org/10.21105/jose.0002](https://doi.org/10.21105/jose.0002)], this basic design pattern was adopted for creating lessons using computable content:



1.  Break it down into small steps
1.  Chunk small steps into bigger steps
1.  Add narrative and connect
1.  Link out to documentation
1.  Interleave easy exercises
1.  Spice with challenge questions/tasks
1.  Publish openly online


## 4) Increasing Student's Performance


### Serving Novice Learners: The Worked-example effect

The worked-example effect is the best known and most widely studied of the cognitive load effects. It refers to providing full guidance on how to solve a problem, resulting in better student performance than problem-solving conditions with no guidance. For complex tasks, inexperienced or beginner learners benefit the most from the worked-examples procedure. One study (Chen et al., 2015) concludes that: "worked example effect occurs for complex, high-element interactivity materials that impose a heavy working memory load" and "when dealing with complex material that learners may have difficulty understanding, high levels of guidance are likely to result in enhanced performance over lower levels of guidance." This research-based guidance seems especially relevant for teaching novice programmers to use computation in the context of their subject matter (science, engineering, or other).

REF — Chen, O., Kalyuga, S. and Sweller, J., 2015. The worked example effect, the generation effect, and element interactivity. Journal of Educational Psychology, 107(3), p.689. [http://doi.org/10.1037/edu0000018](http://doi.org/10.1037/edu0000018) 


## 5) Increasing Students' Preparation their for Career


### Publishing a data narrative as a demonstration of industry ability

For Data Science careers, a publicly shared narrative about a data analytics project goes a long way at demonstrating the student's potential at an interview. Elizabeth Wicks has her students develop a Jupyter notebook that tells the story of a data munging and analysis project done in the class. The students then publish this notebook to their Github profile pages. Being that Jupyter is one of the most popular ways in industry to communicate data science results, the students have a very valuable key to a potential career.

TODO: Add quote from Elizabeth


## **Student benefits**

Jupyter Notebooks support a wide range of learning goals. Its interactivity enables building intuitive understanding of domain knowledge, such as the understanding of a mechanical response of a system while varying parameters or understanding how an algorithm behaves. Notebooks can also help teach effective communication skills, combining prose with graphics into a strong narrative. Finally, notebooks can support teaching or strengthening programming skills, by combining code with text descriptions and visualizations. Even if a notebook is designed to be consumed passively, the exposure to code helps show students how to do something—and that they can do it themselves. This also helps demystify coding for students who do not view themselves as traditional "CS" types.

Integrating notebooks into classes also exposes students to a large and growing ecosystem of open-source tools. This supports their education, but also provides experience in the same environment of tools used in industries in high demand for trained employees, such as data science and machine learning. The open-source nature of these tools also ensures that course content remains accessible and affordable to all students—including those outside the traditional university environment.

Unlike proprietary notebook technologies such as Mathematica, or specific programming languages/environments such as Matlab or C++, the barriers to entry for students learning with Jupyter notebooks can be extremely low. At minimum, during a lecture, students can simply watch/read an interactive demo using a notebook, to replace slides or lecture notes. On their own, using a cloud service such as Binder or JupyterHub, students can open any modern web browser to some address and interact with a notebook (an example of this technology can be found at [https://jupyter.org/try](https://jupyter.org/try)) , without needing any installation or configuration. In the most complicated case, students can install Anaconda and follow simple instructions to install the Jupyter Notebook, which works and looks the same on all platforms—and is free and open source.

Thanks to their interactivity, notebooks enable a spectrum of active learning methods, which have been shown to increase performance in science, engineering, and mathematics [Freeman et al. 2018 [https://doi.org/10.1073/pnas.1319030111](https://doi.org/10.1073/pnas.1319030111)]. To start, students can consume notebook content by reading and running notebooks, then move to editing or completing notebooks as assignments. The top of Bloom's Taxonomy is pure creation, where students can author complete computational essays. In both cases, notebooks support classes where students have a wide range of experience and ability: students who need help can rely on the scaffolding of prose explanations and existing code, while also providing room to stretch and explore for more-experienced students. The additional annotation and prose that accompanies code also helps support non-traditional learners and students from underrepresented groups who may have less initial experience/comfort with programming.

(new stuff) For students



*   Student can focus on the content and concepts over note-taking
*   Interactivity drives engagement, interest, and exploration of concepts 
*   High engagement for students 
    *   Interactive
    *   Real world
    *   Application of concepts
*   Notebooks connect students to authentic external audiences: they can consume notebooks from other classes, and publish notebooks where others can read them.


## **Instructor benefits**

Notebooks can be adopted at a variety of levels and formats, offering flexibility based on the needs of a course and comfort/interest level of the instructor: in-class demos, interactive labs, auxiliary material (e.g., book replacements, lecture note supplements), assignments, or full course content in a flipped learning environment. Notebooks offer a route to active learning methods for instructors without experience of them, but do not force a particular teaching style. At minimum, notebooks can be used to make publishable and interactive lecture notes that blend descriptive comments with code and results to present everything in the right order. Furthermore, these course materials can be developed gradually, starting with a low-effort draft to a more-polished, publishable document that can be easily extended over time—and adopted by others.

(Scaling)

While many notebook authors do use Python, the Jupyter Notebook supports many languages, so students (and instructors) are not tied to one specific language. Indeed, the name Jupyter comes from three languages: Julia, Python, and R. Furthermore, these (free) tools have minimal barriers to entry—using a cloud infrastructure means students and instructors do not have to install anything, while in the "worst" case installations require a few command-line excursions, but these are free, openly available, and cross-platform.

(new stuff)

For instructors

Jupyter Notebooks as the problem solver. Problems it solves for us:



*   grading
*   Teaching hundreds of people
*   Enables conversation with a problem; students can get a part of script working instead of having the whole thing fail
*   Allows you to craft a narrative. (please say more about this)
*   Lecture pacing and flipped classroom
*   Ability to mix and remix high quality content from a variety of sources including audio, video, images, visualizations

Instructor benefits



*   Good sand-box.
*   Allows automated grading (nbgrader) which scales well for large classes
*   Enables interactive and flipped learning
*   Cell structure supports narratives with quick results
*   Strong libraries & ecosystem for many different types of uses (math, science, data science, arts, language, etc)
*   reproducible/shareable?
*   Supports gradual development of course materials, from a low effort first draft to a polished, publishable document. 
*   Low latency - students can improve notebooks through PRs and instructors can push out new/corrected content during a lecture
*   Self-contained assignments can be created that guide a student to the answer of a particular problem.
*   In-class notebooks can be "replayed" outside of class by students to reinforce the ideas.
*   It helps to enable a "flipped" classroom approach, with a single container for the out-of-class content.
*   It's fun.


# Conclusions

We hope that this chapter has demonstrated that teaching with Jupyter will: 1) support your students' learning, 2) give you confidence that you have the needed resources, 3) help you understand the necessary logistics, and 4) help give you clear expectations of what it will do.

In Chapter 3 we will present a variety of pedagogical practices that Jupyter support for teaching and learning.

In Chapter 4 we will explain the primary technical information about Jupyter notebooks and the tools to view and execute them.

In Chapter 5 you will find information on the deployment, assessment, and sharing.
