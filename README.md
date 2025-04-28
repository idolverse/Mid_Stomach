<h1>中腹部：</h1>

本教程是关于中腹部部分的组装。

**注意** ，一旦腿做好了，这些部件肯定会被淘汰，而且是临时的。我还是把它们贴出来了，因为很多建造者都要求。这个教程里缺少图片，我把它们和硬盘一起弄丢了……

在打印所有部件之前，您应该打印一份校准器 (CALIBRATOR)，以检查部件是否能够拼合。如果您在拼合这些部件时遇到困难，可以调整切片软件的水平扩展设置来解决这个问题。此设置可能因切片机和打印机而异，但用户报告称，将其设置为 -0.15 是一个不错的起点。

填充率为 30%，壁厚为 2.5 毫米，最好无筏，无支撑（除非另有说明），大部件使用边缘以避免翘曲。

您需要打印以下所有部分：

1x BotBackLeft

1x BotBackRigt

1x BotCapLeft

1x BotCapRight

1x BotFrontLeft

1x BotFrontRigt

1x HipCoverFront

1x HipCoverLeft

1x HipCoverRight

1x MidPotHolder

2x MidWormRight

你需要两个 HS-805bb 舵机，需要进行破解。两个舵机只使用一块舵机板和一个电位器，这样两个电机就能同步旋转。教程中会详细解释这一点。

你需要65到70个滚珠轴承。你可以使用钢珠或BB枪珠。它们的直径应为6毫米。

我尝试使用Vigor VSD-11AYMB舵机，并制作了一些适合它的文件。可惜的是，这些舵机性能不佳，有时会抖动。另一个恼人的问题是，它们无法通过软件正确“分离”。

视频：https://youtu.be/9G8FDBgAxu0?t=3

<h2>步骤1：</h2>

![DSC06884-600x450](https://github.com/user-attachments/assets/47f784e4-05c2-4b78-8610-16be5d530dae)

检查StomGearV2.stl是否正确适合上腹部部件。

![image](https://github.com/user-attachments/assets/913cdd13-908a-44a7-b910-e22db330540f)

还要确保StoGearAttachV1.stl牢固地固定在 Top Stomach 部件的底面上。更多信息请查看TopStomach 教程。

<h2>步骤2：</h2>

![image](https://github.com/user-attachments/assets/5d5084b1-3c3c-450f-8d2e-b0c78935e027)

将BotBackLeftV1.stl、BotBackRigtV1.stl、BotFrontLeftV1.stl、BotFrontRigtV1.stl组装在一起。

![DSC06826-600x450](https://github.com/user-attachments/assets/fdb70e16-d3e5-4728-8182-890b022ae21c)

最好将它们粘在一起放在平坦的表面上。

![DSC06830-600x450](https://github.com/user-attachments/assets/b4fb4e13-c105-4a5f-8487-c398a943de81)

对于有此需要的用户，还可以选择安装螺栓。

![DSC06827-600x450](https://github.com/user-attachments/assets/67e34058-a62a-4757-a0e4-ce8e2bc6f694)

确保平面尽可能平坦。

![DSC06836-600x450](https://github.com/user-attachments/assets/3700efb4-0c66-4a1d-bdb0-adfeaab80769)

如果表面太不平整，请将一张带有双面胶带的砂纸粘在平板上，然后打磨组件，直到满意为止。

![DSC06886-600x450](https://github.com/user-attachments/assets/c0f7232e-8124-4b49-a671-e0ef3598de85)

将安装滚珠轴承的表面打磨光滑。我个人使用了丙酮，因为我的零件是用ABS打印的。

![image](https://github.com/user-attachments/assets/e714ec3a-8e33-40b6-9321-ba512171e497)

切断HipCoverFrontV1.stl上的预支撑。

![image](https://github.com/user-attachments/assets/415319b7-8758-4e6b-ba21-b2ac78021bc0)

用3毫米螺丝将HipCoverFrontV1.stl安装到你的组件上。我使用遮蔽胶带给黑色部分喷涂了汽车哑光喷漆。

![DSC06887-600x450](https://github.com/user-attachments/assets/889ee7d3-60cb-4218-a282-100d60eda63a)

用螺丝将两个MidWormRightV1.stl文件安装  到舵机摇臂上。用木螺钉将舵机安装到组件上。舵机的连接线将在后面的步骤 3中详细说明。

在此阶段，最好确保 StomGear 能够很好地与您的组件匹配。

![DSC06888-600x450](https://github.com/user-attachments/assets/2beccbba-91da-4d34-a07d-da35dd49a4d2)

在蜗轮上和 StomGear 的通孔中涂上适量的油脂。

![DSC06890-600x450](https://github.com/user-attachments/assets/959090f6-a10d-40eb-9c98-5cbac3c873de)

检查 StomGear 上的电位器孔并将其放置在如图所示的位置。

![DSC06891-600x450](https://github.com/user-attachments/assets/eabae9ff-027c-4555-af68-737a115082da)

适合 StomGear。

![DSC06892-600x450](https://github.com/user-attachments/assets/4b6df3fb-d96c-469b-a5f7-b0f654ef4c36)

让它在整个组装过程中顺利进行。

<h2>步骤3：</h2>

破解伺服系统

您需要按照本教程中的说明从舵机上移除电位器。请记住，Vigor VSD-11AYMB 舵机与 Hitec805BB 舵机略有不同。以下教程针对 Hitec805BB 舵机进行说明。

需要对两个伺服器进行破解才能使其连续旋转。

两个伺服器中的一个将由另一个控制，因此您必须移除该伺服器的电路板和电位器（请妥善保管以备备用，以防有一天您烧毁了 805B 伺服器控制板）。

![image](https://github.com/user-attachments/assets/1d91caef-504b-4bc8-aea0-0e6189a62e0b)

拆除三处焊接，拆下伺服控制板和方形电位器

![image](https://github.com/user-attachments/assets/783d6dbc-0060-4e9d-a6bc-0d93c6e85497)

将两根电线直接焊接在电机上，红点代表正极（我猜）。

![image](https://github.com/user-attachments/assets/f0947043-b78f-4a74-8c92-c774bf01f8f5)

并像往常一样切割阻碍伺服电机完全旋转的小块。

![DSC07259-600x450](https://github.com/user-attachments/assets/44c49a4e-70de-4147-96d4-cc1d0ce9f67c)

将蓝色电缆设置在电机正极侧（红点）

![DSC07258-600x450](https://github.com/user-attachments/assets/731919d2-28bc-454e-a6df-486122d986aa)










