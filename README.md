# codingstudy-with-liujuanjuan-together
跟娟姐一起学习代码
2019.4.15
今天开始，在微信群you can you up nobb 跟着大家一起学习Python编程。
vscode现在已经会使用，但，熟练还谈不上，需要后期不断使用，才能够做到熟练。为了能够用vscode直接使用github，所以不得不现在电脑上安装git。安装的时候，是参考了笑来老师的《自学是门手艺》中的git简介。第一遍，看不懂。看不懂之后，以为git简介没有讲清楚，然后就带着问题去Google，直接搜索“如何在vscode中使用git”，然后在弹出来的内容中选择了两个相对比较贴近问题的解答方案。找出的参考解答内容，相对来说比较详细，两个页面内容看过之后，心里有点眉目。而后，又返回笑来老师的git简介，再次看内容的时候，发现笑来老师已经把内容说明白了呀。（真的，一些内容要反复只字不差的阅读，到处去折腾，虽然说最后找到了解决方法，但是折腾下来，浪费了不少的时间。）。

接着把git安装好。但是安装好之后，想在vscode中使用git clone url，就是不行，始终提示的是git不是内部或外部命令。通过查看群内童鞋的问题交流，发现还需要本地配置，然后又琢磨良久之后，才把git bash打开，把配置命令输入输入进去（在参考笑来老师的git简介和google的解决方案上，因为他们的配置内容都是分开两行的，我以为在git bash上配置的时候也需要通过两行来配置。所以当我在$后输入git config --global user.name "myname"一行之后，直接敲回车然后接着在$后输入git config --global user.email "myemail"回车。然后接着去vscode中想要执行clone仓库的命令，可依然还是提示git不是内部或外部命令）。最后面我尝试着把两行配置内容，在一个$后输入，再回车，接着显示一些，信息，我估计是配置成功了。接着再到vscode的terminal输入git clone url，执行成功。突破成功。

接下来遇到的问题是，在vscode中该如何把change后的文件或者文件夹commit到云端。在看群里打怪文件的时候，起初以为git add -A, git commit -m "你的注释"，git push origin master.这些命令行是单独操作的，最后面操作一遍之后，再回过头去看文件时，发现自己漏看了两个字依次（也不叫漏看吧，反正第一次看完之后，没有发现重点，当操作一次之后，才能体会句中的哪个词是重点应该注意的）。还有就是，在执行这组命令之前，一定是要在相应的仓库下执行，不然会出现：not a git repository。而后，把这几个命令操作一遍之后，再到github网页上去查看相应仓库时，发现commit了文件的修改过后的内容。嗯，真的挺有成就感的。

