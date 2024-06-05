标准流程
========

.. |1b| image:: _static/images/MJt1.png
    :width: 10 %
.. |2b| image:: _static/images/MJt2.png
    :width: 10 %
.. |3b| image:: _static/images/MJt3.png
    :width: 10 %
.. |4b| image:: _static/images/MJt4.png
    :width: 10 %
.. |5b| image:: _static/images/MJt5.png
    :width: 10 %
.. |6b| image:: _static/images/MJt6.png
    :width: 10 %
.. |7b| image:: _static/images/MJt7.png
    :width: 10 %
.. |8b| image:: _static/images/MJt8.png
    :width: 10 %
.. |9b| image:: _static/images/MJt9.png
    :width: 10 %
.. |1t| image:: _static/images/MJs1.png
    :width: 10 %
.. |2t| image:: _static/images/MJs2.png
    :width: 10 %
.. |3t| image:: _static/images/MJs3.png
    :width: 10 %
.. |4t| image:: _static/images/MJs4.png
    :width: 10 %
.. |5t| image:: _static/images/MJs5.png
    :width: 10 %
.. |6t| image:: _static/images/MJs6.png
    :width: 10 %
.. |7t| image:: _static/images/MJs7.png
    :width: 10 %
.. |8t| image:: _static/images/MJs8.png
    :width: 10 %
.. |9t| image:: _static/images/MJs9.png
    :width: 10 %
.. |1w| image:: _static/images/MJw1.png
    :width: 10 %
.. |2w| image:: _static/images/MJw2.png
    :width: 10 %
.. |3w| image:: _static/images/MJw3.png
    :width: 10 %
.. |4w| image:: _static/images/MJw4.png
    :width: 10 %
.. |5w| image:: _static/images/MJw5.png
    :width: 10 %
.. |6w| image:: _static/images/MJw6.png
    :width: 10 %
.. |7w| image:: _static/images/MJw7.png
    :width: 10 %
.. |8w| image:: _static/images/MJw8.png
    :width: 10 %
.. |9w| image:: _static/images/MJw9.png
    :width: 10 %
.. |df| image:: _static/images/MJf1.png
    :width: 10 %
.. |nf| image:: _static/images/MJf2.png
    :width: 10 %
.. |xf| image:: _static/images/MJf3.png
    :width: 10 %
.. |bf| image:: _static/images/MJf4.png
    :width: 10 %
.. |zhong| image:: _static/images/MJd1.png
    :width: 10 %
.. |fa| image:: _static/images/MJd2.png
    :width: 10 %
.. |bai| image:: _static/images/MJd3.png
    :width: 10 %
.. |chun| image:: _static/images/MJh1.png
    :width: 10 %
.. |xia| image:: _static/images/MJh2.png
    :width: 10 %
.. |qiu| image:: _static/images/MJh3.png
    :width: 10 %
.. |dong| image:: _static/images/MJh4.png
    :width: 10 %
.. |mei| image:: _static/images/MJh5.png
    :width: 10 %
.. |lan| image:: _static/images/MJh6.png
    :width: 10 %
.. |ju| image:: _static/images/MJh7.png
    :width: 10 %
.. |zhu| image:: _static/images/MJh8.png
    :width: 10 %


.. _认识麻将牌:

1 认识麻将牌
--------------------
* 数牌

   * 饼/筒
      |1b| |2b| |3b| |4b| |5b| |6b| |7b| |8b| |9b|
   * 条/索
      |1t| |2t| |3t| |4t| |5t| |6t| |7t| |8t| |9t|
   * 万
      |1w| |2w| |3w| |4w| |5w| |6w| |7w| |8w| |9w|
* 字牌

   * 风/四喜
      |df| |nf| |xf| |bf|
   * 箭/三元
      |zhong| |fa| |bai|
* 花牌

   * 君子
      |chun| |xia| |qiu| |dong|
   * 四季
      |mei| |lan| |ju| |zhu|

以上麻将牌，每种各四张。

2 上桌
--------

