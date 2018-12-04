# 迴圈
## for 迴圈
`for` 迴圈的基本格式如下：
    
    for( A ; B ; D )
    {
      C
    }

上述的Code會這跑：A -> if(B) -> C -> D -> if(B) -> C -> D -> if(B)

注意到 B 外面放了 `if` 嗎？

沒錯，這裡的 B 是一個判斷式，在 `for` 迴圈的每一圈開始前檢查 B 是否成立，如果成立就再跑一圈 C -> D ，不成立則跳出。

以下是一個 `for` 迴圈的簡單範例：

    for(int i=1;i<=5;i++)
    {
      cout<<"HELLO!"<<endl;
    }
    
這個迴圈的輸出如下：

    HELLO!
    HELLO!
    HELLO!
    HELLO!
    HELLO!

剛開始看或許很難理解，我們用上面的 `A` 、 `B` 、 `C` 、 `D` 來一步一步觀察吧！

* A ：int i=1

在用 `for` 迴圈時，我們通常會宣告一個
