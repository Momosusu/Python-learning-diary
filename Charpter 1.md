## Charpter 1  
#  List

def print_lol(list_name):
    for each_item in list_name:
        if isinstance (each_item, list):
            print_lol (each_item)
        else:
            print (each_item)
        
list_A = [11, 112, [2222, 222,3,[333, 3, 444],'jjj'],'kkk']
print_lol (list_A)

## VIM COMMEND
:w     将缓冲区写入文件，即保存修改
:wq     保存修改并退出
:x     保存修改并退出
:q     退出，如果对缓冲区进行过修改，则会提示
:q!     强制退出，放弃修改