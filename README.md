# opencv4_4_contrib4_4
1:使用Mingw 编译的opencv4.4+contrib4.4  
2:供Qt使用库文件  
3：使用方法：  
  在系统环境变量中添加*:\opencv440\bin  
  在Qt工程pro文件中添加:  
  INCLUDEPATH+= *:\opencv440\include  
  LIBS += *:\opencv440\lib\libopencv_*.a  
  在使用opencv的文件里添加头文件  
  #include<opencv2/opencv.hpp>  
  #include <opencv2/xfeatures2d.hpp>  
  就可以使用了。
