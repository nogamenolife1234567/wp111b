
若您想開始使用C語言進行編程，以下是一個簡單的範例程式碼，展示了如何撰寫一個簡單的「Hello, World!」程式：

c
Copy code
#include <stdio.h>

int main() {
    printf("Hello, World!\n");
    return 0;
}
這段程式碼使用了C語言的標頭檔 <stdio.h>，其中包含了處理輸入和輸出的函式庫。程式進入點是main函式，並在函式內使用printf函式來輸出「Hello, World!」的訊息。最後，return 0表示程式執行完畢並正常結束。

您可以將上述程式碼複製到一個文本編輯器中，將檔案儲存為.c的副檔名（例如hello.c），然後使用C編譯器（例如GCC）來編譯和執行程式。在命令列中，輸入以下指令進行編譯：

Copy code
gcc hello.c -o hello
這將使用GCC編譯器將hello.c編譯為可執行檔 hello。然後，您可以執行程式：

bash
Copy code
./hello
將輸出看到「Hello, World!」。