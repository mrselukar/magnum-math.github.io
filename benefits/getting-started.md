---
description: Your one stop guide to get started with Magnum in no time
---

# Getting Started

### Selecting the right tool kit for your use-case

Magnum comes in a lot of flavors and is highly flexible. There are various components and they can be mixed and matched for your use case.

To make the selection easy, we have sorted the possibilities in TWO parts. Please spend sometime choosing the right version as per your needs to make the experience smoother.

{% tabs %}
{% tab title="Magnum \(Full\)" %}
[This](https://github.com/Magnum-Math/Magnum) is the full version of Magnum. You input a plain query in normal English and get a step-by-step video solution \(or graph- depending on your query\) generated automatically.   
  
This sounds awesome right? But here's a small checklist of some tools to which you should have the access:

* [x] [GPT-3 Keys from OpenAI](https://beta.openai.com) \(Currently in Beta\)
* [x] Wolfram Alpha AppID \(Check out their [website](https://products.wolframalpha.com/api/documentation/#obtaining-an-appid)- this one is relatively very easy to get\)

Mainly, if you think you can manage to get both of these, awesome! You can head over straight to our [official GItHub repository](https://github.com/Magnum-Math/Magnum), clone the repo and follow the instructions there.

If you feel you can't get these keys right away, don't worry! We have set up the [Magnum Lite version](https://colab.research.google.com/drive/1Vhyx39pztGeVthKrBZZRGVroEYMwh4T5?usp=sharing) just for you. Switch to the next tab to get full information about that.
{% endtab %}

{% tab title="Magnum Lite" %}
[Magnum Lite](https://colab.research.google.com/drive/1Vhyx39pztGeVthKrBZZRGVroEYMwh4T5?usp=sharing) is a special version of Magnum made just for non-programmers, students, teachers and more.This version literally requires NO ACCESS KEYS! You don't need to install anything/ neither do you need to have advanced systems with GPUs and stuff.  
  
With this, you can convert pre-formatted LaTeX code- straight to Manim animations! And all of that right from your browser!  
  
Before we get into using Magnum Lite, you need to have your LaTeX files formatted and ready. Here's how you can do that:

1. Magnum assumes everything is in Math environment \(under those $$$$\). This makes handling equations and things easy. But, at the same time, you need to be a little cautious with text. The best way is to declare text using: `\text{This is formatted text.}` or just by adding separators and treating them as Math elements like this: `This \ is \ formatted \ text.` 
2. Next, you need to make sure that every new step starts from a new line. That means you don't have to declare new lines/line breaks and stuff.
3. Paste everything in Notepad and name it latex.txt

That's it! Here's an example latex.txt file in the "Magnum style":

```text
Equations \ of \ circles \ in \ \mathbb{C}
Suppose \ we \ have \ a \ point \ c\in\mathbb{C}
Let \ C \ be \ the \ circle \ with \ centre \ c and \ radius \ r.
Then \ the \ equation \ of \ C \ is
{|z-c|=r}
Rewriting \ it,
{(z-c)(\overline{z-c})=r^{2}}
Expanding,
{z \bar{z}-\bar{c} z-c \bar{z}+|c|^{2}-r^{2}=0}
Thus, \ we \ can \ say \ that \ the \ equation
{z \bar{z}-\bar{c} z-c \bar{z}+\lambda=0 \quad c\in\mathbb{C}, \lambda\in\mathbb{R}}
is \ the \ equation \ of \ a \ circle \ centered \ at \ c \ with \ radius \ \sqrt{|c|^{2}-\lambda}
..
```

We made this modification to the standard LaTeX files to save you from a lot of effort in declaring Math, adding line breaks, dealing with .tex files and a lot of other difficulties our Beta users had.  
  
Once your latex.txt file is ready, head over straight to the [Official Magnum Lite Playground](https://colab.research.google.com/drive/1Vhyx39pztGeVthKrBZZRGVroEYMwh4T5?usp=sharing) and have fun!

P.S.: Note the two dots at the end? We recommend using it because it will act like an anchor to ensure the last step stays on the screen for a longer time.
{% endtab %}
{% endtabs %}

Before you start using Magnum/ Magnum Lite, we recommend having a look at the [Demo videos](https://drive.google.com/drive/folders/1aZdhZZl6Y4Bw81g0qXY7lkyd-OEFVTAn?usp=sharing) \(contributed by the community\). Have fun!

