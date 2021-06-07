# utl-how-to-set-up-the-classic-1980s-classic-editor
How to set up the Classic 1980s Classic editor 
ow to set up the Classic 1980s Classic editor

This repo
https://tinyurl.com/tbm73sy6
https://github.com/rogerjdeangelis/utl-how-to-set-up-the-classic-1980s-classic-editor

related GitHub repos
https://github.com/rogerjdeangelis?tab=repositories&q=classic&type=&language=&sort=

Setup

Toos>customize tools>toolbars> turn off applicatio toolbar
                               turn off command bar

Tools>options>preferences

    general> set recent file list to 30
             select tet option
    view>    turn on command line
             turn off command bar (does not support scripting - home/store)
             Turn off horizontal scroll (I have 'left 3' on function ket PF3)
             Unfortunately you cannot turn off the vertical scroll bar. If off
               mouse scroll wheel will not work
    edit>    autosave every minute
    results> turn on create listing

    Now type numbers on onthe command line

Your program editor should look like this
  # SAS
  ---------------------------------------
  file view toos run solutions window help
  ----------------------------------------
  Command ==>
   00001
   00002
   00003
   00004

Run this code

download and include "utl_perpac.sas"
https://tinyurl.com/3j6k6x4a

* this should install all my command macros;
%inc "X:\consortia\Sandbox\Roger\oto_macroLibrary\utl_perpac.sas";

https://tinyurl.com/3j6k6x4a

Test Run program and type 'frq sex*age' on command line

   Command ==> frq sex*age
    00001
    00002 data class;
    00003   set sashelp.class;
    00004 run;
    00005

* OUTPUT WINDOW;

Number of Variable Levels

Variable      Levels
--------------------
SEX                2
AGE                6

                                       Cumulative    Cumulative
SEX    AGE    Frequency     Percent     Frequency      Percent
---------------------------------------------------------------
F       11           1        5.26             1         5.26
F       12           2       10.53             3        15.79
F       13           2       10.53             5        26.32
F       14           2       10.53             7        36.84
F       15           2       10.53             9        47.37
M       11           1        5.26            10        52.63
M       12           3       15.79            13        68.42
M       13           1        5.26            14        73.68
M       14           2       10.53            16        84.21
M       15           2       10.53            18        94.74
M       16           1        5.26            19       100.00

You cal also highlight a dataset and enter 'frqh sex*ahe'


