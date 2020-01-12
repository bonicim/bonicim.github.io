---
title: A Shortish Guide to Preparing for a Technical Interview 
layout: post
categories: [interviewing]
---
 
Preparing for a technical interview can be a daunting task. Where should one start? What programming language should I use? What website should I use to practice questions? What books should I read? What questions should I focus on? And a million other questions race through one's mind when trying to prepare. 

While those are good questions to ask, it's important to step back ask two fundamental questions: 

1. What are companies looking for when conducting technical interviews?
1. What are my principles that guide my preparation?

###  What are companies looking for when conducting technical interviews?

When I interview candidates, I am gathering data to answer three critical questions about a candidate: Is this person smart? How does this person think about a problem? Can this person work with me and my team? The candidate will answer these questions for me not directly but through how they react and respond in the technical interview. But what do I mean about these questions? Let's explore each one in detail.

**Is this person smart?** As a potential teammate, I need to find out if you are smart so that you won't waste my time or the team's. But what do I mean by smart? I need to know if you meet the minimum bar on the computer science fundamentals: Algorithms, Data Structures, Discrete Math, Object Oriented Programming, Operating Systems, and System Design. While not an exhaustive list, having a high competency in these fundamentals shows me that you have the foundational intellectual tools tackle any project. 

**How does this person think about a problem?** I need to know how you think, if at all. Did you just memorize the solution to an algorithm question? Or do you understand the nuances of the question and the different ways of solving the question and why? I want to know how you approach problems. I want to know how you develop a mental map of understanding and solving a problem. When solving a problem, it is very important to think “out loud” and walk me through how you are solving the problem. I'm looking to see how you engage the problem. Be sure to talk through your thought process about the questions you are asked, as well as your approach to problems and solutions. Ask specific questions if you need more clarification.

Think about ways to improve the solution you'll present. In many cases, the first answer that springs to mind may need some refining. It is worthwhile to talk about your initial thoughts to a question. A brute force explanation will be received less well than taking time to compose a more efficient solution. Ask clarifying questions if you do not understand the problem or need more information. I'm looking to see which areas leap to your mind as the most important piece of the technological puzzle you've been presented.

**Can this person work with me and my team?** Software engineering is a social process for the most part. The myth of the lone, introverted engineer making highly scalable and quality code is simply that...a myth. I need to know if you can communicate your thinking process. I need to know why you made a design choice over another. I need to know if you can take feedback and are coachable. I need to know if you can teach and make other engineers better...or at least have the potential. There are two qualities of a great engineer: they get stuff done and they make others better. Making others better requires keen social skills such as communication, teamwork, and a bit of humility. Are you that person?

###  What are my principles that guide my preparation?

Now that you know what the interviewer is thinking, you can start working on all those programming questions. But before jumping deep into LeetCode or Hackerrank, you need principles that will guide your preparation so that you are being both efficient and effective with your precious study time, especially for those who are working. Having guiding principles will ensure that you study the right materials in the right way. Your preparation should be so complete that when you finish a technical interview you should feel as if preparation was a lot harder than the interview itself. 

Here are four principles that I recommend:

1. Deliberate Practice Makes Perfect
1. Be Brilliant in the Basics
1. Have a System to Approach a Problem
1. Aim for Unconscious Competence

#### Deliberate Practice Makes Perfect

Most students think that quietly working on LeetCode all day is a perfectly fine way to prepare. It may be a way to practice. But it is both inefficient and ineffective because it lacks any focus. Practice answering programming questions in the same way that athletes or musicians practice their sport or instrument. The athletes and musicians that we admire perform at a high level because they practice deliberately, that is, they focus on one *primary* goal when practicing. For example, the American football quarterback, Tom Brady, has a habit of focusing on one item when he's practicing throwing a football. One day he's throwing the football, but focusing simply on his footwork. On another day, he's focusing on his shoulderwork. 

So how can we apply this on practicing interview questions? There are so many things that you have to perfect for the interview: writing on a whiteboard, speaking and writing, analyzing the runtime and space time complexity, walking your code through an example, coming up with more examples for a question, asking clarifying questions about the programming question, using the right syntax, asking for help when you're stuck, knowing the different solutions for a given problem, knowing the runtimes for all the basic sorting algorithms, and on and on. It's impossible to practice all these skills at once and perfectly. Instead, focus on one and do it really, really well. For example, when I solve a problem, I focus primarily on coming up with lots of examples and edge cases. Doing so has allowed me to improve how quickly I come up with tests and arrive at a decent, first pass solution. 

#### Be Brilliant in the Basics

When I went through Basic Training in the US Marine Corps, my platoon captain emphasized the importance of being brilliant in the basics. Learning how to be a platoon leader is hard; there are so many things to learn that one can be overwhelmed to the point of being intellectually paralyzed. And the only way to be successfull is to focus on doing the basic skills really, really well. No fancy stuff. No stuff you see in the war movies or commercials. Just focus on the fundamentals of being a competent platoon leader. In other words, be brilliant in the basics. 

The same applies to practicing these programming questions. I noticed some students think that working only on hard problems is the best way to practice and ace the interview. That is a mistake. First, you probably will only see one really hard question in the interview. Second and most importantly, companies are evaluating whether you have a strong foundation in Computer Science (see my point about the question: Are you smart?). Instead focus on solving easy, medium, and medium-hard problems that require a solid understanding of CS fundamentals. For example, you should know all the different ways to solve Two Sum and Count Islands. Those are classic problems that are a good way to assess your mastery of the CS foundations. Below is a synopsis of what those foundations. Be brilliant in all these things:  

