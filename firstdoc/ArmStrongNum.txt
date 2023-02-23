public class Armstrong {
 public static boolean armstrong(int n) {
	int temp,temp1=n,mul,sum=0;
	while(temp1>0){
		temp=temp1%10;
		temp1=temp1/10;
		mul=temp*temp*temp;
		sum=sum+mul;
	}
	if(sum==n){
		return true;
	}
	else {
		return false;
	}
 }
}
