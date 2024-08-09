<div>
<table style="width:100%">
    <tr>
        <td align=center>
            <a href="https://item.jd.com/14260998.html">
                <img src="https://img3.doubanio.com/view/subject/l/public/s34761707.jpg" height="300px">
            </a>
        </td>
        <td align=center>
            <a href="https://item.jd.com/12398725.html">
                <img src="https://img3.doubanio.com/view/subject/l/public/s33711257.jpg" height="300px">
            </a>
        </td>
    </tr> 
    <tr align=center>
        <th>
            <a href="https://item.jd.com/14260998.html">
                <p>利用Python进行数据分析》第3版</p>         
            </a>
        </th>
        <th>
            <a href="https://item.jd.com/12398725.html">
                <p>利用Python进行数据分析》第2版</p>         
            </a>
        </th>
    </tr>
    <tr>
        <th align=left>
            <p>各章导读视频：<a href="https://www.bilibili.com/video/BV1pC4y117Bh/">https://www.bilibili.com/video/BV1pC4y117Bh/</a></p>
            <p>学习笔记：<a href="https://github.com/iamseancheney/python_for_data_analysis_3rd_study_note">python_for_data_analysis_3rd_study_note</a></p>
            <p>勘误：<a href="https://github.com/iamseancheney/python_for_data_analysis_3rd_study_note/blob/main/%E5%8B%98%E8%AF%AF.md">链接（感谢读者们的反馈🙏）</a></p>            
            <p>在简书上阅读： <a href="https://www.jianshu.com/p/16e04213aa91">https://www.jianshu.com/p/16e04213aa91</a></p>
            <p>第三版多了41页内容，Pandas升级为1.4.0、Python升级为3.10。第三版最大的变化是紧贴Pandas升级，主要是新增了方法和特性的内容。另外，第三版有作者的<a href="https://wesmckinney.com/book/">在线开源电子版</a>了，GitHub<a href="https://github.com/wesm/pydata-book">地址</a>。</p> 

第三版目录略有调整，不如第二版和第一版的变化大：
- 第4章NumPy基础新增了生成伪随机数；
- 第7章数据清洗新增了扩展数据类型和分类数据，实际是把第二版中第12章的内容放到新版第7章里了；
- 第11章时间序列新增了分组时间重采样。

曾经不止一次听别人抱怨，Pandas的知识点分散、零碎、不便于记忆。在细节上，作者这次在新版中摒弃了许多容易造成记忆混乱的用法。比如，用`axis = "columns"`替代`axis = 1`，简写方式破坏了代码的可读性，作者修改了许多类似的编程细节。新版对初学者更为友好了！
        </th>
        <th align=left>
            <p>在简书上阅读： <a href="https://www.jianshu.com/p/04d180d90a3f">https://www.jianshu.com/p/04d180d90a3f</a></p>
            
下载本书代码，GitHub<a href="https://github.com/wesm/pydata-book/tree/2nd-edition">地址</a>（建议把代码下载下来之后，安装好Anaconda，在目录文件夹中用Jupyter notebook打开）。

本书是2017年10月20号正式出版的，和第1版的不同之处有：

* 包括Python教程内的所有代码升级为Python 3.6（第1版使用的是Python 2.7）
* 更新了Anaconda和其它包的Python安装方法
* 更新了Pandas为2017最新版
* 新增了一章，关于更高级的Pandas工具，外加一些tips
* 简要介绍了使用StatsModels和scikit-learn

对有些内容进行了重新排版。最大的改变是把第1版附录中的Python教程，单列成了现在的第2章和第3章，并且进行了扩充。
        </th>
    </tr>
</table>
</div>

***

> 新版《利用Python进行数据分析》上市后，我一直在寻找一本Python数据分析的进阶书。经过漫长的搜索和等待，总算找到了，书名是《Fast Python》(中文书名极速Python)。

