1. 配置Qt Designer
  
    
    file -> setting -> tools -> External tools -> 添加
    
    Program: D:\venv\character_painting2\Lib\site-packages\pyqt5_tools\designer.exe
    Working dir: $ProjectFileDir$
    
2. 配置PyUIC


    Program: D:\venv\character_painting2\Scripts\python.exe
    Arguments: ic.pyuic $FileName$ -o $FileNameWithoutExtension$.py
    Working dir: $FileDir$
   
3. 配置qrcTopy
    
    
    Projram: D:\venv\character_painting2\Scripts\pyrcc5.exe
    Arguments: $FileName$ -o $FileNameWithoutExtension$_rc.py
    Working dir: $FileDir$