**Algorithms**

* Searching: Know the basic searching algorithms and how to implement them on the fly. 
    * Breadth-first search
    * Depth-first search
    * Binary Search
* Sorting: Know how to sort. Don’t do bubble-sort. You should know the details of at least one n*log(n) sorting algorithm, preferably two (say, quicksort and merge sort). Merge sort can be highly useful in situations where quicksort is impractical, so take a look at it. 

**Data Structures**

* Arrays/ArrayLists
* Stacks/Queues
* Heaps
* Hashtables: Arguably the single most important data structure known to mankind. You absolutely should know how they work. Be able to implement one using only arrays in your favorite language, in about the space of one interview.
* Trees: Know about trees; basic tree construction, traversal and manipulation algorithms. Familiarize yourself with binary trees, n-ary trees, and trie-trees. Be familiar with at least one type of balanced binary tree, whether it’s a red/black tree, a splay tree or an AVL tree, and know how it’s implemented. Understand tree traversal algorithms: BFS and DFS, and know the difference between inorder, postorder and preorder.
* Graphs: There are 3 basic ways to represent a graph in memory (objects and pointers, matrix, and adjacency list); familiarize yourself with each representation and its pros & cons. You should know the basic graph traversal algorithms: breadth-first search and depth-first search. Know their computational complexity, their tradeoffs, and how to implement them in real code. If you get a chance, try to study up on fancier algorithms, such as Dijkstra and A*.

**Concepts to know**  

* Big O Notation 
* Recursion
* Memoization/Dynamic Programming
* Bit manipulation
* Most famous classes of NP-complete problems, such as traveling salesman and the knapsack problem, and be able to recognize them when an interviewer asks you them in disguise. Find out what NP-complete means.

**Discrete Mathematics**

* Spend some time before the interview refreshing your memory on (or teaching yourself) the essentials of combinatorics and probability. You should be familiar with n-choose-k problems and their ilk – the more the better.

**Operating Systems**

* Know about processes, threads and concurrency issues. Know about locks and mutexes and semaphores and monitors and how they work. Know about deadlock and livelock and how to avoid them. Know what resources a processes needs, and a thread needs, and how context switching works, and how it’s initiated by the operating system and underlying hardware. Know a little about scheduling. The world is rapidly moving towards multi-core, so know the fundamentals of “modern” concurrency constructs

 
#### Have a System to Approach a Problem

Rookies flail in a technical interview. They show that they are scattered-brain. They jump from example to coding to debugging, confusing themselves and the interviewer. Believe me, I've seen it and also done it myself in past interviews. This is not the way to approach a technical interview question. 

Have a system. Any system. It doesn't matter what it is. Just have a systematic way to approaching and solving a problem. Having a system will benefit you in three ways: 1) Calms your nerves because you have a plan 2) Clearly communicates to the interviewer how you are thinking and 3) Forces you to be disciplined and organized when you encounter a problem you haven't seen. 

So what system should you use? Whatever works for you. Each person's brain operates differently so only you know what works for you. Whatever system you use, the goal is to be methodical in your approach to solving a problem. I personally use a hybrid system consisting of the Design Recipe and Test Driven Development. 

If you need a system, below is an example of approaching a problem:

* It’s OK to question your interviewer or ask for clarification
* When asked to provide a solution, first define and frame the problem as you see it.
* If you need to assume something - verbally check its a correct assumption!
* Describe how you want to tackle solving each part of the question
* Listen - don’t miss a hint if your interviewer is trying to assist you!
* Is the code clean/bug free? If not, it’s OK to fix bugs and optimize the solution.
* Make sure to test your code.


#### Aim for Unconscious Competence

How will you know when you are ready to start interviewing? When you have achieved Unconscious Competence. This is also known as "being in the zone" or "achieving an autonoumous mastery". A famous dance teacher once wrote that when learning a new dance, [we go through four stages.](https://www.nwdance.net/publications/dance-and-the-four-stages-of-mastery/){:target="_blank"} 

1. Unconscious Incompetence: we don't know what we're doing and don't know that we we're doing it badly. I'm having fun, but mostly because I have no clue what's going on. Ignorance is bliss. 
1. Conscious Incompetence: we know what we're doing and we're doing it badly. I'm really self-conscious and am apologizing for how much I suck.
1. Conscious Competence: we know what we're doing and we're doing it well. I'm really self-conscious but I can do it. I just need some extra time to think about it. 
1. Unconscious Competence: we don't know what we're doing and we're doing it really well. I have mastered this skill. I don't have to think so hard. It just happens. 

Ideally, we should be in the Unconscious Competence state when we start interviewing. And this takes about 10 years. Realistically, most junior engineers and students don't even have two years. But this should be the goal. But for sure, you need to at least attain Conscious Competence when solving a typical programming question. Anything less than that and you are not ready to interview. 

### Final Thoughts

This article is not meant to be a definitive guide on how to prepare for technical interview. Rather, it's meant to steer you in the right direction and give you some pointers on how to own your preparation instead of mindlessly working on LeetCode. And as a parting gift, below is a list of resources that I personally like and will vouch for:

Books
* Cracking the Coding Interview 
* Elements of Programming Interviews 
* Programming Interviews Exposed
* Grokking Algorithms

Coding Practice Websites
* Pramp.com
* Topcoder.com


