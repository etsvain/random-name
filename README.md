## ramdon-name ##
## 生成随机昵称，随机姓名，男生姓名，女生姓名 ##

## 使用方法 ##
## download##
    在需要用到的文件引用即可 // import randomName from 'youpath/random-name'

生成一个名字（男女不限）

    randomName.getName(); 

生成一个名字（男）

    randomName.getMaleName(); 

生成一个名字（女）

    randomName.getName(); 

生成一个昵称

    randomName.getNickName();

生成一个姓

    randomName.getFamilyName();

默认生成姓名含有复姓
若不需要复姓则可以在在调用方法时传入参数false  如：

    randomName.getName(false); 