.. _Mahjong_table:
.. figure:: _static/images/Mahjong_table.png
    
   麻将桌

庄坐在东的位置（但绝大多数除正规比赛外的情况外，大家随便坐下就不再换位置了）。庄通常代表先抓牌的人，一般按逆时针方向轮流坐庄或赢者坐庄。最开始可以通过掷骰子比最大来决定谁最先坐庄。

3 洗牌码牌
----------
* 以只去掉 :ref:`花牌 <认识麻将牌>` 的打法为例。:ref:`数牌 <认识麻将牌>` 和 :ref:`字牌 <认识麻将牌>` 共 136 张。
* 将麻将牌洗乱。
* 按 :ref:`Mahjong_table` 所示，每人面前码 17 墩牌（一墩为上下两张）。注意右侧稍向桌内倾斜，方便抓牌。如果你的玩法不为只包含数牌和风牌的 136 张的情况，请参考 :doc:`/stacking`。

4 掷骰子
--------
* 由庄家掷两枚骰子，点数和为 :math:`x`。
* 庄家为 1，**逆时针** 方向数到第 :math:`x` 家，将这家记为 :math:`A`。
* 由 :math:`A` 再掷两枚骰子，点数和为 :math:`y`。
* 看 :math:`A` 面前的牌墩 **顺时针** 数过 :math:`z=x+y` 墩，这决定了从哪里开始抓麻将牌。
* 如果你认为你的玩法不是这样掷骰子或数牌，请参考 :doc:`/throwing`。
* 根据 :math:`x` 快速计算 :math:`A` 的位置以及根据 :math:`z` 快速计算如何数牌墩的口诀，清参考 :doc:`/throwing`。

5 抓牌
------
* 由庄家开始，按 **逆时针** 方向，每人抓一手（两墩）。这里要注意：第一，庄家抓的是 :math:`A` 面前顺时针跳过 :math:`z` 墩牌后，:math:`(z+1,z+2)` 这一手（两墩）。
* 连续抓三圈。每人手里有 3 手（6 墩，12 张）牌。
* 之后每人再按顺序抓一张，共 13 张牌。
* **注意**，除了麻将牌在被顺时针抓走外，一切都是逆时针进行。（**原因，可跳过**：麻将牌之所以被顺时针抓走，很可能是因为与扑克牌类似。抓扑克牌前，负责洗牌的人通常会用右手将洗好的扑克牌从左往右摊开，这样导致右边的扑克牌在上，左边的扑克牌在下。当扑克牌被一张一张抓走时，牌从右向左逐渐减少。对于麻将牌来说，从右向左逐渐减少就是顺时针方向被抓走。）
* 由于之后开始玩牌时，大家都是抓一张打一张。所以最开始是庄家抓一张打一张。因此，庄家通常会在抓第 13 张牌的同时，把游戏开始时要抓的第一张牌一起抓来，称为 :ref:`jump_draw` 。这样一来，游戏开始后，庄家不用抓牌，直接打出一张牌即可。

.. _jump_draw:
.. figure:: _static/images/jump_draw.png
   :scale: 50 %

   跳牌

6 目标
------
* 基本流程为逆时针方向每人抓一张，再打出去一张。
* 目标：最先把手中的牌构造成和 (hú) 牌形式。和牌形式包括基本和牌形式和特殊和牌形式，具体请参考 :doc:`win`。

6.1 牌型
^^^^^^^^
* 刻子：形如 AAA，如
   |3t| |3t| |3t|，|df| |df| |df|
* 杠：形如 AAAA，如
   |5t| |5t| |5t| |5t|，|zhong| |zhong| |zhong| |zhong|
   
   其功能和刻子一样
* 顺子：形如 BCD 的 :ref:`数牌 <认识麻将牌>`，如
   |2t| |3t| |4t|，|7w| |8w| |9w|
* 面子：包括顺子和刻子（包含杠）
* 将（对子、一对儿将）：形如 EE，如
   |1w| |1w|，|fa| |fa|

