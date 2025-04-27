# csci2400-lab2-bomblab-solved
**TO GET THIS SOLUTION VISIT:** [CSCI2400 lab2-bomblab Solved](https://www.ankitcodinghub.com/product/csci2400-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120172&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI2400 lab2-bomblab Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
This is the git repository into which students should add their bomb lab. You should commit the changes to your attack string as you finish each phase of your bomb lab.

In order to add your bomb lab to this repository, do the following: * Clone your git repository on the coding server or on your own linux system * Update file ./identikey with your IdentiKey * Run make bomb.tar to fetch a bomb and save it to file bomb.tar. It will also be extracted into a bomb directory such as bomb42. * If this fails, * Go the bomblab server link and download your bomb. * Move your bomb file to your git repo for example mv bomb42.tar ~/lab2-bomblab but replace ’42’ with your bomb number * Untar your bomb – tar xvf bomb42.tar but replace ’42’ with your bomb number * Add the bomb directory to your git repo – git add bomb[0-9]* * Do your initial commit – git commit -a -m’initial commit’ * And push your changes – git push

Note that your solution (input) to the bomb needs to be in the file solution.txt of your bomb directory.

Lab Details

The nefarious Dr. Evil has planted a slew of â€œbinary bombsâ€ on our class machines. A binary bomb is a program that consists of a sequence of phases. Each phase expects you to type a particular string on stdin. If you type the correct string, then the phase is defused and the bomb proceeds to the next phase. Otherwise, the bomb explodes by printing “BOOM!!!” and then terminating. The bomb is defused when every phase has been defused.

Step 1: Get Your Bomb

You can obtain your bomb by following the directions above. The tar file will contain the following files:

README: Identifies the bomb and its owners. bomb: The executable binary bomb. bomb.c: Source file with the bombâ€™s main routine and a friendly greeting from Dr. Evil.

You will add a file that must be named solution.txt in your bomb directory that includes the “solution” to your bomb which is the input needed to defuse your bomb.

If for some reason you request multiple bombs, this is not a problem. Choose one bomb to work on and delete the rest or ignore them.

Step 2: Defuse Your Bomb

Your job for this lab is to defuse your bomb. You’re going to need to add

There are several tamper-proofing devices built into the bomb as well, or so we hear.

You can use many tools to help you defuse your bomb. Please look at the hints section for some tips and ideas. The best way is to use your favorite debugger to step through the disassembled binary.

Each time your bomb explodes it notifies the bomblab server, and you lose 1/2 point (up to a max of 20 points) in the final score for the lab — we don’t actually dock you those points, but it’s frustrating to have your bomb explode and so there are consequences to exploding the bomb. You should be careful!

The first four phases are worth 10 points each. Phases 5 and 6 are a little more difficult, so they are worth 15 points each. So the maximum score you can get is 70 points.

Although phases get progressively harder to defuse, the expertise you gain as you move from phase to phase should offset this difficulty. However, the last phase will challenge even the best students, so please donâ€™t wait until the last minute to start. The bomb ignores blank input lines. If you run your bomb with a command line argument, for example,

linux&gt; ./bomb psol.txt

then it will read the input lines from psol.txt until it reaches EOF (end of file), and then switch over to stdin. In a moment of weakness, Dr. Evil added this feature so you donâ€™t have to keep retyping the solutions to phases you have already defused.

To avoid accidentally detonating the bomb, you will need to learn how to single-step through the assembly code and how to set breakpoints. You will also need to learn how to inspect both the registers and the memory states. One of the nice side-effects of doing the lab is that you will get very good at using a debugger. This is a crucial skill that will pay big dividends the rest of your career.

Logistics

This is an individual project. All handins are electronic. Clarifications and corrections will be posted on the course message board.

Handin

You must check in your bomb solution to github. The bomb will also notify us automatically about your progress as you work on it. You can keep track of how you are doing by looking at the class scoreboard at:

http://cs2400.cs.colorado.edu:15213/scoreboard

This web page is updated continuously to show the progress for each bomb.

Hints (Please read this!)

There are many ways of defusing your bomb. You can examine it in great detail without ever running the program, and figure out exactly what it does. This is a useful technique, but it not always easy to do. You can also run it under a debugger, watch what it does step by step, and use this information to defuse it. This is probably the fastest way of defusing it.

We do make one request, please do not use brute force! You could write a program that will try every possible key to find the right one, but this will take more time than just learning how to defuse the bomb. In any case, you’re going to have to explain what each phase does during your grading interview.

gdb

The GNU debugger, this is a command line debugger tool available on virtually every platform. You can trace through a program line by line, examine memory and registers, look at both the source code and assembly code (we are not giving you the source code for most of your bomb), set breakpoints, set memory watch points, and write scripts.

The CS:APP web site http://csapp.cs.cmu.edu/public/students.html has a very handy single-page gdb summary that you can print out and use as a reference. Here are some other tips for using gdb.

To keep the bomb from blowing up every time you type in a wrong input, youâ€™ll want to learn how to set breakpoints.

For online documentation, type â€œhelpâ€ at the gdb command prompt, or type â€œman gdbâ€, or â€œinfo gdbâ€ at a Unix prompt. Some people also like to run gdb under gdb-mode in emacs.

Online diassembler

https://onlinedisassembler.com/static/home/index.html The online disassembler provides a browser-based disassembler for different computer architectures. Itâ€™s primary benefit is that it will automatically extract a flow-chart for the program structure.

objdump -t

objdump -d

Use this to disassemble all of the code in the bomb. You can also just look at individual functions.

Reading the assembler code can tell you how the bomb works.

Although objdump -d gives you a lot of information, it doesnâ€™t tell you the whole story. Calls to system-level functions are displayed in a cryptic form. For example, a call to sscanf might appear as:

8048c36: e8 99 fc ff ff call 80488d4 &lt;_init+0x1a0&gt; To determine that the call was to sscanf, you would need to disassemble within gdb. strings

This utility will display the printable strings in your bomb.
