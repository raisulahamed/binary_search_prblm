# binary_search_prblm


 while(q--){
 int x;   cin>>x;
 int l=0,r=n-1;
 bool found =0;
 while(l<=r){
      int m=(l+r)/2;
      if(a[m]==x){
          found=1;
          break;
      }
      else if(x<a[m]){
           r=m-1;
      }
      else{
         l=m+1;
      }
}
if(found){
    cout<<"YES\n";
}
else{
   cout<<"NO\n";
}
}
          