<div align=center>
<table style="width:100%">
    <tr>
        <td align=center>
            <a href="https://www.amazon.com/Fast-Python-performance-techniques-datasets-ebook/dp/B0C3N4H919">
                <img src="https://pica.zhimg.com/80/v2-b298d639d1535abf0df8c828c8c7cbfa_1440w.png" height="300px">
            </a>
        </td>
        <td align=center>
            <a href="https://item.jd.com/14121183.html">
                <img src="https://pic1.zhimg.com/80/v2-2833cf04fb676ef850eb56ff286526ff_1440w.png" height="300px">
            </a>
        </td>
    </tr> 
    <tr align=center>
        <th>
            <a href="https://www.amazon.com/Fast-Python-performance-techniques-datasets-ebook/dp/B0C3N4H919">
                <p>Fast Python: High performance techniques for large datasets</p>         
            </a>
        </th>
        <th>
            <a href="https://item.jd.com/14121183.html">
                <p>极速Python：高性能编码、计算与数据分析</p>         
            </a>
        </th>
    </tr>
</table>
</div>

<div align=center>
    <p><b>技术链条：Pandas > Arrow > Ray > ChatGPT > ?</b></p>
</div>

这本书在Amazon上市后，评论并不多，只有两个5星评价。但是，看完目录后，我立即就想认真读一读。《利用Python进行数据分析》主要围绕NumPy、Pandas、Matplotlib，内容比较偏基础。而工作中要处理的数据量变得越来越大，对技术的要求越来越高，基础方法已经不够用了，必须使用能处理大规模数据集的新方法。《极速Python》从软件到硬件，从单机到分布式，对Python高性能编程和大数据分析优化进行了系统性讲解。内容亮点包括Python代码分析、数据结构优化、内存优化、高并发编程、NumPy编程、Cython代码重构、pandas进阶、数据存储。针对当下最热点的技术领域，本书还重点讲解了Arrow、GPU编程和分布式数据处理。《Fast Python》比另一本优秀的《High Performance Python》的技术栈还要全！

结合大语言模型研究热潮，阅读《极速Python》可以更好地理解最新的Python数据分析技术对技术界产生了巨大的影响。Pandas的作者Wes近年来主要开发了Arrow。Arrow提供了一种高效的数据格式和交换方式，使得在不同的计算框架和编程语言之间进行数据交换和分析变得更加容易和高效。通过将Arrow和Pandas结合使用，可以获得高性能的数据处理和分析能力。Arrow提供了快速的数据传输和交换机制，而Pandas提供了丰富的数据操作和分析功能。这使得在大规模数据集上进行数据处理和分析变得更加高效和便捷。进而，分布式机器学习框架Ray在Datasets组件中使用了Arrow，而22年底爆火的ChatGPT就是用Ray训练而成的。

***

<div align=center>
<!-- <table style="width:100%"> -->
<!--     <tr align=center> -->
<!--         <th>【Python数据分析群】，拉你入群</th> -->
<!--         <th>AI科技论谈·分享AI新知</th> -->
<!--     </tr> -->
<!--     <tr> -->
<!--         <td align=center> -->
<!--             <img src="https://picx.zhimg.com/80/v2-3301f242afabf3c8365b9ecadef3de6d_1440w.png" height="300px">             -->
<!--         </td> -->
<!--         <td align=center> -->
<!--             <img src="https://picx.zhimg.com/80/v2-72d0e4f4b373738b400c30a5757edb90_1440w.jpeg" width="160px"> -->
<!--         </td> -->
<!--     </tr>  -->
<!-- </table> -->
</div>




<div align=center>
<table style="width:100%">
    <tr align=center>
        <th>【Python数据分析群】，拉你入群</th>
        <th>用三个月完成了翻译，工作砌码回家码字，手竟然脱皮了 :joy:</th>
        <th>感谢赞赏 :sparkling_heart:</th>
    </tr>
    <tr>
        <td align=center>
            <img src="https://picx.zhimg.com/80/v2-3301f242afabf3c8365b9ecadef3de6d_1440w.png" height="300px">            
        </td>
        <td align=center>
            <img src="https://upload-images.jianshu.io/upload_images/7178691-260d699e695f8e81.jpg" height="300px">            
        </td>
        <td align=center>
            <img src="https://pic1.zhimg.com/80/v2-c499eb01a64368f08d77776d6f43e26e_1440w.png" width="160px">
        </td>
    </tr> 
</table>
</div>


