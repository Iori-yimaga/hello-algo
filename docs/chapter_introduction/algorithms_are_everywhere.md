# 算法无处不在

当我们听到“算法”这个词时，很自然地会想到数学。然而实际上，许多算法并不涉及复杂数学，而是更多地依赖于基本逻辑，这些逻辑在我们的日常生活中处处可见。

在正式探讨算法之前，有一个有趣的事实值得分享：**实际上，你已经学会了许多算法，并习惯将他们应用到日常生活中了**。下面，我将举两个具体例子来证实这一点。

**例一：组装积木**。一套积木，除了包含许多零件之外，还附有详细的组装说明书。我们按照说明书一步步操作，就能组装出精美的积木模型。

从数据结构与算法的角度来看，积木的各种形状和连接方式代表数据结构，而组装说明书上的一系列步骤则是算法。

![拼装积木](algorithms_are_everywhere.assets/assembling_blocks.jpg)

**例二：查阅字典**。在字典里，每个汉字都对应一个拼音，而字典是按照拼音的英文字母顺序排列的。假设我们需要查找一个拼音首字母为 $r$ 的字，通常会这样操作：

1. 翻开字典约一半的页数，查看该页首字母是什么（假设为 $m$ ）；
2. 由于在英文字母表中 $r$ 位于 $m$ 之后，所以排除字典前半部分，查找范围缩小到后半部分；
3. 不断重复步骤 1-2 ，直至找到拼音首字母为 $r$ 的页码为止。

=== "<1>"
    ![查字典步骤](algorithms_are_everywhere.assets/look_up_dictionary_step_1.png)

=== "<2>"
    ![look_up_dictionary_step_2](algorithms_are_everywhere.assets/look_up_dictionary_step_2.png)

=== "<3>"
    ![look_up_dictionary_step_3](algorithms_are_everywhere.assets/look_up_dictionary_step_3.png)

=== "<4>"
    ![look_up_dictionary_step_4](algorithms_are_everywhere.assets/look_up_dictionary_step_4.png)

=== "<5>"
    ![look_up_dictionary_step_5](algorithms_are_everywhere.assets/look_up_dictionary_step_5.png)

查阅字典这个小学生必备技能，实际上就是著名的「二分查找」。从数据结构的角度，我们可以把字典视为一个已排序的「数组」；从算法的角度，我们可以将上述查字典的一系列操作看作是「二分查找」算法。

小到烹饪一道菜，大到星际航行，几乎所有问题的解决都离不开算法。计算机的出现使我们能够通过编程将数据结构存储在内存中，同时编写代码调用 CPU 和 GPU 执行算法。这样一来，我们就能把生活中的问题转移到计算机上，以更高效的方式解决各种复杂问题。

!!! tip

    阅读至此，如果你对数据结构、算法、数组和二分查找等概念仍感到一知半解，那么太好了！因为这正是本书存在的意义。接下来，这本书将一步步引导你深入数据结构与算法的知识殿堂。
