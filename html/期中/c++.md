C++是一種強大且廣泛使用的編程語言，它支援多種編程範式，包括面向對象編程（OOP）和泛型編程。以下是一個簡單的C++程式示例，可以印出"Hello, World!"的訊息：

cpp
Copy code
#include <iostream>

int main() {
    std::cout << "Hello, World!" << std::endl;
    return 0;
}
這個程式使用了iostream標頭文件，其中定義了用於輸入和輸出的cout對象。cout對象用於將訊息輸出到控制台。

在main函數中，我們使用cout對象來印出訊息"Hello, World!"。<<運算符用於將訊息附加到cout對象上。std::endl用於插入換行符號。

最後，return 0語句結束程式並返回0作為程式的退出碼。

您可以將上述程式碼保存到一個以.cpp為後綴的文件（例如，hello.cpp），然後使用C++編譯器（如g++）進行編譯和執行。