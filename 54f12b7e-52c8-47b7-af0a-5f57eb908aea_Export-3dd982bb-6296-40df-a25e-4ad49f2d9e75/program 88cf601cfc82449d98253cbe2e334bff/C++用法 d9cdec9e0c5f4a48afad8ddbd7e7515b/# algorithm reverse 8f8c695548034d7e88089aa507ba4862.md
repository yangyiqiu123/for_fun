# #<algorithm> reverse

```cpp
#include <iostream>
#include <string>
#include <algorithm>
using namespace std;

int main() {
    char str[] = "Hello World";
    std::reverse(&str[0], &str[11]);
    // or
    //std::reverse(&str[0], &str[sizeof(str)-1]); 
    cout << str << endl;

    std::string str2 = "Hello World";
    std::reverse(str2.begin(), str2.end());
    cout << str2 << endl;
    
    int arr[] = {4, 5, 6, 7};
    std::reverse(std::begin(arr), std::end(arr));
    for(auto i : arr)
        std::cout << i;
    std::cout << '\n';

    std::vector<int> vec{1, 2, 3};
    std::reverse(std::begin(vec), std::end(vec));
    for (auto i : vec)
        std::cout << i;
    std::cout << '\n';
    
    return 0;
}
```

```cpp
// uva948
#include <iostream>
#include <vector>
#include <algorithm>

using namespace std;

int main(){
    ios_base::sync_with_stdio(0);
    cin.tie(0);

    vector<int> feb;
    feb.push_back(1);
    feb.push_back(2);
    for(int i=2 ;i <10 ;i++){
        feb.push_back(feb[i-1]+feb[i-2]);
    }
    cout<<"before"<<endl;
    for (auto j: feb) cout << j <<' ';
    cout<<endl;

    reverse(feb.begin(),feb.end());

    cout<<"after"<<endl;
    for (auto j: feb) cout << j <<' ';
    cout<<endl;
}
```