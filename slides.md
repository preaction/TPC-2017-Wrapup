
# TPC 2017 Wrapup

<http://preaction.github.io/TPC-2017-Wrapup/>

<div style="width: 40%; float: left">

by [Doug Bell](http://preaction.me)  
<small>(he, him, his)</small>  
[<i class="fa fa-twitter"></i> @preaction](http://twitter.com/preaction)  
[<i class="fa fa-github"></i> preaction](http://github.com/preaction)  
<img src="http://chicago.pm.org/theme/images/chicagopm-small.png" style="border: none; vertical-align: middle" />
[Chicago.PM](http://chicago.pm.org)  

</div>
<div style="width: 20%; float: left; text-align: center">
<img src="http://preaction.me/images/avatar-small.jpg" style="display: inline-block; max-width: 100%"/>
</div>
<div style="width: 40%; float: left">

<small> </small>  
<small> </small>  
[Source on <i class="fa fa-github"></i>](https://github.com/preaction/TPC-2017-Wrapup/)  

[CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode)  

<small>
For speaker view, press `S`<br/>
For full-screen, press `F`
</small>
</div>

------
<!-- .slide: data-background-image="images/t-shirt.jpg" data-background-size="contain" data-background-position="center" data-background-repeat="no-repeat" data-background="#000" -->

# TPC::NA 2017

---
<!-- .slide: data-background-image="images/uspto-madison-room.jpg" data-background-size="contain" data-background-position="center" data-background-repeat="no-repeat" data-background="#000" -->

# USPTO

Alexandria, VA

------

# Talks

---

<!-- .slide: data-background-image="images/talk-joel-house.png" data-background-size="contain" data-background-position="center" data-background-repeat="no-repeat" data-background="#000" -->
<div data-markdown style="margin-top: 12em">
[Watch on YouTube](https://www.youtube.com/watch?v=aJc5yYONBBc&index=32&list=PLA9_Hq3zhoFxdSVDA4v9Af3iutQxLI14m)
</div>
---

<!-- .slide: data-background-image="images/talk-swift.png" data-background-size="contain" data-background-position="center" data-background-repeat="no-repeat" data-background="#000" -->
<div data-markdown style="margin-top: 12em">
[Watch on
YouTube](https://www.youtube.com/watch?v=n-st1-DpKHI&index=39&list=PLA9_Hq3zhoFxdSVDA4v9Af3iutQxLI14m)
</div>
---

<!-- .slide: data-background-image="images/talk-dart.png" data-background-size="contain" data-background-position="center" data-background-repeat="no-repeat" data-background="#000" -->
<div data-markdown style="margin-top: 12em">
[Watch on YouTube](https://www.youtube.com/watch?v=cDMMF_b7Kbs&index=5&list=PLA9_Hq3zhoFxdSVDA4v9Af3iutQxLI14m)
</div>
---

<!-- .slide: data-background-image="images/talk-women.png" data-background-size="contain" data-background-position="center" data-background-repeat="no-repeat" data-background="#000" -->
<div data-markdown style="margin-top: 12em">
[Watch on YouTube](https://www.youtube.com/watch?v=7N3dR2y3Fi8&index=56&list=PLA9_Hq3zhoFxdSVDA4v9Af3iutQxLI14m)
</div>
---

<!-- .slide: data-background-image="images/talk-travel-ban.png" data-background-size="contain" data-background-position="center" data-background-repeat="no-repeat" data-background="#000" -->
<div data-markdown style="margin-top: 12em">
[Watch on YouTube](https://www.youtube.com/watch?v=lc0gjymliOI&index=33&list=PLA9_Hq3zhoFxdSVDA4v9Af3iutQxLI14m)
</div>
---

<!-- .slide: data-background-image="images/talk-election-rt.png" data-background-size="contain" data-background-position="center" data-background-repeat="no-repeat" data-background="#000" -->
<div data-markdown style="margin-top: 12em">
[Watch on YouTube](https://www.youtube.com/watch?v=0-fIOLpIyz0&list=PLA9_Hq3zhoFxdSVDA4v9Af3iutQxLI14m&index=35)
</div>
------

<!-- .slide: data-background-image="images/sawyer-keynote.jpg" data-background-size="contain" data-background-position="center" data-background-repeat="no-repeat" data-background="#000" -->

# Keynote: Perl 5.26

[Watch on YouTube](https://www.youtube.com/watch?v=SYmdef_WQsw&list=PLA9_Hq3zhoFxdSVDA4v9Af3iutQxLI14m&index=8)

---
<!-- .slide: data-background-image="images/sawyer-jacket.png" data-background-size="contain" data-background-position="center" data-background-repeat="no-repeat" data-background="#000" -->
<h1 class="fragment fade-in">Pumpkin(g) Jacket</h1>

---

# `.` in `@INC`

[Watch this section on YouTube](https://youtu.be/SYmdef_WQsw?t=9m28s)

---
<!-- .slide: data-background-image="images/sawyer-security.png" data-background-size="contain" data-background-position="center" data-background-repeat="no-repeat" data-background="#000" -->
---
<!-- .slide: data-background-image="images/sawyer-heredoc.png" data-background-size="contain" data-background-position="center" data-background-repeat="no-repeat" data-background="#000" -->

# Indented `HEREDOC`

---

```perl
if ( $ok ) {
    $dbh->selectall_array( <<ENDSQL
        SELECT
            id,
            DATE_FORMAT( '%Y-%m-%d', datetime ) AS datetime,
            summary,
            facts
        FROM
            test_report
        WHERE
            dist=?
            AND state="pass"
        ENDSQL
}
```

---
<!-- .slide: data-background-image="images/sawyer-avocado.png" data-background-size="contain" data-background-position="center" data-background-repeat="no-repeat" data-background="#000" -->

# 🤦

---
<!-- .slide: data-background-image="images/sawyer-diff.png" data-background-size="contain" data-background-position="center" data-background-repeat="no-repeat" data-background="#000" -->
---

```perl
if ( $ok ) {
<<<<<< HEAD
    return "Old boring";
======
    return "New hotness";
>>>>>> ab0914fd
}
```
---
<!-- .slide: data-background-image="images/sawyer-xx.png" data-background-size="contain" data-background-position="center" data-background-repeat="no-repeat" data-background="#000" -->
---
<!-- .slide: data-background-image="images/sawyer-refalias.png" data-background-size="contain" data-background-position="center" data-background-repeat="no-repeat" data-background="#000" -->
---
<!-- .slide: data-background-image="images/sawyer-scalar-hash.png" data-background-size="contain" data-background-position="center" data-background-repeat="no-repeat" data-background="#000" -->
---
<!-- .slide: data-background-image="images/sawyer-thanks.png" data-background-size="contain" data-background-position="center" data-background-repeat="no-repeat" data-background="#000" -->
------

# Damien Conway

---

# Dios

---

# Keyword::Declare

---

# PPR

Perl Parser: Regex

---

## You Can Parse Perl With Regex!

------

# Your Thoughts

------

# Questions?

---

# Thank You

<http://preaction.github.io/TPC-2017-Wrapup/>

<div style="width: 40%; float: left">

by [Doug Bell](http://preaction.me)  
<small>(he, him, his)</small>  
[<i class="fa fa-twitter"></i> @preaction](http://twitter.com/preaction)  
[<i class="fa fa-github"></i> preaction](http://github.com/preaction)  
<img src="http://chicago.pm.org/theme/images/chicagopm-small.png" style="border: none; vertical-align: middle" />
[Chicago.PM](http://chicago.pm.org)  

</div>
<div style="width: 20%; float: left; text-align: center">
<img src="http://preaction.me/images/avatar-small.jpg" style="display: inline-block; max-width: 100%"/>
</div>
<div style="width: 40%; float: left">

<small> </small>  
<small> </small>  
[Source on <i class="fa fa-github"></i>](https://github.com/preaction/TPC-2017-Wrapup/)  

[CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode)  

</div>

