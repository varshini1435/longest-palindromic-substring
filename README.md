class Main {
    public static void main(String[] args) {
        String s="babad";
        int n=s.length();
        for(int l=0;l<n-1;l++){
            for(int r=l+1;r<n;r++){
                        System.out.println(s.substring(l,r));

            }
        }
        
    }
}
