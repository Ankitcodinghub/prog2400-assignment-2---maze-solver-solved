# prog2400-assignment-2---maze-solver-solved
**TO GET THIS SOLUTION VISIT:** [PROG2400 Assignment 2 – Maze Solver Solved](https://www.ankitcodinghub.com/product/data-structures-prog2400-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117132&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;PROG2400 Assignment 2 – Maze Solver Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
For this assignment, you are tasked to build a console application that will solve a given maze.

The maze will be given to you as a simple text file. The file will contain a 25×25 maze that will use the pipe (|), hyphen (‐) and plus sign (+) to represent the maze walls.

Example:

+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+

| | | | | | |

+-+-+-+-+-+ +-+ + +-+-+ + +-+ + +-+ + + +-+-+ + + +

| | | | | | | | | | | | | | |

Maze Start

Location

+ + + +-+-+ + +-+ + +-+-+ + +-+ + + + +-+-+ +-+-+ +

| | | | | | | | | | | | | | | | + +-+ + +-+-+-+ + + +-+ + + + +-+-+-+-+-+ +-+ +-+-+

| | | | | | | | | | | | | | |

+ + +-+ + +-+ + + +-+ + + + + + + +-+-+-+-+ +-+-+ +

| | | | | | | | | | | | | | | |

+ +-+ +-+ + +-+ +-+ +-+ + +-+-+ + + +-+ +-+ +-+-+-+ | | | | | | | | | | | | | +-+ +-+-+-+-+ +-+-+ +-+ + + +-+-+ +-+-+-+ + + + + +

| | | | | | | | | | | | | + +-+-+ +-+ + + + +-+ +-+-+-+ + +-+ + + +-+-+ + + +

| | | | | | | | | | | | | |

+ + + +-+ + + +-+ + +-+-+-+-+-+ + + + +-+-+-+-+-+-+

| | | | | | | | | | | | | | |

+ + + + +-+ + + +-+ +-+ + +-+ + + +-+-+-+-+ + +-+ +

| | | | | | | | | | | | | |

+-+-+ +-+ +-+-+-+ +-+ +-+-+-+ +-+-+ +-+ + +-+ + +-+

| | | | | | | | | | | | | |

+ + +-+-+ + +-+ +-+ +-+-+-+ + +-+ +-+-+ +-+ + +-+ +

| | | | | | | | | | | |

+ +-+ + +-+ + +-+ +-+ +-+-+-+ + + + +-+-+-+-+ + +-+

| | | | | | | | | | | | | |

+ + +-+ + + +-+-+-+ +-+-+ + +-+-+-+ +-+ + +-+-+-+ +

| | | | | | | | | | | | | |

+ +-+-+-+-+-+ + +-+ + + + +-+ +-+ + +-+-+-+-+ + + +

| | | | | | | | | | | | | | |

+ + +-+ + + + + + +-+-+ + + +-+ +-+-+-+-+ +-+-+ +-+ | | | | | | | | | | | | | | +-+-+ + + + + + + +-+ + +-+-+ +-+ +-+-+-+-+ + +-+-+

| | | | | | | | | | | | | | | | | |

+ + + + + + + +-+ + +-+ + + + + +-+ + + + + + + + +

| | | | | | | | | | | | | | | | | | |

+ +-+ + +-+ +-+ +-+-+ + +-+-+-+ + +-+ +-+-+ +-+-+ +

| | | | | | | | | | | | | | |

+ + + +-+ + + + + + + +-+ + + +-+-+ +-+-+ +-+ +-+-+

| | | | | | | | | | | | |

+-+-+-+ +-+-+ +-+ +-+ +-+-+ + + +-+-+-+-+ + + + + +

| | | | | | | | | | | |

+ +-+ +-+-+-+-+ +-+ +-+-+-+-+ + +-+ + +-+-+-+-+ + +

| | | | | | | | | | | +-+ +-+ + +-+-+-+ +-+ +-+-+ + + + +-+-+-+-+-+ +-+ +

| | | | | | | | | | | | | + + + +-+ + +-+-+-+ +-+ + +-+-+-+-+ + +-+ + +-+-+ +

| | | | | | | | | | | | | | | |

+ +-+-+-+-+ + +-+-+ + + + +-+ + + + +-+ +-+-+ + + +

| | | | | | | | |

Maze Exit

+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+

Data Structures (PROG2400)

Your application will then read the maze file and, using stacks and/or queues, produce the solution to the maze as a second text file. The solution through the maze will be noted using another character, such as the pound sign (#).

The maze solution file will resemble the following:

+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+

############| | | | | | |

+-+-+-+-+-+#+-+ + +-+-+ + +-+ + +-+ + + +-+-+ + + +

|#####| #| | | | | | | | | | | | |

+#+ +#+-+-+#+ +-+ + +-+-+ + +-+ + + + +-+-+ +-+-+ +

|#| |#|#####| | | | | | | | | | | |

+#+-+#+#+-+-+-+ + + +-+ + + + +-+-+-+-+-+ +-+ +-+-+

|#|###|###| | | | | | | | | | | | +#+#+-+ +#+-+ + + +-+ + + + + + + +-+-+-+-+ +-+-+ +

|#|###| |#| | | | | | | | | | | |

+#+-+#+-+#+ +-+ +-+ +-+ + +-+-+ + + +-+ +-+ +-+-+-+ |###|#####| | | | | | | | | | | +-+#+-+-+-+-+ +-+-+ +-+ + + +-+-+ +-+-+-+ + + + + +

| ##### | | | | | | | | | | | |

+ +-+-+#+-+ + + + +-+ +-+-+-+ + +-+ + + +-+-+ + + +

| | | ###| | | | | | | | | | |

+ + + +-+#+ + +-+ + +-+-+-+-+-+ + + + +-+-+-+-+-+-+

| | | |###| | | | | | | | | | |

+ + + +#+-+ + + +-+ +-+ + +-+ + + +-+-+-+-+ + +-+ +

| | |###| | | | | | | | | | |

+-+-+ +-+#+-+-+-+ +-+ +-+-+-+ +-+-+ +-+ + +-+ + +-+

|###| |#| | | | | | | | | | |

+#+#+-+-+#+ +-+ +-+ +-+-+-+ + +-+ +-+-+ +-+ + +-+ +

|#|###|###| | | | | | | | |

+#+-+#+#+-+ + +-+ +-+ +-+-+-+ + + + +-+-+-+-+ + +-+

|#|###|#| | | | | | | | | | |

+#+#+-+#+ + +-+-+-+ +-+-+ + +-+-+-+ +-+ + +-+-+-+ +

|#|#####| |### | | | | | | | |###| |

+#+-+-+-+-+-+#+#+-+ + + + +-+ +-+ + +-+-+-+-+#+#+ +

|#|#####| |#|#| | | | | | | |#####|# |

+#+#+-+#+ + +#+#+ +-+-+ + + +-+ +-+-+-+-+#+-+-+#+-+

|###|###| | |#|#|#####| | | |#########| |### |

+-+-+#+ + + +#+#+#+-+#+ +-+-+ +-+#+-+-+-+-+ +#+-+-+

| |#| | | |#|###|###| | | |###| | | |#|###|

+ + +#+ + + +#+-+ +#+-+ + + + +#+-+ + + + + +#+#+#+

| | |#| | | |###| |###| | | |#| | | |###|#|

+ +-+#+ +-+ +-+#+-+-+#+ +-+-+-+#+ +-+ +-+-+ +-+-+#+

| | #| | | |#| |#| |###| | | |#####|

+ + +#+-+ + + +#+ + +#+-+ + +#+-+-+ +-+-+ +-+#+-+-+

| |###| |###| | # | |#| | |###| |

+-+-+-+#+-+-+#+-+ +-+#+-+-+ +#+ +-+-+-+-+ + + +#+ +

| |#######| |###| |#| | | |#| |

+ +-+ +-+-+-+-+ +-+#+-+-+-+-+#+ +-+ + +-+-+-+-+#+ +

| | | |###|#######|#| | | |###|

+-+ +-+ + +-+-+-+#+-+#+-+-+#+#+ + +-+-+-+-+-+ +-+#+

| | | |#######|###| |###| | | | | #|

+ + + +-+ +#+-+-+-+#+-+ + +-+-+-+-+ + +-+ + +-+-+#+

| | | |#|#######| | | | | | | | | |#|

+ +-+-+-+-+#+#+-+-+ + + + +-+ + + + +-+ +-+-+ + +#+

| |###| | | | | | | ##

+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+

Note:

You can also assume that the maze always starts at the top left‐hand corner and ends at the bottom right‐hand corner.
