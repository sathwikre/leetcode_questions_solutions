class Solution {
    public boolean isPerfectSquare(int num) {
        long st=0,end=num;
        while(st<=end) {
            long mid=(st+end)/2;
            if(mid*mid==num) return true;
            if(mid*mid>num) end = mid-1;
            else st = mid+1;

        }  
        return false;
    }
}
