---
layout: default
title: "CS 331: Data Structures and Algorithms"
---
<header>
  <h1>{{ page.title }}</h1>

  <section id="announcements">
  <h2>Announcements</h2>
  <div markdown="1">
  - Welcome to the Spring 2022 edition of CS 331: Data Structures and Algorithms!
  </div>
  </section>
</header>

<section id="calendar">
  <h2>Calendar</h2>
  <div markdown="1">
  The lecture calendar is tentative and will be updated as the semester progresses.

  All starter lecture notebooks can be accessed [via Google Colab](https://colab.research.google.com/github/cs331ds/lectures/) (and directly in the [Git repository](https://github.com/cs331ds/lectures))

  <script>
    function nbHtmlURL(name) {
      document.write("<a href=\"https://htmlpreview.github.io/?https://github.com/cs331ds/lectures/blob/main/html/" + name + ".html\">" + name + "</a>");
    }

    function nbURL(name) {
      document.write("<a href=\"https://github.com/cs331ds/lectures/blob/completed/" + name + ".ipynb\">" + name + "</a>");
    }
  </script>

  <table class="calendar">
    <thead>
    <tr>
      <th>Date</th>
      <th>Topic</th>
      <th>Notes</th>
      <th>Supplements</th>
    </tr>
    </thead>
    <tbody>
      <tr>
        <td>Aug 25</td>
        <td>
          Syllabus and Overview
        </td>
        <td>
          <a href="assets/slides/introduction.pdf">00-intro.pdf</a>
        </td>
        <td>
          <a href="syllabus.html">Syllabus</a><br>
          PythonDS <a href="https://runestone.academy/runestone/books/published/pythonds/Introduction/WhyStudyDataStructuresandAbstractDataTypes.html">1.5</a>-<a href="https://runestone.academy/runestone/books/published/pythonds/Introduction/WhyStudyAlgorithms.html">1.6</a>
        </td>
      </tr>
      <tr>
        <td>Aug 27 - Sep 8</td>
        <td>
          Python language intro
        </td>
        <td>
          <script>nbURL("01-lang-intro-a");</script><br>
          <script>nbURL("02-lang-intro-b");</script><br>
          <script>nbURL("03-lang-intro-c");</script>
        </td>
        <td>
          PythonDS <a href="https://runestone.academy/runestone/books/published/pythonds/Introduction/ReviewofBasicPython.html">1.7</a>-<a href="https://runestone.academy/runestone/books/published/pythonds/Introduction/ObjectOrientedProgramminginPythonDefiningClasses.html">1.13</a><br>
          <a href="https://docs.python.org/3/tutorial/index.html">Python Tutorial</a>
        </td>
      </tr>
      <tr>
        <td>Sep 10 - Sep 15</td>
        <td>
          Python data structures
        </td>
        <td>
          <script>nbURL("04-ds-demo");</script>
        </td>
        <td>
          PythonDS <a href="https://runestone.academy/runestone/books/published/pythonds/Introduction/GettingStartedwithData.html#built-in-collection-data-types">1.8.2</a>
        </td>
      </tr>
      <tr>
        <td>Sep 17 - Sep 22</td>
        <td>Timing and Runtime complexity</td>
        <td>
          <a href="assets/slides/runtime-complexity.pdf">runtime-complexity.pdf</a><br>
          <script>nbURL("05-timing");</script>
        </td>
        <td>
          PythonDS <a href="https://runestone.academy/runestone/books/published/pythonds/AlgorithmAnalysis/WhatIsAlgorithmAnalysis.html">3.2</a>-<a href="https://runestone.academy/runestone/books/published/pythonds/AlgorithmAnalysis/Dictionaries.html">3.7</a>
        </td>
      </tr>
      <tr>
        <td>Sep 24</td>
        <td>
          Array-backed list
        </td>
        <td>
          <script>nbURL("06-array-list");</script>
        </td>
        <td>
          PythonDS <a href="http://interactivepython.org/runestone/static/pythonds/BasicDS/Lists.html">4.19</a>-<a href="https://runestone.academy/runestone/books/published/pythonds/BasicDS/TheUnorderedListAbstractDataType.html">4.20</a>

        </td>
      </tr>
      <tr>
        <td>Sep 29</td>
        <td>
          Iterators and Generators
        </td>
        <td>
          <script>nbURL("07-iterators");</script>
        </td>
        <td>
        </td>
      </tr>
      <tr>
        <td>Oct 1</td>
        <td>
          Linked structures
        </td>
        <td>
          <script>nbURL("08-linked-structures");</script>
        </td>
        <td>
        </td>
      </tr>
      <tr>
        <td>Oct 6 - Oct 13</td>
        <td>
          Linked list
        </td>
        <td>
          <script>nbURL("09-linked-list");</script>
        </td>
        <td>
          PythonDS <a href="http://interactivepython.org/runestone/static/pythonds/BasicDS/ImplementinganUnorderedListLinkedLists.html">4.21</a>
        </td>
      </tr>
      <tr>
        <td>Oct 15 - Oct 22</td>
        <td>
          Map
        </td>
        <td>
          <script>nbURL("10-map");</script>
        </td>
        <td>
          PythonDS <a href="http://interactivepython.org/runestone/static/pythonds/SortSearch/Hashing.html">6.5</a>
        </td>
      </tr>
      <tr>
        <td>Oct 27</td>
        <td>
          Stack
        </td>
        <td>
          <script>nbURL("11-stack-and-queue");</script>
        </td>
        <td>
          PythonDS <a href="https://runestone.academy/runestone/books/published/pythonds/BasicDS/WhatisaStack.html">4.3</a>-<a href="https://runestone.academy/runestone/books/published/pythonds/BasicDS/InfixPrefixandPostfixExpressions.html">4.9</a>
        </td>
      </tr>
  <!--    <tr style="background: #ffd700;">
        <td>Jun 16</td>
        <td>Midterm Exam</td>
        <td></td>
        <td></td>
      </tr> -->
      <tr>
        <td>Oct 29</td>
        <td>
          Queue
        </td>
        <td>
          <script>nbURL("11-stack-and-queue");</script>
        </td>
        <td>
          PythonDS <a href="https://runestone.academy/runestone/books/published/pythonds/BasicDS/WhatIsaQueue.html)">4.10</a>-<a href="https://runestone.academy/runestone/books/published/pythonds/BasicDS/SimulationPrintingTasks.html">4.14</a>
        </td>
      </tr>
      <tr>
        <td>Nov 03 - Nov 05</td>
        <td>
          Priority queue
        </td>
        <td>
          <script>nbURL("12-priority-queue");</script>
        </td>
        <td>
          Videos: Priority queues <a href="https://youtu.be/bhp9rUtKA_0">#1</a>, <a href="https://youtu.be/zhu_WH0345w">#2</a>, <a href="https://youtu.be/9NgcT30DA3k">#3</a><br>
          PythonDS <a href="http://interactivepython.org/runestone/static/pythonds/Trees/PriorityQueueswithBinaryHeaps.html">7.8</a>-<a href="http://interactivepython.org/runestone/static/pythonds/Trees/BinaryHeapImplementation.html">7.10</a>
        </td>
      </tr>
      <tr>
        <td>Nov 10 - Nov 12</td>
        <td>
          Recursion
        </td>
        <td>
          <script>nbURL("13-recursion");</script>
        </td>
        <td>
          Videos: Recursion <a href="https://youtu.be/2ksEIzfUWxk">#1</a>, <a href="https://youtu.be/kizcHxT9VwQ">#2</a><br>
          PythonDS <a href="https://runestone.academy/runestone/books/published/pythonds/Recursion/WhatIsRecursion.html">5.2</a>-<a href="https://runestone.academy/runestone/books/published/pythonds/Recursion/TowerofHanoi.html">5.10</a>, <a href="https://runestone.academy/runestone/books/published/pythonds/SortSearch/TheMergeSort.html">6.11</a>
        </td>
      </tr>
      <tr>
        <td>Nov 17</td>
        <td>
          Tree structures
        </td>
        <td>
          <script>nbURL("14-bst");</script>
        </td>
        <td>
          PythonDS <a href="https://runestone.academy/runestone/books/published/pythonds/Trees/ExamplesofTrees.html">7.2</a>-<a href="https://runestone.academy/runestone/books/published/pythonds/Trees/NodesandReferences.html">7.5</a>
        </td>
      </tr>
      <tr>
        <td>Nov 19</td>
        <td>
          Binary search tree
        </td>
        <td>
          <script>nbURL("15-bst-ds");</script>
        </td>
        <td>
          Video: <a href="https://youtu.be/OUsuIuipbmA">BSTrees</a><br>
          PythonDS <a href="https://runestone.academy/runestone/books/published/pythonds/Trees/BinarySearchTrees.html">7.11</a>-<a href="https://runestone.academy/runestone/books/published/pythonds/Trees/SearchTreeAnalysis.html">7.14</a>
        </td>
      </tr>
      <tr style="background: #90ee90;">
        <td>Nov 22 - Nov 26</td>
        <td>Thanksgiving Break</td>
        <td></td>
        <td></td>
      </tr>
      <tr>
        <td>Dec 1 - Dec 3</td>
        <td>AVL tree</td>
        <td>
          <script>nbHtmlURL("16-avl-tree");</script>
        </td>
        <td>
          Videos: AVLTrees <a href="https://youtu.be/11lvwy2daic">#1</a>, <a href="https://youtu.be/JHt17lrmv-M">#2</a>, <a href="https://youtu.be/hdt4XGQdIKs">#3</a><br>
          PythonDS <a href="https://runestone.academy/runestone/books/published/pythonds/Trees/BalancedBinarySearchTrees.html">7.15</a>-<a href="https://runestone.academy/runestone/books/published/pythonds/Trees/AVLTreeImplementation.html">7.17</a>
        </td>
      </tr>
      <!-- <tr style="background: #ffd700;">
        <td>Jul 02</td>
        <td>Final Exam</td>
        <td><a href="final-exam-guide.html">17-final-exam-guide</a></td>
        <td></td>
      </tr> -->
    </tbody>
  </table>
  </div>

</section>

<section id="etc" markdown="1">
## Resources

### Syllabus

  - [Course syllabus](syllabus.html)

### Staff

  - Instructor:
      - Michael Lee &lt;<lee@iit.edu>&gt;
      - Office: SB 226C
      - Office Hours: [Make an appointment](https://calendly.com/michaelee/officehours)
  - TAs:
      - **Section 01**: TBA &lt;<tba@hawk.iit.edu>&gt;
          - Hours: Mon 2-3:30PM, Wed 3-5:30pm

### Reference materials

  - [Lecture video playlist](https://www.youtube.com/playlist?list=PLdrRMzNWVMEzl4G5zOlyF5BAQZ0IOFGwS)
  - [Problem Solving With Algorithms and Data Structures Using Python](http://interactivepython.org/runestone/static/pythonds/index.html)
  - [The Python Tutorial](https://docs.python.org/3/tutorial/index.html)
  - [The Python Standard Library documentation](https://docs.python.org/3/library/index.html)

### Development Tools

  - [Mimir](https://class.mimir.io/login)
  - [Python](https://www.python.org/downloads/)
  - [Google Colaboratory](https://colab.research.google.com/)
  - [Jupyter Notebook Install Guide](http://jupyter.org/install.html)

### Exam Catalog

  - [Spring 2020 Midterm Exam 1](assets/exams/2020-spring-midterm1.pdf), [WP solutions](assets/exams/2020-spring-midterm1-sols.pdf)
  - [Fall 2019 Midterm Exam 2](assets/exams/2019-fall-midterm2.pdf), [WP solutions](assets/exams/2019-fall-midterm2-sols.pdf)
  - [Fall 2019 Midterm Exam 1](assets/exams/2019-fall-midterm1.pdf), [WP solutions](assets/exams/2019-fall-midterm1-sols.pdf)
  - [Spring 2019 Midterm Exam 1](assets/exams/2019-spring-midterm1.pdf)
  - [Spring 2019 Midterm Exam 2](assets/exams/2019-spring-midterm2.pdf)
  - [Summer 2018 Midterm Exam](assets/exams/2018-summer-midterm.pdf)
  - [Spring 2018 Midterm Exam 1](assets/exams/2018-spring-midterm1.pdf)
  - [Fall 2017 Midterm Exam 1](assets/exams/2017-fall-midterm1.pdf)
  - [Fall 2017 Midterm Exam 2](assets/exams/2017-fall-midterm2.pdf), [WP solutions](assets/exams/2017-fall-midterm2-sols.pdf)
  - [Summer 2017 Final Exam](assets/exams/2017-summer-final.pdf)
  - [Summer 2017 Midterm Exam](assets/exams/2017-summer-midterm.pdf)
  - [Spring 2017 Midterm Exam 1](assets/exams/2017-spring-midterm1.pdf)
  - [Spring 2017 Midterm Exam 2](assets/exams/2017-spring-midterm2.pdf)
  - [Fall 2016 Midterm Exam 1](assets/exams/2016-fall-midterm1.pdf)
  - [Fall 2016 Midterm Exam 2](assets/exams/2016-fall-midterm2.pdf)
  - [Fall 2016 Final Exam](assets/exams/2016-fall-final.pdf)
  - [Summer 2016 Midterm Exam 1](assets/exams/2016-summer-midterm1.pdf)
  - [Spring 2016 Midterm Exam 1](assets/exams/2016-spring-midterm1.pdf)
  - [Spring 2016 Midterm Exam 2](assets/exams/2016-spring-midterm2.pdf)
  - [Fall 2015 Midterm Exam 1](assets/exams/2015-fall-midterm1.pdf)
  - [Fall 2015 Midterm Exam 2](assets/exams/2015-fall-midterm2.pdf)
</section>