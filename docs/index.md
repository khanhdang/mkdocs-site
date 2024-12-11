---
hide:
- navigation
- toc
---

# <span id="greeting">ようこそ！</span>

![Image title](./assets/images/Khanh_N_DANG.jpg){class="avatar"}

Hello! My name is Khanh N. DANG.
I am currently an **Associate Professor** in the Division of Computer Engineering, Department of Computer Science and Engineering, [The University of Aizu](https://www.u-aizu.ac.jp/en/). I earned my Ph.D. from [The University of Aizu](https://www.u-aizu.ac.jp/en/) and my M.Sc. from [Paris XI University](https://en.wikipedia.org/wiki/Paris-Sud_University) (now [Paris-Saclay University](https://www.universite-paris-saclay.fr/en)). Prior to joining the University of Aizu, I worked at [Vietnam National University, Hanoi](https://vnu.edu.vn/eng/) and [Dolphin-IC](https://www.dolphin-ic.com/).

**Research Interests:** My current research covers three key topics: *(1) carbon-efficient computing*, *(2) 3D-IC technology*, and *(3) neuromorphic computing*. I am particularly interested in advancing computing architectures that achieve ultra-low-power and scalable solutions suitable for safe, responsible real-world deployment.


!!! success "Prospective Students"
    Research opportunities in VLSI design, carbon-efficient computing, and neuromorphic computing are available for GT undergraduate and graduate students. 
    Interested candidates are encouraged to check [this page](joinus.md) to know more.

<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>

<script>
    
var text = [ "Welcome!", "Xin chào!", "Bonjour!", "नमस्ते!",　"你好！", "ようこそ！"];
var counter = 0;
var elem = $("#greeting");
setInterval(change, 4000);
function change() {
    elem.fadeOut(1500,function(){
        elem.html(text[counter]);
        counter++;
        if(counter >= text.length) { counter = 0; }
        elem.fadeIn(1500);
    });
}

</script>