6.2 基本和牌形式
^^^^^^^^^^^^^^^^
将牌型构造成 4 个面子 + 1 对将，即 4 * (AAA 或 AAAA 或 BCD) + EE，如

.. image:: _static/images/MJs1.png
    :width: 6 %
.. image:: _static/images/MJs2.png
    :width: 6 %
.. image:: _static/images/MJs3.png
    :width: 6 %
.. image:: _static/images/MJt2.png
    :width: 6 %
.. image:: _static/images/MJt2.png
    :width: 6 %
.. image:: _static/images/MJt2.png
    :width: 6 %
.. image:: _static/images/MJw5.png
    :width: 6 %
.. image:: _static/images/MJw6.png
    :width: 6 %
.. image:: _static/images/MJw7.png
    :width: 6 %
.. image:: _static/images/MJf1.png
    :width: 6 %
.. image:: _static/images/MJf1.png
    :width: 6 %
.. image:: _static/images/MJf1.png
    :width: 6 %
.. image:: _static/images/MJw7.png
    :width: 6 %
.. image:: _static/images/MJw7.png
    :width: 6 %

7 过程
------
基本过程为按逆时针的方向，每人抓一张再打出去一张。在其他人打出来某张牌后，你应当及时查看自己手里的牌，并考虑如下操作：

* 碰：如果你手里有 AA，其他人打出来一张 A，你 **可以** 在下一个人抓牌之前喊出 **碰**，并将其他人打出的这张 A 和自己手里的两张 A 一起亮出来。（你可以将三张 A 中的一张背面朝上或横向摆放，以记录这一碰来自于谁。比如是对家打出的 A，就把三张 A 中中间那张背面朝上 🀈🀫🀈 或横向摆放。如果是上家打出的 A，就把三张 A 中左边那张背面朝上 🀫🀈🀈 或横向摆放。）由于碰牌相当于从外面拿了一张牌，因此需要打出一张牌。在你打出一张牌后，如果没人响应（如继续碰你打出的这张牌），就轮到你的下家（右手边）抓牌了。
* 吃：如果你手里有 BC，你的上家（左手边）打出来一张 A 或 D，你 **可以** 在下一个人抓牌之前喊出 **吃**，并将上家打出的这张 A 或 D 和自己手里的 BC 一起亮出来（你可以像碰一样，通过背面朝上或横向摆放记录这一吃来自于谁。）由于吃牌相当于从外面拿了一张牌，因此需要打出一张牌。在你打出一张牌后，如果没人响应（如继续碰你打出的这张牌），就轮到你的下家（右手边）抓牌了。**注意，绝大多数地方的麻将规则不允许吃**。
* 杠（可以额外赢钱）：

   * 明杠：

      * 直杠/碰杠：如果你手里有 AAA，其他人打出来一张 A，你 **可以** 在下一个人抓牌之前喊出 **杠**，并将其他人打出的这张 A 和自己手里的三张 A 一起亮出来。（你可以像碰一样，通过背面朝上或横向摆放记录这一杠来自于谁。）
      * 续杠：如果你已经碰出了 AAA，轮到自己摸牌时又摸到一张 A，你 **可以** 选择开杠，并将这张自己摸上来的 A 和桌面上碰出的三张 A 摆在一起。
   * 暗杠：如果你手里有未亮出过的 AAAA（四张 A 全部来自自己），你 **可以** 在任何自己摸牌后，将 AAAA 开出。比如，你手里有 AAA，你摸上来一张 A，你 **可以** 选择立即开出此暗杠。注意两点，第一，大多数地方暗杠需要亮出，有些地方暗杠不展示牌面。第二，如果在游戏结束之前未开出此暗杠，则不视为杠。

   由于杠的功能和碰出来的刻子功能一样，所以你会因为开杠而多出一张牌来，此时你需要再额外抓一张（通常是牌墩的末尾），再打出去一张。在你打出一张牌后，如果没人响应，就轮到你的下家（右手边）抓牌了。关于开杠的全部详细细节，请参考 :doc:`/kong`。 

8 记分
------