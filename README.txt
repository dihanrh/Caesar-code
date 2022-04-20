# Caesar-code

Caesar Code is also known as Caesar Cipher. This is an encryption process. An algorithm has been written in this writing to make any word encrypted by Caesar Code.

The steps to make a word encrypted by Caser Code has been given below:

Step 1:  Start.

Step 2: Declare String s and take input.

Step 3: Declare ns and assign size of string s in it. Declare int ar[ns], en[ns], tmp; char ae[ns].

Step 4: Declare char rs[25] , int nv =  65.

Step 5: Start loop , i= 0 and till i<= 25 .

5.1: rs[i] = char (nv)

5.2: increment nv as nv = nv+1 .

5.3 :Terminate the loop.

Step 6: Start loop , i=0 , i< ns .

6.1: Formulate : ar[i] = int(s[i]) – 65 .

6.2: Start loop , j= 0 , j<= 25 .

6.3: Check if (ar[i] == j ) is true :

6.3.1 : Assign tmp = j  , tmp = (tmp + k ) % 26 .

6.3.1.1  : check if ( tmp < 0) , if true , assign tmp += 26 .

6.3.2 : Assign ae[i] = rs[tmp]

6.3.3 :Terminate loop if j<= 25.

6.4: Execute ae[i].

6.5: Terminate loop if i< ns.

Step 7: Stop
