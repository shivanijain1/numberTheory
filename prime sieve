#include <bits/stdc++.h>
#define ll long long
using namespace std;
ll prime[1000000];
void prime_sieve  (ll n){
    for (int i=0;i<=n;i++)prime[i]=1;
    prime[0]=0;prime [1]=0;
    for (ll i=2;i<=n;i++){
        if (prime[i]){
            for (ll j=i*i;j<=n;j+=i){
                prime [j]=0;
            }
        }
    }
    for (ll i=2;i<n;i++){
        if (prime[i])cout<<i<<" ";
    }
}
int main() {
	ll n;cin>>n;
	prime_sieve (n);
	return 0;
}
// time complexity O(Nlog(logN))
