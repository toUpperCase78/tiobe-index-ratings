# TIOBE Index Ratings

**Index Ratings for Popular Programming Languages from TIOBE**

<!-- ![TIOBE Logo](https://i.ibb.co/J2JCXXF/tiobe-logo.png) -->
![TIOBE Logo](tiobe_index_logo.png)

TIOBE Index Rating (more formally, TIOBE Programming Community Index) is an indicator for measurement of the programming languages' popularity. It gets updated once every month (although the dates are not regular). 

The ratings are based on the number of talented engineers world-wide, courses and 3rd party vendors. To calculate the ratings, 25 search engines (e.g. Google, Bing, Yahoo!, Baidu) are also used. In order to qualify a language, it must have its own Wikipedia entry; the explanations must be stated clearly for being a programming language. Furthermore, it should be "Turing complete" and have at least 5000 hits for "language programming" for Google.
  
According to the authorities, this index is NOT an indication for the best programming language. Rather, it is a helpful measurement to choose the language strategically for software development.

## Source

All the datasets presented here are taken from this web site. Click the link for more information: https://www.tiobe.com/tiobe-index/

## Datasets

There are **two** main types of datasets available: 

**FIRST TYPE** contains all the ratings for popular programming languages, starting from June 2001. Surely, new lines are inserted when a new index rating is published monthly. New languages might be added later as inidividual columns once they've made to the top 20.

**SECOND TYPE** shows the ratings for top 20 programming languages that were presented to the monthly index list, starting from **September 2020** up to the latest month individually. Naturally, new ones will exist as separate datasets in monthly basis. After some time, the lists from the previous years are grouped together in their belonging directories. 

All rating values are carefully fetched by examining the graphical plots of all aforementioned programming languages.

Furthermore, there exist sub-types in this repo: **Very Long Term History** contains the rankings of popular programming languages according to the index as 5-year intervals (two versions for year 2023 and 2025, respectively) and **Programming Language of the Year** represents the list of programming languages entered the hall of fame by having the highest rise in ratings every year, since 2003.

## Analyses

Currently, there are two analyeses available: **January 2023** & **November 2020**. 

Click on the corresponding notebook file (.ipynb) above to inspect and see how the ratings for many programming languages have been changed in time: 

**Tiobe_Index_Ratings_(Jan2023).ipynb** or **Tiobe_Index_Ratings_(Nov2020).ipynb**.

## Languages Being Tracked
  
In this repo, these programming languages (total of 32) are being tracked monthly (starting from September 2020):
  
* `C`
* `Java`
* `Python`
* `C++`
* `C#`
* `Visual Basic`
* `JavaScript`
* `PHP`
* `R`
* `SQL`
* `Go`
* `Swift`
* `Perl`
* `Assembly Language`
* `Ruby`
* `MATLAB`
* `Groovy`
* `Rust`
* `Objective-C`
* `Dart`
* `Classic Visual Basic` (since October 2020)
* `PL/SQL` (since October 2020)
* `Delphi/Object Pascal` (since November 2020)
* `Transact-SQL` (since November 2020)
* `Fortran` (since April 2021)
* `Prolog` (since August 2021)
* `Lua` (since March 2022)
* `Scratch` (since October 2022)
* `COBOL` (since July 2023)
* `Julia` (since August 2023)
* `Kotlin` (since September 2023)
* `Ada` (since March 2025)

## Headlines

### March 2025: The dinosaurs strike back

It is interesting to see that very old languages are sneaking into the TIOBE index top 20. Fortran and Delphi are competing for a top 10 position, whereas COBOL and this month's new entry Ada are a little bit further down the list. All of them show an uptrend. Why is this? Why aren't the new and promising languages shining instead?

I think that it has to do with the many vital legacy systems that keep the world running. Most of them are developed with the aid of these dinosaur languages. Now that the last of the core developers of these systems are about to retire, companies avoid any risk and choose to keep the existing systems and even extend them rather than replacing them by newer systems based on more modern languages. Note that we name these languages dinosaurs, but they have evolved over time and are pretty up to date. All of them have new language definitions. Check out Fortran 2023, Delphi 12 (released in 2024), Ada 2023 and COBOL 2023. We might frown to see these languages being in the TIOBE index top 20, but they definitely serve a purpose and deserve credit. _(Paul Jensen - Chief Executive Officer)_

### February 2025: Fast, Faster, Fastest!

Now that the world needs to crunch more and more numbers per second, and hardware is not evolving fast enough, speed of programs is getting important. Having said this, it is not surprising that the fast programming languages are gaining ground in the TIOBE Index. Programming language C++ climbed to position 2 recently, Go has become a steady top 10 player, and Rust is at an all-time high of 1.47%. Moreover, fast languages Mojo and Zig are knocking on the top 50 door at positions #51 and #56, respectively.

You might wonder how Python, known as a slow language, is able to survive next to these race monsters. This is because there is another driver nowadays except for performance: how easy it is to learn a new programming language. Apart from crunching more numbers, the world also needs more programmers. Developing applications completely in AI is not possible yet. Hence, the demand for new programmers is still very high. Since the number of graduated software engineers is lower than is needed, all kind of non-software engineers are jumping on the programming bandwagon, and their favorite language is Python. This is why Python is here to stay. _(Paul Jensen - Chief Executive Officer)_

### January 2025: Python is TIOBE's programming language of the year 2024!

Programming language Python has won the title "TIOBE's programming language of the year 2024". This award is given to the programming language with the highest incrase in ratings in one year time. Python gained a whopping 9.3% in 2024. This is far ahead of its competition: Java +2.3%, JavaScript +1.4% and Go +1.2%. Python is everywhere nowadays, and it is the undisputed default language of choice in many fields. It might even become the language with the highest ranking ever in the TIOBE Index. Python's only serious drawbacks are (and thus leaving room for competition) its lack of performance and that most errors occur in-time.

Apart from this, two interesting things happened in the TIOBE Index top 10 in 2024. The C language lost a lot of popularity and was surpassed by C++ and Java. The main reason for this is that C is replaced by C++ in a lot of embedded software systems. Java and C++ are currently fighting for the top 2 position. The other interesting thing is that PHP said a final farewell to the top 10 and is replaced by Go, which is a top 10 keeper.

Lots of eyes were on Rust and Kotlin this year. Did they live up to their promises in 2024? Rust is still getting more popular. Despite the amazing speed of Rust programs, its steep learning curve will never make it become the lingua franca of the common programmer unfortunately. Kotlin, on the other hand, disappointed: it didn't break through and even lost (possibly permanent) its top 20 position in 2024.

Further down the list we see two new promising languages: Rust's competitor Zig climbed from #149 to #61 in 2024, whereas Mojo, the faster Python, jumped from position #194 to #68. Especially Mojo, which was first released only 2 years ago, addresses exactly what is needed in the programming field. I have high hopes that it will get close to a top 20 position in 2025. _(Paul Jensen - Chief Executive Officer)_
