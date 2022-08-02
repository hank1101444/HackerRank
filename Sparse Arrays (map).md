```cpp
#include <iostream>
using namespace std;
#include <string>
#include <map>
int main(){
    int n;
    map<string, int> mp;
    string s;
    while(cin >> n){
        for(int i=0;i < n;++i){
            cin >> s;
            mp[s]++;
        }
        cin >> n;
        for(int i=0;i < n;++i){
            cin >> s;
            // ! can be printed in order
            cout << mp[s] << '\n';
        }
        // no need this
        
        
        // for(int i =0;i <v2.size();++i ){
        //     int ans = 0;
        //     for(int j=0;j < v1.size();++j){
        //         if(v2[i] == v1[j])
        //             ++ans;
        //     }
        //     cout << ans << '\n';
        // }
        mp.clear();
    }
    return 0;
}

```
