# Insertion-sort


        int arr[]={4,1,3,9,2};
        for(int i=1; i<arr.length; i++)
        {
          int j=i-1;
          int temp=arr[i];
          while( j>=0 && temp<arr[j] )
          {
            arr[j+1] = arr[j];
            j--;
          }
          arr[j+1]= temp;
          
        }
        
        
        for(int i=0; i<arr.length; i++)
      {
        System.out.print(arr[i]+" ");
       }
