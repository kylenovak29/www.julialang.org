---
author: <a href="https://github.com/StefanKarpinski">Stefan Karpinski</a>
date: "2019-02-12T00:00:00Z"
title: The Julia Project and Its Entities
slug: julia-entities
---

There are a number of entities surrounding the Julia programming language. Understandably, many people are not entirely clear on what these groups are and what their relationship to each other is. It’s pretty hard to know about these things without being in the thick of it. In this blog post I’ll give an overview of these groups and how they’re related to the project.

## Julia

The Julia project was founded by [Jeff Bezanson](https://github.com/JeffBezanson), [Alan Edelman](https://en.wikipedia.org/wiki/Alan_Edelman), [Viral Shah](https://en.wikipedia.org/wiki/Viral_B._Shah) and myself ([Stefan Karpinski](https://en.wikipedia.org/wiki/Stefan_Karpinski)). It consists of some code and a community of people who work on that code. The most clear cut line that can be drawn is that there is a set of people who have commit access to the [JuliaLang](https://github.com/JuliaLang) GitHub organization: there are currently 67 committers (36 active and 31 dormant). This set of people doesn’t really define the project, however, since there are many people who are prolific contributors to the Julia ecosystem but who do not have “commit bit.” The communal nature of open source makes it difficult to precisely define where the Julia project ends and the greater community begins, which is exactly how we like it.

## Julia Stewards

One official group of people representing the Julia project does exist: [Julia Stewards](https://julialang.org/community/stewards/). This group exists to handle conflict resolution and reports of inappropriate or problematic behavior in the Julia community and ecosystem. The current stewards are: Milan Bouchet-Valat, Simon Byrne, Tim Holy, Katharine Hyatt, Steven Johnson, Stefan Karpinski, and Viral Shah. This group gets (rare) emails about potentially problematic situations and confidentially discusses and decides on what to do about them. The stewards group is not responsible for making any kinds of technical decisions or steering the project in any other way—it just exists to handle complaints and disputes, which fortunately are exceedingly rare.

## The Julia Lab

A lot of the early work on the development of core Julia was done at MIT in what is now known as [The Julia Lab](https://julia.mit.edu) under the direction of professor Alan Edelman. All of the co-creators of Julia have been part of the lab at some point. In those early days, we didn’t call it the Julia Lab yet, it was just an office where some people worked on high performance computing, numerical linear algebra, [random matrix theory](https://en.wikipedia.org/wiki/Random_matrix), and this new programming language called Julia. Although not formally part of the Julia Lab, [Jeremy Kepner](https://www.ll.mit.edu/biographies/jeremy-kepner) of Lincoln Laboratory was an early believer in and funder of the lab’s work on Julia and continues to support this work. Since those early days, things have gotten a lot more organized under the leadership (in chronological order) of [Jiahao Chen](https://jiahao.github.io), [Andreas Noack](https://github.com/andreasnoack) and [Valentin Churavy](https://github.com/vchuravy), and the Julia Lab remains a steady source of major innovations and contributions to Julia.

There are several other groups at MIT that have made major contributions to Julia over the years besides the Julia Lab. [Steven Johnson](https://en.wikipedia.org/wiki/Steven_G._Johnson), also a professor at MIT, heads up his own group but in his spare time has become one of the most prolific contributors to Julia (currently #10 by commits). The [JuMP](http://www.juliaopt.org) and [Cassette](https://github.com/jrevels/Cassette.jl) projects are primarily developed by current and former members of professor Juan Pablo Vielma’s [optimization research group](http://www.mit.edu/~jvielma/students.html). There are so many research groups at MIT using Julia these days, making major contributions to its ecosystem and to science, that it has become commonplace for Alan to discover that some neighbor of his at [CSAIL](https://www.csail.mit.edu) is using Julia completely unbeknownst to him. So definitely don’t consider this list exhaustive—I just didn’t want to appear to give the Julia Lab all the credit for work on Julia coming out of MIT. And of course, there’s incredible work being done on Julia by people at many other universities all around the world.

## NumFOCUS

NumFOCUS is a US 501(c)(3) nonprofit organization promoting open practices in scientific research, data science, and scientific computing by serving as a fiscal sponsor for open source projects and organizing community-driven educational programs in these areas. Through NumFOCUS, both [individuals](http://numfocus.org/membership) and [corporations](https://numfocus.org/sponsors) have the opportunity to donate to any of NumFOCUS’s fiscally sponsored projects including Julia, NumPy, Jupyter, Pandas, JuMP, rOpenSci, QuantEcon, and [many others](https://numfocus.org/sponsored-projects/). This is possible because these projects have entered into a contractual and legal relationship with NumFOCUS. This means that a set of people serving as the project’s leadership body has signed an agreement stating that they, or their successors, will manage the technical direction and programs of the project within the scope of the organization’s nonprofit status. NumFOCUS is the legal and financial administrator of project funds, disbursing as requested by the project’s leadership body with ultimate oversight by the NumFOCUS board of directors.

Despite what “fiscally sponsored project” may sound like, NumFOCUS does not have a big bag of money that it gives out to projects however it wants to. Rather, it means that NumFOCUS is legally able to accept donations from individuals, companies, private foundations and government entities to be spent on the fiscally sponsored projects. There are [other projects](https://numfocus.org/sponsored-projects/affiliated-projects) affiliated with NumFOCUS that are not fiscally sponsored, including Conda, Cython, Dask, SciPy, and scikit-learn. These projects can’t receive money through NumFOCUS because they don’t have the same legal relationship.

Julia’s signatories with NumFOCUS are Jeff Bezanson, Tim Holy, Steven Johnson, Viral Shah, and John Myles White. This set of people was chosen to be trustworthy, independent (not all from any one company or organization), and representative of the open source project. Signatories provide oversight to make sure that funding is being used for legitimate purposes. Other members of the Julia community are also actively involved with NumFOCUS in other capacities: I am a former board member and still on the [advisory council](https://numfocus.org/community/people#people-advisorycouncil) and Jane Herriman is a current [board member](https://numfocus.org/community/people#people-directors).

What kind of money goes to Julia through NumFOCUS and how is it spent? When you click on the "Donate to Julia button" on the Julia website, your donation goes to NumFOCUS and is earmarked to be used for the Julia project. This money is used to pay for infrastructure and personnel costs, including website hosting, continuous integration services, and anyone who is working on Julia through NumFOCUS (no one at the moment). By far the biggest flow of money through NumFOCUS for Julia is for the annual Julia conference—JuliaCon. Money from JuliaCon ticket sales and sponsorships go to NumFOCUS which then pays vendors for services required to make JuliaCon happen and reimburse anyone who has reimbursable conference-related expenses. Excess money (if any) from JuliaCon goes into the same pool as donations. JuliaCon finances are managed by the finance chair and approved by the JuliaCon organizing committee as representatives of the project and community. All money that goes in and out of NumFOCUS is a matter of [public record](https://numfocus.org/legal) since it is a nonprofit.

## Julia Computing

In 2015, the four co-creators of Julia along with [Keno Fischer](https://github.com/keno) and [Deepak Vinchhi](https://www.linkedin.com/in/deepakvinchhi/) founded [Julia Computing](https://juliacomputing.com/), a United States C corporation. Julia Computing provides products, support and services around Julia, including [JuliaBox](https://juliabox.com), [JuliaPro](https://juliacomputing.com/products/juliapro.html), [JuliaTeam](https://juliacomputing.com/products/juliateam.html) and [JuliaAcademy](https://juliaacademy.com/). The company employs many of the top contributors to Julia itself (half of the top ten contributors by commits) and to major Julia packages, especially for data science and machine learning. Even though there’s no formal connection between the company and the open source project, Julia Computing is deeply committed to Julia’s success and is proud to sponsor JuliaCon each year and drive so much open source Julia development.

## Conclusion

I hope that this clarifies what the entities surrounding the Julia project are and how they relate to each other. This picture will certainly evolve and change over time, and as it does so we'll try to keep an accurate description of these entities and relationships available as they develop.